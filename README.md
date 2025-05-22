# User Registration Application

A simple user registration application with MongoDB integration.

## Project Structure

```
/
├── pages/
│   └── index.html  # Frontend HTML form for user registration
├── api/
│   └── add-user.js # Backend API for handling user registration
├── vercel.json     # Vercel configuration
├── package.json    # Project dependencies
└── README.md       # Project documentation
```

## Features

- User registration form with name and email fields
- MongoDB integration for data storage
- Serverless API endpoint for handling form submissions
- Vercel deployment configuration

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Set up environment variables:
   Create a `.env` file with your MongoDB connection string:
   ```
   MONGODB_URI=your_mongodb_connection_string
   ```

3. Run the development server:
   ```
   npm run dev
   ```

4. Deploy to production:
   ```
   npm run deploy
   ```

## Technologies Used

- HTML/JavaScript for frontend
- Node.js for backend API
- MongoDB for database
- Vercel for serverless deployment
