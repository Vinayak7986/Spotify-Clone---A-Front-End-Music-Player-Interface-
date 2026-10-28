<div align="center">

# 🎵 Spotify Web Player Clone
### *Pixel-Perfect, Highly Responsive Web Player Interface Built with Modern HTML5, Advanced CSS3 & Vanilla JavaScript*

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://vinayak7986.github.io/Spotify-Clone---A-Front-End-Music-Player-Interface-/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3_Flexbox_%26_Grid-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

</div>

---

## 📌 Overview
An interactive front-end web application that faithfully replicates the user experience, typography, dark mode aesthetics, and playback controls of the official **Spotify Web Player**. Built completely from the ground up without heavy external UI frameworks, this project demonstrates mastery of modern **CSS Flexbox**, **CSS Grid**, responsive media queries, and audio-player component architecture.

---

## ✨ Key Architectural Features

- **Iconic Spotify Dark UI:** Faithfully styled using Spotify's signature brand design system (dark background `#121212`, card background `#232323`, and electric green accents `#1ed760`).
- **Tri-Pane Layout Architecture:**
  1. **Navigation Sidebar:** Persistent navigation containing Home, Search, Your Library, Playlist creation cards, and podcast discoverability.
  2. **Main Content View:** Scrollable music showcase featuring curated card albums ("Recently Played", "Trending Now", "Featured Charts") with hover elevation effects and zoom animations.
  3. **Sticky Bottom Playback Bar:** Persistent music control dock containing Album Art thumbnail, Song Title/Artist, Play/Pause toggle, Skip controls, Track Progress Bar, and Volume Slider.
- **Pure CSS Component Design:** Engineered using advanced CSS variables, custom range sliders (`<input type="range">`), overflow clipping, and smooth transition states.
- **Responsive Viewport Adaptability:** Layout dynamically collapses sidebar navigation into compact icon bars on smaller viewports and reflows album grids across mobile breakpoints.

---

## 🏗️ UI Layout Architecture

```
┌────────────────────────────────────────────────────────────────────────┐
│                        TOP NAVIGATION BAR                              │
│   [<] [>] Navigation | [Explore Premium] [Install App] [User Avatar]   │
├───────────────────┬────────────────────────────────────────────────────┤
│   SIDEBAR NAV     │              MAIN SCROLLABLE DISPLAY               │
│ • Home            │  🔥 Recently Played                                │
│ • Search          │  [Album 1] [Album 2] [Album 3] [Album 4]           │
│ ───────────────── │                                                    │
│ 📚 Your Library   │  📈 Trending near you                              │
│ • Create Playlist │  [Album 5] [Album 6] [Album 7] [Album 8]           │
│ • Browse Podcasts │                                                    │
├───────────────────┴────────────────────────────────────────────────────┤
│                       FIXED BOTTOM MUSIC PLAYER                        │
│ [Art + Track Info] ── [⏮ ⏸ ⏭ Progress Slider 03:45] ── [🔊 Volume Slider] │
└────────────────────────────────────────────────────────────────────────┘
```

---

## 📁 Repository Structure

```
Spotify-Clone/
├── index.html                   # Root deployment entry point (GitHub Pages redirect)
├── cssproject/
│   ├── index.html               # Main semantic HTML5 markup & structural skeleton
│   ├── style.css                # Pure CSS3 styling (Flexbox, Grid, Custom Sliders)
│   ├── logo.png                 # Spotify brand vector asset
│   ├── library_icon.png         # Music library iconography
│   ├── card1img.jpeg to card6.  # Curated album art thumbnails & high-res posters
│   ├── player_icon1 to 5.png    # Playback controllers (shuffle, prev, play, next, loop)
│   └── backward_icon.png        # History navigation controls
└── README.md                    # Project documentation & engineering specs
```

---

## 🎨 Design Tokens & Specifications

| Element | Specification | Hex / Value |
| :--- | :--- | :--- |
| **Primary Canvas** | Deep Dark Background | `#000000` |
| **Card Container** | Elevated Container Surface | `#121212` / `#232323` |
| **Brand Accent** | Spotify Vibrant Green | `#1ed760` |
| **Text Primary** | High-Contrast Headings | `#ffffff` |
| **Text Secondary** | Muted Subtitles & Artists | `#b3b3b3` |
| **Typography** | Font Family | `Montserrat, sans-serif` |
| **Border Radius** | Cards & Action Buttons | `0.75rem` / `100px` (Pills) |

---

## 🚀 Getting Started & Local Setup

### Prerequisites
- Any modern web browser (Google Chrome, Firefox, Safari, Edge)
- Optional: VS Code with the **Live Server** extension

---

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Vinayak7986/Spotify-Clone---A-Front-End-Music-Player-Interface-.git
   cd Spotify-Clone---A-Front-End-Music-Player-Interface-
   ```

2. **Open the project:**
   - **Method A (Direct Browser Execution):**  
     Double-click `cssproject/index.html` to open it in your default browser.
   - **Method B (VS Code Live Server):**  
     Open the folder in VS Code, right-click `cssproject/index.html`, and choose **"Open with Live Server"**.

---

## 🌐 Live Demonstration
Interact with the live application on **GitHub Pages**:  
👉 **[https://vinayak7986.github.io/Spotify-Clone---A-Front-End-Music-Player-Interface-/](https://vinayak7986.github.io/Spotify-Clone---A-Front-End-Music-Player-Interface-/)**

---

## 👨‍💻 Author
**Vinayak More**  
Software Engineer & Full-Stack Developer  
- **GitHub:** [@Vinayak7986](https://github.com/Vinayak7986)  
- **LinkedIn:** [vinayak-more-b37309264](https://www.linkedin.com/in/vinayak-more-b37309264/)  
- **Portfolio:** [vinayakmore.netlify.app](https://vinayakmore.netlify.app/)  

---

## 🛡️ License
This project is open-source and licensed under the MIT License.