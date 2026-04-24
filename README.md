# AP-Gurukul Telegram Web App

This is the Vite + React application optimized to run inside the Telegram Messenger as a Telegram Mini App.

## 🔄 Universal Data Sync & Authentication
**This application shares a unified Firebase database with the entire AP-Gurukul ecosystem.** 
- Users authenticate via **Gmail (Google Auth)** or their Telegram ID. If a user logs into this Telegram App with their Gmail account, their profile, progress, and history are perfectly synced with the Next.js Web App and Mobile App!
- When an admin adds new questions to the database via the Admin Portal, they instantly appear here in real-time.

## 🚀 Getting Started

First, run the development server:
```bash
npm install
npm run dev
```
Open [http://localhost:3001](http://localhost:3001) with your browser. To test Telegram-specific features, you will need to inject the Telegram Web App script or test via BotFather.

## 🤝 Contributing
Please see the `CONTRIBUTING.md` and `SECURITY.md` files for guidelines. As an open-source contributor, you will test this UI against our public staging APIs.
