
# Entrepreneur Skilling Platform

An interactive web-based platform to **empower aspiring entrepreneurs** with essential skills through courses, quizzes, and personalized certificates.

---

## 🌟 Key Features

- ✅ **Login System** (basic frontend login form)
- 📚 **5 Skill-Building Courses**:
  - Business Planning
  - Marketing
  - Finance
  - Operations
  - Leadership
- 🧠 **10 Quiz Questions per Course**
- 📊 **Real-Time Score Evaluation**
- 🏆 **Scoreboard** displaying previous quiz scores
- 🎓 **Certificate of Achievement** for scores ≥ 8
- 🖼️ **Styled Certificate** with background, borders, and logo
- 💾 **Local Storage** to save user quiz results

---

## ⚙️ How It Works

1. User logs in with name and age.
2. Selects a course and starts the quiz.
3. After answering all 10 questions:
   - If score ≥ 8: a certificate with their name and course is shown.
   - If score < 8: a retry encouragement message is shown.
4. Score is saved in browser's local storage and shown in the **Scoreboard**.
5. The platform is fully responsive and styled with logo and background.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Storage**: Browser LocalStorage
- *(Optional future feature: Flask/Python backend for user data and session management)*

---

## 🚀 Future Improvements

- Export certificate as downloadable PDF
- Admin dashboard to manage users and scores
- Quiz timer and progress bar
- Mobile optimization
- Backend database integration (SQLite or MongoDB)

---

## 📦 Getting Started

1. **Clone this repository**:
   git clone https://github.com/SaiNiharikaYadav/entrepreneur-skilling-platform.git
   cd entrepreneur-skilling-platform
