# 🌍 Wanderlust - Travel Listings Web Application

Wanderlust is a full-stack web application where users can explore, create, edit, and manage travel listings.  
It allows users to view different travel places, add their own listings with images, and share reviews.

🔗 **Live Demo:**  
https://wanderlust01-zhxt.onrender.com/listings

---

## 🚀 Features

- 🏝️ View all travel listings
- ➕ Add new listings with images
- ✏️ Edit existing listings
- ❌ Delete listings
- 📸 Image upload functionality
- ⭐ Review and rating system
- 🔐 User Authentication (Login & Signup)
- 📱 Responsive design

---

## 🛠️ Tech Stack

### Frontend:
- HTML
- CSS
- JavaScript
- Bootstrap / EJS (if used)

### Backend:
- Node.js
- Express.js

### Database:
- MongoDB
- Mongoose

### Other Tools & Services:
- Cloudinary (for image storage)
- Render (for deployment)
- Git & GitHub

---

## 📂 Project Structure

```
Wanderlust/
│── models/        # Database models
│── routes/        # Application routes
│── views/         # EJS templates
│── public/        # Static files (CSS, JS, images)
│── utils/         # Utility functions
│── app.js         # Main server file
│── package.json   # Project dependencies
```

---

## ⚙️ Installation & Setup (Run Locally)

Follow these steps to run the project on your local machine:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/wanderlust.git
cd wanderlust
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Create a .env file in root folder and add:
```
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
SESSION_SECRET=your_session_secret
```

### 4️⃣ Run the server
```bash
node app.js
```

### 5️⃣ Open in browser
```
http://localhost:3000
```

---

## 📸 Screenshots

### 🏠 Home / Listings Page
(Add screenshot here)

### ➕ Add Listing Page
(Add screenshot here)

### ⭐ Review Section
(Add screenshot here)

---

## 🔐 Environment Variables

This project uses environment variables for security.  
Create a `.env` file and add:

- MONGO_URI (MongoDB Atlas connection string)
- CLOUDINARY_CLOUD_NAME
- CLOUDINARY_KEY
- CLOUDINARY_SECRET
- SESSION_SECRET

---

## 🚧 Future Improvements

- 🔍 Search and filter listings
- 🗺️ Map integration (Google Maps / Mapbox)
- ❤️ Wishlist / Favorites feature
- 💬 User profile dashboard
- 📊 Advanced UI/UX improvements

---

## 👩‍💻 Author

**Shobha Goswami**  
GitHub: https://github.com/your-github-username  

---

## 📜 License

This project is created for learning and educational purposes.
