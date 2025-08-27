# School Club Manager

## Introduction

School Club Manager is a comprehensive web-based platform designed to streamline the management of school clubs and student participation. The application provides an intuitive interface for students, club leaders, and administrators to interact, manage club activities, handle applications, and communicate effectively. By automating club operations, School Club Manager reduces manual workload, increases transparency, and enhances the overall experience for all users involved in school clubs.

Whether you are a student looking to join a club, a club leader managing applications and announcements, or an administrator overseeing all clubs, this platform offers tailored tools to meet your needs.

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
