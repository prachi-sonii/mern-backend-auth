# 🚀 MERN Authentication Backend

A backend authentication system built using the MERN stack, following MVC architecture, with RESTful APIs for user registration and login. The APIs are tested using Postman, and user data is stored in ongoDB.

---

## 📌 Features

* User Registration (Sign Up)
* User Login (Sign In)
* RESTful API design
* MVC (Model–View–Controller) architecture
* MongoDB database integration
* API testing using Postman
* Environment variable management using dotenv

---

## 🛠️ Tech Stack

Node.js – Backend runtime
Express.js – Web framework
MongoDB – NoSQL database
Mongoose – ODM for MongoDB
Postman – API testing
Git & GitHub – Version control
Nodemon – Development tool



## 📂 Project Structure

```text
mern-backend-auth/
│
├── index.js                
├── package.json           
├── README.md               n
│
├── config/
│   └── db.js              
│
├── models/
│   └── User.js            
│
├── controllers/
│   └── authController.js   
│
├── routes/
│   └── authRoutes.js      
│
└── .env                    
```





## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

bash
git clone https://github.com/prachi-sonii/mern-backend-auth.git
cd mern-backend-auth


---

### 2️⃣ Install dependencies

bash
npm install


---

### 3️⃣ Create `.env` file

env:
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/mern_auth


---

### 4️⃣ Run the server

bash:

npm run dev


Server will start at:


http://localhost:5000


---

## 🔗 API Endpoints

### 🔹 Register User


POST /api/auth/register


**Request Body (JSON):**

json
{
  "name": "John Doe",
  "email": "john@gmail.com",
  "password": "123456"
}


---

### 🔹 Login User


POST /api/auth/login


**Request Body (JSON):**

json
{
  "email": "john@gmail.com",
  "password": "123456"
}


---

## 🔄 Workflow (MVC)


Client (Postman / Frontend)
        ↓
Routes (Express)
        ↓
Controllers (Business Logic)
        ↓
Models (Mongoose)
        ↓
MongoDB Database
        ↓
Response to Client


---

## 🧪 Testing

* APIs tested using Postman
* Verified responses and database insertion
* MongoDB data verified using MongoDB Compass

---

## 🎓 Learning Outcomes

* Understood and implemented MVC architecture
* Built RESTful APIs using Express
* Connected backend to MongoDB using Mongoose
* Debugged real-world backend issues
* Used Git & GitHub for project versioning

---




