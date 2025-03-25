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
git clone https://github.com/mukund7296/booking_system_berlin.git
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

## OUTPUT as Image's
<img width="1403" alt="image" src="https://github.com/user-attachments/assets/a365f2a1-0fd0-4113-b6fa-f70f7617643f" />

# Login Page
<img width="767" alt="image" src="https://github.com/user-attachments/assets/85c2215b-ee22-4db5-b8e8-a9d0dad670c0" />

# Registration page
<img width="855" alt="image" src="https://github.com/user-attachments/assets/af06eff2-4ee1-46b4-9f72-892e4fdb8b11" />

# Main page
<img width="1426" alt="image" src="https://github.com/user-attachments/assets/50b477d8-767d-43bf-945a-c5fbdae283da" />

# booking details

<img width="1152" alt="image" src="https://github.com/user-attachments/assets/8cb0e408-b97c-47c0-8fc4-37f704d7f96b" />

# Admin interface  Users
<img width="1432" alt="image" src="https://github.com/user-attachments/assets/d78e49ca-fd8c-411d-a18c-fcaa2a43e192" />

# Admin interface  Facilities
<img width="1428" alt="image" src="https://github.com/user-attachments/assets/945a551d-940e-4c98-930d-4aa2787102c4" />

# Admin interface  Facilities subpage (Add New facilities)
<img width="1099" alt="image" src="https://github.com/user-attachments/assets/dafa1e95-feee-41cd-96a3-d299780f514d" />

Only the admin can approve bookings after verifying availability and payment. Once approved, the bookings will be visible under the "My Bookings" section as confirmed.
<img width="1401" alt="image" src="https://github.com/user-attachments/assets/a118d434-0f53-48f6-9112-01db3b3a6638" />

# Docker Runing screenshot

<img width="1219" alt="image" src="https://github.com/user-attachments/assets/e9e025f6-e834-4c0b-8216-9c4615e02bb6" />
# You can execute all Django commands using this terminal as well.


<img width="1424" alt="image" src="https://github.com/user-attachments/assets/815a1b7c-5dba-4397-ab74-07e3072cc6f6" />


# Thank you






