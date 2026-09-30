# TeacherHub

TeacherHub is an education-focused project that combines collaboration, attendance, student management, and wellness tools in one platform. It is designed for modern classrooms and academic teams that need a simple digital workspace for communication, scheduling, tasks, and monitoring participation.

## Project Introduction

This project brings together several modules:

- Team collaboration dashboard inspired by Microsoft Teams
- Face detection and recognition attendance system
- Student/class management flow
- AI agent mental health support for students and staff
- Teacher and admin reporting tools

The goal is to make digital learning easier, more organized, and more engaging for both teachers and students.

## Features

### Team Collaboration
- Secure login and registration
- Team-based dashboards and channels
- Task management and file sharing
- Direct messaging and notifications

### Attendance System
- Webcam-based face recognition
- Class and student tracking
- Attendance status updates
- CSV export and absence email reporting

### AI Mental Health Agent
- AI-assisted wellbeing guidance and support prompts
- Student-friendly educational interface
- Focused support for emotional and academic wellbeing

## Project Structure

- `index.html` — main landing page
- `login.html` — login page
- `auth.js` — authentication logic
- `script.js` — shared frontend logic
- `style.css` — shared styling
- `face-attendance/` — face recognition attendance tool
- `mental-health/` — wellness-related interface
- `Teams com/` — Flask-based collaboration system

## Requirements

### For the static frontend pages
- Any modern browser such as Chrome, Edge, or Firefox

### For the Flask application (`Teams com`)
- Python 3.9 or newer
- pip

## How to Use

### 1. Open the main website
Open the project root and launch the landing page in a browser:

```text
index.html
```

### 2. Use the login and dashboard pages
The application supports a login flow and access to collaboration tools for teachers and students.

### 3. Run the Flask team platform
From the project root, open a terminal and run:

```bash
cd "Teams com"
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

Then open:

```text
http://localhost:5000
```

### 4. Use the face attendance system
Open the attendance feature directly from the browser:

```text
face-attendance/index.html
```

Allow camera access when prompted. The system can detect faces and mark attendance in the browser without uploading data to a server.

## Quick Start

### Frontend preview
- Open `index.html` in your browser.

### Collaboration app
- Run the Flask app from the `Teams com` folder.

### Face attendance
- Open `face-attendance/index.html` and enable the camera.

## Notes

- The attendance system is browser-based and uses local processing for face detection.
- The collaboration platform is built with Flask and SQLite for local development.
- For production deployment, configure secure environment settings and deploy behind a proper web server.

## License

This project is intended for educational and demonstration purposes and can be adapted for classroom or academic use.
