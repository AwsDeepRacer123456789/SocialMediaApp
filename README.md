ConnectSpace - MERN Social App
A fully responsive social media web application built using the MERN stack. This project supports authentication, real-time interaction features like comments, post filtering, pagination, and a modern UI. It was a great opportunity to deepen my understanding of full-stack development and apply best practices for scalable web applications.

🚀 Key Features
Create, edit, delete, and like posts

Email & Google Sign-In (OAuth 2.0)

Filter posts by search keywords or tags

View post details with similar recommendations

Leave and view comments on individual posts

Paginated post browsing for better performance

Clean, responsive UI with Material-UI

⚙️ Technologies Used
Frontend

React.js

Redux Toolkit

Material-UI

Backend

Node.js

Express.js

MongoDB Atlas

JWT Authentication

Google OAuth API

Deployment

Frontend: Netlify

Backend: Render or Railway

🛠 Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/connectspace.git
cd connectspace
Install frontend & backend dependencies

bash
Copy
Edit
cd client
npm install
cd ../server
npm install
Add environment variables

Create a .env file inside the server/ directory:

env
Copy
Edit
PORT=5000
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_secret
GOOGLE_CLIENT_ID=your_google_client_id
Run locally

Start the backend server: npm start (in server/)

Start the frontend client: npm start (in client/)

App will be running on http://localhost:3000

📁 Project Structure
bash
Copy
Edit
connectspace/
├── client/         # React frontend
├── server/         # Express backend
└── README.md
🖼 Preview

📌 Learnings
This project helped me:

Implement full-stack authentication (JWT + OAuth)

Use Redux effectively for global state

Understand RESTful API design

Improve performance using pagination

Apply Material-UI for responsive design systems

