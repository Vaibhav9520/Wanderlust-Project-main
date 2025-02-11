# Wanderlust - Major Project

## 📌 Project Overview
Wanderlust is a full-stack web application that allows users to explore, create, and review travel listings. It includes authentication, image uploads, and interactive maps using **Mapbox**.

## 🚀 Features
- 🗺️ **Interactive Maps** with Mapbox
- 📸 **Image Uploads** using Cloudinary
- 🔐 **User Authentication** with Passport.js
- 💬 **Flash Messages** for user notifications
- 💾 **MongoDB Database** for storing listings & user data
- 🎭 **EJS Templating** for dynamic UI rendering
- 🌍 **CRUD Functionalities** for Listings & Reviews

## 🛠️ Tech Stack
- **Frontend**: EJS, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: Passport.js
- **File Storage**: Cloudinary
- **Session Storage**: Connect-Mongo
- **Middleware**: Method-Override, Express-Session, Connect-Flash

## 📂 Project Structure
```
major-project/
│-- public/              # Static files (CSS, JS, images)
│-- views/               # EJS templates
│-- routes/              # Express routes (listings, users, reviews)
│-- models/              # Mongoose models (User, Listing, Review)
│-- controllers/         # Business logic for routes
│-- utils/               # Utility functions (error handling, validation)
│-- app.js               # Main entry point
│-- .env                 # Environment variables
│-- package.json         # Dependencies & project info
```

## ⚡ Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/major-project.git
   cd major-project
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Create a `.env` file and add:
   ```sh
   ATLASDB_URL=your_mongodb_url
   MAPBOX_ACCESS_TOKEN=your_mapbox_token
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   SESSION_SECRET=your_secret_key
   ```

4. Start the server:
   ```sh
   npm start
   ```
   Or using Nodemon:
   ```sh
   npm run dev
   ```

5. Open in browser:
   ```
http://localhost:8080
```

## 🔧 Usage
- Sign up or log in to create and manage listings.
- Search and explore different travel destinations.
- Leave reviews and ratings on listings.
- View interactive maps powered by **Mapbox**.

## 🚀 Deployment
- You can deploy the project using **Render**, **Vercel**, or **Heroku**.
- Ensure that MongoDB is hosted on **MongoDB Atlas** for production.

## 🛠️ Dependencies
```json
{
  "express": "^4.21.1",
  "mongoose": "^8.8.2",
  "passport": "^0.7.0",
  "@mapbox/mapbox-sdk": "^0.16.1",
  "cloudinary": "^1.41.3",
  "ejs": "^3.1.10"
}
```

## 🤝 Contributing
Feel free to fork this repository and submit pull requests.

## 📜 License
This project is licensed under the **MIT License**.

## 📞 Contact
For any queries, feel free to reach out at **vaibhavsingh01080@example.com** or open an issue in this repository.

