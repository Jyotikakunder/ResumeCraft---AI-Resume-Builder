# ResumeCraft — AI Resume Builder

ResumeCraft is a modern, responsive resume-building web application designed to help users create professional resumes quickly and easily.

The application provides a clean resume-building interface where users can enter their personal information, education, skills, work experience, projects, certifications, languages, and achievements. Users can preview their resume, switch between templates, customize preferences, and print or save their resume as a PDF.

## Features

### Landing Page

* Professional and responsive landing page
* Introduction to ResumeCraft
* Features overview
* Resume template showcase
* How-it-works section
* FAQ section
* Call-to-action sections

### User Authentication

* Login page
* Signup page
* Forgot password interface
* Password visibility toggle
* Password strength indicator
* Logout functionality
* Demo authentication using browser localStorage

### Dashboard

* Create a new resume
* View saved resumes
* Search resumes
* Edit resumes
* Delete resumes
* Manage resume data

### Resume Builder

Users can create a complete resume with sections such as:

* Full name
* Profile photo
* Email
* Phone number
* Address
* LinkedIn
* GitHub
* Personal website
* Professional summary
* Education
* Technical skills
* Soft skills
* Work experience
* Projects
* Certifications
* Languages
* Achievements
* Awards
* Hackathons
* Volunteer experience

### Resume Templates

ResumeCraft includes multiple resume styles:

* Modern
* Clean
* Executive

Users can switch between templates while creating their resume.

### Live Preview

* Real-time resume preview
* Professional formatting
* Responsive preview
* Template switching
* Print-friendly resume
* PDF generation through browser print functionality

### Profile Management

* Edit personal information
* Upload profile photo
* Add professional links
* Update phone and location
* Change password interface
* View account information

### Settings

* Dark mode
* Light mode
* Interface themes
* Font preferences
* Default resume template
* A4/Letter page preference
* Auto-save preference
* Profile photo preference
* Notification preferences
* Account management

### Data Storage

The current frontend version uses browser `localStorage` to store:

* User information
* Profile information
* Resume information
* Profile photo
* Template preferences
* Theme preferences
* Notification settings
* Resume settings

## Technologies Used

* HTML5
* CSS3
* JavaScript
* LocalStorage API
* Responsive Web Design
* Browser Print API

## Project Structure

```text
ResumeCraft/
│
├── index.html
├── login.html
├── signup.html
├── forgot-password.html
├── dashboard.html
├── resume-builder.html
├── preview.html
├── profile.html
├── settings.html
│
└── README.md
```

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

Open the project folder in VS Code or another code editor.

### 3. Run the application

You can simply open:

```text
index.html
```

in your browser.

For a better development experience, you can use the **Live Server** extension in VS Code.

### 4. Create an account

Open the signup page and create a demo account.

The application stores the account and resume information locally in the browser using `localStorage`.

## Application Flow

```text
Landing Page
      ↓
   Sign Up
      ↓
    Login
      ↓
  Dashboard
      ↓
Resume Builder
      ↓
 Live Preview
      ↓
Print / Save as PDF
```

## Resume Creation Flow

```text
Personal Information
        ↓
Professional Summary
        ↓
Education
        ↓
Skills
        ↓
Work Experience
        ↓
Projects
        ↓
Certifications
        ↓
Languages
        ↓
Achievements
        ↓
Choose Template
        ↓
Preview Resume
        ↓
Print / Save as PDF
```

## Responsive Design

ResumeCraft is designed to work across different screen sizes.

The interface adapts to:

* Desktop
* Laptop
* Tablet
* Mobile devices

Responsive layouts are implemented using CSS media queries.

## Data Storage

This version of ResumeCraft is a frontend-based project.

User and resume information is stored using the browser's `localStorage` API.

Example:

```javascript
localStorage.setItem(
  "resumeCraftProfile",
  JSON.stringify(profile)
);
```

This allows the application to retain data when the user refreshes the browser.

> Note: localStorage is suitable for a frontend demonstration but should not be used for storing sensitive production credentials or passwords.

## Future Improvements

The project can be extended with a proper backend and additional AI functionality.

Planned improvements include:

* AI-generated professional summaries
* AI skill suggestions
* AI-generated project descriptions
* AI-generated cover letters
* Resume ATS score
* Resume keyword suggestions
* Drag-and-drop section ordering
* Resume sharing links
* Cloud-based resume storage
* User authentication with a backend
* Database integration
* Secure password management
* Import existing resumes
* Export resumes directly as PDF
* More professional resume templates
* Job-description based resume optimization

## Future Technology Stack

A future full-stack version could use:

```text
Frontend
HTML + CSS + JavaScript

Backend
Node.js + Express.js

Database
MongoDB / MySQL

Authentication
JWT / Secure Authentication

AI
AI API for resume assistance

Deployment
Vercel / Netlify / Render
```

## Screens / Pages

The project contains the following major pages:

| Page                   | Purpose              |
| ---------------------- | -------------------- |
| `index.html`           | Landing page         |
| `login.html`           | User login           |
| `signup.html`          | Account creation     |
| `forgot-password.html` | Password recovery UI |
| `dashboard.html`       | Resume management    |
| `resume-builder.html`  | Resume creation      |
| `preview.html`         | Resume preview       |
| `profile.html`         | User profile         |
| `settings.html`        | Application settings |

## Key Highlights

* Clean professional UI
* Responsive design
* Multiple resume templates
* Live resume preview
* Browser-based data persistence
* Profile management
* Theme customization
* Dark mode
* Resume printing
* Modular multi-page structure
* Beginner-friendly frontend implementation

## Project Purpose

ResumeCraft was developed as a practical web development project to demonstrate frontend development skills, responsive UI design, JavaScript functionality, browser-based data storage, and the implementation of a complete resume-building workflow.

## Disclaimer

ResumeCraft is currently a frontend/demo application. Authentication, password management, database storage, and AI features are represented through frontend interfaces and local browser storage. A production version would require a secure backend, database, authentication system, and server-side validation.

## Author

**Jyotika Kunder**

BCA Student | Web Development Enthusiast

---

⭐ If you found this project useful, consider giving the repository a star!
