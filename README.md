# WCC-demo
# WCC Project Analyzer — Demo Project

## Project Information

**Project Name:** WCC Project Analyzer

**Track:** Everyday Automation

**Team Name:** Team Alpha

---

## Problem

Hackathon participants often spend a significant amount of time manually checking whether their project is ready for submission.

Important items such as:

- Project information
- Public repository
- README
- Demo URL
- Required files
- Problem evidence

can easily be missed before submission.

---

## Solution

WCC Project Analyzer is a participant-facing pre-submission readiness checker.

It analyzes a project's submission information and performs automated checks where possible.

The system helps participants identify missing or unverifiable submission items before they submit their project through the official submission process.

---

## Features

- Project information validation
- Public GitHub repository verification
- README verification
- Required repository file verification
- Demo URL reachability verification
- Human-review indicators for requirements that cannot be automatically verified
- Re-check support

---

## Demo

**Demo URL:**

https://example.com

> Note: A reachable demo URL only confirms that an HTTP response can be received. It does not prove that the application is fully functional.

---

## Repository

**GitHub Repository:**

https://github.com/example/wcc-project-analyzer

---

## Technology Stack

### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS

### Backend

- Python
- FastAPI
- SQLAlchemy
- Pydantic

### Database

- SQLite for local development
- PostgreSQL-compatible architecture for production

---

## Backend API

The backend provides:

### Health

```text
GET /health
