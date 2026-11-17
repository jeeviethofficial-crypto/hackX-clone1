# hackX 11.0 — Website Clone

A complete, high-fidelity offline-capable clone of [hackX 11.0](https://hackx.lk) — Sri Lanka's Premier Inter-University Startup Challenge organized by the Department of Industrial Management, University of Kelaniya.

## 🚀 Quick Start

Run with Python (no installation required):
```bash
python3 -m http.server 3000
```
Or with Node / npx:
```bash
npm start
# or: npx serve -s . -l 3000
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🎨 Design & Aesthetic System
- **Theme**: Futuristic deep-space cybernetic dark mode (`#010814`) with glowing radial gradients (`#1A6FD4` electric sapphire and `#5BB8FF` neon cyan).
- **Typography**: Complete local font family `TT Hoves Pro` and `TT Hoves Pro Expanded` (9 weights: Light, Regular, Medium, Bold, ExtraBold, Black).
- **Effects**: Backdrop blur glassmorphism (`backdrop-blur-3xl`, `bg-[#010814]/80`, `border-white/10`), animated glow paths, and glowing particle lights.

---

## 📂 Project Structure

```
hackX/
├── index.html                           # Main landing page with full interactive enhancements
├── package.json                         # Project runner scripts
├── README.md                            # Documentation and project guide
├── hackX-11.0-Delegate-Booklet.pdf      # Official delegate information booklet
├── hackxlogo.webp                       # hackX official vector/raster branding
├── Hero Front Layer New.webp            # Hero front perspective element
├── Hero - BG Img.webp                   # Hero background space vista
├── timeline mountain.webp               # Mountain silhouette for timeline journey
├── FAQ Image.webp                       # Cybernetic visual for FAQ section
├── allorganizerslogo.webp               # Organizers & Department logos
├── footer-center.webp                   # Footer centerpiece
├── footer-side.webp                     # Footer accent elements
├── footer circle.png                    # Footer ambient circle element
├── Xlogo-favicon.png                    # Brand favicon icon
│
├── fonts/                               # TT Hoves Pro typography suite
│   ├── TT Hoves Pro Trial Light.ttf
│   ├── TT Hoves Pro Trial Regular.ttf
│   ├── TT Hoves Pro Trial Medium.ttf
│   ├── TT Hoves Pro Trial Bold.ttf
│   ├── TT Hoves Pro Trial ExtraBold.ttf
│   ├── TT Hoves Pro Trial Black.ttf
│   ├── TT Hoves Pro Trial Expanded Regular.ttf
│   ├── TT Hoves Pro Trial Expanded Medium.ttf
│   └── TT Hoves Pro Trial Expanded Bold.ttf
│
├── criteria-images/                     # Eligibility & criteria badges
│   ├── icon-1.webp
│   ├── icon-2.webp
│   └── icon-3.webp
│
├── winner-cards/                        # Awards & prize tier representations
│   ├── 1.webp
│   ├── 2.webp
│   └── 3.webp
│
├── timeline-bgs/                        # Phase background banners
│   ├── registration.webp
│   ├── Proposal Submission.webp
│   ├── Workshops.webp
│   ├── Semi FInals.webp
│   └── Finals.webp
│
├── horizontal timeline/                 # Horizontal progression visuals
│   ├── 2.webp
│   └── 3.webp
│
├── Memories/                            # Moments of Innovation from hackX 10.0
│   ├── Opening Ceremony.webp
│   ├── Networking Moments.webp
│   ├── Focused Audience.webp
│   ├── Team Showcase.webp
│   ├── Expert Deliberation.webp
│   ├── Prize Presentation.webp
│   ├── The Team.webp
│   └── Official Merch.webp
│
├── OC/                                  # Organizing Committee executive photos
│   ├── Praveen.webp                     # Chief Coordinator
│   ├── Tharushi.webp                    # Chief Coordinator
│   ├── Tharindu.webp                    # Partnership Coordinator
│   ├── Sameera.webp
│   ├── Imasha.webp
│   ├── Thilini.webp
│   ├── Charith.webp
│   └── Manumi.webp
│
├── partners-logos/                      # 14 Partner & Sponsor logos
│   ├── 01-ministry.png
│   ├── 02-nsf.png
│   ├── 03-evonsys.png
│   ├── 04-lionbit.png
│   ├── 05-nventures.png
│   ├── 06-generation-alpha.png
│   ├── 07-slasscom.png
│   ├── 08-tie-colombo.png
│   ├── 09-virtusa.png
│   ├── 10-helakuru-esana.png
│   ├── 11-escape-the-room.png
│   ├── 12-waters-edge.png
│   ├── 13-xtreamyouth.png
│   └── 14-perfect-events.png
│
├── section 2/                           # Section 2 floating 3D artifacts
│   ├── Top left.webp
│   ├── Top Right.webp
│   └── Bottom Center.webp
│
├── _next/                               # Next.js stylesheets and client runtime
│   └── static/chunks/
│       ├── 1f95rdjwglmzl.css            # Tailwind & custom CSS stylesheet
│       └── *.js                         # Runtime scripts & animations
│
├── robots.txt                           # Search engine crawling rules
└── sitemap.xml                          # XML site map
```

---

## ⚡ Interactive Features Included
1. **Preloader Animation**: Sleek cybernetic loading sweep with automatic fade-out upon asset initialization.
2. **Smooth Anchor Navigation**: Navbar and CTA links (`#about`, `#timeline`, `#rewards`, `#memories`, `#oc`, `#partners`, `#faq`, `#ask-ai`) smoothly glide to their targets.
3. **FAQ Accordion**: 7 expandable questions with animated states and responsive layouts for both mobile and desktop.
4. **Interactive Ask AI Assistant**:
   - Quick action prompt chips (*Registration*, *Eligibility*, *Timeline*, *Rules & Guidelines*, *About hackX*, *Prizes*, *Contact*).
   - Dynamic query matching with typing indicators and markdown-formatted responses.
   - Contact email and phone hotlinks.
5. **Direct Booklet Download**: Download the official [hackX-11.0-Delegate-Booklet.pdf](file:///Users/jeeveith/Desktop/hackX/hackX-11.0-Delegate-Booklet.pdf) locally.
# hackX-clone1
