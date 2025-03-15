project Live link below 
https://cerebrascoder.com/p/420936
![Image](https://github.com/user-attachments/assets/b9c6296f-edfb-434d-9860-25c746dbb904)

MERN Stack App - User Authentication, Agent Management, and CSV Upload
This is a MERN (MongoDB, Express.js, React.js, Node.js) Stack application that includes user authentication, agent management, CSV file upload, and task distribution.

🚀 Features
✅ User Authentication (Login with JWT)
✅ Agent Management (Add, View Agents)
✅ CSV File Upload (Process and Distribute)
✅ MongoDB Integration
✅ Secure API with Express.js
✅ React.js Frontend with Material UI

📁 Project Structure
bash
Copy
Edit
MERN-Project/
├── backend/
│   ├── models/          # Mongoose models
│   ├── routes/          # API Routes
│   ├── config/          # Database config
│   ├── middleware/      # Authentication middleware
│   ├── server.js        # Main backend file
│   ├── package.json     # Backend dependencies
│   ├── .env             # Environment variables
│
├── frontend/
│   ├── src/
│   │   ├── components/  # React components
│   │   ├── pages/       # Pages like Dashboard
│   │   ├── App.js       # Main App component
│   │   ├── index.js     # Entry point
│   ├── package.json     # Frontend dependencies
│
├── .gitignore
├── README.md
🛠 Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-username/MERN-Project.git
cd MERN-Project
2️⃣ Setup the Backend
sh
Copy
Edit
cd backend
npm install
Create a .env file inside backend/:
ini
Copy
Edit
MONGO_URI=mongodb://localhost:27017/mern-stack-app
JWT_SECRET=your_secret_key
Start the backend:
sh
Copy
Edit
npm run dev
3️⃣ Setup the Frontend
sh
Copy
Edit
cd ../frontend
npm install
npm start
📡 API Endpoints
Method	Endpoint	Description
POST	/api/auth/login	User Login
POST	/api/agents/add	Add New Agent
GET	/api/csv/list	Get CSV Distributed List
🚀 Deployment
Frontend: Deploy on Netlify/Vercel
Backend: Deploy on Render/Railway
👨‍💻 Tech Stack
Frontend: React.js, Material UI
Backend: Node.js, Express.js
Database: MongoDB
Auth: JWT, bcrypt.js
File Upload: Multer, PapaParse
📜 License
This project is MIT licensed. Feel free to use and modify.
