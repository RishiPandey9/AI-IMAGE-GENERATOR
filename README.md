
# 🎨 AI Image Generator (DALL·E)

An **AI-powered full-stack web application** that generates high-quality images from text prompts using **OpenAI’s DALL·E API**. Users can create AI images, preview them, download them, and share them with a public community gallery.

---

## 🚀 Features

* 🧠 Generate images from text prompts using DALL·E
* 🎲 “Surprise Me” prompt generator
* 🖼️ Real-time image preview
* ⬇️ Download generated images
* 🌐 Community showcase (public gallery)
* 🔍 Search images by name or prompt
* ☁️ Cloud image storage using Cloudinary
* 📦 MongoDB database integration

---

## 🛠️ Tech Stack

### Frontend (Client)

* **React.js**
* **Vite**
* **Tailwind CSS**
* **React Router**
* **File Saver**
* **ESLint**

### Backend (Server)

* **Node.js**
* **Express.js**
* **MongoDB (Mongoose)**
* **OpenAI API (DALL·E)**
* **Cloudinary**
* **CORS & dotenv**

---

## 📁 Project Structure

```
rishipandey9-ai-image-generator/
│
├── client/                 # Frontend (React + Vite)
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── page/           # Home & Create Post pages
│   │   ├── assets/         # Images & icons
│   │   ├── utils/          # Helper functions
│   │   └── constant/       # AI prompt constants
│   └── package.json
│
├── server/                 # Backend (Node + Express)
│   ├── mongodb/            # MongoDB connection & models
│   ├── routes/             # API routes
│   └── index.js
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the **server** directory:

```env
OPENAI_API_KEY=your_openai_api_key
MONGODB_URL=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/rishipandey9/AI-IMAGE-GENERATOR.git
cd rishipandey9-ai-image-generator
```

### 2️⃣ Start Backend Server

```bash
cd server
npm install
npm start
```

Server runs on: `http://localhost:8080`

### 3️⃣ Start Frontend Client

```bash
cd client
npm install
npm run dev
```

Frontend runs on: `http://localhost:5173`

---

## 📡 API Endpoints

### Generate Image

```
POST /api/v1/dalle
```

### Get All Posts

```
GET /api/v1/post
```

### Create New Post

```
POST /api/v1/post
```

---

## 📸 Screenshots

*Add screenshots here (Home page, Image generation, Gallery view)*

---

## 📌 Future Enhancements

* User authentication
* Like & comment system
* Image categories
* Prompt history
* Deployment with custom domain

---

## 👨‍💻 Author

**Rishi Pandey**

* GitHub: [rishipandey9](https://github.com/rishipandey9)
* Role: Full-Stack Developer | AI Enthusiast

---
