# **Travel Story App**


A modern web application for documenting and sharing your travel experiences through personalized stories and photos.
📱 Demo Screenshots

Dashboard

Show Image

Beautifully organized travel stories with location tags
Interactive cards featuring stories from 
Like/favorite functionality for saving memorable stories
Clean, intuitive interface with easy navigation

Authentication Screens
Show Image

Modern, user-friendly signup and login interfaces
Stunning travel imagery that inspires adventure
Streamlined user authentication process
Responsive design that works across all devices

✨ Features

User Authentication

Secure signup and login functionality
JWT-based authentication system
Password protection with encryption


Story Management

Create and publish travel stories
Add location tags and dates
Upload and manage travel photos
Edit and customize story content


Interactive Elements

Like/favorite stories for quick access
Location-based story organization
Date-based story tracking


Responsive Design

Modern, clean user interface
Mobile-first approach
Seamless experience across devices



🚀 Getting Started
Prerequisites

Node.js (v14 or higher)
MongoDB (local or cloud instance)
npm or yarn package manager

Installation

Clone the repository

bashCopygit clone https://github.com/yourusername/travel-story-app.git
cd travel-story-app

Install dependencies

bashCopynpm install

Configure environment variables
Create a .env file in the root directory:

envCopyPORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

Start the development server

bashCopynpm run dev
The application will be available at:

Frontend: http://localhost:5173
Backend: http://localhost:8000

💻 Tech Stack
Frontend

React.js
Tailwind CSS
React Router
Axios for API calls

Backend

Node.js
Express.js
MongoDB
JWT for authentication
Multer for image uploads

Database

MongoDB Atlas

📝 Usage Guide
Creating an Account

Navigate to the signup page
Enter your full name, email, and password
Click "CREATE ACCOUNT" to register

Logging In

Visit the login page
Enter your registered email and password
Click "LOGIN" to access your dashboard

Managing Stories

Click the "+" button on the dashboard to create a new story
Fill in the story details:

Title
Description
Location
Photos


Use the edit and delete options to manage existing stories
Click the heart icon to favorite stories
