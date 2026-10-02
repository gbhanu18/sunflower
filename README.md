# Sunflower

Full-stack web app with a React frontend and a Python backend that serves trained ML models.

> TODO: Replace this line with 1-2 sentences on what Sunflower does and who it's for.

## Live demo

- Frontend: TODO (Vercel link)
- Backend API: TODO (Render link)

## Features

- User login and authentication
- Dashboard with analysis tools and results
- History of past analyses
- Profile and settings pages
- PDF export of results
- TODO: add your main feature (e.g. model predictions)

## Tech stack

**Frontend:** React, TypeScript, Vite, Tailwind CSS, shadcn/ui, deployed on Vercel

**Backend:** Python, Flask, trained ML models (Jupyter notebooks for training), Docker, deployed on Render

## Project structure

```
sunflower/
├── frontend/   # React + Vite app
└── backend/    # Python API, models and trained model files
```

## Getting started

### Backend

```bash
cd backend
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # macOS/Linux
pip install -r requirements.txt
python server.py
```

### Frontend

```bash
cd frontend
cp .env.example .env         # set the backend URL inside .env
npm install
npm run dev
```

The frontend runs at `http://localhost:5173` by default.

## Environment variables

Copy `frontend/.env.example` to `frontend/.env` and fill in the values, for example the backend API URL.

## Screenshots

TODO: add 2-3 screenshots of the dashboard and results page.

## Author

Gujjala Bhanuprakash
GitHub: [@gbhanu18](https://github.com/gbhanu18)
