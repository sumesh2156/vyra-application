# VYRA - Food, Diet & Workout Tracker

## Overview
VYRA is a web-based fitness application designed to log daily food intake, track macros/water, generate custom meal plans, build workout splits, and analyze insights.

## Project Structure
- `index.html`: The main web application file.
- `firebase-config.js`: Contains your Firebase authentication & database keys.
- `firestore.rules`: Security rules to deploy in your Firebase Firestore console.

## Setup Instructions
1. Upload `index.html` and `firebase-config.js` to your web server or hosting service (e.g., GitHub Pages, Netlify, Vercel, Firebase Hosting).
2. Ensure both files are stored in the same root directory.
3. Apply the security rules from `firestore.rules` inside your Firebase Console under **Firestore Database > Rules**.
