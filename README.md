# FocusForge

FocusForge is a student-focused productivity and concentration web app designed to help users build deep focus, track study time, and develop consistent learning habits. It aims to turn distraction into discipline through simple, intentional design.

![FocusForge Dashboard](https://img.shields.io/badge/Status-Active%20Development-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Flask](https://img.shields.io/badge/Flask-2.0+-lightgrey)

---

## Why FocusForge?

### Students often struggle with:

- 📱 Losing focus during study sessions
- ⏰ Poor time management
- 🔄 Lack of consistency
- 📊 No clear visibility of effort spent

FocusForge addresses these problems with a **minimal, distraction-free interface** that encourages intentional work and deep focus.

---

## ✨ Key Features

### 🎯 Focus Sessions
Start dedicated focus sessions to study without distractions. Choose from flexible session durations (25, 45, 60, or 90 minutes).

### ⏱️ Study Time Tracking
Track how much time you spend focusing each day with detailed statistics:
- **Today's Focus Time** - Minutes of deep work completed today
- **Total Study Time** - All-time cumulative focused learning hours
- **Current Streak** - Consecutive days of maintaining focus discipline

### 🎨 Clean Dashboard
A modern, monochrome dashboard that shows your progress at a glance. Built with a student-first approach to reduce cognitive overload.

### 🧘 Minimal UI
Designed to reduce cognitive load and keep attention on work. No unnecessary animations, notifications, or distractions.

### 📚 Student-First Design
Built specifically for students and self-learners who want to develop sustainable study habits.

---

## 🎯 Benefits

✅ Improves concentration and deep work ability  
✅ Builds daily study consistency through streak tracking  
✅ Helps students understand how they actually spend time  
✅ Encourages discipline through simple habits  
✅ Reduces overwhelm caused by complex productivity tools  

---

## 🛠️ Tech Stack

- **Backend**: Python (Flask)
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Storage**: LocalStorage (for MVP, database integration planned)
- **Version Control**: Git & GitHub

---

## 📁 Project Structure

```
focusforge/
│
├── app.py                 # Flask application entry point
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── .gitignore            # Git ignore rules
│
├── static/               # Static assets
│   ├── css/
│   │   └── style.css    # Main stylesheet (monochrome design)
│   └── js/
│       └── timer.js     # Timer logic and data persistence
│
└── templates/            # HTML templates
    └── dashboard.html   # Main dashboard interface
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/focusforge.git
cd focusforge
```

2. **Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the application**
```bash
python app.py
```

5. **Open in browser**
```
http://127.0.0.1:5000
```

---

## 💻 Usage

1. **Enter your study task** - Define what you're working on
2. **Choose session duration** - Select 25, 45, 60, or 90 minutes
3. **Start focusing** - Begin your distraction-free session
4. **Track progress** - View your daily focus time and streaks
5. **Build consistency** - Return daily to maintain your streak

---

## 📊 Current Features

- ✅ Customizable focus timer (25/45/60/90 min)
- ✅ Task input for session context
- ✅ Real-time countdown display
- ✅ Pause and reset functionality
- ✅ Daily focus time tracking
- ✅ Total study hours counter
- ✅ Streak tracking system
- ✅ Data persistence (localStorage)
- ✅ Responsive design for mobile/desktop
- ✅ Monochrome minimal UI

---

## 🔮 Roadmap

### Phase 1 (Current)
- [x] Basic timer functionality
- [x] Study time tracking
- [x] Minimal dashboard UI

### Phase 2 (Coming Soon)
- [ ] User authentication (login/signup)
- [ ] Database integration (SQLite/PostgreSQL)
- [ ] Session history and analytics
- [ ] Break reminders
- [ ] Custom session durations

### Phase 3 (Future)
- [ ] Weekly/monthly progress reports
- [ ] Focus mode (ambient sounds)
- [ ] Goal setting features
- [ ] Export study data
- [ ] Mobile app (React Native)

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Nitik**  
- GitHub: https://github.com/Nitikpsn
---

## 🙏 Acknowledgments

- Inspired by deep work principles and minimalist productivity tools
- Built for students who want to respect their time and build sustainable habits
- Design influenced by modern monochrome aesthetics

---

## 📧 Contact

Have questions or suggestions? Feel free to:
- Open an issue on GitHub
- Reach out via email
- Submit a pull request

---

<div align="center">

### 💡 Vision

**FocusForge is not just a tool—it's a system to help students respect their time, train their focus, and grow steadily every day.**

*Built for students and self-learners*

</div>

---

## ⭐ Star History

If you find FocusForge helpful, please consider giving it a star! It helps others discover the project.

[![Star History Chart](https://api.star-history.com/svg?repos=YOUR_USERNAME/focusforge&type=Date)](https://star-history.com/#YOUR_USERNAME/focusforge&Date)
