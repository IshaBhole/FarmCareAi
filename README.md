w # FarmCare AI - Smart Farming Solution

A comprehensive AI-powered platform that revolutionizes agriculture through intelligent crop recommendations, disease detection, soil analysis, and yield prediction.

## 🏗️ Project Structure

```
FarmCareAi/
├── frontend/                    # React TypeScript Frontend
│   ├── src/                    # Source code
│   │   ├── components/         # Reusable UI components
│   │   ├── pages/             # Page components and routes
│   │   ├── store/             # State management (Zustand)
│   │   ├── lib/               # External integrations (Firebase, etc.)
│   │   ├── types/             # TypeScript definitions
│   │   └── ai/                # AI-related utilities
│   ├── public/                # Static assets (images, videos)
│   ├── package.json           # Frontend dependencies
│   └── README.md              # Frontend documentation
│
├── backend/                    # Python Flask Backend
│   ├── app.py                 # Main Flask application
│   ├── crop_model.pkl         # Pre-trained ML model
│   ├── train.py               # Model training script
│   ├── requirements.txt       # Python dependencies
│   └── README.md              # Backend documentation
│
├── supabase/                   # Database migrations
├── package.json               # Root project configuration
└── README.md                  # This file
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher)
- Python (v3.8 or higher)
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd FarmCareAi
   ```

2. **Install all dependencies:**
   ```bash
   npm install
   npm run install-all
   ```

3. **Start the development environment:**
   ```bash
   npm run dev
   ```

This will start both frontend (http://localhost:5173) and 
backend (http://127.0.0.1:5000) servers concurrently.

## 📁 Folder Descriptions

### 🎨 Frontend (`/frontend`)
**Purpose**: User interface and client-side functionality

**Contains**:
- React TypeScript application
- UI components and pages
- State management
- Authentication logic
- Static assets (images, videos)
- Build configuration files

**Key Technologies**: React, TypeScript, Tailwind CSS, Vite, Firebase

### 🔧 Backend (`/backend`)
**Purpose**: Server-side logic and API services

**Contains**:
- Flask web server
- Machine learning models
- API endpoints
- Data processing scripts
- Training datasets
- Python dependencies

**Key Technologies**: Flask, scikit-learn, pandas, joblib

### 🗄️ Database (`/supabase`)
**Purpose**: Database schema and migrations

**Contains**:
- SQL migration files
- Database structure definitions

## 🛠️ Development Commands

### Root Level Commands
```bash
npm run dev          # Start both frontend and backend
npm run frontend     # Start only frontend
npm run backend      # Start only backend
npm run install-all  # Install all dependencies
npm run build        # Build frontend for production
```

### Frontend Commands
```bash
cd frontend
npm run dev          # Development server
npm run build        # Production build
npm run preview      # Preview production build
npm run lint         # Code linting
```

### Backend Commands
```bash
cd backend
python app.py        # Start Flask server
python train.py      # Train ML model
pip install -r requirements.txt  # Install Python deps
```

## 🌟 Features

- **Crop Recommendations**: AI-powered suggestions based on soil and weather data
- **Disease Detection**: Image-based plant disease identification
- **Soil Testing**: Comprehensive soil analysis and recommendations
- **Yield Prediction**: Forecast crop yields using machine learning
- **Market Insights**: Real-time market data and pricing
- **Treatment Plans**: Customized treatment recommendations
- **Weather Integration**: Real-time weather data and forecasts
- **User Authentication**: Secure user accounts and data management

## 🔗 API Endpoints

### Backend API (Port 5000)
- `GET /health` - Health check
- `POST /predict` - Crop recommendation prediction

### Frontend (Port 5173)
- `/` - Homepage
- `/signin` - User sign in
- `/signup` - User registration
- `/dashboard` - Main dashboard
- `/dashboard/soil-testing` - Soil analysis
- `/dashboard/crop-recommendations` - Crop suggestions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Team

FarmCare AI Development Team

## 📞 Support

For support and questions, please open an issue on GitHub or contact our team.

---

**Happy Farming! 🌱**
