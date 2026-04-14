# 🧘‍♂️ ZenFlow - Yoga Booking System

ZenFlow is a lightweight, modern web application designed to help yoga studios manage session bookings with a clean, user-friendly interface. It emphasizes a "Zen" aesthetic using soft color palettes and modern CSS techniques like Glassmorphism.

---

## 📖 Table of Contents
* [Features](#-features)
* [Tech Stack](#-tech-stack)
* [Installation](#-installation)
* [Color Palette](#-color-palette)
* [How It Works](#-how-it-works)

---

## ✨ Features

* **Responsive Dashboard:** A clear grid of available yoga slots that adapts to mobile, tablet, and desktop.
* **Instant Booking Modal:** A seamless popup booking form that doesn't require page refreshing.
* **Modern Login UI:** A dedicated, attractive login page designed to welcome practitioners back.
* **Fast Performance:** Built with pure HTML/CSS for lightning-fast load times.
* **Yoga-Themed Design:** Uses calming "Sage Green" and "Warm Sand" tones.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic structure for accessibility.
* **CSS3:** Flexbox and Grid for layout, plus CSS Variables for easy branding updates.
* **Google Fonts:** Utilizes the 'Poppins' font for a clean, modern feel.

---

## 🚀 Installation

Since this is a front-end project, no complex setup is required:

1.  **Download** the repository files.
2.  Ensure `index.html`, `login.html`, and your CSS files are in the same folder.
3.  **Open** `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

---

## 🎨 Color Palette

We use the following CSS variables defined in the `:root`:

| Variable | Hex Code | Purpose |
| :--- | :--- | :--- |
| `--primary` | `#76a193` | Primary buttons and Sage accents |
| `--accent` | `#d4a373` | Warm highlights and links |
| `--dark` | `#2d3436` | Main typography for readability |
| `--light` | `#f8f9fa` | Clean background sections |

---

## 💡 How It Works

This project uses the **CSS `:target` selector** to handle UI states without needing complex JavaScript:
* **Booking Form:** Triggered via `#booking-form` ID in the URL.
* **Responsive Grid:** Automatically re-aligns cards using `grid-template-columns: repeat(auto-fit, ...)`.

---

## 📝 License
This project is open-source and available under the **MIT License**.
