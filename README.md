# Basic Login System with Node.js and Docker

A simple login system built with Node.js, Express, and Docker.

## Features

- User registration
- User login
- Password hashing
- Responsive UI
- Docker containerization

## Prerequisites

- Node.js (if running locally)
- Docker (if running with Docker)

## Running the Application

### Using Docker

1. Build the Docker image:
```bash
docker build -t login-dock .
```

2. Run the container:
```bash
docker run -p 3000:3000 login-dock
```

### Running Locally

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Security Notes

This is a basic implementation for demonstration purposes. In a production environment, you should:

1. Use a proper database instead of in-memory storage
2. Implement proper session management
3. Add CSRF protection
4. Use environment variables for sensitive data
5. Implement rate limiting
6. Add input validation and sanitization 