🐾 AdoptPaws - Pet Adoption Platform

A full-stack MERN web application that allows users to browse pets, add them to a wishlist, and request adoptions. Admins can manage adoption requests, approve or decline them, and handle suggested pets. The platform focuses on secure authentication, responsive design, and a seamless adoption workflow.

🚀 Features

User Authentication – Secure signup/login with JWT and password hashing.
Profile Management – Update user info and view adoption history.
Pet Browsing – Browse pets with detailed information.
Wishlist – Add and remove pets from wishlist (user-specific).
Adoption Requests – Users can request adoptions; admins approve/decline.
Admin Dashboard – Manage adoption requests and suggested pets.
Payment Simulation – Complete adoption with simulated payment flow.
Notifications – Popup alerts for wishlist and adoption actions.

📌 Prerequisites

Node.js & npm – [Download here](https://nodejs.org/en/download)
MongoDB – Install or use Atlas
Environment Variables – Create .env file in backend/ with:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

🔑 Important Notes

User Authentication – JWT tokens must be stored securely in the frontend.
Admin Access – Admin login is separate from user login; credentials exist only in the admin collection.
Security – Never commit .env files with secrets to GitHub.

💻 Getting Started

Clone the repository

```bash
git clone https://github.com/yourusername/adoptpaws.git
cd adoptpaws
```

Backend setup
```
cd backend
npm install
npm run dev
```

Frontend setup
```
cd ../frontend
npm install
npm start
```

📊 Workflow

User Flow
Signup/Login → Profile created.
Browse pets → View details.
Add pets to wishlist → Stored per user.
Request adoption → Status tracked in profile.

Admin Flow

Login → Access dashboard.
View adoption requests → Approve or decline.
Manage suggested pets → Add or remove pets.
User Flow:

Signup/Login → Profile created.

Browse pets → View details.

Add pets to wishlist → Stored per user.

Request adoption → Status tracked in profile.

Admin Flow:

Login → Access dashboard.

View adoption requests → Approve or decline.

Manage suggested pets → Add or remove pets.

Data Flow:

Frontend calls backend APIs → Backend interacts with MongoDB → Responses update frontend UI dynamically.

🏷️ Summary:

MERN full-stack pet adoption app.

Users can browse pets, manage wishlists, request adoptions, and track status.

Admins approve requests and manage pets via secure dashboard.

