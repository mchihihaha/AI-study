# AI-Study: AI-Powered Learning Platform

An intelligent learning platform that combines time management, AI-powered study optimization, and adaptive practice testing.

## 🎯 Features

### Core Features
- **📅 Time Management & Task Scheduling** - Organize learning schedule with smart reminders
- **🤖 AI-Powered Study Assistant** - Get personalized learning recommendations
- **📝 Smart Notes & Slide Optimization** - AI extracts key concepts from study materials
- **📚 Practice Testing & Exam Simulation** - AI-generated quizzes with detailed feedback
- **📊 Learning Analytics** - Track progress and optimize study patterns
- **👥 Multi-User Support** - Full authentication and user management
- **🎓 Adaptive Learning Paths** - AI suggests optimal study sequences

### AI Capabilities
- Automatic slide content extraction and summarization
- Intelligent quiz generation based on study materials
- Real-time study recommendations
- Performance analysis and weakness identification
- Content optimization for better retention

## 🏗️ Architecture

```
AI-study/
├── frontend/                 # React + TypeScript frontend
├── backend/                  # Node.js + Express backend
├── database/                 # MongoDB schemas
├── ai-service/              # AI integration service
└── docker-compose.yml       # Docker orchestration
```

## 🚀 Tech Stack

### Frontend
- React 18 + TypeScript
- TailwindCSS for styling
- Redux for state management
- Axios for API calls

### Backend
- Node.js + Express
- MongoDB for database
- JWT for authentication
- OpenAI API integration

### Infrastructure
- Docker & Docker Compose
- Environment-based configuration

## 📋 Project Structure

- `frontend/` - React web application
- `backend/` - Express.js API server
- `database/` - MongoDB models and schemas
- `ai-service/` - AI service for OpenAI integration
- `docs/` - Documentation

## 🔧 Setup Instructions

### Prerequisites
- Node.js 16+
- MongoDB
- OpenAI API Key
- Docker (optional)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/mchihihaha/AI-study.git
cd AI-study
```

2. **Setup Environment Variables**
```bash
cp .env.example .env
# Edit .env with your configuration
```

3. **Install Dependencies**
```bash
# Backend
cd backend && npm install

# Frontend
cd ../frontend && npm install
```

4. **Start Services**
```bash
# Using Docker Compose
docker-compose up -d

# Or manually
# Terminal 1: Backend
cd backend && npm run dev

# Terminal 2: Frontend
cd frontend && npm start
```

## 📚 API Endpoints

### Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/refresh` - Refresh token

### Study Management
- `GET /api/study/tasks` - Get all study tasks
- `POST /api/study/tasks` - Create new task
- `PUT /api/study/tasks/:id` - Update task
- `DELETE /api/study/tasks/:id` - Delete task

### AI Features
- `POST /api/ai/summarize` - Summarize study content
- `POST /api/ai/generate-quiz` - Generate quiz questions
- `POST /api/ai/analyze-performance` - Analyze learning performance
- `POST /api/ai/recommend-content` - Get study recommendations

### Analytics
- `GET /api/analytics/progress` - Get learning progress
- `GET /api/analytics/weaknesses` - Identify weak areas
- `GET /api/analytics/insights` - Get learning insights

## 🤖 AI Integration

### OpenAI API Usage
- **GPT-4/GPT-3.5** for content summarization and recommendations
- **Embedding API** for semantic search and content matching
- **Fine-tuning** for personalized learning patterns

### Features
1. **Content Summarization** - Extract key points from slides/notes
2. **Quiz Generation** - Create smart practice questions
3. **Performance Analysis** - Identify learning gaps
4. **Adaptive Recommendations** - Suggest optimal study paths

## 📖 Learning Features

### Study Planning
- Create study schedules and goals
- Set time blocks for different subjects
- Track completion and adjust plans

### Practice Testing
- AI-generated quizzes tailored to content
- Multiple difficulty levels
- Detailed answer explanations
- Performance analytics

### Content Optimization
- Slide analysis and summarization
- Key concept extraction
- Visual learning enhancement
- Study material recommendations

## 🔐 Security

- JWT-based authentication
- Password hashing with bcrypt
- Rate limiting on API endpoints
- CORS configuration
- Environment-based secrets

## 🤝 Contributing

Contributions are welcome! Please follow the contribution guidelines.

## 📄 License

MIT License - see LICENSE file for details

## 📞 Support

For issues, questions, or suggestions, please open an issue on GitHub.

---

**Built with ❤️ for better learning**
