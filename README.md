# Rathod Hub 3.0

Mobile + PC installable study app with **Study Material**, **Live Chat**, and **Doubt Room**.

## Firebase setup
1. Create a Firebase project and add a Web App.
2. Copy the Web SDK config into `firebase-config.js`.
3. Firebase Authentication → Sign-in method → enable **Anonymous**.
4. Firestore Database → create database.
5. Install Firebase CLI and deploy rules: `firebase deploy --only firestore:rules`.
6. Add study resources to the `materials` collection with fields: `title`, `description`, `subject`, `type`, `url`, `createdAt`.

Until Firebase config is added, the app runs safely in local demo mode.

## GitHub Pages
Repository Settings → Pages → Source: **GitHub Actions**. Every push to `main` deploys automatically.

## Install
Open the deployed site in Chrome/Edge and select **Install App**. It works as a PWA on Android and desktop.

## Status
Firebase backend connected and GitHub Pages deployment enabled.
