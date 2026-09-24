<div align="center">

  # 🚖 Rapido Landing Page Clone

  <p align="center">
    <strong>A pixel-perfect, modern, and fully responsive landing page replica of India's #1 ride-hailing platform — Rapido.</strong>
  </p>

  <p align="center">
    <a href="https://github.com/Shabber10/Frontend-html-css-Rapido-/stargazers"><img src="https://img.shields.io/github/stars/Shabber10/Frontend-html-css-Rapido-?color=f9c935&logo=github&style=for-the-badge" alt="Stars" /></a>
    <a href="https://github.com/Shabber10/Frontend-html-css-Rapido-/network/members"><img src="https://img.shields.io/github/forks/Shabber10/Frontend-html-css-Rapido-?color=f9c935&logo=github&style=for-the-badge" alt="Forks" /></a>
    <a href="https://render.com"><img src="https://img.shields.io/badge/Render-Deployed-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render" /></a>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  </p>

  <br />

  <a href="#-how-to-deploy-on-render">
    <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render" height="38" />
  </a>

</div>

---

## 📌 Table of Contents

- [✨ Overview](#-overview)
- [🚀 Key Features](#-key-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🌐 How to Deploy on Render](#-how-to-deploy-on-render)
  - [Method 1: Manual Static Site (Recommended)](#method-1-manual-static-site-recommended)
  - [Method 2: Blueprint Deployment (render.yaml)](#method-2-blueprint-deployment-renderyaml)
- [💻 Run Locally](#-run-locally)
- [🎨 Design Highlights](#-design-highlights)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Overview

This project is a clean, semantic, and responsive recreation of the **Rapido** landing page. It showcases pure **HTML5** and **CSS3** capabilities without heavy framework dependencies, focusing on layout accuracy, crisp typography, intuitive booking interactions, and brand aesthetic (distinctive yellow & dark contrast).

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
| **Google Fonts** | `Poppins` typography for clean modern readability |
| **Render** | Fast, free cloud hosting for static websites |

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
├── render.yaml               # Render Infrastructure-as-Code configuration
└── README.md                 # Project documentation
```

---

## 🌐 How to Deploy on Render

Deploying this static site on **[Render](https://render.com)** takes under 2 minutes.

### Method 1: Manual Static Site (Recommended)

1. **Sign in to Render**:
   - Go to [dashboard.render.com](https://dashboard.render.com/) (Sign in with your GitHub account).

2. **Create New Static Site**:
   - Click the **"New +"** button in the top navigation bar.
   - Select **"Static Site"**.

3. **Connect Repository**:
   - Select `Shabber10/Frontend-html-css-Rapido-` from your repository list.
   - *(If not visible, click "Configure GitHub App" to grant access to the repo).*

4. **Configure Settings**:
   Fill in the configuration fields:
   - **Name**: `rapido-frontend` *(or any preferred name)*
   - **Branch**: `main`
   - **Build Command**: *(Leave completely blank or empty)*
   - **Publish Directory**: `.` *(a single dot representing the root directory)*

5. **Deploy**:
   - Click **"Create Static Site"**.
   - Render will instantly deploy your site and provide a free live URL (e.g. `https://rapido-frontend.onrender.com`).

---

### Method 2: Blueprint Deployment (render.yaml)

Since this repository already includes a [`render.yaml`](./render.yaml) file:

1. Go to your [Render Dashboard](https://dashboard.render.com/).
2. Click **"New +"** > **"Blueprint"**.
3. Connect `Shabber10/Frontend-html-css-Rapido-`.
4. Render will automatically detect `render.yaml` and configure the static site with zero manual inputs!
5. Click **"Apply"** to deploy.

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
