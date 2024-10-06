# Django-React Full Stack Application

This project demonstrates a full-stack web application built with Django for the backend and React for the frontend. It includes a REST API, which connects the frontend React components with Django's database operations, creating a seamless user experience.

## Table of Contents
| Section                | Description                                              |
|------------------------|----------------------------------------------------------|
| [Project Setup](#project-setup) | Instructions for setting up the project locally     |
| [Backend Setup (Django)](#backend-setup-django) | How to set up the Django backend        |
| [Frontend Setup (React)](#frontend-setup-react) | How to set up the React frontend        |
| [Running the Application](#running-the-application) | How to run both servers concurrently   |
| [Folder Structure](#folder-structure) | Overview of the project directory structure    |
| [Contributing](#contributing) | Guidelines for contributing to the project          |

## Project Setup

| Step                    | Description                                                                              |
|-------------------------|------------------------------------------------------------------------------------------|
| Backend Setup (Django)   | Navigate to the `backend` directory and set up the Django backend environment.           |
| Frontend Setup (React)   | Navigate to the `frontend` directory and set up the React frontend environment.           |

### Backend Setup (Django)
| Step   | Command/Instruction                                         |
|--------|-------------------------------------------------------------|
| Step 1 | Navigate to the `backend` directory: `cd backend`           |
| Step 2 | Create a virtual environment: `python3 -m venv env`         |
| Step 3 | Activate the virtual environment: `source env/bin/activate` (Windows: `env\Scripts\activate`) |
| Step 4 | Install dependencies: `pip install -r requirements.txt`     |
| Step 5 | Run database migrations: `python manage.py migrate`         |
| Step 6 | Start Django development server: `python manage.py runserver`|

### Frontend Setup (React)
| Step   | Command/Instruction                                         |
|--------|-------------------------------------------------------------|
| Step 1 | Navigate to the `frontend` directory: `cd frontend`         |
| Step 2 | Install dependencies: `npm install`                         |
| Step 3 | Start React development server: `npm start`                 |

## Running the Application

| Step   | Command/Instruction                                             |
|--------|-----------------------------------------------------------------|
| Step 1 | Ensure both servers (Django backend and React frontend) are running. |
| Step 2 | Start Django server: `python manage.py runserver`               |
| Step 3 | Start React server: `npm start`                                 |
| Step 4 | Open the React app: `http://localhost:3000`                     |
| Step 5 | Ensure frontend communicates with backend via API requests.     |

## Folder Structure

| Folder/Files            | Description                                                   |
|-------------------------|---------------------------------------------------------------|
| `backend/`              | Contains the Django backend, including manage.py and app files |
| `frontend/`             | Contains the React frontend, including src and package.json    |


