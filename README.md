MongoDB, Express, React, Node Project

A full-stack social media application built with the MERN Stack (MongoDB, Express, React, Node.js). This app includes powerful features like Google Authentication, pagination, post filtering, comments, and responsive design — making it one of the most complete MERN tutorials on YouTube.

🚀 Features

✅ Full CRUD for posts
🔐 Authentication with Email & Google OAuth
🔍 Search and filtering by title and tags
💬 Commenting system
📄 Paginated post feed
🧠 Recommended posts engine
📱 Fully responsive UI
🛠️ Tech Stack

Frontend: React.js, Redux, Material-UI
Backend: Node.js, Express.js, MongoDB Atlas
Authentication: JSON Web Token (JWT), Google OAuth
Deployment: Netlify (Frontend), Render/Heroku (Backend)
📦 Installation

Clone the repository:
git clone https://github.com/your-username/mern-social-media.git
cd mern-social-media
Install dependencies for both client and server:
cd client
npm install
cd ../server
npm install
Set up environment variables:
Create .env in the server folder and add:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
Run the application:
Backend: npm start
Frontend (in client/): npm start
Visit: http://localhost:3000
📁 Folder Structure

.
├── client/         # React frontend
├── server/         # Node.js backend with Express
├── README.md
🌐 Live Demo
