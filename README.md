# **🖼️ Pinterest Clone**

A full-stack Pinterest-inspired web application built using **Node.js**, **Express.js**, **MongoDB**, and **Passport.js** for authentication. Users can register, log in, upload pins, and view them in a beautiful, responsive masonry-style layout.

---

## **🚀 Features**

- 🧑‍💼 **User Authentication** (Register/Login/Logout) with Passport.js
- 📌 **Upload Pins** (Images with descriptions)
- 🖼️ **View Feed** – display all pins in a masonry grid
- 🗑️ **Delete Pins** (only by the uploader)
- 🌐 **Responsive Design** with Tailwind CSS
- 🛠️ **EJS templating** for rendering views

---

## **🛠️ Tech Stack**

- **Frontend**: EJS, Tailwind CSS, Vanilla JS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: Passport.js (Local Strategy)
- **File Upload**: Multer
- **Session Management**: express-session

---

## **📂 Project Structure**

pinterest-clone/
├── models/
│ ├── post.js # Post schema (image, text, date, likes)
│ └── users.js # User schema (username, password, email, posts, etc.)
│
├── routes/
│ ├── index.js # Main routing logic
│ └── users.js # User auth routes
│
├── views/
│ ├── feed.ejs # Main feed page with pins
│ ├── login.ejs # Login page
│ ├── register.ejs # Registration page
│ ├── upload.ejs # Upload form for pins
│ └── partials/ # Header/footer partials
│
├── public/
│ └── uploads/ # Uploaded image files
│
├── app.js # Express app entry point
├── package.json # Project metadata and dependencies
└── .gitignore # Ignoring node_modules and other files


---

## **🔑 Installation & Setup**

installation:
  - step: Clone the repository
    command: |
      git clone https://github.com/dpbd-2004/pinterest-clone.git
      cd pinterest-clone

  - step: Install dependencies
    command: npm install

  - step: Start MongoDB
    note: Ensure MongoDB is running locally or use MongoDB Atlas URI in the code

  - step: Run the application
    command: node app.js

  - step: Open in browser
    url: http://localhost:3000


