# Mindful Journal

Mindful Journal is a full-stack web application that allows users to register, log in, and manage their notes. Built with Django on the backend and React on the frontend, the application features JWT-based authentication and PostgreSQL for data storage. The app provides a clean and functional user interface for creating, viewing, and deleting notes.

## Features

- **User Authentication**: Sign up, log in, and log out securely using JWT tokens.
- **Note Management**: Create, view, and delete notes with a simple interface.
- **Protected Routes**: Only authenticated users can access specific routes and manage their notes.
- **RESTful API**: The backend is built with Django REST Framework, offering secure API endpoints.
- **PostgreSQL Database**: Data persistence is handled with PostgreSQL, ensuring secure and efficient data storage.

## Tech Stack

### Backend
- Django
- Django REST Framework
- PostgreSQL
- JWT for authentication

### Frontend
- React
- Axios for API requests
- React Router for navigation

## Installation


### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/SultanMalik1/Mindful-Journal.git
   cd Mindful-Journal/backend
2. Install dependencies and set up the virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
3. Set up environment variables for PostgreSQL and JWT settings.

4. Run migrations and start the server:
    ```bash
    python manage.py migrate
    python manage.py runserver

### Frontend Setup
  1. Navigate to the frontend directory:

    ```bash
    cd ../frontend
  2. Install the required dependencies:

    ```bash
    npm install

  3. Start the React development server:
        ```bash
        npm start

### API Endpoints
- User Registration: /api/user/register/
- Login: /api/token/
- Notes:
- Create and List Notes: /api/notes/
- Delete Note: /api/notes/delete/<int:pk>/





