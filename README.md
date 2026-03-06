# SENDO

A secure file sharing application that allows users to share files through QR codes with automatic expiration. Built with a Node.js backend and vanilla JavaScript frontend, SENDO provides a simple and efficient way to share files temporarily.

## Tech Stack

### Backend
- Runtime: Node.js 18+
- Framework: Express 5
- File Upload: Multer
- QR Code Generation: qrcode
- Security: Helmet, CORS
- Unique IDs: nanoid
- Environment Variables: dotenv
- Development: nodemon

### Frontend
- Vanilla JavaScript, HTML, CSS
- Static file serving

### Deployment
- Platform: Render
- Configuration: render.yaml included

## Features

- Upload files and generate unique sharing links
- QR code generation for easy mobile access
- Automatic file expiration and cleanup
- Secure file handling with Helmet middleware
- CORS enabled for cross-origin requests
- Logging with Morgan
- Hot reload development environment

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have Node.js installed (Version 18 or higher recommended).

### Installation

1. Clone the repository
```
git clone https://github.com/kaung-h-zaw/SENDO.git
```

2. Navigate into the directory
```
cd SENDO
```

3. Install server dependencies
```
cd server
npm install
```

4. Set up environment variables

Create a .env file in the server directory with your configuration:
```
PORT=3000
BASE_URL=http://localhost:3000
```

5. Start the development server
```
npm run dev
```

The server will start on the specified port with hot reload enabled.

## Deployment

The project includes a render.yaml configuration file for easy deployment to Render. Simply connect your GitHub repository to Render and it will automatically detect the configuration.

## Project Structure

```
SENDO/
├── server/          # Backend Node.js application
│   ├── server.js    # Main server file
│   └── package.json # Server dependencies
├── web/             # Frontend static files
│   └── public/      # Static assets
├── render.yaml      # Render deployment configuration
└── LICENSE          # MIT License
```

## License

Copyright (c) 2026 Kaung Htet Zaw. All Rights Reserved.

This project is proprietary software. The source code, design, and content may not be copied, distributed, modified, or used without explicit written permission from the author. You are granted permission to view the code for the purpose of evaluating the author's skills.

## Contact

Kaung Htet Zaw - [LinkedIn](https://www.linkedin.com/in/kaung-h-zaw/)

Project Link: https://github.com/kaung-h-zaw/SENDO
