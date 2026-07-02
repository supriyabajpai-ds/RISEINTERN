# RiseIntern

RiseIntern is a web-based internship management and recommendation platform designed to bridge the gap between students and recruiters. The platform provides dedicated dashboards for students, recruiters, and administrators, enabling seamless internship posting, application management, and candidate selection.

🔗 **Live Demo:** [rise-intern.vercel.app](https://rise-intern.vercel.app)

## Overview

The platform streamlines the internship lifecycle end-to-end — from students discovering relevant opportunities to recruiters managing applicants to admins overseeing the whole system.

## Features

- **Student Dashboard** — Browse and apply to internships, track application status
- **Recruiter Dashboard** — Post internships, review and manage candidate applications
- **Admin Dashboard** — Oversee platform activity, manage users and listings
- **Authentication** — Login flow for students and recruiters
- **Smart Recommendations** — NLP-based matching to surface relevant internships for students
- **Chatbot** — In-app assistant to help users navigate the platform

## Tech Stack

- HTML, CSS, JavaScript (frontend pages for each dashboard/role)
- JSON-based internship data store
- NLP-driven recommendation logic

## My Contribution

This was a group project built with a team. I worked on the **database and NLP components**, collaborating closely with a teammate on:
- Structuring and managing the internship data used across the platform
- Building the NLP-based logic behind the recommendation/chatbot functionality

Other team members contributed the dashboard UIs (student, recruiter, admin) and authentication flows.

## Project Structure

```
├── index.html          # Landing page
├── login.html / login2.html      # Authentication
├── student2.html        # Student dashboard
├── recruiter2.html       # Recruiter dashboard
├── admin.html / admin2.html      # Admin dashboard
├── bot.html            # NLP chatbot interface
├── intern.json          # Internship data
└── re.html
```

## Getting Started

Clone the repo and open `index.html` in your browser, or visit the [live demo](https://rise-intern.vercel.app).

```bash
git clone https://github.com/supriyabajpai-ds/RISEINTERN.git
```
