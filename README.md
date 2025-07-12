# 🌆 Cloudinary Image Uploader

A modern, responsive **Image Uploader Web App** built with **Node.js**, **Express**, **MongoDB**, **Multer**, and **Cloudinary**.  
This app allows users to upload images directly from the browser, store them securely in Cloudinary, and save metadata to MongoDB.

It features a sleek, dark-themed UI using **EJS templating** for dynamic rendering.

---

## 🚀 Features

- 📁 Upload images with a smooth file input interface
- ☁️ Secure image storage on **Cloudinary**
- 🗃 Metadata (filename, URL, public ID) stored in **MongoDB**
- 🎨 Modern, responsive UI with a dark theme
- 🖼 Instant preview of uploaded image
- 📦 File handling with **Multer**
- 🔐 Secure credential management via `.env`

---

## 🛠 Tech Stack

- **Backend:** Node.js, Express.js, Multer, Mongoose  
- **Frontend:** HTML5, CSS3, EJS (Embedded JavaScript)  
- **Database:** MongoDB Atlas  
- **Cloud Storage:** Cloudinary  
- **Templating:** EJS

---

## 📸 Screenshots

| Preview | 
|-------------|
| ![Preview](<img width="1365" height="665" alt="Screenshot 2025-07-13 010730" src="https://github.com/user-attachments/assets/858a5ab0-4b5a-4bd3-bc36-515617dee8cd" />
) 

> *(Tip: Replace these placeholder URLs with real screenshots from your app)*

---

## 📂 Project Structure

project-root/
├── public/ # Static assets (optional)
├── views/
│ └── index.ejs # Upload form view
├── server.js # Main backend server
├── .env # Environment variables (excluded from Git)
├── package.json
└── README.md


---

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/RushikeshJadhav2004/Image_Uploader.git
   cd Image_Uploader

2.  Install dependencies

     npm install

3.  Set up your .env file
       Create a .env file in the root folder:

   PORT=2000
   
  CLOUD_NAME=your_cloudinary_cloud_name
  CLOUD_API_KEY=your_cloudinary_api_key
  CLOUD_API_SECRET=your_cloudinary_api_secret
  MONGO_URI=your_mongodb_connection_uri

4.  Run the application
      npm start


🌐 Deployment
To deploy this app on Render:

Push your code to GitHub

Go to Render.com → New → Web Service

Connect your GitHub repo

Set your build command as: npm install

Set your start command as: npm start

Add your .env variables in the dashboard

Done! 🎉 Your app is live.


👤 Author
Rishii Jadhav
🔗 LinkedIn
🔗 GitHub


📝 License
This project is licensed under the MIT License.



---

Let me know if you’d like:
- A **LinkedIn post caption**
- A `deploy` badge
- Feature ideas to enhance the app further (like gallery view, delete image, multi-upload)

You're ready to showcase this project! 🚀
    

    
