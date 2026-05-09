# 🌾 Raitha-Varta

<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

<p align="center">
AI-powered farmer assistance application developed using Generative AI technologies.
</p>

---

# 📌 Internship Project

- **Project Name:** Raitha-Varta  
- **Domain:** Android App Development using Generative AI  
- **Company:** MindMatrix  
- **Developed By:** Srushti EB  
- **College:** Alva's College  
- **Technologies Used:** Kotlin, React, TypeScript, Gemini AI  

---

# 🚀 Features

- 🌱 AI-based farmer assistance
- 📷 Crop image analysis
- 🤖 Gemini AI integration
- 🌦 Agriculture support system
- 📱 Android application using Kotlin
- ⚡ Fast frontend development using React + Vite
- 🔥 JSON Server support for local API

---

# 🛠 Tech Stack

## Frontend
- React
- Vite
- TypeScript

## Android Development
- Kotlin
- Android Studio

## Backend / API
- JSON Server
- Gemini API

## Tools
- Node.js
- npm
- Git & GitHub

---

# 📂 Project Structure

```bash
Raitha-Varta/
│── android/
│── src/
│── public/
│── components/
│── services/
│── db.json
│── .env.local
│── package.json
│── vite.config.ts
```

---

# 📥 Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Raitha-Varta.git
cd Raitha-Varta
```

---

# ▶️ Run Locally

## ✅ Prerequisites

Install the following before running the project:

- Node.js
- npm
- Android Studio
- Android Emulator
- Kotlin Support Plugin

---

# Step 1: Install Dependencies

```bash
npm install
```

---

# Step 2: Create Environment File

Create a file named:

```bash
.env.local
```

Add your Gemini API Key:

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

---

# Step 3: Run JSON Server (Important)

If the emulator is not fetching data properly, run JSON Server.

Install JSON Server globally:

```bash
npm install -g json-server
```

Start JSON Server:

```bash
json-server --watch db.json --port 3001
```

---

# Step 4: Start Development Server

```bash
npm run dev
```

---

# 📱 Android Emulator Fix

If localhost is not working inside the Android Emulator:

Use:

```bash
http://10.0.2.2:5173
```

Instead of:

```bash
http://localhost:5173
```

Because Android Emulator cannot access localhost directly.

---

# 🔧 Additional Fix

If port or connection issue occurs:

Run:

```bash
npm run dev -- --host
```

Then open:

```bash
http://YOUR_IP_ADDRESS:5173
```

inside emulator browser.

---

# 🔥 GitHub Upload Steps

## Initialize Git

```bash
git init
```

---

## Add Files

```bash
git add .
```

---

## Commit Files

```bash
git commit -m "Initial Commit - Raitha Varta"
```

---

## Create GitHub Repository

Repository Name:

```bash
Raitha-Varta
```

---

## Connect Repository

```bash
git remote add origin https://github.com/YOUR_USERNAME/Raitha-Varta.git
```

---

## Push Code

```bash
git branch -M main
git push -u origin main
```

---

# 📸 Screenshots

Add your project screenshots here.

---

# ⭐ GitHub Topics

```text
android
kotlin
react
vite
typescript
genai
gemini-api
farmers
ai
internship-project
```

---

# 📄 License

This project is developed for educational and internship purposes.

---

# 🙌 Acknowledgement

Special thanks to MindMatrix for providing the opportunity to work on Android App Development using Generative AI technologies.
