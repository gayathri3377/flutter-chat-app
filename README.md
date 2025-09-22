# Real-Time Chat Application

This is a simple **chat application** built with Flutter.  
It lets people sign up, create a small profile with a picture, and start chatting instantly in a shared global room. Messages show up in real-time, so everyone can see them the moment they are sent.  

---

## Functionalities
- **Sign up or log in** using email and password (handled by Firebase Auth).  
- **Set up a profile** with your name and a picture (stored in Firebase Storage).  
- **Chat in real-time** with everyone in a global room (messages saved in Cloud Firestore).  
- **Get notifications** when new messages arrive (using Firebase Cloud Messaging).  

---

## Working
- **Flutter (Dart)** → builds the app for Android and iOS.  
- **Firebase** → takes care of the heavy lifting:
  - Auth → handles login and signup.  
  - Firestore → stores chat messages so everyone sees them live.  
  - Storage → keeps profile pictures safe.  
  - Cloud Messaging → pushes notifications.  

---
