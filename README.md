# CivicFix: Hyper-Local Issue Tracker 🇮🇳

![React](https://img.shields.io/badge/Frontend-React-informational)
![TailwindCSS](https://img.shields.io/badge/Style-TailwindCSS-informational)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)
![Supabase](https://img.shields.io/badge/Alt%20DB-Supabase-lightgrey)
![Maps](https://img.shields.io/badge/Maps-Google%20Maps%20API-blue)
![Maps](https://img.shields.io/badge/Maps-MapmyIndia%20API-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)
![Made by](https://img.shields.io/badge/Made%20by-Binary%20Bros-%23ff69b4)

> Report issues around you with a photo and a location. Track fixes on a public map. Help authorities respond faster and better.

---

## 🌟 Inspiration
We asked a simple question: why do small problems around us never get fixed? Potholes, broken streetlights, and overflowing garbage affect daily life. Complaints get lost, people give up. CivicFix turns that frustration into action. Report an issue in seconds, then watch it move toward a solution in the open.

---

## 🚀 What it does
- Snap a photo of a local issue
- Location is auto tagged with Google Maps or MapmyIndia
- Issues appear on a public map for everyone
- People upvote issues that affect them
- The complaint is forwarded to the relevant municipal authority
- Reporters earn Civic Hero points when issues are resolved

Municipal bodies get a clean dashboard with reported vs resolved counts, response time, and issue hot spots.

---

## 🛠️ Built With
- **Frontend**: React, TailwindCSS
- **Backend and Database**: Firebase Auth, Firestore, Firebase Storage
- **Alternative SQL backend**: Supabase
- **Maps and Geolocation**: Google Maps API or MapmyIndia API
- **Cloud Hosting**: Firebase Hosting
- **Auth Options**: Google Sign In, Phone OTP
- **Design and Collab**: Figma, GitHub

---

## 📦 Quick Start

### 1) Clone and install
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/civicfix.git
cd civicfix
npm install
```

### 2) Environment
Create a file called `.env` in the project root. If you use Vite, prefix with `VITE_`. Example keys below.

```bash
# Firebase
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=

# Mapping
VITE_GOOGLE_MAPS_API_KEY=      # or
VITE_MAPMYINDIA_API_KEY=
```

### 3) Run the app
```bash
# Vite
npm run dev

# or Create React App
npm start
```

Open http://localhost:5173 or http://localhost:3000 depending on your setup.

---

## 📖 Project Story

### How we built it
We kept it mobile first. React handles UI, Firebase stores data and photos, maps handle geolocation. When an issue is marked resolved, Civic Hero points update in real time.

### Challenges
GPS accuracy in crowded areas, privacy vs transparency, and different municipal workflows. Building fast while staying simple was the hardest part.

### What we learned
Design for everyone, not only power users. Real civic problems are social and technical. Trust matters as much as code.

---

## 🔮 Roadmap
- Pilot with a mid sized Indian city
- Offline reporting with sync
- Anonymous mode
- AI that detects issue type from the photo
- Predictive dashboards for authorities
- Localization and rollout to more regions

---

## 👥 Team
Built with care by **Binary Bros**. We believe small actions add up. CivicFix helps people take those actions.

---

## 🖼️ Screenshots
_Add screenshots in the `/docs` folder and link them here._

---

## 🤝 Contributing
Pull requests are welcome. Open an issue to discuss changes.

---

## 📜 License
MIT License. See `LICENSE` for details.
