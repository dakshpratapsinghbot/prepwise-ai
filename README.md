# PrepWise AI 🚀

PrepWise AI is a full-stack web application designed to help students and job seekers prepare smarter for interviews using AI.

The platform analyzes your resume along with a job description and generates personalized interview questions, identifies skill gaps, and provides a structured preparation roadmap.

This project was built to explore full-stack development and integrate AI into real-world applications.

---

## ✨ Features

* 🔐 User Authentication (Login & Register)
* 📄 Resume Upload (PDF support)
* 🧠 AI-powered Interview Preparation Report
* ❓ Technical & Behavioral Interview Questions
* 📊 Skill Gap Analysis
* 🗺️ Personalized Preparation Roadmap
* 📥 Download Resume as PDF
* 📚 View Previous Reports

---

## 🛠️ Tech Stack

### Frontend

* React
* React Router
* Vite
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### Tools & Integrations

* Google Gemini API (AI responses)
* JWT Authentication
* Multer (File Uploads)
* Puppeteer (PDF Generation)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/prepwise-ai.git
cd prepwise-ai
```

---

### 2️⃣ Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file inside the Backend folder:

```env
MONGO_URI=your_mongodb_connection
GOOGLE_GENAI_API_KEY=your_gemini_api_key
JWT_SECRET=your_secret_key
PORT=3000
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

## 🌐 Running URLs

* Frontend: http://localhost:5173
* Backend: http://localhost:3000

---

## 📂 Project Structure

```
prepwise-ai
│
├── Backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middlewares
│   └── services
│
├── Frontend
│   ├── components
│   ├── pages
│   ├── features
│   └── styles
```

---

## ⚡ How It Works

1. User registers or logs in
2. Uploads resume + enters job description
3. Backend sends data to Gemini AI
4. AI generates:

   * Interview Questions
   * Match Score
   * Skill Improvement Suggestions
5. Report is stored and displayed to the user

---

## 🚀 Future Enhancements

* 🎤 Mock Interview Simulation
* 📹 Video Interview Practice
* 🎨 Improved UI/UX
* 📄 DOCX Resume Support
* 📈 Interview Performance Tracking

---

## 👨‍💻 Author

**Daksh Pratap Singh**

This project was built as a learning project to practice full-stack development and AI integration.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
