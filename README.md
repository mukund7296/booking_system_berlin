# booking-system

# Django + Docker + PostgreSQL

This project sets up a Django web application with Docker and PostgreSQL using `docker-compose`.

## Prerequisites
- Docker installed ([Download](https://www.docker.com/get-started/))
- Python installed ([Download](https://www.python.org/downloads/))
- Git installed ([Download](https://git-scm.com/downloads))

## Setup Instructions

### 1. Clone the Repository
```sh
git clone <your-repository-url>
cd django-docker
```

### 2. Create a Virtual Environment & Install Dependencies
```sh
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

### 3. Build and Run with Docker
```sh
docker-compose up --build
```

### 4. Access Django App
Open your browser and go to:
```
http://127.0.0.1:8000/
```

## Database Configuration
The app uses PostgreSQL with the following credentials:
```plaintext
Database: django_db
User: django_user
Password: django_password
Host: db
Port: 5432
```

## Useful Docker Commands
- Stop containers: `docker-compose down`
- Check logs: `docker-compose logs`
- Rebuild containers: `docker-compose up --build`

