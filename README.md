# 🚀 3D Developer Portfolio - Madala Spoorthi

A high-performance, ultra-responsive 3D developer portfolio built with **React**, **Three.js**, **Tailwind CSS 4**, and **motion/react**. This portfolio features a dynamic 3D workspace, interactive animations, and a fully functional contact system using **Brevo**.


---

## ✨ Features

- **Extreme Responsiveness**: Perfectly optimized for all devices, from small mobile screens to iPad Pro (1024px) side-by-side layouts.
- **3D Interactive Scene**: A stunning 3D desk environment powered by **React Three Fiber** and **Drei**.
- **Dynamic HUD**: Futuristic terminal-style HUD elements that adapt to your screen size.
- **Smooth Animations**: High-performance scroll tracking and entrance effects using **motion/react**.
- **Brevo Email Integration**: A working contact form that sends messages directly to your inbox via the Brevo API.
- **Modern UI**: Built with the latest **Tailwind CSS 4** for lightning-fast styling.

---

## 🛠 Tech Stack

| Tech              | Description                           |
|-------------------|---------------------------------------|
| **React 19**      | Modern UI development                 |
| **Vite**          | High-speed build tool and dev server  |
| **Tailwind CSS 4**| Latest utility-first CSS framework    |
| **Three.js**      | 3D rendering engine                   |
| **Motion/React**  | Next-gen animation library            |
| **Brevo API**     | Transactional email service           |

---

## 🚀 Getting Started

### 1. Installation
```bash
git clone https://github.com/spoorthimadala/portfolio.git
cd portfolio
npm install
```

### 2. Environment Setup
Create a `.env` file in the root directory and add your Brevo credentials (see `.env.example` for reference):

```env
VITE_BREVO_API_KEY=your_key_here
VITE_BREVO_SENDER_EMAIL=your_verified_sender@email.com
VITE_BREVO_TO_EMAIL=your_personal@email.com
```

### 3. Development
```bash
npm run dev
```
The app will be available at `http://localhost:5173`.

---

## 📁 Project Structure

```bash
├── public/
│   ├── assets/             # Images, textures, and UI assets
│   ├── models/             # 3D models (Tech Desk, Orbitals)
├── src/
│   ├── components/         # Interactive UI components (HeroText, Timeline, etc.)
│   ├── constants/          # Site content and data
│   ├── sections/           # Major page sections (Hero, About, Projects, etc.)
│   ├── App.jsx             # Root component
│   └── index.css           # Global styles and Tailwind imports
├── .env.example            # Environment variable template
└── vite.config.js          # Vite configuration
```

---

## 📬 Contact

If you have any questions or just want to connect, feel free to reach out through the contact form on the site!

---

## ⭐ Acknowledgments

This project was built and refined with a focus on cutting-edge responsiveness and modern 3D web design. 

