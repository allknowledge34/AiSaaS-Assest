
# 🤖 AiSaas – Full Stack AI SaaS Platform (MERN + PostgreSQL)

AiSaas is a full-featured AI-powered SaaS web application built using the MERN stack with PostgreSQL (Neon) and modern authentication & subscription systems.

This platform provides multiple AI tools under a single subscription-based system including content generation, image processing, and resume analysis.

------------------------------------------------------------
![Demo App](AiSaaS-Assest/clientside/assets/maxresdefault-16.jpg)
------------------------------------------------------------

Perfect for:
• Resume projects  
• Hackathons  
• SaaS portfolio showcase  
• Full-stack developer portfolio  

------------------------------------------------------------

## 🚀 Key Features

✔ Secure User Authentication (Sign-up / Login / Profile Management)  
✔ Subscription Billing System (Premium access model)  
✔ Serverless PostgreSQL Database (Neon)  
✔ Protected premium AI features  
✔ Scalable SaaS-ready architecture  

------------------------------------------------------------

## 🤖 AI Features

### 📝 Article Generator
• Generate full-length articles  
• Input: Title & word length  
• AI-powered content generation  

### 📰 Blog Title Generator
• Input: Keyword & category  
• AI-generated blog titles  

### 🎨 Image Generator
• Input: Custom prompt  
• AI-based image generation  

### 🖼 Background Remover
• Upload image  
• Get transparent background output  

### 🧹 Image Object Remover
• Upload image  
• Describe object to remove  
• AI removes selected object  

### 📄 Resume Analyzer
• Upload resume  
• AI-powered resume feedback  
• Skills analysis & improvement suggestions  

------------------------------------------------------------

## 🏗 Architecture

• MERN Stack (MongoDB / Express / React / Node.js)  
• PostgreSQL (Neon serverless database)  
• Clerk Authentication  
• Subscription-based access control  
• API-driven AI integration  
• Modular scalable SaaS structure  

------------------------------------------------------------

## 🛠 Tech Stack

• React.js  
• Node.js  
• Express.js  
• MongoDB  
• PostgreSQL (Neon)  
• Clerk Authentication  
• Subscription Billing System  
• AI APIs (LLM & Image APIs)  

------------------------------------------------------------

## 📂 Project Structure

AiSaas/
│
├── client/
├── server/
├── routes/
├── controllers/
├── middleware/
├── database/
└── utils/

------------------------------------------------------------

## 🔐 Authentication

• Secure sign-up & login  
• Profile management  
• Protected premium routes  
• Role-based feature access  

------------------------------------------------------------

## 💳 Subscription System

• Premium subscription access  
• Billing integration  
• Feature-based access control  
• Secure payment handling  

------------------------------------------------------------

```bash
CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

#Clipdrop Setup
CLIPDROP_API = 'YOUR_CLIPDROP_API'

#Gemini Setup
GEMINI_API = 'YOUR_GEMINI_API'

# MongoDB Setup ( required )
DATABASE_URI = "YOUR_POSTAQL_DB_URI"

CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
```

## ⚙️ Run the server

```bash
cd server
npm install
npm start

```

## 📱 Run the client

```bash
cd client
npm install
npm run dev
```

------------------------------------------------------------

## 📌 Learning Outcomes

By building this project, you will learn:

• Full-stack SaaS development  
• Subscription-based architecture  
• PostgreSQL integration  
• Authentication & access control  
• AI API integration  
• Scalable web app structure  

------------------------------------------------------------
## 🤝 Contributing

Contributions are welcome to improve features and performance.

---

## ⭐ Support

If you found this project helpful, please give it a star ⭐

------------------------------------------------------------
