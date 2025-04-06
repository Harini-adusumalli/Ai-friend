# AI Friend - Mental Health Support Application

A web application that provides mental health support through AI-powered chat, mood tracking, journaling, and self-care features.

## Features

- 🤖 AI-powered chat support
- 📊 Mood tracking and analytics
- 📝 Journaling capabilities
- 🧘 Self-care recommendations
- 🔐 Secure user authentication
- 💬 Real-time chat interface

## Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- Google Gemini API key
- npm or yarn package manager

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-friend.git
cd ai-friend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:
```env
PORT=5000
NODE_ENV=development
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=24h
GEMINI_API_KEY=your_gemini_api_key
ALLOWED_ORIGINS=http://localhost:3000,http://localhost:5000
BCRYPT_SALT_ROUNDS=12
```

4. Start the development server:
```bash
npm start
```

## Security

This application implements several security measures:
- JWT-based authentication
- Password hashing with bcrypt
- CORS protection
- Environment variable protection
- Input validation and sanitization

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google Gemini AI for the chat capabilities
- MongoDB for database support
- All contributors and supporters of the project 
