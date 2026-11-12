# 🌍 Wanderlust – Travel Listing Platform

Wanderlust is a full-stack web application inspired by Airbnb that allows users to explore, create, and manage travel listings. Users can share their travel experiences, upload property images, and write reviews.

## 🚀 Live Demo

[Visit Wanderlust](https://majorproject-0ggn.onrender.com/listings)

## ✨ Features

- **User Authentication:** Secure signup and login using Passport.js.
- **Create Listings:** Users can add new travel or accommodation listings.
- **Manage Listings:** Edit and delete listings.
- **Image Uploads:** Upload and store images using Cloudinary.
- **Reviews & Ratings:** Users can share reviews on listings.
- **Authorization:** Only authorized users can modify their own listings.
- **Responsive UI:** User-friendly interface.

## 🛠️ Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript
- EJS
- Bootstrap

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Authentication & Storage**
- Passport.js
- Passport Local Mongoose
- Cloudinary
- Multer

## 📸 Project Screenshots

_Add your project screenshots here._

## ⚙️ Installation & Setup

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project folder:

   ```bash
   cd MajorProject
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your environment variables.

   ```env
   MONGODB_URI=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   SECRET=your_session_secret
   ```

   Use the exact environment variable names expected by your application.

5. Start the application:

   ```bash
   npm start
   ```

6. Open your browser and visit:

   `http://localhost:8080`

## 📂 Project Structure

```text
MajorProject/
│
├── controllers/
├── init/
├── models/
├── public/
│   ├── css/
│   └── js/
├── routes/
├── utils/
├── views/
├── app.js
├── middleware.js
├── schema.js
├── package.json
└── .env
```

## 🔐 Security

- Keep database credentials and API keys private.
- Never commit your `.env` file.
- Use `.gitignore` to exclude sensitive files.

## 👨‍💻 Author

**Manan Vashishtha**

- GitHub: [Manan-Vashishtha](https://github.com/Manan-Vashishtha)
- LinkedIn: [Manan Vashishtha](https://www.linkedin.com/in/manan-vashishtha/)

---

⭐ If you like this project, consider giving it a star!