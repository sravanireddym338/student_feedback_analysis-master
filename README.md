# Student Feedback Analysis

A simple Python web application for collecting and analyzing student feedback about courses and trainers.

## Overview
This project uses Flask to provide a small feedback portal where students can submit ratings and comments, and admins can view summarized analytics.

## Features
- Student feedback form
- Course and trainer selection
- Section-wise rating analysis
- Average score dashboard
- Bar chart visualization
- JSON endpoints for reports

## Tech Stack
- Python
- Flask
- MySQL
- Matplotlib
- HTML/CSS/JavaScript

## Project Files
- `app.py` - Main Flask app and routes
- `config.py` - MySQL database connection settings
- `seed_responses.py` - Script to insert sample feedback data
- `document.md` - Additional project documentation

## Requirements
- Python 3
- MySQL Server
- pip

## Setup
1. Clone the repository.
2. Open the project folder.
3. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

4. Install dependencies:

```bash
pip install flask mysql-connector-python matplotlib
```

5. Create a MySQL database and update the connection details in `config.py`.

## Run the Application
```bash
python app.py
```

Then open:

```text
http://127.0.0.1:5000/
```

## Main Routes
- `/` - Home page
- `/feedback-form` - Student feedback form
- `/analysis` - Admin dashboard
- `/chart.png` - Feedback chart image
- `/admin/trainers-by-course-json` - Course/trainer JSON data
- `/admin/student-details-json` - Student review JSON data

## Notes
This is a basic student feedback and analytics project intended for academic or learning use.
