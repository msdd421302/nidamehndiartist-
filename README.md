# Nida Mehndi Artist - Premium Bridal Website

A luxury, fully responsive website for Nida Mehndi Artist, built with React, Vite, Tailwind CSS, and Firebase.

## 🚀 Live Demo
You can view the live site here: [Insert your URL here]

## 🛠️ Features
- **Luxury Aesthetic**: Deep burgundy and gold theme designed for premium bridal services.
- **Interactive Portfolio**: High-fidelity gallery with image lightbox previews.
- **Booking System**: Integrated with Firebase Firestore for persistent data and Auth for secure login.
- **WhatsApp Integration**: Automated booking message generation for the artist.
- **Responsive Design**: Optimized for desktop, tablet, and mobile.

## 📦 Deployment Instructions

### Option 1: Manual Upload (Hostinger / cPanel)
1. Run the build command:
   ```bash
   npm run build
   ```
2. Open the `dist` folder.
3. Upload all contents of the `dist` folder to your server's `public_html` directory.
4. Ensure the `.htaccess` file (included in `public/`) is also uploaded to handle routing.

### Option 2: GitHub Pages
1. Push this repository to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set the source to **GitHub Actions**.
4. Use a standard Static Web App workflow or the one provided in `.github/workflows/deploy.yml`.

## ⚙️ Development Setup
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the dev server:
   ```bash
   npm run dev
   ```

## 🔒 Security
- Security rules for Firestore are located in `firestore.rules`.
- Ensure your Firebase project configuration is updated in `firebase-applet-config.json`.

---
© 2025 Nida Mehndi Artist. All Rights Reserved.
