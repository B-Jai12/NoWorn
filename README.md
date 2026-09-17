<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,25,30&height=220&section=header&text=Noworn&fontSize=80&fontAlignY=38&desc=Customer-Driven%20Apparel%20%7C%20Design%20Freedom%20%7C%20Physical%20Expression&descAlignY=60&animation=fadeIn&fontColor=ffffff" width="100%"/>

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Formspree](https://img.shields.io/badge/Waitlist-Formspree-FF5A5F?style=for-the-badge&logo=mailgun&logoColor=white)](https://formspree.io)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

<br/>

> **Don't wear someone else's idea. Create and wear your own.**  
> Noworn is a customer-driven clothing platform transforming how apparel is conceived, personalized, and made.

<br/>

**[✨ Business Vision](#-about-noworn) &nbsp;•&nbsp; [🔄 Why Noworn is Different](#-why-noworn-is-different) &nbsp;•&nbsp; [🎨 The Customer Experience](#-the-customer-experience) &nbsp;•&nbsp; [💻 Technical Architecture](#-technical-architecture) &nbsp;•&nbsp; [🚀 Quick Start](#-local-development)**

<br/>

</div>

---

# Part I: Business Concept & Vision

## 👕 About Noworn

**Noworn is not another online clothing store.** 

Most fashion websites treat customers as passive consumers: a brand designs a seasonal line, manufactures thousands of identical units, stocks them in warehouses, and presents customers with a catalog of predetermined options. If none of those designs fully resonate with your personal identity or artistic taste, you compromise.

**Noworn reverses this dynamic.**

Inspired by the visual freedom, boundless inspiration, and creative empowerment of tools like **Pinterest** and **Canva**, Noworn is building an intuitive canvas tailored exclusively for clothing. We believe your wardrobe should reflect your mind, your stories, and your personal aesthetic — not the seasonal guesswork of a fashion brand.

With Noworn:
- **You are the designer:** You start with a digital canvas rather than a locked catalog.
- **You explore and curate:** Blend typography, graphics, textures, and bespoke visual concepts.
- **We handle the physical craft:** What you imagine and preview in digital space is produced as a high-quality physical garment and delivered to your doorstep.

---

## ⚡ Why Noworn is Different

| Traditional Apparel Model | The Noworn Model |
|---|---|
| **Brand Decides:** Designers define colors, graphics, and styles months in advance. | **Customer Imagines:** You explore ideas and express your own creative vision. |
| **Mass Production:** Fixed batches manufactured with high inventory risk and waste. | **Customer Customizes:** You tune placement, scales, fonts, and garment details. |
| **Passive Choice:** Customer selects from what is left on the rack or in stock. | **On-Demand Production:** Noworn manufactures your specific design into physical reality. |
| **Wearing the Brand:** You walk around as an advertisement for someone else's label. | **Wearing Your Creation:** You wear an authentic extension of your personal style. |

```
Traditional:  Brand Decides  ──►  Manufactures Collection  ──►  Customer Picks Leftovers
Noworn:       Customer Creates ──► Customer Customizes ──► Noworn Produces ──► Customer Wears
```

---

## 🔄 The Customer Experience

Noworn guides users through a seamless 6-step creative journey:

```
┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│ 01. Discover │───►│  02. Create  │───►│ 03. Customize│
└──────────────┘    └──────────────┘    └──────────────┘
                                                │
┌──────────────┐    ┌──────────────┐            │
│   06. Wear   │◄───│ 05. Produce  │◄───┌───────┴──────┐
└──────────────┘    └──────────────┘    │ 04. Preview  │
                                        └──────────────┘
```

1. **`01 — Discover`**: Explore curated aesthetic feeds, moodboards, and artistic motifs to spark inspiration.
2. **`02 — Create`**: Open a distraction-free blank canvas with full freedom to compose typography, vector art, and layouts.
3. **`03 — Customize`**: Adjust garment cuts, fabric weights, color palettes, print placements, and embroidery accents.
4. **`04 — Preview`**: Examine your piece with high-fidelity, interactive 3D perspective and real-time visual tilt.
5. **`05 — Produce`**: Seamless transition from digital pixels to physical textile production and precise on-demand manufacturing.
6. **`06 — Wear`**: Unbox and wear a garment that exists nowhere else in the world — designed by you.

---

# Part II: Website Implementation & Technical Setup

## 🖥️ Repository Implementation

The current repository represents the public **Launch & Waitlist Platform** for Noworn, built with performance, smooth micro-interactions, and zero framework overhead.

### Implemented Features
- **3D Perspective Parallax Tilt:** Dynamic hero showcase (`assets/tshirt-hero.png`) reacting in real-time to cursor coordinates with mathematical 3D transform matrices.
- **Glassmorphic Cyber Dark UI:** Polished dark color scheme, responsive typography via Google Fonts (`Instrument Serif` & `Inter`), and subtle glow states.
- **Zero-Dependency Engine:** Pure HTML5, modern CSS custom properties (variables, flexbox, CSS Grid), and vanilla ES6+ JavaScript.
- **Waitlist Pipeline:** Integrated Formspree endpoint with client-side email verification and instant submission feedback states.
- **Fully Responsive:** Fluid layouts tested across ultra-wide, desktop, tablet, and mobile screens.

---

## 🛠️ Technical Architecture

```
NoWorn/
├── assets/
│   └── tshirt-hero.png       # High-resolution hero asset for 3D tilt
├── index.html                # Semantic HTML5 layout and accessibility hooks
├── README.md                 # Project and business documentation
└── .gitignore                # Git exclusions
```

### Technology Breakdown
- **Markup:** Semantic HTML5 (`header`, `main`, `section`, `footer`)
- **Styles:** Vanilla CSS3 (Custom properties, 3D transform perspective, CSS Grid)
- **Logic:** Vanilla JavaScript (ES6+ MouseEvent listeners, DOM manipulation)
- **Email Pipeline:** Formspree API integration
- **Typography:** Google Fonts (`Instrument Serif` for editorial luxury, `Inter` for technical clarity)

---

## 🚀 Local Development

Because Noworn is built entirely with vanilla web standards, there are **no dependencies to install** and **no build steps required**.

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/B-Jai12/NoWorn.git
   cd NoWorn
   ```

2. **Open directly in your browser:**
   - **Option A (Instant):** Double-click `index.html` or open it with your browser:
     ```bash
     # Windows PowerShell
     Start-Process index.html
     ```
   - **Option B (Local Live Server):** Run any local HTTP server:
     ```bash
     # Using Python
     python -m http.server 3000

     # Or using Node's npx serve
     npx serve .
     ```
   Visit `http://localhost:3000` to interact with the experience.

---

## 👤 Author & Concept Creator

**Jaideep Botla** ([@B-Jai12](https://github.com/B-Jai12))  
B.Tech AIML Student & Product Builder • Innovating at the intersection of digital design, software, and physical consumer products.