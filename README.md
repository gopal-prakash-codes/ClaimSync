# ClaimSync - Claims Management System

## Overview
ClaimSync is a full-stack web application designed to streamline the management of claims on parts. Built with Django for the backend and React for the frontend, the application ensures a seamless user experience with efficient claim handling and secure authentication.

## Features
- **User Authentication**: Secure sign-up, login, and logout functionality.
- **Claims Management**: Users can create, view, update, and delete claims on parts.
- **Responsive UI**: Modern React-based frontend designed for an optimal user experience.
- **REST API**: Django REST Framework (DRF) for efficient data handling.
- **Database Integration**: PostgreSQL for robust and scalable data storage.

## Tech Stack
### Backend
- **Python** (v3.10+)
- **Django** (v5.x)
- **Django REST Framework (DRF)**

### Frontend
- **React** (v18.x)
- **Axios** (for API communication)
- **Tailwind CSS** (for styling)

### Database
- **PostgreSQL**

## Installation & Setup
### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/gopal-prakash-codes/ClaimSync.git
   cd fafco/backend
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```bash
   python manage.py migrate
   ```
5. Start the development server:
   ```bash
   python manage.py runserver
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

---