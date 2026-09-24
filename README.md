<div align="center">

  # 🚖 Rapido Landing Page Clone

  <p align="center">
    <strong>A pixel-perfect, modern, and fully responsive landing page replica of India's #1 ride-hailing platform — Rapido.</strong>
  </p>

  <p align="center">
    <a href="https://github.com/Shabber10/Frontend-html-css-Rapido-/stargazers"><img src="https://img.shields.io/github/stars/Shabber10/Frontend-html-css-Rapido-?color=f9c935&logo=github&style=for-the-badge" alt="Stars" /></a>
    <a href="https://github.com/Shabber10/Frontend-html-css-Rapido-/network/members"><img src="https://img.shields.io/github/forks/Shabber10/Frontend-html-css-Rapido-?color=f9c935&logo=github&style=for-the-badge" alt="Forks" /></a>
    <a href="https://app.netlify.com/start/deploy?repository=https://github.com/Shabber10/Frontend-html-css-Rapido-"><img src="https://img.shields.io/badge/Netlify-Ready-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Netlify" /></a>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  </p>

  <br />

  <p align="center">
    <a href="https://app.netlify.com/start/deploy?repository=https://github.com/Shabber10/Frontend-html-css-Rapido-">
      <img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" height="42" />
    </a>
  </p>

</div>

---

## 📌 Table of Contents

- [✨ Overview](#-overview)
- [🖼️ Preview & Showcase](#️-preview--showcase)
- [🚀 Key Features](#-key-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [⚡ How to Deploy on Netlify](#-how-to-deploy-on-netlify)
  - [Method 1: Connect GitHub Repository (Recommended)](#method-1-connect-github-repository-recommended)
  - [Method 2: One-Click Deploy Button](#method-2-one-click-deploy-button)
  - [Method 3: Netlify Drop (Instant Drag & Drop)](#method-3-netlify-drop-instant-drag--drop)
- [🌐 Netlify Configuration Explained](#-netlify-configuration-explained)
- [💻 Run Locally](#-run-locally)
- [🎨 Design Highlights](#-design-highlights)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Overview

This project is a clean, semantic, and responsive recreation of the **Rapido** landing page. It showcases pure **HTML5** and **CSS3** capabilities without heavy framework dependencies, focusing on layout accuracy, crisp typography, intuitive booking interactions, and brand aesthetic (distinctive yellow `#F9C935` & dark contrast).

---

## 🖼️ Preview & Showcase

<div align="center">
  <img src="images/banner_image_new.png" alt="Rapido Banner Preview" width="85%" style="border-radius: 12px; box-shadow: 0 8px 30px rgba(0,0,0,0.12);" />
  <p><em>Hero section with ride-hailing visual and instant booking form widget</em></p>
</div>

---

## 🚀 Key Features

- 🎯 **Hero Section & Booking Widget**: Eye-catching headline with an interactive pickup & drop location form.
- 🛵 **Services Grid**: Showcases Rapido's fleet including Bike-Taxi, Auto, Cab, Parcel delivery, Travel & Stay, and Metro Ticket bookings.
- 💡 **Value Proposition ("What we offer")**: Highlights quick pickups, best everyday fares, and nationwide city coverage.
- 👨‍✈️ **Captain Onboarding ("Earn with Rapido")**: Driver recruitment section encouraging users to become Rapido Captains.
- 📱 **App Download Section**: High-contrast call-to-actions promoting both Customer and Captain mobile applications.
- 🧭 **Comprehensive Footer**: Quick links, legal & safety policies, app store badges, and interactive social icons.
- 📱 **Mobile & Desktop Responsive**: Fluid flexbox and grid layouts adaptable to all screen sizes.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic web page structure and accessible markups |
| **CSS3** | Modern styling, CSS Grid, Flexbox, custom transitions & hover effects |
| **Google Fonts** | `Poppins` font family for modern, clean typography |
| **Netlify** | Global Edge CDN hosting, atomic deploys, and automated SSL/HTTPS |

---

## 📁 Project Structure

```bash
Frontend-html-css-Rapido-/
├── images/                   # Vector SVGs, icons, and promotional PNG assets
│   ├── app_store.svg
│   ├── auto_service.png
│   ├── banner_image_new.png
│   ├── bestfare_offer.png
│   ├── bike_service.png
│   ├── cab_service.png
│   ├── image.png
│   ├── metro_service.png
│   ├── nevertofar_offer.png
│   ├── parcel_service.png
│   ├── play_store.svg
│   ├── serviceimage.svg
│   ├── showcase_image.png
│   └── travel_service.png
├── index.html                # Main semantic HTML markup
├── style.css                 # Global stylesheet and responsive design rules
├── netlify.toml              # Netlify deployment configuration
├── render.yaml               # Alternative Render blueprint configuration
└── README.md                 # Project documentation
```

---

## ⚡ How to Deploy on Netlify

### Method 1: Connect GitHub Repository (Recommended)

This method connects your GitHub repository so that **every time you push new code, Netlify automatically redeploys your site**!

1. Go to **[app.netlify.com](https://app.netlify.com/)** and log in (or sign up) with your **GitHub** account.
2. Click **"Add new site"** (top right) ➔ select **"Import an existing project"**.
3. Choose **GitHub** as your Git provider.
4. Select your repository: **`Shabber10/Frontend-html-css-Rapido-`**.
5. Netlify will automatically detect the settings from [`netlify.toml`](./netlify.toml):
   - **Branch**: `main`
   - **Build command**: *(leave empty)*
   - **Publish directory**: `.`
6. Click **"Deploy Frontend-html-css-Rapido-"**.
7. In ~15 seconds, Netlify will generate your live URL (e.g., `https://your-app-name.netlify.app`).

> [!TIP]
> You can change your site name to something custom like `rapido-clone.netlify.app` anytime in **Site configuration > Change site name**!

---

### Method 2: One-Click Deploy Button

Deploy directly to your Netlify account in one step:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Shabber10/Frontend-html-css-Rapido-)

---

### Method 3: Netlify Drop (Instant Drag & Drop)

If you want a live link immediately without setting up GitHub permissions:

1. Open **[app.netlify.com/drop](https://app.netlify.com/drop)** in your browser.
2. Drag and drop the `rapido` project folder directly into the box.
3. Your site is deployed immediately with a live preview link.

---

## 🌐 Netlify Configuration Explained

This project includes a pre-configured [`netlify.toml`](./netlify.toml) file:

```toml
[build]
  publish = "."
```

- **`publish = "."`**: Informs Netlify's build bot that `index.html` and static assets reside directly in the root directory, ensuring zero build errors and ultra-fast deployment.

---

## 💻 Run Locally

You can run this project locally without any package managers or dependencies:

### Option A: Open directly in Browser
Simply double-click [`index.html`](./index.html) or right-click and choose **Open with > Chrome / Firefox / Edge**.

### Option B: Using VS Code Live Server
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click [`index.html`](./index.html) and select **"Open with Live Server"**.

### Option C: Using Python
```bash
# Python 3
python -m http.server 8000
```
Open `http://localhost:8000` in your browser.

---

## 🎨 Design Highlights

- **Rapido Signature Yellow**: `#F9C935` / `#FFC107` accents for primary brand recognition.
- **Micro-Interactions**: Smooth hover elevations on cards, interactive buttons, and navigation transitions.
- **Card-Based UI**: Clean modular cards with rounded corners and subtle shadows for readable visual hierarchy.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. Feel free to use this template for learning and personal projects!

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/Shabber10">Shabber Hussain</a></sub>
</div>
