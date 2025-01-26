# LeetCode Clone 

### Built With React, NextJS, TypeScript, TailwindCSS, Firebase

# [Demo](https://youtu.be/igqiduZR-Gg)

![Screenshot of App](https://i.ibb.co/b3XDkdN/Full-Stack-1.png)
# leetcode-yt

# Foobar

A full-featured LeetCode clone built using Next.js, Firebase, Recoil, and TypeScript, providing an interactive coding environment with authentication, problem-solving, and code submission functionalities.

Table of Contents
Overview
Features
Tech Stack
Project Timeline
Installation
Usage
Deployment
Screenshots
Contributing
License
Contact


Overview
The LeetCode Clone is a web-based coding platform that allows users to solve coding problems in an interactive editor, track progress, and manage authentication with Firebase.

Features
🔐 Authentication (Signup/Login/Reset Password)
🧩 Coding workspace with a rich text editor
🗂 Problem listing with solutions and test cases
❤️ Like, Dislike, and Star problems
⏲ Timer for problem-solving tracking
🎉 Confetti celebration for successful submissions
💾 Save code to local storage
🌓 Dark and Light mode
🚀 Deployed using Vercel
Tech Stack
Frontend: Next.js (React.js), TypeScript, TailwindCSS
State Management: Recoil
Database: Firebase Firestore
Authentication: Firebase Auth
UI Components: React-Toastify, React-Quill
Deployment: Vercel
Project Timeline
1. Initial Setup
[0:00:00] Intro
[0:00:29] Demo of the App
[0:05:23] Project Setup
2. Authentication
[0:08:51] Auth Page Setup
[0:13:19] Auth Page Navbar
[0:18:54] AuthModal Layout UI
[0:22:16] Login UI
[0:29:41] Signup UI
[0:31:59] Reset Password UI
[0:33:13] Integrating Recoil Auth State
[0:47:31] Firebase Setup
[0:52:41] Signup Functionality
[1:01:21] Login Functionality
[1:05:14] Auth Page Route Guard
3. Application UI
[1:08:01] Home Page UI
[1:12:50] Problems Table UI
[1:21:01] YouTube Video Modal
[1:29:51] Topbar Update On Auth
[1:32:46] Logout Functionality
[1:37:11] Auth Modal Optimizations
[1:38:44] Reset Password Functionality
[1:42:56] React Toastify Notifications
[1:47:19] Image Optimizations
4. Problem Solving Interface
[1:54:33] Creating [pid] page and updating topbar
[2:02:27] Creating Timer.tsx
[2:12:31] Creating Workspace.tsx
[2:15:18] Splitting the Page
[2:19:47] Creating ProblemDescription.tsx
[2:26:03] Creating PreferenceNav.tsx
[2:34:39] Creating Code Editor
[2:41:10] Adding Test Cases UI
[2:50:15] Creating EditorFooter.tsx
[2:56:32] Data Handling Explained
5. Adding Problems
[3:01:50] Two Sum Problem
[3:12:52] Reverse Linked List
[3:18:05] Jump Game Problem
[3:20:13] Valid Parentheses Problem
[3:21:16] Search 2D Matrix Problem
6. Backend & Firestore Integration
[3:22:01] Using SSG for [pid].tsx
[3:46:47] Updating test cases UI
[3:51:39] Initializing Firestore
[3:55:56] Adding Problems to DB
[4:12:09] Fetch Problems
[4:32:58] Create Users in DB
[4:40:33] Fetch Problem Data
7. Additional Features
[4:51:28] Loading Skeletons
[4:56:35] Get user data on the problem
[5:06:23] Like functionality
[5:27:51] Dislike functionality
[5:39:03] Star functionality
[5:46:03] Next and Previous problem
[5:55:23] Solving Hydration Error
[5:58:08] Confetti Celebration
8. Final Touches & Deployment
[6:01:43] Code Submission
[6:20:50] Save code to local storage
[6:24:48] Solving bugs
[6:31:08] Toggle Full Screen
[6:34:13] SettingsModal UI
[6:41:33] SettingsModal Functionality
[6:54:23] Update Home Page
[6:59:11] Sandboxing Technique
[7:01:58] Deployment
[7:05:08] Firebase Rules
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/leetcode-clone.git
cd leetcode-clone
Install dependencies:

bash
Copy
Edit
npm install
Set up environment variables:
Create .env.local and add Firebase credentials and other secrets.

Run the development server:

bash
Copy
Edit
npm run dev
Deployment
This project can be deployed easily on Vercel.

Install Vercel CLI:

bash
Copy
Edit
npm install -g vercel
Deploy:

bash
Copy
Edit
vercel --prod
Screenshots

Contributing
Contributions are welcome!

Fork the project
Create a feature branch (git checkout -b feature-name)
Commit your changes (git commit -m "Add feature")
Push to the branch (git push origin feature-name)
Create a Pull Request
License
This project is licensed under the MIT License.


