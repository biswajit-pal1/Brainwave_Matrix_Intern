# Task 02 -- Blog Application using MERN Stack

## 📖 Overview
This project is a **Blog Application** built using the MERN stack (MongoDB, Express.js, React.js, Node.js).  
It provides CRUD functionality where users can create, view, edit, and delete blog posts.  
The app also supports **image upload via Cloudinary** and **authentication with JWT**.

---

## ✨ Features
- 📝 Create, edit, and delete blog posts  
- 📑 View all posts and detailed blog pages  
- 📷 Upload blog images using Cloudinary  
- 🔐 User authentication with JWT  
- 📱 Responsive design for desktop and mobile  
- ⚡ Smooth user experience with React frontend & Express backend  

---

## 🛠 Tech Stack
- **Frontend:** React.js, CSS (or Tailwind if used)  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Cloud Storage:** Cloudinary  
- **Auth:** JWT (JSON Web Token)  
- **Other Tools:** REST API, Axios, npm  

---

## 🚀 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Brainwave_Matrix_Intern.git
   cd Brainwave_Matrix_Intern/Task-02
   ```

2. Install dependencies:

   - For frontend:
     ```bash
     cd frontend
     npm install
     ```

   - For backend:
     ```bash
     cd backend
     npm install
     ```

3. Copy the `.env.example` file inside the **backend** folder and rename it to `.env`.  
   Then, update the values with your own credentials (MongoDB URI, Cloudinary keys, JWT secret, etc.).

4. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

5. Start the frontend app:
   ```bash
   cd frontend
   npm run dev
   ```
   The app will run at:
   ```
   http://localhost:5173
   ```

---

## 📂 Project Structure
```
Task-02/
│── frontend/      # React frontend
│── backend/       # Express backend
│── README.md      # Project documentation
│── .env.example   # Example environment variables
```
