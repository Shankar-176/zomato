# 🍽️ Zomato Clone — React + MUI + SCSS

A responsive, front-end **Zomato-style restaurant discovery UI** built with **React 18**, **Material UI (MUI)**, and **SCSS**.  
This project recreates core Zomato experiences such as curated collections, delivery options, city listings, FAQs (accordion), and a polished landing page flow.

> ⚠️ This is a **frontend-only demo**. All data is static (see `src/data.js`). No backend or real APIs are integrated.

---

## ✨ Features

- ⚛️ **React 18** (Create React App) with functional components
- 🎨 **Material UI 5** for accessible UI components & icons
- 💅 **SCSS modules** for maintainable styling
- 📱 **Responsive layouts** with grid-based sections
- 🧩 Modular components (Header, Collections, Delivery, Cities, CTA, Footer, Accordion, Cards, etc.)
- 🧪 CRA test tooling (`react-scripts test`)

---

## 🗂️ Project Structure

```
Zomato-main/
├── README.md              # Project documentation (this file)
└── zomato/
    ├── package.json       # CRA dependencies & scripts
    ├── public/            # Static assets & CRA index.html
    │   ├── favicon.ico
    │   ├── index.html
    │   ├── logo192.png
    │   ├── logo512.png
    │   └── manifest.json
    └── src/
        ├── App.js         # App root composition
        ├── index.js       # React root bootstrap
        ├── app.scss       # Global styles
        ├── data.js        # Mock data (cuisines, chains, etc.)
        ├── assets/        # Images & logos
        └── components/    # Modular UI components
            ├── Header/
            ├── Footer/
            ├── Collections/
            ├── Delivery/
            ├── Cities/
            ├── CTA/
            ├── Card/
            ├── Accordian/
            └── AccContainer/
```

---

## 🛠️ Tech Stack

- **Frontend:** React 18, CRA (`react-scripts`)
- **UI Library:** Material UI 5 (`@mui/material`, `@mui/icons-material`)
- **Styling:** SCSS (`sass`)
- **State & Data:** Local mock data (`data.js`)
- **Tooling:** Web Vitals, CRA testing libraries

---

## 🚀 Getting Started

### 1️⃣ Prerequisites
- Node.js **>= 16** (LTS recommended)
- npm **>= 8** or yarn

### 2️⃣ Install
```bash
cd zomato
npm install
# or
yarn install
```

### 3️⃣ Run (Development)
```bash
npm start
# CRA dev server on http://localhost:3000
```

### 4️⃣ Build (Production)
```bash
npm run build
# Optimized production build in /build
```

---

## 📦 Scripts

- `npm start` — Start dev server with hot reload
- `npm run build` — Build production-ready static files
- `npm test` — Run tests
- `npm run eject` — Eject CRA (⚠️ irreversible)

---

## 🔧 Configuration

- No API keys or `.env` required (mock data only).
- To add real APIs later, create `.env` in `zomato/` and prefix vars with `REACT_APP_`.

---

## 🧱 Component Highlights

- **Header** — Navigation, hamburger menu, login/signup
- **Collections** — Curated restaurant/food categories
- **Delivery** — Food delivery categories
- **Cities** — Popular city links
- **Accordion (FAQ)** — Expandable info panels
- **Cards** — Reusable content cards
- **CTA** — Call-to-action section
- **Footer** — Social links & download buttons

---

## 🧭 Roadmap (Future Enhancements)

- 🔗 Connect with live Zomato / third-party APIs
- 🛒 Add search & filter state management
- 📱 Enhance mobile-first UI/UX
- ⚡ Implement lazy loading & code splitting
- ✅ Add unit & integration tests

---

## 🤝 Contributing

1. Fork the repo  
2. Create a feature branch: `git checkout -b feat/awesome`  
3. Commit changes: `git commit -m "feat: add awesome thing"`  
4. Push: `git push origin feat/awesome`  
5. Open a Pull Request  

Follow [Conventional Commits](https://www.conventionalcommits.org/) for clarity.

---

## 📄 License

This project is provided **as-is** for educational/demo purposes.  
Add a LICENSE file if you plan to distribute under an open-source license.

---

💡 *Built with React, SCSS, and Material UI as a frontend clone project.*
