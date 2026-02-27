# 🚀 Riyas K - Personal Portfolio

A sleek, responsive, and performant personal portfolio website for Riyas K, built with pure Vanilla HTML, CSS, and JavaScript. 

## 🌟 Overview

This portfolio is designed to showcase skills, experience, projects, and educational background in a clean, professional manner. The architecture utilizes a modern **"Bento Box" grid layout**, where content is organized into highly legible and structured blocks.

The aesthetic leans into a minimalist, **light-mode glassmorphism** theme, utilizing a strict 4-color accent palette (Teal, Pink, Orange, Yellow) overlaid onto a solid light canvas. To prioritize content delivery, speed, and formal professionalism, the site relies on a **static rendering approach**, intentionally omitting complex scroll-reveals or heavy 3D hover animations.

## 🛠️ Technology Stack

- **HTML5**: Handles the scalable document architecture and semantic tags.
- **CSS3 Layout**: Employs CSS Grid for the foundational 3-column Bento Box structure and Flexbox for precise alignment.
- **CSS3 Theming**: Utilizes extensive CSS Variables (`:root`) to tightly manage color palettes, typography, and border properties globally.
- **Vanilla JavaScript**: Lightweight DOM manipulation tailored exclusively for essential UX elements (e.g., sticky navigation morphing on scroll).
- **Lucide Icons**: Integrated via CDN to provide crisp, scalable SVG iconography.
- **Google Fonts**: Uses "Inter" for highly legible, modern sans-serif typography.

## 🎨 Design System

**Base Palette:**
- Background Canvas: **`#ECECEC`** (Light Gray Canvas)
- Primary Text: **`#121212`** (Sharp Dark Charcoal)
- Secondary Text: **`#5a5a5a`** (Medium Gray)
- Card Containers: Formatted as frosted glass cards (`rgba(255,255,255, 0.4)`) with subtle `.08` opacity dark borders.

**Accent Colors (4-Stripe System):**
- Teal: **`#9b4b4b`** 
- Pink: **`#f06a7c`** 
- Orange: **`#fc9e60`** 
- Yellow: **`#ffe259`** 

**Buttons & Actions:**
The primary "Download Resume" calls-to-action utilize a stark, formal **Deep Charcoal (`#121212`)** fill that eleganty slides into a semi-transparent white wash upon user interaction, yielding a highly professional tactile response.

## 📐 Structural Layout

The application is encapsulated within a `<main class="container">` wrapping elements. The key sections are mapped via anchor IDs:

1. **`#home` (Hero Section):** 
   - Welcomes the user with a gradient text headline.
   - Houses the profile picture block.
   - Offers quick-action glass buttons linking to directly email, clip the phone number, or visit LinkedIn. 
   - Holds quick links to verifiable Certificates.

2. **`#experience-projects`:**
   - Features a vertical timeline element highlighting critical intern positions (e.g., Google AI/ML).
   - Showcases the featured "SAP Sales & Inventory Management System" project alongside technical dependency tags (AWS, SAP ERP, ABAP, SQL, SAP HANA).
   - Educational Background and Leadership (NCC) accomplishments.

3. **`#skills`:**
   - A wide layout cleanly slicing technical ability into "Core Skills" (Java, C, JS), "Tools & Platforms" (AWS, GitHub, SAP), and theoretical "Core Fundamentals" (OOP, Networks, DBMS).

4. **`#contact` (Footer):**
   - A concluding sticky block delivering the final resume download call-to-action and direct contact metadata.

## 🚀 Quick Start / Local Development

Since this project avoids heavy frontend frameworks (like React, Vue, or Next.js) and build tools (like Webpack or Vite), launching it locally is extremely straightforward with zero installation required.

1. Clone or download the repository to your local machine.
2. Locate the project folder (`porti`).
3. Simply double-click on **`index.html`** to open it directly into any modern web browser (Google Chrome, Firefox, Safari, Edge).
4. For hot-reloading capability during active development, you may use extensions such as **Live Server** on VS Code.

## 📁 File Structure

```text
porti/
│
├── index.html       # The central page structure and content
├── style.css        # All global styles, bento layouts, and strict light themes
├── script.js        # Minimal logic for navbar scrolling and icon rendering
├── resume.pdf       # Downloadable target for user interaction (Add file here)
├── profile.png      # User avatar image file (Add file here)
├── certificates/    # Directory holding verifiable achievement PDF files
│   ├── oci.pdf
│   ├── aiml.pdf
│   └── java.pdf
└── README.md        # This project documentation file
```

---
*Developed by Riyas K for professional distribution.*
