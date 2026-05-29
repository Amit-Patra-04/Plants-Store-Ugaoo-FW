# Plantex - Premium Plant Store Website

An elegant, fully responsive, and interactive multi-section landing page for a modern plant e-commerce shop called **Plantex** (inspired by Ugaoo). This website is built using semantic HTML5, custom vanilla CSS properties, and vanilla Javascript. It features scroll-triggered reveal animations, accordion FAQs, a contact section, and a persistent dark/light theme toggle.

---

## Preview

![Plantex Preview]<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/eb44607c-ff34-4cee-ab94-47868ca33acd" />

---

## 🔗 Live View
*Experience the website live: [[Plantex Link](https://plant-store-plantex.netlify.app/)]* 

---

## ✨ Features

- **🌓 Persistent Dark/Light Mode:** Seamlessly switch between dark and light themes. User preference is saved using `localStorage` and automatically loaded on subsequent visits.
- **📱 Fully Responsive Design:** Optimised layouts for mobile, tablet, and desktop viewports using CSS grid, flexbox, and media queries.
- **✨ ScrollReveal Animations:** Elegant entrance animations for elements as you scroll down the page, providing a premium feel.
- **📂 Interactive FAQ Accordion:** Clean accordion interaction using JavaScript to toggle answers to frequently asked questions with smooth height transitions.
- **🎯 Active Section Navigation:** The header dynamically highlights the current section as the user scrolls through the page.
- **🔝 Scroll Up Feature:** A back-to-top button that appears dynamically after scrolling past a threshold, enabling users to jump back to the navigation bar.
- **🎨 Custom Design Tokens:** Built using a flexible HSL green-based color palette (`--hue: 152`) configured using CSS custom properties (variables) for fast maintenance and styling.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic markup structure (`<header>`, `<main>`, `<section>`, `<footer>`, `<article>`).
- **CSS3:** Custom variables, grid/flexbox layouts, custom keyframes, scroll-behavior, and dark mode theme variables.
- **JavaScript (ES6):** Custom accordion handler, scroll state listeners, mobile menu toggle, and local storage state synchronization.
- **Libraries & Assets:**
  - [ScrollReveal.js](https://scrollrevealjs.org/) for scroll entrance animations.
  - [Remix Icon](https://remixicon.com/) for modern vector iconography.
  - [Google Fonts](https://fonts.google.com/) - Poppins family.

---

## 📂 Project Structure

```
Plants-Store-Ugaoo-FW-/
├── Material/
│   ├── About.jpeg
│   ├── Fav.png
│   ├── Hand Cradling Plant.jpeg
│   ├── Man with Potted Plant.jpeg
│   ├── Product1.png (Peace Lily)
│   ├── Product2.png (Bamboo Palm)
│   ├── Product3.png (Peperomia Green)
│   ├── Product4.png (Golden Hahnii)
│   ├── Product5.png (ZZ Plant - XL)
│   ├── Product6.png (Aralia Golden)
│   ├── Woman Gardening in Lush Greenery.jpeg
│   ├── card1.png
│   ├── card2.png
│   ├── card3.png
│   ├── card4.png
│   ├── main.png
│   └── plnt.jpeg
├── index.html
├── main.js
├── scrollreveal.min.js
├── styles.css
└── README.md
```

---

## 📖 Sections Walkthrough

### 1. Header & Navigation
- Features the **Plantex** logo and nav links.
- Responsive mobile side menu slide-in animation.
- Sticky glassmorphic backdrop shadow when scrolling down.
- Persistent Dark/Light theme toggle button.

### 2. Home Section
- Hero showcase featuring the main plant image, social follow links (Facebook, Instagram, LinkedIn), and an call-to-action button linking directly to Ugaoo's collection.

### 3. About Section
- Informational segment listing value propositions (on-time delivery, care guides, check-up after sales, and a 100% money-back guarantee).

### 4. Steps Section
- Easy-to-follow guide to start caring for plants:
  1. **Choose Plant**
  2. **Place an order**
  3. **Get plants delivered**

### 5. Products Section
- Features a display of premium, hand-picked plants from the showroom with direct external shopping links to Ugaoo:
  - **Peace Lily Plant** (₹299)
  - **Bamboo Palm Plant** (₹399)
  - **Peperomia Green Plant** (₹249)
  - **Golden Hahnii Plant** (₹299)
  - **ZZ Plant - XL** (₹2,299)
  - **Aralia Golden Plant** (₹249)

### 6. FAQs Section
- An interactive accordion containing common queries about light requirements, self-watering pots, boosting growth, flowering issues, succulent care, and soil types.

### 7. Contact Us Section
- Quick communication details (phone support, email address) alongside a clean, interactive message form for custom queries.

### 8. Footer Section
- Newsletter subscription, highlight of current store offers (Free shipping, All India delivery, XL plants), accepted credit cards showcase, and developer credits.

---

## 🚀 Getting Started

To run the project locally:

1. Clone or download this repository.
2. Ensure you have the `Material/` directory containing all assets in the root folder.
3. Open `index.html` directly in your web browser, or use a local development server like **Live Server** (VS Code extension) or any node server to run it.

```bash
# Example if using python to run a simple server:
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## 👤 Credits

Inspired by the designs and collections of [Ugaoo](https://www.ugaoo.com/).
