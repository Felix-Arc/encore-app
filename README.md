# Encore App

## Overview
Encore is a Social Music Platform for artists and fans. 
Includes Frontend (Mobile/Web/Admin), Backend (Microservices), and feed & recommendation algorithms.

## Features
- Artist & Fan Feed with posts, images, videos
- Like, Comment, Share
- Reels / Short Clips
- Floating Action Button
- Responsive Design (Mobile & Desktop)
- Dark & Light Theme
- Admin Dashboard

## Tech Stack
### Backend
- Python + FastAPI
- PostgreSQL, Redis, Celery, Elasticsearch
- Docker & docker-compose
### Frontend
- React Native (Mobile)
- Next.js (Web)
- Admin Dashboard: React + Tailwind
### Cloud / Storage
- AWS S3, CDN
- CI/CD: GitHub Actions
- Authentication: JWT, OAuth2

## Installation / Dev Setup
### Backend
cd backend
pip install -r requirements.txt
docker-compose up

### Frontend Web
cd frontend/web
npm install
npm run dev

### Frontend Mobile
cd frontend/mobile
npm install
npm run dev

### Admin Dashboard
cd frontend/admin
npm install
npm run dev

## Project Structure
- backend/ → Microservices, shared utils, tests, Docker setup
- frontend/ → Mobile, Web, Admin
- algorithms/ → Feed & Recommendation Algorithms
- docs/ → Tech Stack & Documentation
- assets/ → Images, Icons, Logos, Sounds

## Quick Dev Tips
- Pull latest dev branch: git pull origin dev
- Create feature branch: git checkout -b feature/xyz
- Commit & push: git add . && git commit -m "feat: XYZ" && git push origin feature/xyz
- Open PR against dev → Review → Merge

## License
MIT
