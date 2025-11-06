# Real-time Chat Application

A modern real-time chat application built with MERN stack (MongoDB, Express.js, React, Node.js) and Socket.IO.

## Features

- 🔐 User authentication
- 💬 Real-time messaging
- 🖼️ Image sharing
- 👤 User profiles
- 🔄 Online status indicators
- 📱 Responsive design

## Tech Stack

- **Frontend:**
  - React.js
  - Tailwind CSS
  - DaisyUI
  - Zustand for state management
  - Socket.IO client

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Socket.IO
  - JWT authentication

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/Akshat2gupta/Realtimechat-v1.git
cd real-time-chat
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd frontend
npm install
```

4. Set up environment variables
```bash
# In backend/.env
PORT=5001
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

# In frontend/.env
VITE_SERVER_URL=http://localhost:5001
```

### Running the Application

1. Start the backend server
```bash
cd backend
npm run dev
```

2. Start the frontend development server
```bash
cd frontend
npm run dev
```

The application will be available at `http://localhost:5173`

## Author

- **Akshat Gupta**
- Email: akshat2gupta@gmail.com

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.