# Portfolio

A modern, responsive portfolio website with user authentication system built using HTML, CSS, JavaScript, Node.js, Express, and MongoDB. This project showcases my skills in full-stack web development and provides a secure platform for portfolio management.

## Features

- 🎨 Modern and responsive design
- 🌓 Dark/Light theme toggle
- 🔒 User authentication system
  - User registration
  - User login
  - Remember me functionality
  - Secure password handling
  - JWT-based authentication
- 📱 Mobile-friendly interface
- 📝 Contact form
- 🖼️ Portfolio showcase
- 💼 Skills section
- 👤 About section

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome Icons

### Backend
- Node.js
- Express.js
- MongoDB
- JWT (JSON Web Tokens)
- bcryptjs for password hashing

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/try/download/community) (v4.4 or higher)
- npm (Node Package Manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Mubiru/Portfolio.git
cd Portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following content:
```env
MONGODB_URI=mongodb://localhost:27017/portfolio
JWT_SECRET=your-secret-key-here
PORT=3000
```

4. Start MongoDB service on your system

5. Start the server:
```bash
npm start
```

6. Open your browser and navigate to:
```
http://localhost:3000
```

## Project Structure

```
Portfolio/
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── script.js
│   │   └── auth.js
│   └── images/
├── server.js
├── package.json
├── .env
└── README.md
```

## API Endpoints

- `POST /api/register` - Register a new user
- `POST /api/login` - Login user
- `GET /api/profile` - Get user profile (protected route)
- `POST /api/logout` - Logout user

## Features in Detail

### Authentication System
- Secure user registration with password hashing
- JWT-based authentication
- Remember me functionality
- Protected routes
- Session management

### Portfolio Features
- Responsive design for all screen sizes
- Dark/Light theme toggle with local storage
- Smooth scrolling navigation
- Dynamic content loading
- Contact form with validation

## Security Features

- Password hashing using bcryptjs
- JWT token-based authentication
- Protected API routes
- Input validation and sanitization
- Secure session management

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Mubiru - [mubiru@example.com](mailto:mubiru@example.com)

Project Link: [https://github.com/Mubiru/Portfolio](https://github.com/Mubiru/Portfolio) 
