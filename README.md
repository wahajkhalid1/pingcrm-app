# PingCRM App

A modern CRM application built with React + TypeScript (Frontend) and FastAPI (Backend).

## Tech Stack

- **Frontend**: React + TypeScript + Vite
- **Backend**: FastAPI
- **Database**: PostgreSQL (via Supabase/Neon)
- **Deployment**:
  - Frontend: Vercel
  - Backend: koyeb

## Prerequisites

- Node.js (v18 or higher)
- Python 3.9+
- npm or yarn package manager
- PostgreSQL database (local or cloud)

## Project Structure

```
pingcrm-app/
├── frontend/           # React frontend application
│   ├── src/           # Source code
│   ├── public/        # Static assets
│   └── package.json   # Frontend dependencies
├── backend/           # FastAPI backend application
│   ├── app/          # Application code
│   ├── tests/        # Test files
│   └── requirements.txt # Backend dependencies
└── README.md         # Project documentation
```

## Local Development Setup

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the backend directory:
```env
DATABASE_URL=postgresql://user:password@localhost:5432/pingcrm
SECRET_KEY=your-secret-key
```

5. Start the backend server:
```bash
uvicorn app.main:app --reload
```

The backend API will be available at `http://localhost:8000`

## Database Setup

1. Create a PostgreSQL database:
```bash
createdb pingcrm
```

2. Update the `DATABASE_URL` in your backend `.env` file with your database credentials.


## Deployment URLs

- Frontend: [https://pingcrm-frontend-8e9e.vercel.app/]
- Backend: [https://external-stevena-wahaj-17ce92c7.koyeb.app/docs]

## Project Status

### Completed Features
- [ ] Frontend setup with React + TypeScript
- [ ] Backend setup with FastAPI
- [ ] Database integration
- [ ] Basic CRUD operations


### Time Spent
- 2.5 hours

## AI Tools Used
- [ ] ChatGPT
- [ ] Cursor

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

## License

[Add your license information here]
