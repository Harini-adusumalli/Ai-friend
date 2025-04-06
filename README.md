# AI Friend - Mental Health Support Application

A web application that provides mental health support through AI-powered chat, mood tracking, journaling, and self-care features.

![AI Friend Screenshot](images/screenshot.png)

## 🌟 Features

- 🤖 **AI-Powered Chat Support**
  - Real-time conversation with AI
  - Emotionally intelligent responses
  - Context-aware interactions

- 📊 **Mood Tracking**
  - Daily mood logging
  - Mood analytics and trends
  - Personalized insights

- 📝 **Journaling**
  - Secure private journal
  - AI-powered writing prompts
  - Emotion analysis

- 🧘 **Self-Care Tools**
  - Guided meditation
  - Breathing exercises
  - Personalized recommendations

- 🔐 **Security**
  - JWT-based authentication
  - Password hashing
  - Secure API endpoints

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- Google Gemini API key
- npm or yarn package manager

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/ai-friend.git
cd ai-friend
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
   - Copy `.env.example` to `.env`
   - Fill in your credentials:
```env
# Server Configuration
PORT=5000
NODE_ENV=development

# MongoDB Configuration
MONGODB_URI=your_mongodb_connection_string

# JWT Configuration
JWT_SECRET=your_secure_jwt_secret
JWT_EXPIRES_IN=24h

# Gemini AI Configuration
GEMINI_API_KEY=your_gemini_api_key

# CORS Configuration
ALLOWED_ORIGINS=http://localhost:3000,http://localhost:5000

# Security
BCRYPT_SALT_ROUNDS=12
```

4. **Start the development server**
```bash
npm start
```

## 🛠️ Project Structure

```
ai-friend/
├── server/                 # Backend server code
│   ├── routes/            # API routes
│   ├── middleware/        # Custom middleware
│   ├── services/          # Business logic
│   └── scripts/           # Utility scripts
├── js/                    # Frontend JavaScript
├── css/                   # Stylesheets
├── images/                # Static images
└── *.html                 # Frontend pages
```

## 🔒 Security Features

- **Authentication**
  - JWT-based authentication
  - Password hashing with bcrypt
  - Secure session management

- **Data Protection**
  - Environment variable protection
  - Input validation and sanitization
  - CORS protection

- **API Security**
  - Rate limiting
  - Request validation
  - Error handling

## 📚 API Documentation

### Authentication Endpoints

- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout

### Chat Endpoints

- `POST /api/chat/send` - Send message to AI
- `GET /api/chat/history` - Get chat history

### Journal Endpoints

- `POST /api/journal/entry` - Create journal entry
- `GET /api/journal/entries` - Get journal entries
- `DELETE /api/journal/entry/:id` - Delete journal entry

### Mood Tracking Endpoints

- `POST /api/mood/log` - Log mood
- `GET /api/mood/history` - Get mood history
- `GET /api/mood/analytics` - Get mood analytics

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Google Gemini AI for the chat capabilities
- MongoDB for database support
- All contributors and supporters of the project

## 📞 Support

For support, email support@aifriend.com or join our [Discord community](https://discord.gg/aifriend).

## 📈 Roadmap

- [ ] Mobile app development
- [ ] Group therapy sessions
- [ ] Voice chat support
- [ ] Multi-language support
- [ ] Advanced analytics dashboard 
