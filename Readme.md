# 🧑‍💼 Mini LinkedIn‑like Community Platform
A mini LinkedIn-style social network where users can register, create a profile, and post public updates. Built with modern technologies like Next.js, MongoDB, and Clerk authentication.

## 🔗 Live Demo
🌐Link: https://linkedin-clone-a077e.web.app

## 🛠️ Tech Stack
- **Frontend**: React.js (Create React App)
- **Authentication**: Firebase Authentication (Email & Google Login)
- **Database**: Firebase Firestore
- **Styling**: CSS,SCSS
- **Hosting**: Firebase Hosting.

 ## 📸 Features
- ✅ Register/Login using **Email/Password** or **Google Authentication**
- ✅ User Profile (Name, Email, Bio, Profile Picture)
- ✅ **Public Feed** for text/image posts with timestamp
- ✅ Like and comment on posts
- ✅ Search for users and connect
- ✅ Responsive layout with navigation, modals, and forms

  ## 🚀 Getting Started
   1. Clone the Repository- https://github.com/pr-priya/LinkedIn-Clone
   2. Install Dependencies
      - npm install
   3. Firebase Setup
     - Go to Firebase Console and create a new project
     - Enable Authentication:
         - Email/Password
         - Google provider
     - Create a Firestore database (in test mode)
     - Optional: Set up Firebase Hosting
    4. Add Firebase Configuration
        - Create a file named firebaseConfig.js in the src folder:
            - const firebaseConfig = {
                 apiKey: "YOUR_API_KEY",
                 authDomain: "YOUR_AUTH_DOMAIN",
                 projectId: "YOUR_PROJECT_ID",
                 storageBucket: "YOUR_STORAGE_BUCKET",
                 messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
                 appId: "YOUR_APP_ID"
};
export default firebaseConfig;

    5. Run the App
        - npm start
    6. Deploy with Firebase Hosting (Optional)
        - npm install -g firebase-tools
        - firebase login
        - firebase init hosting
        - firebase deploy

  🧪 Demo Login (Optional)
     - Use Google Sign-In or register using Email/Password
        
        
         
   
  
 
  

 

 

 
