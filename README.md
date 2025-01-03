# 📚 Bookstore App

## 🏷️ Overview
The Bookstore App is a dynamic MERN stack application tailored for students and book enthusiasts. It offers features like user authentication, an extensive library of subject-specific PDFs, organized previous year question papers (PYQs), and much more to enhance learning and reading experiences.

## ✨ Features

### 🔐 Secure User Authentication
- Easy **Login** and **Signup** options.
- Advanced security with data encryption.

### 📖 Extensive Book Collection
- Access a wide range of **subject-specific book PDFs**.
- Add descriptions and ratings to books.

### 🗂️ Organized PYQs
- Browse **Previous Year Question Papers** by subject and year.
- Perfect for exam preparation.

### 🔍 Smart Search & Filters
- Instantly find books and PYQs with a powerful search bar.
- Apply filters by subject or year.

### 📌 Personalization Features
- Bookmark favorite books and PYQs.
- Track your reading progress with a built-in tracker.

### 🌐 Scalable Backend
- Dynamic API-based data fetching.
- Designed to handle large datasets efficiently.

### 💬 Community Interaction
- Join discussion forums to share notes and insights.

### 🌙 Customizable Themes
- Toggle between light and dark modes for better readability.

## 💻 Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

## ⚙️ Installation

### Prerequisites
- Node.js and npm installed.
- MongoDB installed locally or access to a MongoDB Atlas cluster.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bookstore-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bookstore-app
   ```
3. Install dependencies:
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```
4. Set up the environment variables in the `backend/.env` file:
   ```env
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```
5. Start the application:
   - Backend:
     ```bash
     cd backend && npm start
     ```
   - Frontend:
     ```bash
     cd frontend && npm start
     ```
6. Open `http://localhost:3000` to explore the app.

## 📜 License
This project is licensed under the MIT License.

## 📧 Contact
Feel free to reach out for queries at [adityaaman.codex@gmail.com]. 

