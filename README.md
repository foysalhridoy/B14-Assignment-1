# Programming Hero - AI-Driven Full Stack Web Engineering Course, Assignment-1

### 🎯 DevConf 2026 — Landing Page

A fully responsive conference landing page built with **HTML5** and **CSS3**, recreating a real-world event website from a design screenshot — including a hero banner, speaker showcase, pricing plans, stats, and a "Why Attend" section.

---

## 📖 Project Overview

This project is **Assignment-1** of the *AI-Driven Full Stack Web Engineering* course at **Programming Hero**. The goal was to convert a static design (screenshot) into a clean, semantic, and fully responsive HTML/CSS landing page for a fictional developer conference — **DevConf 2026**.

The build process followed a real development workflow: starting from a base layout, comparing the live output against the design reference, and fixing mismatches (content, spacing, images, and structure) step by step — just like a beginner developer would during a hands-on practice sprint.

---

## ✨ Features

- **Responsive Navbar** with logo and navigation links
- **Hero Banner** with a full-width background image and call-to-action button
- **Speakers Section** showcasing 4 speaker cards with photo, track tag, name, and role
- **Pricing Section** with 3 tiered plans (Standard, Pro, Team) and a highlighted "Pro" plan
- **Highlights/Stats** section displaying key event numbers
- **Why Attend?** section with reason cards and a benefits checklist
- **Footer** with logo and social media links
- Fully **responsive design** — adapts smoothly across desktop, tablet, and mobile screens

---

## 🛠️ Tech Stack

| Technology       | Purpose                          |
|-------------------|-----------------------------------|
| HTML5             | Page structure & semantic markup |
| CSS3              | Styling, layout, and responsiveness |
| Font Awesome      | Icons throughout the UI          |
| CSS Grid & Flexbox | Layout system                   |
| Media Queries     | Responsive breakpoints            |

---

## 📁 Folder Structure

```
devconf-2026-landing-page/
│
├── index.html          # Main HTML file
├── style.css           # All styling and responsive rules
├── images/              # Local image assets (logo, speaker photos, etc.)
│   ├── logo.png
│   ├── andrej-karpathy.jpg
│   ├── demis-hassabis.jpg
│   ├── gary-marcus.jpg
│   └── mustafa-suleyman.jpg
└── README.md            # Project documentation
```

---

## 🧩 Sections Implemented

1. **Navbar** — Logo + navigation menu + Register button
2. **Hero Banner** — Headline, description, and CTA over a background image
3. **Speakers** — Grid of 4 speaker cards
4. **Pricing** — 3-tier pricing cards with feature lists
5. **Highlights** — Quick stats in a dark stat bar
6. **Why Attend** — Reasons + benefits card with CTA
7. **Footer** — Logo, social links, and copyright

---

## 🔧 Fixes & Improvements Made During Development

While comparing the code against the target design, the following corrections were made:

- Corrected speaker name typos and track labels to match the design
- Updated the navbar menu links to match the final design (`Speakers`, `Schedule`, `Tracks`, `Venue`, `Blog`)
- Added missing price subtext (`per person`, `up to 10 people`) under each pricing card
- Replaced inline SVG placeholder images with proper `img src` references for easy local image swapping
- Added a background image to the hero banner section
- Replaced Font Awesome logo icons with real `img` logo references in the navbar and footer
- Fine-tuned image sizing for better visual balance

---

## 🚀 How to Run Locally

1. Clone or download this repository
   ```bash
   git clone <your-repository-url>
   ```
2. Add your own images inside the `images/` folder using the exact file names referenced in `index.html`
3. Open `index.html` in your browser — no build tools or server required

---

## 📱 Responsiveness

The layout has been tested and optimized for:
- 💻 Desktop (1240px+)
- 📱 Tablet (768px – 1024px)
- 📱 Mobile (below 768px, including small phones under 480px)

---

## 👤 Author

Built as part of the **Programming Hero — AI-Driven Full Stack Web Engineering Course**, Assignment-1.

---

## 📄 License

This project is for educational purposes only, created as a course assignment.
