# ❤️ Valentine Website for Tracy

A fully custom, mobile‑optimized Valentine’s website built with love for **Tracy**.  
This project includes interactive features, animations, a gallery, a story timeline, a map showing the distance between us, and a custom password lock (for fun, not security).  
The entire experience is themed in a romantic **wine-red palette**.

This site was created as a personal Valentine’s gift by **Mthokozisi**.

***

## 🌟 Features

### 🔐 Password-Protected Entry

A fun lock screen where she must enter an inside-joke passphrase before accessing the site.

### ❤️ Valentine Ask

A playful “Will you be my Valentine?” section with:

*   A **Yes** button (confetti celebration + love letter reveal)
*   A **No** button that dodges away

### 📸 Photo Gallery

A responsive photo grid with:

*   Hover captions
*   Lightbox viewer
*   Mobile-friendly layout
*   Smooth zoom animations

### 🕰️ Countdown Timer

Live countdown until our next meet‑up date, with:

*   Days
*   Hours
*   Minutes
*   Seconds

### 🗺️ Distance Map (Cape Town ↔ Siteki)

Interactive Leaflet map that:

*   Shows both of our cities
*   Draws a connection line
*   Calculates distance in kilometers

### 💌 Love Letter

A handwritten-style romantic letter, displayed with soft styling and wine-red accents.

### 🎶 Music Player

Optional play/pause button for “our song”.

### 📖 Our Story Timeline

A dynamic timeline highlighting important milestones in our relationship.

### 💫 Visual Enhancements

*   Floating hearts
*   Confetti hearts
*   Back-to-top button
*   Smooth scrolling
*   Mobile-safe insets (iPhone Dynamic Island compatible)

### 🖼️ Wine-Red Theme

A custom color palette using CSS variables for easy customization.

***

## 🛠️ Technologies Used

*   **HTML5**
*   **CSS3** (custom properties, gradients, responsive design)
*   **JavaScript (Vanilla)**
*   **Leaflet.js** for the interactive map
*   **GitHub Pages** for free hosting

No external frameworks required.

***

## 📂 Project Structure

    / (root)
     ├── index.html
     ├── photos/
     │    ├── photo1.jpg
     │    ├── photo2.jpg
     │    └── ...etc
     ├── our-song.mp3  (optional)
     ├── README.md

Images go in `photos/`.  
Music file goes in root next to `index.html`.

***

## 🔧 Customization

### 1. Update Her Name

Inside the `<script>` tag:

```js
const HER_NAME = "Tracy";
```

### 2. Update the Passphrase

```js
const PASS_PHRASE = "Natalie";
```

### 3. Update the Countdown Date

```js
const MEET_UP_ISO = "2026-03-20T18:00:00+02:00";
```

### 4. Update City Coordinates

Replace with your actual locations:

```js
const CITY_A = { name: "Cape Town", lat: -33.9249, lng: 18.4241 };
const CITY_B = { name: "Siteki",    lat: -26.4517, lng: 31.9462 };
```

### 5. Change Photos

Just swap out images inside the `photos/` folder and update their filenames in the gallery section.

***

## 🚀 Deployment (Free via GitHub Pages)

1.  Go to **Settings → Pages**
2.  Source: `Deploy from branch`
3.  Branch: `main`
4.  Folder: `/ (root)`
5.  Save

Your site becomes live at:

    https://<your-username>.github.io/<your-repo>/

***

## ⚠️ Disclaimer

The password lock is **not** secure — it’s intentionally lightweight and made for fun, not for protecting sensitive information.

***

## 💖 Created With Love

This project is a personal Valentine’s gift made by **Mthokozisi**  
for **Tracy**, with love, intention, and care.
