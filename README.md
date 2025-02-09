# Social Media Platform

## 📌 Overview
This project is a **social media platform** that allows users to **create accounts, post content, like, comment, and follow other users**. The platform provides an interactive and engaging experience similar to popular social media apps.

## 🚀 Features
- **User Authentication** (Signup, Login, Logout)
- **Profile Management** (Edit bio, change profile picture)
- **Create, Edit, Delete Posts**
- **Like and Comment on Posts**
- **Follow/Unfollow Users**
- **Real-time Notifications**
- **Secure Backend APIs**

## 🛠️ Tech Stack
### **Frontend**:
- React.js
- Tailwind CSS / Bootstrap
- Redux (for state management)

### **Backend**:
- Node.js with Express.js
- MongoDB (Mongoose ORM)
- JWT Authentication

### **Other Tools**:
- Cloudinary (for image uploads)
- WebSockets (for real-time features)
- Postman (for API testing)
- Git & GitHub (for version control)

## 📌 Project Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Swayamgupta07/Social-Media-Platform.git
cd Social-Media-Platform
```

### **2️⃣ Install Dependencies**
#### **Frontend**
```bash
cd client
npm install
```
#### **Backend**
```bash
cd server
npm install
```

### **3️⃣ Configure Environment Variables**
Create a **.env** file inside the `server/` directory and add the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### **4️⃣ Run the Application**
#### **Start Backend Server**
```bash
cd server
npm run dev
```
#### **Start Frontend Client**
```bash
cd client
npm start
```

## 🖼️ Adding Profile Pictures & Posts
- Users should upload images to their profile using the **edit profile** option.
- All images are stored using **Cloudinary**.
- Posts can contain **text, images, and hashtags**.

## 🛠️ API Endpoints
### **Authentication**
- `POST /api/auth/register` → Register a new user
- `POST /api/auth/login` → User login

### **User Management**
- `GET /api/users/:id` → Get user profile
- `PUT /api/users/:id` → Update profile
- `DELETE /api/users/:id` → Delete account

### **Posts**
- `POST /api/posts` → Create a new post
- `GET /api/posts` → Fetch all posts
- `DELETE /api/posts/:id` → Delete a post

### **Interactions**
- `POST /api/posts/:id/like` → Like a post
- `POST /api/posts/:id/comment` → Add a comment
- `GET /api/posts/:id/comments` → Get all comments

## 🔧 Future Enhancements
- **Dark Mode UI**
- **Stories Feature**
- **Direct Messaging (Chat System)**
- **Video Upload Support**
- **AI-powered content moderation**

## 🤝 Contributing
We welcome contributions! Fork the repository, create a new branch, and submit a PR.

## 📜 License
This project is open-source and licensed under the **MIT License**.

---
Developed by **Swayam Gupta** 🚀
