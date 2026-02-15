
# 🔐 Firebase Authentication UI (React + Vite)

A simple and clean Firebase Authentication project built using **React + Vite** with a modern centered UI design.

This project demonstrates how to implement:

* Email & Password Authentication
* User Registration
* Firebase configuration using environment variables
* Clean and responsive UI design
* Secure project structure

---

## 🚀 Features

✅ User Registration
✅ Full Name, Email, Password form
✅ Firebase Authentication Integration
✅ Environment-based configuration
✅ Clean centered card UI
✅ Gradient background design
✅ GitHub-ready project structure

---

## 🛠️ Tech Stack

* React (Vite)
* Firebase Authentication
* JavaScript (ES6+)
* CSS (Custom Styling)

---

## 📁 Project Structure

```
firebase-auth-ui/
│
├── public/
│
├── src/
│   ├── components/
│   │   └── Register.jsx
│   ├── firebase.js
│   ├── App.jsx
│   ├── main.jsx
│   └── style.css
│
├── .env.example
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/shreyasnarsale/firebase_auth.git
cd firebase_auth
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Setup Firebase

Go to **Firebase Console** → Create Project → Enable Authentication → Enable Email/Password method.

Then copy your Firebase config keys.

---

### 4️⃣ Create Environment File

Copy `.env.example` and create a new file:

```
.env
```

Paste your Firebase credentials:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

⚠️ Never push `.env` to GitHub.

---

### 5️⃣ Run the Project

```bash
npm run dev
```

Open in browser:

```
http://localhost:5173
```

---

## 🎨 UI Preview

* Centered authentication card
* Gradient background
* Styled input fields
* Modern button hover effect
* Clean spacing & alignment

---

## 🔒 Security Best Practices

* Firebase keys stored in `.env`
* `.env` added in `.gitignore`
* Only `.env.example` pushed to GitHub
* No sensitive credentials committed

---

## 📌 Future Improvements (Optional)

* Login Page
* Logout functionality
* Protected routes
* Google Sign-In
* Tailwind CSS UI
* Context API for global auth state
* Deployment to Netlify / Vercel

---

## 👨‍💻 Author

**Shreyas Narsale**
GitHub: [https://github.com/shreyasnarsale](https://github.com/shreyasnarsale)


