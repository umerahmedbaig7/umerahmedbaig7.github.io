<div align="center">

# 🤖 Umer Ahmed Baig Mughal
### Personal Portfolio Website — Robotics & AI Engineer

[![HTML5](https://img.shields.io/badge/HTML5-Pure-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Custom-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Framework](https://img.shields.io/badge/Framework-None-1ec896?style=for-the-badge)](https://github.com/umerahmedbaig7)
[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)](https://github.com/umerahmedbaig7)
[![License](https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge)](./LICENSE)

<br>

> *"A portfolio is not merely a collection of projects — it is the deliberate construction of an identity. Every animation, every colour choice, every section ordering is an argument: this is who I am, what I have built, and where I am going. This one is mine."*

<br>

**Author:** Umer Ahmed Baig Mughal <br>
**Program:** MSc Robotics and Artificial Intelligence <br>
**Specialization:** Machine Learning · Computer Vision · Autonomous Systems · Robotic Motion Control · Human-Robot Interaction <br>
**Institution:** ITMO University — Saint Petersburg, Russia

</div>

---

## 📋 Table of Contents

- [📖 About This Repository](#-about-this-repository)
- [🌐 Live Preview](#-live-preview)
- [🗂️ Repository Structure](#️-repository-structure)
- [🎨 Design System](#-design-system)
- [🧩 Website Sections](#-website-sections)
  - [🚀 Hero](#-hero)
  - [👤 About](#-about)
  - [💼 Experience & Education](#-experience--education)
  - [🛠️ Skills & Expertise](#️-skills--expertise)
  - [🔬 Projects](#-projects)
  - [📄 Publications & Research](#-publications--research)
  - [🏆 Awards & Achievements](#-awards--achievements)
  - [📬 Contact](#-contact)
- [⚙️ Technical Implementation](#️-technical-implementation)
- [✨ UI/UX Features](#-uiux-features)
- [🧰 Tech Stack](#-tech-stack)
- [🚀 Quick Start](#-quick-start)
- [👤 Author](#-author)
- [📄 License](#-license)

---

## 📖 About This Repository

This repository contains the complete source code for my personal portfolio website — a single-page, fully hand-coded web experience built with **pure HTML, CSS, and vanilla JavaScript**, with no frameworks, no build tools, and no external component libraries. Every element — from the animated SVG robot mascot floating in the hero section, to the particle-node canvas background, to the project carousels with lightbox — is authored from scratch.

The portfolio is structured as a deliberate narrative in six acts. It opens with a cinematic hero that establishes identity — a typewriter cycling through eight role descriptions, an animated robot SVG with glowing eyes and a scanning head beam, and four live stat counters. It then moves through a terminal-style About section, an interactive timeline of professional experience, an animated skill bar dashboard, a filterable project grid with image and video carousels, a peer-reviewed publication record, hackathon awards from international competitions, and finally a contact section. The result is not a template — it is a bespoke engineering artefact, built the same way I build robotics software: from first principles, with full control over every layer.

The visual language is consistent throughout: a deep-space dark background (`#050714`), a signature mint-green accent (`#1ec896`), a secondary electric blue (`#3878ff`), and a gold highlight for awards (`#f0a500`). The typography pairs **Syne** (a geometric display font) with **Space Mono** (a monospace typeface), giving the site its distinctive engineering-meets-editorial feel.

### 🎯 What You Will Find Here

| 🏷️ Section | 📌 Content | ✨ Key Feature |
|:-----------:|:----------:|:--------------:|
| Hero | Name · Role · Bio · Stats | Animated robot SVG · Typewriter · Canvas |
| About | Profile · Contacts · Terminal card | Syntax-highlighted pseudocode panel |
| Experience | My Lighting · Pakistan Lighting | Timeline with image galleries |
| Education | ITMO · MUET · College · School | Responsive education grid |
| Skills | 9 proficiency bars · 4 tag categories | Scroll-animated fill bars |
| Projects | NeRF · TriNav · Self-Driving · ML | Filterable grid · Carousels · Lightbox |
| Publications | IJGDC 2020 (peer-reviewed) | DOI / journal link |
| Awards | 3 hackathon results from ROSATOM events | Gold / silver badge system |
| Contact | Email · LinkedIn · Phone · Form | Obfuscated email · Mailto form |

---

## 🌐 Live Preview

🔗 **[https://umerahmedbaig7.github.io](https://umerahmedbaig7.github.io)**

The portfolio is also fully viewable locally from the cloned repository:

```bash
# Option 1 — open directly in your browser
open index.html

# Option 2 — serve locally with Python
python -m http.server 8000
# then visit http://localhost:8000

# Option 3 — serve locally with Node
npx serve .
# then visit http://localhost:3000
```

> 💡 No build step, no `npm install`, no compilation required. The site is 100% self-contained in `index.html` plus the `images/` directory.

---

## 🗂️ Repository Structure

```
📦 umerahmedbaig7.github.io/
│
├── 📄 index.html                              # ← Complete single-page portfolio (4 300+ lines)
│
├── 📄 README.md
│
└── 📁 images/
    ├── 🖼️  Me.webp                            # Profile photo (About section)
    │
    ├── 📁 Project/
    │   ├── 📁 NeRF/
    │   │   ├── 🖼️  NeRF-1.jpeg               # Depth-Supervised NeRF — render 1
    │   │   ├── 🖼️  NeRF-2.jpeg               # Depth-Supervised NeRF — render 2
    │   │   └── 🖼️  NeRF-3.jpeg               # Depth-Supervised NeRF — render 3
    │   ├── 📁 TriNav/
    │   │   ├── 🖼️  TriNav-1.jpg              # TriNav framework — view 1
    │   │   ├── 🖼️  TriNav-2.png              # TriNav framework — view 2
    │   │   ├── 🖼️  TriNav-3.png              # TriNav framework — view 3
    │   │   └── 🎥  visualization.mp4         # TriNav simulation video
    │   ├── 📁 Self-Driving/
    │   │   ├── 🖼️  Self-Driving_Car-1.png    # Self-driving car — view 1
    │   │   └── 🖼️  Self-Driving_Car-2.png    # Self-driving car — view 2
    │   └── 📁 MLR/
    │       ├── 🖼️  ML-1.png                  # ML in Robotics — view 1
    │       ├── 🖼️  ML-2.png                  # ML in Robotics — view 2
    │       └── 🖼️  ML-3.png                  # ML in Robotics — view 3
    │
    ├── 📁 Experience/
    │   ├── 🖼️  LT300-A.png                   # Accelerated Aging-Life Test System
    │   ├── 🖼️  HIPOT.png                     # High Power Tester
    │   ├── 🖼️  Gonio.png                     # Goniophotometer
    │   ├── 🖼️  Glue-F.png                    # Glue Dispenser (My Lighting)
    │   ├── 🖼️  Spectro.png                   # Spectroradiometer
    │   ├── 🖼️  SMT.png                       # SMT PCB Assembly
    │   └── 🖼️  Glue-P.jpg                    # Glue Station (Pakistan Lighting)
    │
    └── 📁 Awards & Achievement/
        ├── 📁 Obnisk-Summer-School/
        │   └── 🖼️  1.jpg … 11.jpg            # ObninskTech Summer 2025 (11 photos)
        ├── 📁 Obnisk-Winter-School/
        │   └── 🖼️  1.jpg … 8.jpg             # ObninskTech Winter 2025 (8 photos)
        └── 📁 WAW/
            ├── 🖼️  1.jpg … 8.jpg             # World Atomic Week 2025 (8 photos)
            └── 🎥  9.mp4                     # World Atomic Week — event video
```

---

## 🎨 Design System

The entire visual identity is defined through a single CSS variable block at the top of `index.html` — no external stylesheets, no design tokens file, no CSS preprocessor. Every component derives its colours from this system, making global re-theming a single-file operation.

### Colour Palette

| Variable | Value | Role |
|:--------:|:-----:|:----:|
| `--green` | `#1ec896` | Primary accent — borders, glows, highlights, icons |
| `--green-dim` | `rgba(30,200,150,0.10)` | Subtle card backgrounds and hover fills |
| `--green-border` | `rgba(30,200,150,0.22)` | Card and element border colour |
| `--green-glow` | `0 0 28px rgba(30,200,150,0.22)` | Box-shadow glow on interactive elements |
| `--blue` | `#3878ff` | Secondary accent — TriNav, robot detail, orbit ring |
| `--gold` | `#f0a500` | Awards section — gold badge and star icons |
| `--bg` | `#050714` | Primary background (deep space navy) |
| `--bg2` | `#08091e` | Alternate section background |
| `--bg3` | `#0c1130` | Tertiary surface |
| `--text` | `#dce8ff` | Primary text (cool white) |
| `--text-muted` | `rgba(180,200,240,0.52)` | Secondary text — captions and labels |
| `--text-dim` | `rgba(180,200,240,0.22)` | Tertiary text — scroll hint, decorative |

### Typography

| Variable | Font | Use |
|:--------:|:----:|:---:|
| `--font-d` | `Syne` (400/600/700/800) | Display — headings, section titles, nav logo |
| `--font-m` | `Space Mono` (400/700) | Monospace — tags, labels, terminal content, body descriptions |
| *(accent)* | `IM Fell English Italic` | Loaded but available for editorial accents |

---

## 🧩 Website Sections

### 🚀 Hero

The hero (`#hero`) is a full-viewport two-column grid. The left column contains the identity block: a green `// Robotics & AI Engineer` tag, the full name with `Mughal` highlighted in green, a **typewriter** cycling through eight phrases (MSc programme, autonomous systems, robot perception, deep learning, intelligent systems, human-robot interaction, motion planning, embedded systems), a bio paragraph, seven skill tags, and three CTA buttons (View Projects, GitHub, Get In Touch). The right column displays a custom **animated SVG robot mascot** — 280×290px, with glowing eye animation (`eyeGlow`), pulsing antenna (`antPulse`), a scanning head beam (`scanHead`), rotating orbit rings (`dashMove`), a waveform display on the chest, and a floating body animation — sitting above a 2×2 stats grid counting up to **10 Repos · 1 Publication · 3+ Years · 3 Awards**.

The canvas background (`#bgCanvas`) renders three simultaneous layers: a network of drifting nodes connected by orthogonal green lines at proximity < 190px, particle floaters, and five shooting stars that streak diagonally across the upper half of the screen.

### 👤 About

Section 01. A two-column grid — left column holds a **terminal window** styled with macOS traffic-light dots and a `umer@itmo:~/ — profile.py` title bar. Inside, a syntax-highlighted Python pseudoclass displays the full profile: `role`, `university`, `focus`, `industry_exp`, `publication`, `awards`, and `languages`, followed by a docstring bio and a `print()` statement announcing openness to PhD roles and collaborations. The right column shows the profile photo, contact rows (Email, Phone, LinkedIn, GitHub, Origin, Status), and a green `● Open to opportunities` indicator.

### 💼 Experience & Education

Section 02. A vertical timeline of two professional roles, each rendered as a card with a left **image gallery** (auto-advancing, dot-navigated, captioned) and a right details block.

| # | Role | Company | Period | Location |
|:-:|:----:|:-------:|:------:|:--------:|
| 1 | Lab Manager | My Lighting (Private) Limited | 09/2022 – 10/2024 | Karachi, Pakistan |
| 2 | Lab Engineer | Pakistan Lighting LED Private Limited | 02/2021 – 08/2022 | Karachi, Pakistan |

**My Lighting** responsibilities: QC and R&D protocol development for indoor/outdoor lighting products, photometric and goniophotometric measurements, IES file generation, photometric reports, team leadership, and workflow integration between hardware testing and data analysis. Equipment shown: LT300-A Aging System, HIPOT Tester, Goniophotometer, Glue Dispenser.

**Pakistan Lighting** responsibilities: Lab protocol development for luminaire testing, IES file generation with DIALux, precision instrument calibration (spectroradiometers, SMT PCB systems, laser markers, LED driver benches), and instrumentation training delivery. Equipment shown: Spectroradiometer, SMT Assembly, Glue Station.

The **Education** subsection below the timeline presents four cards in a responsive grid:

| Degree | Institution | Period | Grade |
|:------:|:-----------:|:------:|:-----:|
| MSc Robotics & Artificial Intelligence | ITMO University, Saint Petersburg | 09/2024 – 08/2026 | **CGPA 4.9 / 5.0** |
| BEng Electronic Engineering | Mehran University of Engineering & Technology | 01/2016 – 12/2019 | CGPA 3.01 / 4.0 |
| Intermediate (Pre-Engineering) | College of Excellence for Boys, Hyderabad | 08/2013 – 08/2015 | 74.5% |
| Matriculation | Public School Hyderabad | 04/2011 – 04/2013 | 76.2% |

### 🛠️ Skills & Expertise

Section 03. A two-column layout. The left column renders nine **animated proficiency bars** — on scroll entry the green fill animates from 0% to target width, each labelled with name and percentage:

| Skill | Proficiency |
|:-----:|:-----------:|
| Python | 92% |
| PyTorch / TensorFlow | 87% |
| MATLAB / Simulink | 84% |
| OpenCV / Computer Vision | 85% |
| ROS / Robotics Middleware | 82% |
| C / C++ | 82% |
| MuJoCo / Gazebo Simulation | 83% |
| LabVIEW | 80% |
| NI Multisim | 80% |

The right column organises skills into four tagged categories — **AI & Machine Learning** (Deep Learning, NeRF/3D Reconstruction, CNNs/SegNet, Autoencoders, RL, Transfer Learning, Jupyter/Colab), **Robotics & Control** (PID, MPC, DWA, A\*, EKF/UKF, Trajectory Planning, SLAM, Robotic Motion Control), **Embedded & Hardware** (Arduino, STM32, PCB Design, AutoCAD, SMT Assembly, IoT Systems, LiDAR Sensing), and **Tools & Professional** (Git/GitHub, DIALux, Technical Writing, Project Management, Team Leadership, R&D Protocols).

### 🔬 Projects

Section 04. A filterable grid with five category buttons (All / Computer Vision / Navigation / Machine Learning / Hardware). Each project card contains an **auto-advancing image carousel** with dot navigation and a lightbox viewer (click to expand, keyboard arrow-key navigation, video support), a date range, title, description, tech tag pills, and GitHub / paper links.

| # | Project | Period | Key Result | Category |
|:-:|:-------:|:------:|:----------:|:--------:|
| 1 ⭐ | **Depth-Supervised NeRF for 3D Reconstruction** | 09/2025 – 02/2026 | Hybrid strategy PSNR **22.32 dB** (+2.4 dB over RGB-only) | Computer Vision |
| 2 | **TriNav: Tri-Layer Navigation Framework** | 02/2025 – 06/2025 | A\* + DWA + MPC in MuJoCo, real-time obstacle avoidance | Navigation |
| 3 | **Self-Driving Car (LiDAR + Image Processing)** | 10/2018 – 10/2019 | CNN / Mask R-CNN · **Published** IJGDC Vol.13 | Computer Vision · Hardware |
| 4 | **ML in Robotics — End-to-End Pipeline Collection** | MSc Coursework | SegNet + Autoencoder + RL in PyTorch | Machine Learning |

*⭐ = Featured project.*

### 📄 Publications & Research

Section 05. A single peer-reviewed publication card with journal badge, full citation, and ResearchGate link:

> **"Self-Driving Car Using LiDAR Sensing and Image Processing"**
> Umer Ahmed Baig, et al. — *International Journal of Grid and Distributed Computing (IJGDC)*, Vol. 13, No. 2, pp. 77–88, 2020. ISSN: 2005-4262 · NADIA Publisher.

The paper presents a framework for autonomous vehicle perception using CNN and Mask R-CNN for environment classification and obstacle detection, validated through both simulation and real-world deployment, and integrating LiDAR point-cloud data with RGB image processing.

### 🏆 Awards & Achievements

Awards subsection within Section 05, presenting three international competition results, each with a multi-image carousel, badge, organisation, and description:

| 🥇 Award | Event | Organiser | Date |
|:--------:|:-----:|:---------:|:----:|
| 🥇 1st — Engineering Hackathon + 🥇 1st — Atomic Triathlon | ObninskTech Summer University | ROSATOM & MEPhI · Obninsk, Russia | 28 June 2025 |
| 🥉 3rd — Engineering Hackathon | ObninskTech Winter School | ROSATOM & MEPhI · Obninsk, Russia | 08 February 2025 |
| 🌐 Participation | World Atomic Week — Global HackAtom | ROSATOM · Moscow · 35+ countries · 1,200+ participants | 28 September 2025 |

*Summer University: Designed an interactive website with chatbot integration for peaceful nuclear technology education; won the Atomic Triathlon competing alongside students from 40+ countries. Winter School: Developed engineering solutions in a multidisciplinary environment with professionals from 39 countries.*

### 📬 Contact

Section 06. Two-column grid — left: a headline ("Let's build something **intelligent** together"), an availability note, and direct contact links (Email, LinkedIn, Phone). Right: a styled contact form with Name, Email, Subject, and Message fields, and a "Send Message" button that composes a mailto. The email address is obfuscated in JavaScript (`umerahmedbaig98@gmail.com`) to prevent scraping. Response time stated as within 24 hours.

---

## ⚙️ Technical Implementation

The entire site is a single `index.html` file of ~4,300 lines. There are no dependencies to install, no build pipeline to run, and no external scripts beyond three Google Fonts imports. Every interactive behaviour is authored in vanilla JavaScript at the bottom of the file.

### Canvas Background Engine

The `#bgCanvas` element runs a continuous `requestAnimationFrame` loop rendering three independent layers on a single `<canvas>`:

- **Node network** — ~60 drifting circular nodes, each with random velocity. Nodes closer than 190px are connected by L-shaped orthogonal paths (`moveTo → lineTo → lineTo`) with opacity proportional to `1 - d/190`. The connection colour is `rgba(30,200,150,α)` with a 0.5px stroke weight, producing the characteristic circuit-board aesthetic.
- **Particle layer** — smaller secondary particles drifting upward, fading in and out.
- **Shooting stars** — 5 `Star` objects that traverse the upper half of the canvas diagonally at random speeds and lengths, with a gradient fade from transparent tail to opaque head. Stars reset to a new random position when they exit the canvas boundary.
- **Mouse glow** — a `createRadialGradient` centred on the cursor position, emitting a 160px soft green radial gradient that follows the mouse, giving the canvas a reactive quality without any per-node mouse interaction.

### Custom Cursor

A two-part cursor system replaces the default browser cursor: a 6px solid green dot (`#cursor`) that snaps to the exact mouse position, and a 28px translucent ring (`#cursor-ring`) that follows with 12% lerp smoothing (`rx += (mx - rx) * 0.12`). On hover over any `a`, `button`, or `.f-btn`, the ring expands to 1.9× its normal size and becomes fully opaque via a CSS class `.h`, providing tactile visual feedback for all interactive targets.

### Carousel + Lightbox System

All project and award cards share a single carousel implementation. Each `[data-carousel]` container holds a `.proj-imgs` strip that translates on the X-axis by `idx * 100%`. An auto-advance interval fires every 3.8 seconds, pausing on mouseenter and resuming on mouseleave. Clicking the carousel body (not a button or dot) opens the **lightbox** — a full-screen backdrop with `backdrop-filter: blur(14px)`, displaying the full-resolution image or video. Navigation in the lightbox supports mouse click (prev/next buttons), keyboard (`ArrowLeft`, `ArrowRight`, `Escape`), and click-outside-to-close. Video items use a `.car-video-thumb` class with a `data-src` attribute; the lightbox attaches the `src` attribute only on open, and removes it on close to prevent background audio.

### Scroll Reveal System

Every major content element carries a `.reveal` class, which sets it to `opacity: 0; transform: translateY(26px)`. An `IntersectionObserver` watches all `.reveal` elements and adds `.vis` (resetting opacity and transform with a 0.7s ease transition) when they enter the viewport. Staggered children use `.rd1`, `.rd2`, `.rd3` utility classes that add `transition-delay` of 0.1s, 0.2s, and 0.3s respectively, producing cascading reveal animations across grid items.

### Skill Bar Animation

Each `.sk-fill` bar stores its target width in a `data-w` attribute. On scroll entry (via the same `IntersectionObserver`), the bar's inline `width` style is set to `data-w + '%'`, and the CSS transition `width 1.1s cubic-bezier(0.4,0,0.2,1)` animates the fill from 0.

### Stats Counter

The four hero stats (`10`, `1`, `3+`, `3`) use a `data-target` attribute. On the first `IntersectionObserver` trigger, a `setInterval` increments a counter from 0, easing toward the target by adding `Math.ceil(remaining / 8)` per tick, then stopping when the target is reached. Items with `data-suffix="+"` append the suffix on completion.

---

## ✨ UI/UX Features

| Feature | Implementation | Detail |
|:-------:|:--------------:|:------:|
| **Animated Loader** | CSS `@keyframes ldFill` | Progress bar fills over 2.4s; loader fades out after DOM ready |
| **Custom Cursor** | RAF lerp loop | Dot snaps; ring follows at 12% lerp; expands 1.9× on hover |
| **Typewriter** | Vanilla JS interval | 8 phrases, character-by-character type and delete with blinking cursor |
| **Canvas Background** | `requestAnimationFrame` | Node network + particles + shooting stars + mouse glow |
| **Animated SVG Robot** | CSS `@keyframes` | 10 independent animations: eye glow, antenna pulse, scan beam, orbit rings, waveform, core pulse, ear glow, signal dots, float |
| **Stats Counters** | `IntersectionObserver` + interval | Ease-to-target counting with optional suffix |
| **Scroll Reveal** | `IntersectionObserver` | Fade-up with configurable stagger delays |
| **Skill Bars** | `IntersectionObserver` + CSS transition | Animated width fill from 0 to target % |
| **Project Filter** | JS class toggle + `display` | Five category buttons filter `.proj-card` by `data-cat` attribute |
| **Image Carousels** | JS `translateX` + `setInterval` | Auto-advance every 3.8s, pause on hover, prev/next/dot controls |
| **Video in Carousel** | Lazy `src` assign | `data-src` prevents preload; src set only on lightbox open |
| **Lightbox** | Full-screen overlay | Blur backdrop, keyboard nav, fade transition, video support, counter |
| **Social Sidebar** | Fixed left column | GitHub, LinkedIn, Email icons with vertical line, fade-in after 2.8s |
| **Nav Scroll Spy** | `scroll` event | Active link highlights as sections enter viewport with −130px offset |
| **Nav Shrink** | `scroll` event | Padding reduces after 60px scroll |
| **Mobile Menu** | Hamburger with CSS transform | Three-bar → X transform; full-screen overlay menu |
| **Email Obfuscation** | JS string concat + `\x40` | Email address assembled at runtime, never present in HTML source |
| **Back to Top** | Fixed button, scroll toggle | Appears after 400px scroll |
| **Experience Galleries** | Separate gallery system | Auto-advance 3.6s, captions keyed to filename map |
| **Responsive Layout** | CSS Grid + Media Queries | Breakpoints at 1060px (hero) and 780px (mobile); all grids collapse to single column |

---

## 🧰 Tech Stack

<div align="center">

| 🛠️ Technology | 🎯 Role | 📍 Used In |
|:-------------:|:-------:|:----------:|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white) | Document structure, semantic sectioning, inline SVG authoring | Entire site |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white) | CSS variables, Grid, Flexbox, keyframe animations, media queries, custom scrollbar, backdrop-filter | Entire site |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) | Cursor, typewriter, canvas engine, carousels, lightbox, scroll-reveal, counters, filter, nav spy | Entire site |
| ![Canvas API](https://img.shields.io/badge/-Canvas_API-555?logo=html5&logoColor=white) | Node network, shooting stars, mouse glow, particle layer | Hero background |
| ![SVG](https://img.shields.io/badge/-Inline_SVG-FFB13B?logo=svg&logoColor=black) | Robot mascot (animated), nav logo, loader icon, all UI icons | Hero, Nav, Loader, Cards |
| ![Google Fonts](https://img.shields.io/badge/-Google_Fonts-4285F4?logo=google&logoColor=white) | Syne (display), Space Mono (mono), IM Fell English (italic) | Typography |
| ![IntersectionObserver](https://img.shields.io/badge/-IntersectionObserver-1ec896?logo=javascript&logoColor=white) | Scroll-reveal, skill bar animation, stats counter trigger | Skills, Projects, About |

</div>

**No CSS frameworks. No JavaScript libraries. No npm packages. No build pipeline.** Every animation curve, every layout breakpoint, every interactive behaviour is written explicitly in raw CSS and vanilla JavaScript — the same first-principles approach applied to the robotics algorithms documented in my other repositories.

---

## 🚀 Quick Start

### Prerequisites

None. A modern web browser is the only requirement (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+).

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/umerahmedbaig7/umerahmedbaig7.github.io.git
cd umerahmedbaig7.github.io
```

### 2️⃣ Open the Portfolio

```bash
# Direct file open (simplest)
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux

# Or serve over HTTP (recommended — prevents any CORS issues with local assets)
python -m http.server 8000
# Visit: http://localhost:8000
```

### 3️⃣ File Structure Note

The `images/` directory must sit alongside `index.html` at the root level. All image paths are relative — moving `index.html` without the `images/` folder will result in broken assets.

```
your-folder/
├── index.html       ← open this
└── images/          ← must be here
```

> 💡 The portfolio is fully functional offline — no API calls, no CDN dependencies beyond the Google Fonts preconnect (which degrades gracefully if unavailable).

---

## 👤 Author

<div align="center">

### Umer Ahmed Baig Mughal

🎓 **MSc Robotics and Artificial Intelligence** — ITMO University, Saint Petersburg <br>
🏛️ *Faculty of Control Systems and Robotics* <br>
🔬 *Specialization: Machine Learning · Computer Vision · Autonomous Systems · Robotic Motion Control · Human-Robot Interaction* <br>
📍 *Based in Saint Petersburg, Russia · Originally from Karachi, Pakistan* <br>
📬 *umerahmedbaig98@gmail.com* · 📞 *+92 348 366 1218*

[![GitHub](https://img.shields.io/badge/GitHub-umerahmedbaig7-181717?style=for-the-badge&logo=github)](https://github.com/umerahmedbaig7)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-umer--ahmed--baig7-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/umer-ahmed-baig7)

</div>

---

## 📄 License

This repository is shared for **portfolio and reference purposes**. The source code structure, design system, and implementation patterns are open for learning and inspiration. Direct reproduction as a personal portfolio without modification is discouraged — build your own. Proper attribution is appreciated if any significant portions are reused.

---

<div align="center">

*umerahmedbaig7.github.io | Umer Ahmed Baig Mughal — MSc Robotics & AI | ITMO University*

⭐ *If this portfolio's design, animation, or technical implementation gave you ideas for your own — consider leaving a star!* ⭐

</div>
