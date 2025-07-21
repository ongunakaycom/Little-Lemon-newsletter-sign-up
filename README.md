# 📨 Little Lemon – Newsletter Sign-Up App

**Little Lemon Newsletter Sign-Up** is a mobile application built using **React Native** and **Expo**. This app simulates a simple onboarding flow where users can subscribe to the fictional Little Lemon newsletter. It features elegant screen transitions using **React Navigation**, along with a clean and minimal user interface.

---

## 🧱 Stack Overview

| Layer         | Technology              |
|--------------|--------------------------|
| Framework     | React Native (Expo)      |
| Language      | JavaScript (ES6)         |
| Navigation    | React Navigation         |
| Styling       | React Native Stylesheet  |
| Assets        | Custom Little Lemon logo |
| Platform      | Android, iOS, Web        |

---

## 🧪 Features

✅ Welcome screen with logo and intro message  
✅ Subscription screen with input validation  
✅ Screen-to-screen navigation  
✅ Expo starter configuration for cross-platform support  
✅ Reusable utility functions in `utils/`

---

## 📁 Directory Structure

```
Little-Lemon-newsletter-sign-up/
├── assets/                    # App icons and branding
│   ├── little-lemon-logo.png
│   └── splash.png
├── navigators/               # Navigation stack setup
│   └── RootNavigator.js
├── screens/                  # App screens
│   ├── SubscribeScreen.js
│   └── WelcomeScreen.js
├── utils/                    # Shared utility functions
│   └── index.js
├── App.js                    # Entry point
├── little_lemon.gif          # Demo animation
├── app.json                  # Expo app config
├── package.json              # Dependencies
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 Run Locally

### 📦 Install Dependencies

```bash
npm install
```

### 📱 Start App

```bash
# Start Expo server
npm start
# OR for specific platforms:
npm run android
npm run ios
npm run web
```

> Requires Expo Go on mobile, or iOS/Android simulator installed.

---

## 🎞️ Demo

![Little Lemon Newsletter Flow](./little_lemon.gif)

---

## 📦 Dependencies

```json
"expo": "~46.0.16",
"react-native": "0.69.6",
"react": "18.0.0",
"@react-navigation/native": "^6.0.12",
"@react-navigation/native-stack": "^6.8.0"
```

---

## 📬 Author

I'm Ongun Akay, a Senior Full-Stack Developer with expertise across various technologies.

About Me:  
👀 I specialize in full-stack development with extensive experience in frontend and backend technologies.
🌱 Currently, I'm sharpening my skills in advanced concepts of web development.
💞️ I’m always open to exciting collaborations and projects that challenge my abilities.
📫 Reach me at: [info@ongunakay.com](mailto:info@ongunakay.com)

---

## 📄 License

MIT License – See [`LICENSE`](./LICENSE)
