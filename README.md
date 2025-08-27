# School Club Manager

## Introduction

A full-stack application designed to help students manage extracurricular clubs efficiently. The platform allows students to discover clubs, apply to them, and stay updated. Club owners have the ability to manage members, events, and announcements seamlessly.  

---

## ✨ Features

- **Club Management**

  - Create, edit, and delete clubs.
  - View club details and member lists.
  - Update club information and images.

- **Application System**

  - Students can browse clubs and submit applications.
  - Support for general and role-specific application questions.
  - Application status tracking for students.
  - Club leaders can review, accept, or reject applications.

- **Announcements**

  - Club leaders can post announcements visible to members and applicants.
  - Centralized dashboard for viewing all club announcements.

- **Dashboard & Analytics**

  - Admin and club leader dashboards for monitoring club activity.
  - View statistics on applications, membership, and selection results.

- **User Authentication & Roles**

  - Secure registration and login for students and admins.
  - Role-based access control (student, club leader, admin).
  - Manage permissions and club leadership assignments.

- **Selection Results**

  - Club leaders can publish selection results.
  - Students can view their application outcomes.

- **Responsive Frontend**
  - Modern, mobile-friendly UI using HTML, CSS, and JavaScript.
  - Organized templates for easy navigation and usability.

---

## 🛠️ Tech Stack

- **Backend**

  - **Python 3.x**
  - **Flask**: Lightweight web framework for routing, request handling, and session management.
  - **WTForms**: For building and validating web forms.
  - **SQLite**: Embedded database for storing users, clubs, applications, and other data.

- **Frontend**

  - **HTML5**: Structure of web pages.
  - **CSS3**: Styling and responsive design (custom stylesheets in `static/css/`).
  - **JavaScript**: Client-side interactivity (custom scripts in `static/js/`).

- **Templates**

  - **Jinja2**: Flask’s templating engine for dynamic HTML rendering.

## 📝 Project Structure
  - `clubmanager/`: Main application package containing forms, models, utility functions, and route handlers.
  - `static/`: Static assets (CSS, JS, images).
  - `templates/`: HTML templates for all pages.
  - `run.py`: Application entry point.
  - `schoolclubmanager.db`: SQLite database file.
  - `requirement.txt`: List of required Python packages.

---

## How to Run

Follow these steps to set up and run the School Club Manager project:

1. **Install Python 3.x**  
   Make sure Python 3.x is installed on your system.

2. **Install dependencies**  
   Open a terminal in the project directory and run:

```
pip install -r requirement.txt
```

3. **Initialize the database (if not already present)**  
   The file `schoolclubmanager.db` should exist. If not, run the app once to auto-create it, or use a provided script if available.

4. **Run the application**  
   In the project directory, execute:

```
python run.py
```

5. **Access the web app**  
   Open your browser and go to:

```
http://localhost:5000
```

6. **Register and start using the platform**

- Register as a student or admin.
- Browse clubs, apply, manage, and interact as needed.
