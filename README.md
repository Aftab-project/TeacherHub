# TeacherHub

TeacherHub is a teacher-focused digital classroom hub designed to support modern education through a Microsoft Teams-like platform. The project combines communication, video collaboration, attendance automation, and AI-powered student wellbeing support in one system.

## Project Introduction

This project is built around three core functions:

1. A teacher collaboration hub similar to Microsoft Teams for messaging, video calls, and meeting transcription.
2. A face recognition attendance system that automatically marks students present when they are detected.
3. An AI agent that helps teachers recognize potential student mental health concerns and suggests supportive actions.

Together, these features create a complete ecosystem for digital classroom management, communication, and student support.

## Features

### Teacher Collaboration Hub
- Secure login and registration
- Teams-style messaging and channels
- Video call support and meeting collaboration
- Meeting transcription and classroom communication tools
- File sharing, tasks, and notifications

### Face Recognition Attendance
- Webcam-based face recognition
- Automatic present/absent marking
- Class and student tracking
- Attendance status updates and reporting

### AI Mental Health Support Agent
- AI-assisted identification of possible student wellbeing concerns
- Guidance for teachers on how to support students
- Early intervention support for academic and emotional wellbeing

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
