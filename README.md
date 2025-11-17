\# 📊 SubTrackr – Smart Subscription Tracker



SubTrackr is a lightweight web application that helps users track all their subscriptions in one place.  

It includes login, subscription management, renewal reminders, and total monthly spending — all powered by Firebase.



This project is deployed using \*\*Vercel\*\*, and Firebase API keys are securely handled using \*\*serverless API routes + environment variables\*\* (no API keys in GitHub).



---



\## 🚀 Features



\### 🔐 Authentication

\- Email/Password Signup  

\- Secure Login  

\- Logout  

\- Powered by Firebase Authentication  



\### 📦 Subscription Management

\- Add new subscriptions  

\- Edit existing ones  

\- Delete subscriptions  

\- Renewal date tracking  

\- Automatic “Renewal Soon” and “Expired” indicators  

\- Shows total monthly cost  



\### ☁️ Cloud Database (Firestore)

\- Stores all subscriptions  

\- Data scoped to each user  

\- Real-time fetching and updates  



\### 🔒 Secure API Key Handling

\- Firebase config is NOT inside frontend code  

\- `/api/firebase` serverless endpoint returns config  

\- Uses Vercel environment variables  

\- Keys are never exposed in GitHub  



---



\## 📁 Project Structure



your-project/

│── index.html # Main app UI + Firebase logic

│── style.css # Styling

│── api/

│ └── firebase.js # Secure Firebase config (serverless API)

│── .gitignore

│── README.md



