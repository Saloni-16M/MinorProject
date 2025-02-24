# Surplus Smile

This is a **MERN (MongoDB, Express, React, Node.js) stack** project that includes features like authentication, API routing, and frontend styling using Bootstrap 5.

## 🛠 Technologies Used
- **Frontend:** React, Bootstrap 5
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Security:** bcrypt (for password hashing), CORS (for cross-origin resource sharing)

## 📌 Features
- User authentication (signup, login with hashed passwords)
- Secure API routes using JWT
- Responsive UI with Bootstrap 5
- RESTful API for CRUD operations

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Saloni-16M/MinorProject.git
cd MinorProject
```

### 2️⃣ Install Dependencies
#### Backend
```sh
cd backend
npm install
```
#### Frontend
```sh
cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file in the backend directory and add the following:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application
#### Start Backend Server
```sh
cd backend
npm start
```
#### Start Frontend Server
```sh
cd frontend
npm start
```

## 🔗 API Endpoints
| Method | Endpoint          | Description             |
|--------|------------------|-------------------------|
| POST   | /api/auth/signup | Register a new user    |
| POST   | /api/auth/login  | Authenticate user      |
| GET    | /api/users       | Fetch user data        |

## 🛡 Security Features
- **bcrypt**: Hashes user passwords before storing in MongoDB.
- **JWT (JSON Web Tokens)**: Used for secure authentication.
- **CORS**: Enables safe cross-origin requests.


---
### 🎯 Contributions
Feel free to contribute by creating a pull request or reporting issues!

