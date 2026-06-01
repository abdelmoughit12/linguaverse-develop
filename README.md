# 🌍 LinguaVerse

### Learn Languages Smarter with AI, Gamification & Real-Time Interaction

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.22+-02569B?style=for-the-badge&logo=flutter" />
  <img src="https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart" />
  <img src="https://img.shields.io/badge/Firebase-Backend-FFCA28?style=for-the-badge&logo=firebase" />
  <img src="https://img.shields.io/badge/Gemini-AI%20Powered-8E75FF?style=for-the-badge" />
</p>

---

## 📱 About The Project

**LinguaVerse** is an AI-powered mobile application designed to make language learning more interactive, immersive, and engaging.

Built with **Flutter**, the platform combines:

* 🎯 Smart quizzes
* 🤖 AI-generated exercises
* 🎮 Gamification mechanics
* 🔊 Speech & pronunciation tools
* ⚡ Real-time interactions
* ☁️ Firebase cloud services

The project was developed as part of the **Mobile Development & Metaverse Module** at **ENSIAS Taroudant (2025–2026)**.

---

# ✨ Key Features

## 🤖 AI Quiz Engine

Generate dynamic quizzes using **Google Gemini 1.5 Flash**.

### Features

* AI-generated questions
* Instant feedback system
* Countdown timer
* Animated interactions
* Adaptive difficulty
* Robust JSON parsing
* Error handling for overloaded AI services

---

## 🎮 Gamification System

Make learning addictive and motivating.

### Includes

* XP points system
* Perfect score bonuses
* Progress tracking
* Learning streaks
* SQLite local synchronization
* Firestore cloud sync

---

## 🔐 Authentication & Security

Powered by Firebase Authentication.

### Implemented

* Email/password login
* Secure registration
* Password reset via email
* Session persistence
* Logout management

---

## 🔊 Audio & Pronunciation

Improve speaking and listening skills.

### Technologies

* Text-To-Speech (TTS)
* Speech-To-Text (STT)
* Pronunciation challenge system

---

## 🧠 Smart Learning System

Spaced Repetition System (SRS) for optimized memorization.

### Benefits

* Better long-term retention
* Personalized review scheduling
* Adaptive learning flow

---

# 🏗️ Architecture

The project follows:

* **MVVM Architecture**
* **Clean Architecture Principles**
* Modular feature-based structure

```bash
lib/
├── core/
│   ├── services/
│   ├── utils/
│   └── constants/
│
├── features/
│   ├── auth/
│   ├── lessons/
│   ├── quiz/
│   ├── ai_quiz/
│   ├── gamification/
│   ├── duel/
│   └── pronunciation/
│
├── shared/
│   ├── widgets/
│   ├── theme/
│   └── components/
│
├── router.dart
├── app.dart
└── main.dart
```

---

# ⚙️ Tech Stack

| Category         | Technology        |
| ---------------- | ----------------- |
| Framework        | Flutter 3.22+     |
| Language         | Dart              |
| State Management | Riverpod          |
| Navigation       | Go Router         |
| Backend          | Firebase          |
| Local Database   | SQLite (sqflite)  |
| AI Engine        | Google Gemini API |
| TTS              | flutter_tts       |
| STT              | speech_to_text    |
| Charts           | fl_chart          |
| AR               | ar_flutter_plugin |
| ML               | Google ML Kit     |

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/linguaverse.git
cd linguaverse
```

---

## 2️⃣ Install Dependencies

```bash
flutter pub get
```

For iOS:

```bash
cd ios
pod install
cd ..
```

---

## 3️⃣ Firebase Configuration

### Android

Place:

```bash
google-services.json
```

inside:

```bash
android/app/
```

### iOS

Place:

```bash
GoogleService-Info.plist
```

inside:

```bash
ios/Runner/
```

⚠️ Never commit these files.

---

## 4️⃣ Environment Variables

```bash
cp .env.example .env
```

Add your Gemini API key:

```env
GOOGLE_API_KEY=YOUR_KEY
```

---

## 5️⃣ Run The App

```bash
flutter run
```

Specific devices:

```bash
flutter run -d chrome
flutter run -d "iPhone 15 Pro"
```

---

# 🌿 Git Workflow

```bash
main
 └── develop
      ├── feature/auth
      ├── feature/ai-quiz
      ├── feature/gamification
      ├── feature/pronunciation
      ├── feature/duel
      └── feature/lessons
```

---

# 📋 Development Rules

✅ Conventional commits only

```bash
feat(auth): add login validation
fix(quiz): correct timer bug
```

✅ Always branch from `develop`

✅ Rebase before Pull Request

❌ Never commit:

* `.env`
* `google-services.json`
* `GoogleService-Info.plist`

---

# 👨‍💻 Team

| Member               | Role                     |
| -------------------- | ------------------------ |
| Hiba EL OUAFI        | Authentication & AI      |
| Zineb BOUGHEDDA      | Lessons & Gamification   |
| Abdelmoughit MOURADI | Quiz & Firebase          |
| Achraf MOUASIS       | Audio & Machine Learning |

### Academic Supervisor

**Pr. Latifa RASSAM**

---

# 📸 Screenshots

*Add your application screenshots here*

```md
![Home Screen](assets/screens/home.png)
![Quiz Screen](assets/screens/quiz.png)
```

---

# 🔮 Future Improvements

* 🌍 Multiplayer language battles
* 🧑‍🏫 AI conversation tutor
* 🥽 VR/AR immersive learning
* 📊 Advanced analytics dashboard
* 🧠 Personalized AI learning paths

---

# 📄 License

This project was developed for educational purposes at ENSIAS Taroudant.

---


