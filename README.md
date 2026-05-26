# 🚀 CareerAI — Ace Your Internship

CareerAI is an intelligent web application powered by AI to help you prepare for internship interviews and advance your career. Get AI-driven resume analysis, practice mock interviews, identify skill gaps, and follow a personalized learning roadmap.

---

## ✨ Features

### 📄 **Resume Analyzer**
- Upload your resume (PDF, DOC, DOCX)
- Get an **ATS (Applicant Tracking System) score** out of 100
- Receive detailed section-by-section feedback
- Identify missing keywords for your target role
- Get actionable recommendations for improvement

### 🎤 **Mock Interview**
- Practice with **AI-generated interview questions**
- Choose from multiple roles: Frontend Developer, Backend Developer, Full Stack Developer, Data Analyst, ML Engineer, Product Manager
- Select interview types: Technical, HR, or Mixed
- Get real-time **AI feedback** on your answers
- Practice with **text or voice input** (Web Speech API)
- Track performance across multiple interview sessions

### 📊 **Skill Gap Analyzer**
- Analyze your current skills vs. target role requirements
- Get a **skill match percentage**
- Identify skills you have vs. skills you need
- Category-based breakdown (Technical, Soft Skills, Tools, etc.)
- Priority ranking of skills to learn

### 🗺️ **Learning Roadmap**
- Generate a **personalized 30-day learning plan**
- Week-by-week breakdown with specific learning objectives
- Track your progress with completion checkmarks
- All data synced to your account

### 👤 **User Authentication**
- Create a secure account with email and password
- Sign in from any device
- All data persists to your profile
- Account management and settings

### 📈 **Dashboard**
- Overview of your career readiness
- Resume ATS score snapshot
- Interview performance metrics
- Skill match percentage
- Day streak tracker for consistent practice
- Recent activity feed

---

## 🛠️ Technologies Used

- **Frontend**: Vanilla JavaScript (no frameworks)
- **Styling**: Custom CSS with responsive design
- **Storage**: Browser localStorage for data persistence
- **APIs**: 
  - Pollinations.ai for AI-powered analysis and question generation
  - Web Speech API for voice recording/transcription
- **File Parsing**: Custom binary parsers for PDF/DOC/DOCX file formats
- **Browser APIs**: FileReader API, localStorage, Web Speech API
---

## Quick start (run locally)
1. Open a terminal and change to the project directory:

```powershell
cd "c:\Users\Anjali\OneDrive\Desktop\ac\build-careerai-web-application (1)"
```

2. Start a static server (Python 3 recommended):

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Or with Node (if you have npx):

```bash
npx http-server -p 8000
```

3. Open the app in your browser:

```
http://localhost:8000
```

---
## 📁 Project Structure
```
build-careerai-web-application/
├── index.html          # App + CSS + JS (loads fragments from pages/)
├── pages/              # Individual screen fragments loaded at runtime
│   ├── dashboard.html
│   ├── resume.html
│   ├── interview.html
│   ├── skillgap.html
│   ├── roadmap.html
│   └── settings.html
└── README.md       


## 🎯 How to Use

### **1. Sign Up / Login**
- Click "Sign Up" to create a new account
- Enter your full name, email, and password
- Or use "Login" if you already have an account

### **2. Resume Analysis**
1. Navigate to **Resume** from the sidebar
2. Upload your resume (PDF, DOC, or DOCX)
3. Select your target role
4. Click "Analyze Resume"
5. View your ATS score and get recommendations

### **3. Mock Interview**
1. Go to **Interview** section
2. Choose your target role and interview type
3. Select number of questions (3, 5, or 7)
4. Pick input mode: Text or Voice
5. Start the interview and answer each question
6. Get AI feedback after each answer
7. View your final interview score

### **4. Skill Gap Analysis**
1. Navigate to **Skill Gap**
2. Select your target role
3. List your current skills
4. Click "Analyze Skill Gap"
5. See which skills you have and which you need

### **5. Learning Roadmap**
1. Go to **Roadmap**
2. Enter your target role and skills to learn
3. Click "Generate Roadmap"
4. Follow the 30-day plan week by week
5. Mark steps as complete as you progress

---

## 🤖 AI Integration

### Pollinations.ai API
This app uses the **Pollinations.ai** REST API for:
- Resume analysis with detailed feedback
- Interview question generation
- Skill gap assessment
- Learning roadmap creation

The AI processes natural language and provides intelligent, personalized recommendations.

---

## 💾 Data Storage

All user data is stored locally in your browser using **localStorage**:
- ✅ User profiles and authentication
- ✅ Resume analysis results
- ✅ Interview history and scores
- ✅ Skill gap data
- ✅ Learning roadmap progress
- ✅ Daily activity log

**Note**: Data is NOT sent to external servers. It stays on your device.

---

## 🎤 Voice Interview Feature

The mock interview supports voice input using the **Web Speech API**:
1. Click the 🎤 button to start recording
2. Speak your answer clearly
3. Click again to stop recording
4. Your speech is transcribed automatically
5. Submit for AI feedback

**Requirements**:
- Microphone access permission
- Modern browser with Web Speech API support
- Quiet environment for better transcription

---

## 🐛 Troubleshooting

### **Server won't start**
```bash
# Make sure Python is installed
python --version

# Try on a different port if 8000 is in use
python -m http.server 9000

---

## 🔐 Security Notes

- Passwords are hashed locally before storage
- All user data is stored in browser localStorage
- No data is transmitted to external servers (except AI API calls)
- Use HTTPS in production for enhanced security

---

## 📊 Key Metrics

The application tracks and displays:
- **ATS Score**: 0-100 rating for resume compatibility
- **Interview Score**: 0-100 based on answer quality
- **Skill Match**: 0-100% match for target role
- **Day Streak**: Consecutive days of practice
- **Question Scores**: Individual feedback for each interview question

---

## 🎨 Customization

### Modify Target Roles
Edit the role options in `script.js` and `index.html`:
```javascript
// Available roles can be customized
const roles = [
  "Frontend Developer",
  "Backend Developer",
  // Add more roles here
];
```

### Change Color Theme
Edit CSS variables in `styles.css`:
```css
:root {
  --primary: #7c3aed;      /* Main purple */
  --success: #10b981;       /* Green */
  --danger: #ef4444;        /* Red */
  --warning: #f59e0b;       /* Amber */
  /* Customize colors here */
}
```


## 📜 License

This project is provided as-is for educational and career development purposes.

---

## 🚀 Future Enhancements

Potential features for future versions:
- 📧 Email integration for progress reports
- 🤖 Advanced AI models for better feedback
- 🏆 Leaderboard and achievements system
- 🎓 Integration with learning platforms
- 📊 Detailed analytics dashboard
- 🎯 Goal tracking and milestone notifications
- 🌍 Multi-language support

---

**Made with ❤️ for aspiring interns and career professionals.**

**Start practicing today and ace your next internship! 🚀**
