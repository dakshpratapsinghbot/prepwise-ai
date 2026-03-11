# Interview AI

Interview AI is a small full-stack project that helps students prepare for interviews.
The application uses AI to analyze a user's resume and job description and then generates interview questions, skill gap suggestions, and a preparation plan.

This project was built mainly for learning full-stack development and understanding how AI APIs can be integrated into web applications.

## Features

* User registration and login
* Upload resume (PDF)
* Enter job description and personal background
* AI generates an interview preparation report
* Suggested technical and behavioral interview questions
* Skill gap analysis
* Simple preparation roadmap
* Download resume as PDF
* View previous interview reports

## Tech Stack

**Frontend**

* React
* React Router
* Vite
* Axios

**Backend**

* Node.js
* Express.js
* MongoDB
* Mongoose

**Other Tools**

* Google Gemini API (for AI responses)
* JWT Authentication
* Multer (file upload)
* Puppeteer (PDF generation)

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/yourusername/interview-ai.git
cd interview-ai
```

### 2. Setup Backend

```
cd Backend
npm install
```

Create a `.env` file inside the Backend folder.

```
MONGO_URI=your_mongodb_connection
GOOGLE_GENAI_API_KEY=your_gemini_api_key
JWT_SECRET=your_secret_key
PORT=3000
```

Start backend server:

```
npm run dev
```

### 3. Setup Frontend

```
cd Frontend
npm install
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

Backend will run on:

```
http://localhost:3000
```

## Project Structure

```
interview-ai
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

## How the App Works

1. User registers or logs in.
2. User uploads a resume and adds job description.
3. The backend sends this information to Gemini AI.
4. AI generates interview questions, match score, and improvement suggestions.
5. The report is stored in the database and shown to the user.

## Future Improvements

Some things that can be added in the future:

* Mock interview simulation
* Video interview practice
* Better UI design
* Support for DOCX resumes
* Interview performance tracking

## Author

Kunal Pratap Singh

This project was created as a learning project to practice full-stack development and AI integration.
