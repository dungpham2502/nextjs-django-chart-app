# Django and Next.js Full-Stack Application

This project is a full-stack web application using **Django** for the backend and **Next.js** for the frontend. Docker is used to containerize both services.

## Setup and Run

### Prerequisites

- Docker installed.

### Steps

1. **Clone the repository:**

   git clone https://github.com/your-repo-url.git
   cd your-repo

2. **Build and run the application**

   docker-compose up --build

3. **Access the application**

   Frontend: http://localhost:3000
   Backend: http://localhost:8000

4. **Stop the application**

## Libraries and Tools Used

### Backend

- Django: Backend framework.
- Django REST Framework: API creation.
- CORS Headers: Handling cross-origin requests.

### Frontend

- Next.js: React-based frontend framework.
- Chart.js: Chart rendering.
- Axios: HTTP client for API calls.

### Docker

- Docker: Containerization.
- Docker Compose: Managing multiple containers.

## Approach and Thought Process

- Modular Design: Separation of concerns between backend (Django API) and frontend (Next.js).
- API Communication: Frontend consumes data from Django API via Axios.
- Docker: Provides consistency across environments and simplifies deployment.
