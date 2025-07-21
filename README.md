
# 🛡️ Cybersecurity Training Package

A beginner-friendly interactive web app designed to educate users (especially students) on essential cybersecurity concepts through short videos, quizzes, and feedback forms.

## 🚀 Features

- 🔐 Login & Sign-Up with Murdoch student emails only (via Firebase)
- 🎥 4 concise training modules with integrated videos:
  - Cybersecurity Essentials
  - Strong Passwords
  - Multi-Factor Authentication (MFA)
  - Summary
- 📝 Topic-based Quizzes (Auto-graded)
- 📊 Personal Report generation with scores
- 💬 Feedback survey for continuous improvement

## 📁 Project Structure

```
📦 root/
├── index.html          # Main app (contains all HTML, CSS, JS)
├── intro.mp4           # Training video for Cybersecurity Essentials
├── password.mp4        # Training video for Strong Passwords
├── your-mfa-video.mp4  # Training video for MFA
├── summary.mp4         # Training video for Summary
├── README.md           # You're reading this!
```

## 🔧 How to Use

### 1. 📦 Setup Firebase (Optional for Deployment)

If you're hosting the app yourself, you can update the Firebase configuration in the script section at the bottom of `index.html` with your own Firebase project credentials.

### 2. 🖥️ Running the App

Just open `index.html` in any modern web browser.

> ✅ Tip: If you’re deploying to GitHub Pages or another static host, make sure all video files are uploaded too!

### 3. 👥 User Flow

- **Sign Up:** Use a valid `@student.murdoch.edu.au` email to register.
- **Login:** Access your dashboard after authentication.
- **Watch Videos:** Training modules become interactive after completion.
- **Take Quizzes:** Triggered at the end of each module or via the Quiz tab.
- **Submit Feedback:** Available under the “Survey” tab.
- **Generate Report:** Tabulates completed modules and scores in the “Report” section.

## ⚠️ Requirements

- Modern Browser (Chrome, Firefox, Edge, etc.)
- Internet access for Firebase and Tailwind CDN


## ✨ Credits

Developed by **[Your Name]**  
Powered by:  
- Firebase Authentication  
- TailwindCSS  
- Vanilla JS  

## 📜 License

This project is for educational use. Please do not use real credentials during testing.  
