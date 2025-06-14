# cv-roaster-app
AI CV Roaster

# 🔥 CV Roaster - Get Your Resume Brutally (But Constructively) Roasted

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://moonpiesheldon1337.github.io/cv-roaster-app/)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)](https://firebase.google.com/)
[![AI](https://img.shields.io/badge/AI-Google%20Gemini-blue)](https://ai.google.dev/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

> **Because your CV deserves honest feedback, even if your feelings don't.**

An AI-powered tool that provides brutally honest (yet constructive) feedback on your CV/resume. Built with Google's Gemini AI and designed to help job seekers understand why they might be getting rejected - all while having a good laugh at themselves.

## 🎯 What It Does

- **📄 PDF Analysis**: Upload your CV in PDF format
- **🔥 AI Roasting**: Get savage but constructive feedback from a cybersecurity expert persona
- **💡 Actionable Insights**: Learn exactly why your CV might be getting rejected
- **😂 Comedy Therapy**: Laugh at your career mistakes instead of crying about them
- **🎭 Safe Space**: Get honest feedback without hurting anyone's feelings

## ✨ Features

### 🤖 AI-Powered Analysis
- Uses Google's Gemini 2.0 Flash model for intelligent CV analysis
- Cybersecurity expert persona provides industry-relevant insights
- Balances humor with genuine career advice

### 🎨 Clean UI/UX
- Drag-and-drop PDF upload
- Real-time feedback display
- Mobile-responsive design
- Firebase authentication integration

### ⚡ Performance
- Serverless Firebase Functions backend
- Fast PDF processing
- Secure API key management

## 🚀 Live Demo

Try it out: [CV Roaster Live App](https://moonpiesheldon1337.github.io/cv-roaster-app/)

## 🛠️ Tech Stack

### Frontend
- **HTML5/CSS3/JavaScript**: Pure vanilla JS for simplicity
- **Firebase SDK**: Authentication and function calls
- **PDF.js**: Client-side PDF text extraction
- **Responsive Design**: Works on all devices

### Backend
- **Firebase Functions**: Serverless backend
- **Google Gemini AI**: Natural language processing
- **Node.js**: Runtime environment
- **Axios**: HTTP client for API calls

### Infrastructure
- **Firebase Hosting**: Frontend deployment
- **Firebase Authentication**: User management
- **Google Cloud**: Scalable infrastructure

## 📦 Installation & Setup

### Prerequisites
- Node.js (18+)
- Firebase CLI
- Google Cloud Project with Gemini API access

### 1. Clone the Repository
```bash
git clone https://github.com/moonpiesheldon1337/cv-roaster-app.git
cd cv-roaster-app
```

### 2. Frontend Setup
```bash
# Frontend is ready to go - just update Firebase config in index.html
# Replace the Firebase config object with your project's config
```

### 3. Backend Setup
```bash
cd functions
npm install
```

### 4. Configure Environment Variables
```bash
# Set your Gemini API key
firebase functions:config:set gemini.key="YOUR_GEMINI_API_KEY"

# Or set in environment
export GEMINI_KEY="YOUR_GEMINI_API_KEY"
```

### 5. Deploy
```bash
# Deploy functions
firebase deploy --only functions

# Deploy frontend
firebase deploy --only hosting
```

## 🔧 Configuration

### Firebase Setup
1. Create a new Firebase project
2. Enable Authentication, Functions, and Hosting
3. Get your Firebase config and update `index.html`

### Gemini API Setup
1. Get API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Set the key using Firebase functions config
3. Update the API endpoint if needed

### Environment Variables
```bash
# Required
GEMINI_KEY=your_gemini_api_key_here

# Optional
FIREBASE_PROJECT_ID=your_project_id
```

## 📁 Project Structure

```
cv-roaster-app/
├── functions/                 # Firebase Functions (Backend)
│   ├── index.js              # Main function logic
│   ├── package.json          # Dependencies
│   └── .eslintrc.js          # Linting rules
├── public/                   # Frontend files
│   ├── index.html            # Main application
│   ├── style.css             # Styling
│   └── script.js             # Frontend logic
├── README.md                 # This file
└── firebase.json             # Firebase configuration
```

## 🎮 Usage

1. **Upload CV**: Drag and drop your PDF resume
2. **Wait for Magic**: AI analyzes your CV (usually takes 10-30 seconds)
3. **Get Roasted**: Receive your brutally honest feedback
4. **Improve & Repeat**: Fix issues and test again

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Areas for Contribution
- 🎨 UI/UX improvements
- 🤖 Additional AI personalities
- 📊 Analytics and insights
- 🌐 Internationalization
- 🔧 Performance optimizations

## 🐛 Known Issues & Limitations

- **PDF Limitations**: Complex layouts might not extract text perfectly
- **AI Limitations**: Gemini AI may occasionally be too creative with roasts
- **File Size**: Large PDFs (>10MB) might take longer to process
- **Rate Limits**: Gemini API has usage quotas

## 📈 Roadmap

- [ ] **Multiple AI Personalities** (HR Manager, Tech Lead, etc.)
- [ ] **Industry-Specific Analysis** (Tech, Finance, Marketing)
- [ ] **CV Templates** & Suggestions
- [ ] **Comparison Tool** (Before/After analysis)
- [ ] **Export Reports** (PDF reports of feedback)
- [ ] **Chrome Extension** (Analyze job posts)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini AI** for the natural language processing
- **Firebase** for the excellent serverless platform
- **PDF.js** for client-side PDF processing
- **The Job Market** for being brutal enough to inspire this tool

## 🤔 FAQ

### Q: Is my CV data stored anywhere?
**A:** No! CV content is processed in real-time and not stored on our servers.

### Q: How accurate is the AI feedback?
**A:** The AI provides general guidelines based on common CV best practices. Always consider industry-specific requirements.

### Q: Can I use this for commercial purposes?
**A:** Yes! The MIT license allows commercial use. Just give credit where due.

### Q: Why did you build this?
**A:** Because getting rejected without feedback sucks, and sometimes we all need a good laugh at ourselves.

## 📞 Support

- **Email**: [sahil.bh@gmail.com]

---

**Remember**: If you can't laugh at your own CV, who can you laugh at? 😄

⭐ **Star this repo if it helped you get roasted (and hopefully hired)!**
