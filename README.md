# EduSphere

A full-stack Learning Management System (LMS) built with Next.js and Django, featuring course management, interactive modules, and live video classrooms.

## Project Structure

This repository is organized into two main parts:

- **`edu-sphere/`**: The frontend application built with Next.js 13, TailwindCSS, and Shadcn UI.
- **`backend/`**: The robust Django backend API providing database management, authentication, and core application logic.

## Features

- **Course Management:** Create, organize, and manage course content.
- **Interactive UI:** A highly interactive frontend with drag-and-drop support and a modern design.
- **Live Video Classrooms:** Integration with video SDKs for real-time virtual learning.
- **REST API:** A reliable and scalable backend API built with Django.

## Getting Started

### Prerequisites
- Node.js (v16+)
- Python (3.8+)
- PostgreSQL or SQLite (default)

### Frontend Setup (`edu-sphere/`)
1. Navigate to the frontend directory: `cd edu-sphere`
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`

### Backend Setup (`backend/`)
1. Navigate to the backend directory: `cd backend`
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - Mac/Linux: `source venv/bin/activate`
   - Windows: `venv\Scripts\activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run migrations: `python manage.py migrate`
6. Start the server: `python manage.py runserver`
