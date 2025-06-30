# Rehearsal Scheduler

This project is a web app for bands and music groups to schedule rehearsals, invite members, track RSVPs, manage attendance, build setlists, and communicate—all in one place.

## Features
- Schedule rehearsals, invite members, track attendance and availability
- Manage and share setlists
- Notes and messaging for each event
- Calendar integration (Google/Apple)
- Automated reminders and notifications
- Upload/share music files and practice materials
- Mobile responsive
- Admin/member roles

## Stack
- React.js (front-end)
- Node.js (API/backend)
- PostgreSQL
- JWT authentication
- File uploads to S3
- GitHub Actions for CI/CD

## Setup
1. Clone the repository
2. See the backend and frontend setup instructions in the `/api` and `/client` folders
3. Configure environment variables (PostgreSQL, S3, mail API keys)
4. Run `npm install` in both subfolders
5. Deploy

## Deployment
See `docker-compose.yml` for container setup. Configure deployment environments (Heroku, AWS, Vercel, etc.).

## Security
All user data encrypted. Supports OAuth and industry best practices for privacy.

## Project Management
- Google Docs Project Plan: https://docs.google.com/document/d/1wQaD9U9Gfk9_7iNQyGGZlAJOQWIJg8s8uuI2T0T1Iow
- Development Tracker: https://docs.google.com/spreadsheets/d/1o7Pq6xZtu4xwDu6P6sFqmNrz16HfZdkI2h2mbtSFRnk
