# ✈️ TravelBookingWebsite

<div align="center">

![Travel Booking Banner](https://img.shields.io/badge/Travel-Booking%20Website-blue?style=for-the-badge&logo=airplanemodeactive&logoColor=white)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://figma.com)

[![GitHub repo size](https://img.shields.io/github/repo-size/Sabina-Sheoran/TravelBookingWebsite?style=flat-square)](https://github.com/Sabina-Sheoran/TravelBookingWebsite)
[![GitHub last commit](https://img.shields.io/github/last-commit/Sabina-Sheoran/TravelBookingWebsite?style=flat-square)](https://github.com/Sabina-Sheoran/TravelBookingWebsite/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

**A modern, visually stunning travel booking web application designed in Figma and built with HTML, CSS, and JavaScript.**

[🌐 Live Demo](#live-demo) · [📸 Screenshots](#screenshots) · [🚀 Getting Started](#getting-started) · [🤝 Contributing](#contributing)

</div>

---

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Design](#design)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Pages Overview](#pages-overview)
- [Screenshots](#screenshots)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🌍 About the Project

**TravelBookingWebsite** is a full-featured, responsive travel booking platform that allows users to discover destinations, search for flights, hotels, and vacation packages, and complete secure bookings — all from a single, elegant interface.

The project was initially designed using **Figma** as a high-fidelity UI prototype, and is being implemented as a fully functional web application using modern frontend technologies.

### 🎯 Key Goals

- Provide a **seamless user experience** for searching and booking travel
- Deliver a **mobile-responsive** layout optimized for all screen sizes
- Showcase a **modern, clean UI** inspired by leading travel platforms
- Serve as a **portfolio project** demonstrating frontend design and development skills

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 **Destination Search** | Search and explore destinations worldwide with smart filtering |
| ✈️ **Flight Booking** | Search one-way, round-trip, or multi-city flights |
| 🏨 **Hotel Search** | Browse hotels with star ratings, amenities, and price ranges |
| 📦 **Vacation Packages** | Curated all-inclusive travel packages |
| 🗺️ **Interactive Maps** | Visual destination exploration with map integrations |
| 📅 **Date Picker** | Intuitive calendar-based check-in/check-out selection |
| 👥 **Guest Management** | Specify number of adults, children, and rooms |
| 💳 **Secure Checkout** | Step-by-step booking confirmation flow |
| 📱 **Responsive Design** | Fully optimized for mobile, tablet, and desktop |
| 🌙 **Modern UI/UX** | Premium glassmorphism and gradient design aesthetic |

---

## 🛠️ Tech Stack

### Frontend
- **HTML5** — Semantic markup and accessibility
- **CSS3** — Custom properties, Flexbox, Grid, animations
- **JavaScript (Vanilla)** — Dynamic UI interactions and API integrations

### Design
- **Figma** — Full UI/UX prototyping and design system
- **Google Fonts** — Premium typography (Inter, Outfit)
- **Font Awesome / Heroicons** — Icon library

### Tools & Workflow
- **Git & GitHub** — Version control and collaboration
- **VS Code** — Development environment
- **Chrome DevTools** — Debugging and responsive testing

---

## 🎨 Design

The complete UI/UX design for this project was created in **Figma**, featuring:

- 🎨 **Curated color palette** — rich blues, warm accents, and clean whites
- ✏️ **Custom typography** using modern Google Fonts
- 📐 **Consistent spacing and layout grid** (8px base grid system)
- 🪟 **Glassmorphism effects** on cards and overlays
- 🌈 **Gradient backgrounds** for hero sections and CTAs
- 💡 **Micro-animations** for enhanced user engagement
- 📱 **Mobile-first responsive breakpoints**

> The Figma design file is available in the repository as `Untitled.fig`. Open it with [Figma Desktop](https://www.figma.com/downloads/) or import it at [figma.com](https://figma.com).

---

## 📁 Project Structure

```
TravelBookingWebsite/
│
├── index.html              # Homepage / Landing Page
├── flights.html            # Flight Search Page
├── hotels.html             # Hotel Search & Listing Page
├── packages.html           # Vacation Packages Page
├── destination.html        # Destination Detail Page
├── booking.html            # Booking / Checkout Page
├── confirmation.html       # Booking Confirmation Page
│
├── css/
│   ├── style.css           # Global styles and design tokens
│   ├── components.css      # Reusable UI components
│   ├── responsive.css      # Media queries and breakpoints
│   └── animations.css      # Keyframes and transition effects
│
├── js/
│   ├── main.js             # Core application logic
│   ├── search.js           # Search and filter functionality
│   ├── datepicker.js       # Calendar/date picker component
│   ├── booking.js          # Booking flow and form validation
│   └── api.js              # API integration layer
│
├── assets/
│   ├── images/             # Destination photos, icons, logos
│   │   ├── destinations/   # Destination-specific images
│   │   ├── hotels/         # Hotel preview images
│   │   └── icons/          # Custom SVG icons
│   └── fonts/              # Local font files (if any)
│
├── Untitled.fig            # Figma design source file
├── Untitled.pdf            # Exported design PDF / prototype
│
└── README.md               # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

All you need is a modern web browser and optionally a local server:

- **Browser**: Chrome, Firefox, Safari, or Edge (latest versions)
- **Optional**: [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VS Code extension for hot-reload
- **Optional**: [Node.js](https://nodejs.org/) (v16+) if using any build tools

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Sabina-Sheoran/TravelBookingWebsite.git
   cd TravelBookingWebsite
   ```

2. **Or download the ZIP**

   Click **Code → Download ZIP** on GitHub and extract the files.

### Running Locally

#### Option 1: Open directly in browser
```bash
# Simply open index.html in your browser
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

#### Option 2: Use VS Code Live Server
1. Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. Right-click `index.html` → **Open with Live Server**
3. App opens at `http://localhost:5500`

#### Option 3: Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

#### Option 4: Node.js HTTP Server
```bash
npx serve .
# Then visit the URL shown in terminal
```

---

## 📄 Pages Overview

### 🏠 Home / Landing Page (`index.html`)
The entry point of the application featuring:
- Hero section with a full-width destination search bar
- "Search by Category" tabs: Flights, Hotels, Packages, Activities
- Featured destinations carousel
- "Why Travel With Us" section with highlights
- Newsletter signup and footer

### ✈️ Flight Search (`flights.html`)
- One-way / Round-trip / Multi-city toggle
- Departure & destination airport selector (with autocomplete)
- Travel date pickers with calendar UI
- Passenger count & cabin class selector
- Search results with filtering & sorting (price, duration, stops)
- Flight cards with airline info, timings, layovers, and price

### 🏨 Hotel Search (`hotels.html`)
- Location search with city/property name input
- Check-in / Check-out date pickers
- Room count and guest configuration
- Results with grid/list view toggle
- Hotel cards with ratings, amenities ribbons, and price per night
- Interactive map view alongside listings

### 📦 Vacation Packages (`packages.html`)
- Pre-built curated packages (Beach, Adventure, City, Luxury)
- Filter by budget, duration, destinations, rating
- Package cards with itinerary highlights, inclusions, and CTA

### 🗺️ Destination Detail (`destination.html`)
- Destination hero with immersive photo gallery
- About section, best time to visit, local tips
- Available hotels & packages for the destination
- Similar destinations recommendations

### 💳 Booking / Checkout (`booking.html`)
- Multi-step booking form (Guest Details → Add-ons → Payment)
- Order summary sidebar with real-time price breakdown
- Secure payment form (credit/debit card, UPI, wallets)
- Booking policies and cancellation info

### ✅ Confirmation (`confirmation.html`)
- Success animation with booking reference number
- Booking summary (itinerary, passenger details, total paid)
- Options to download ticket / send to email
- "Explore More" CTAs

---

## 📸 Screenshots

> *(Screenshots and GIFs of the live UI will be added here as the project develops)*

| Page | Preview |
|---|---|
| 🏠 Homepage | *Coming soon* |
| ✈️ Flight Search | *Coming soon* |
| 🏨 Hotel Listing | *Coming soon* |
| 💳 Checkout | *Coming soon* |

---

## 🗺️ Roadmap

### Phase 1 – Foundation ✅
- [x] Figma UI/UX design
- [x] Repository setup
- [x] Project structure planning

### Phase 2 – Core Development 🔄
- [ ] Homepage / Landing Page
- [ ] Flight search & results
- [ ] Hotel search & listing
- [ ] Responsive layouts for all pages

### Phase 3 – Advanced Features 🔜
- [ ] Vacation packages page
- [ ] Destination detail pages
- [ ] Booking & checkout flow
- [ ] Form validation and error handling

### Phase 4 – Polish & Deploy 🔜
- [ ] Animations and micro-interactions
- [ ] Performance optimization
- [ ] Accessibility (WCAG 2.1 compliance)
- [ ] Deployment (GitHub Pages / Netlify / Vercel)

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. **Fork** the repository
2. **Create** your feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit** your changes
   ```bash
   git commit -m 'feat: Add some AmazingFeature'
   ```
4. **Push** to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open** a Pull Request

### Commit Convention
This project follows [Conventional Commits](https://www.conventionalcommits.org/):
- `feat:` — New feature
- `fix:` — Bug fix
- `docs:` — Documentation changes
- `style:` — Code style / formatting
- `refactor:` — Code refactoring
- `chore:` — Build process or auxiliary tool changes

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2026 Sabina Sheoran

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 📬 Contact

**Sabina Sheoran**

[![GitHub](https://img.shields.io/badge/GitHub-Sabina--Sheoran-181717?style=flat-square&logo=github)](https://github.com/Sabina-Sheoran)

> ⭐ If you found this project useful or interesting, please consider giving it a **star** — it helps a lot!

---

<div align="center">

Made with ❤️ and ☕ by **Sabina Sheoran**

</div>