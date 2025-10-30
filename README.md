# MindMate

**MindMate** is a modern **Mental Wellness Platform** built using **React.js**, **Node.js**, and **MongoDB**. It aims to provide users with a safe, personalized, and AI-assisted space for improving mental health through mood tracking, journaling, therapy session scheduling, and wellness insights.

---

## 🧠 Overview

MindMate bridges technology and emotional wellbeing by offering digital tools for users to monitor and enhance their mental health. The platform enables real-time emotion tracking, mindfulness exercises, chat-based support, and secure storage of user wellness data.

---

## 🚀 Features

* **User Authentication:** Secure signup and login using JWT-based authentication.
* **Mood Tracker:** Record daily moods and get visual insights on emotional trends.
* **AI Chat Support:** An AI-powered chatbot that listens and provides mindfulness tips.
* **Journaling:** Private digital diary with encryption to ensure privacy.
* **Therapist Portal:** Allows verified therapists to manage sessions and interact with clients.
* **Community Section:** Safe, moderated community for peer support.
* **Dashboard Analytics:** Visual representation of user mood trends, goals, and progress.

---

## 🧩 Tech Stack

| Layer                         | Technology                                                           |
| ----------------------------- | -------------------------------------------------------------------- |
| **Frontend**                  | React.js (with Hooks, Context API, Tailwind CSS)                     |
| **Backend**                   | Node.js + Express.js                                                 |
| **Database**                  | MongoDB (Mongoose ORM)                                               |
| **Authentication**            | JWT (JSON Web Tokens)                                                |
| **AI Integration (optional)** | OpenAI API / Gemini API                                              |
| **Hosting**                   | Vercel (Frontend), Render/Heroku (Backend), MongoDB Atlas (Database) |

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/mindmate.git
cd mindmate
```

### 2. Setup environment variables

Create a `.env` file in both `server` and `client` directories.

**Backend (.env)**

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_api_key   # optional if using AI features
```

**Frontend (.env)**

```env
REACT_APP_API_BASE_URL=http://localhost:5000/api
```

### 3. Install dependencies

```bash
# In root directory
yarn install  # or npm install

# Navigate to server
cd server && yarn install

# Navigate to client
cd ../client && yarn install
```

### 4. Run the app

```bash
# Run backend
cd server
npm start

# Run frontend in another terminal
cd client
npm start
```

App will be available at: **[http://localhost:3000](http://localhost:3000)**

---

## 📁 Folder Structure

```
mindmate/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page-level components
│   │   ├── context/        # State management (Context API)
│   │   └── utils/          # Helper functions
│   └── package.json
│
├── server/                 # Node.js backend
│   ├── config/             # DB and environment configuration
│   ├── controllers/        # Request handlers
│   ├── models/             # Mongoose models
│   ├── routes/             # Express routes
│   └── server.js           # App entry point
│
└── README.md
```

---

## 🔒 Security & Privacy

* All personal data and journals are **encrypted** before storage.
* **JWT tokens** ensure secure authentication.
* **HTTPS** enforced for all API communications.
* No user data shared with third parties.

---

## 🧠 Future Enhancements

* Integrate **voice journaling** using speech-to-text APIs.
* Add **real-time therapist chat** with end-to-end encryption.
* Expand AI chatbot with **emotion-aware responses**.
* Introduce **habit formation tracker** with gamification elements.

---

## 🧪 Testing

```bash
# Run backend tests
cd server
npm test

# Run frontend tests
cd client
npm test
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---

## 💬 Acknowledgements

* Built with ❤️ using React, Node, and MongoDB.
* Inspired by modern wellness platforms like Calm & Headspace.
* Thanks to the open-source community for libraries and frameworks.

---

**MindMate – Your AI Companion for Better Mental Wellness.**
