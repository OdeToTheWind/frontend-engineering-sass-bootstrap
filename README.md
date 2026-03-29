# Frontend Engineering Mastery: SASS + Bootstrap 100 Demos

[![SASS CI](https://github.com/OdeToTheWind/frontend-engineering-sass-bootstrap/actions/workflows/sass-build.yml/badge.svg)](https://github.com/OdeToTheWind/frontend-engineering-sass-bootstrap/actions)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**A production-grade progressive learning monorepo** with **100 complete frontend demos** built with **HTML5, SASS (SCSS), Bootstrap 5**, and vanilla JavaScript (ES6+). 

This repository takes you from beginner fundamentals to advanced 2D/3D production-ready applications. Every demo is fully responsive, accessible (WCAG AA), Lighthouse-optimized (>95), and includes Figma design references.

**Live Central Portfolio**: [https://frontend-engineering-sass-bootstrap.vercel.app](https://frontend-engineering-sass-bootstrap.vercel.app) (powered by Demo-100)  
**GitHub**: https://github.com/OdeToTheWind/frontend-engineering-sass-bootstrap  
**Location**: Bengaluru, Karnataka, India  
**Last Updated**: March 29, 2026

---

## Overview

This is a complete **Frontend Engineering Mastery** project featuring exactly **100 professional demos** using **SASS + Bootstrap 5**.  

The collection is structured into four progressive levels as requested:

1. **Beginner Projects (1–25)** – Core SASS variables, mixins, Bootstrap grid/components, basic responsiveness, and Git fundamentals.
2. **Intermediate Projects (26–50)** – Advanced SASS architecture (7-1 pattern), custom Bootstrap themes, interactivity, filters, and dark mode.
3. **Advanced Projects (51–75)** – Full-fledged 2D/3D experiences with GSAP, CSS 3D transforms, light Three.js, performance optimization, and component libraries.
4. **Professional / Real-World Demos (76–100)** – Production-grade multi-page applications with Figma traceability, backend integration (only in Demo-100), deployment, and professional showcase.

**Demo-100** acts as the **central live website** that showcases all 100 demos, making your portfolio recruiter-ready and professional.

---
## Why This Repository?

- Exactly **100 demos** divided into 4 levels as per the original agenda.
- Professional monorepo structure inspired by large-scale engineering projects.
- Complete **Figma → SASS/Bootstrap → GitHub → Live** workflow.
- Real-world practices: 7-1 SASS architecture, design tokens, component library, CI/CD.
- **2D + 3D** experiences using pure CSS, SASS, GSAP, and light Three.js.
- **Demo-100** serves as the **single live website** showcasing all 100 demos.

---

## Repository Structure

```bash
frontend-engineering-sass-bootstrap/
├── .github/                          # GitHub Actions CI/CD pipelines
│   └── workflows/
│       ├── sass-build.yml            # Compile SASS + run tests
│       ├── deploy-demos.yml          # Auto-deploy to Netlify/Vercel
│       └── lighthouse.yml            # Performance & accessibility checks
├── build/                            # Compiled CSS/JS bundles (gitignored)
├── docs/                             # Professional documentation & learning artifacts
│   ├── figma/                        # All 100 Figma design files (linked per demo)
│   ├── architecture.md                # SASS design system & Bootstrap overrides
│   └── progress/
│       ├── demo-01.md
│       ├── demo-02.md
│       ... 
│       └── demo-100.md               # One markdown per demo (learnings, screenshots, challenges)
├── src/
│   ├── beginner/                     # Cleaner naming
│   │   ├── demo-01-personal-portfolio/
│   │   ├── demo-02-restaurant-menu/
│   │   └── ... (up to demo-25)
│   ├── intermediate/
│   ├── advanced/
│   └── professional/
│       └── demo-100-developer-portfolio/     # ← Changed name (shorter)
│           ├── frontend/                     # ← All your HTML, SCSS, JS here
│           ├── supabase/
│           └── pocketbase/
├── public/                           # Shared static assets (icons, fonts, images)
├── tests/                            # Jest + Playwright tests (selected demos)
├── .gitignore
├── LICENSE
├── README.md                         # ← You are reading this
├── package.json                      # Root npm scripts (sass, vite, lint)
├── vite.config.js                    # Unified dev server & build tool (one command per demo)
├── .env.example
└── CONTRIBUTING.md
```

## Daily Progress

| Day | Project / Topic                                      | Level          | Status       | Key Learnings / Deliverables                                                                                          |
|-----|------------------------------------------------------|----------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
| 01  | Personal Portfolio Landing Page                      | Beginner       | ✅ Completed  | SASS variables, nesting, Bootstrap navbar, hero section, cards, Bootstrap utilities                                   |
| 02  | Simple Restaurant Menu Website                       | Beginner       | ⏳ Planned  | SASS mixins, Bootstrap cards + grid, hover effects, responsive images                                                 |
| 03  | Fitness Gym Landing Page                             | Beginner       | ⏳ Planned  | SASS partials (@import), hero overlay, pricing tables, Bootstrap buttons & spacing                                    |
| 04  | Travel Agency Homepage                               | Beginner       | ⏳ Planned  | Destination cards, Bootstrap carousel, testimonial section, SASS color maps                                           |
| 05  | E-commerce Product Listing Page                      | Beginner       | ⏳ Planned  | Product grid with filters, Bootstrap flex & grid, basic SASS loops                                                    |
| 06  | Blog Homepage with Sidebar                           | Beginner       | ⏳ Planned  | Article cards, Bootstrap offcanvas sidebar, responsive typography with SASS                                           |
| 07  | Photography Portfolio                                | Beginner       | ⏳ Planned  | Masonry-style gallery using Bootstrap grid + SASS, CSS custom properties + SASS functions                             |
| 08  | Coffee Shop Landing Page                             | Beginner       | ⏳ Planned  | Dark mode toggle with SASS variables, Bootstrap modals                                                                |
| 09  | Real Estate Property Listing                         | Beginner       | ⏳ Planned  | Property cards, Bootstrap tabs & navs                                                                                 |
| 10  | Music Artist Landing Page                            | Beginner       | ⏳ Planned  | Audio player UI, Bootstrap + SASS @keyframes animations                                                               |
| 11  | Job Board Landing Page                               | Beginner       | ⏳ Planned  | Job cards, Bootstrap accordion component                                                                              |
| 12  | Yoga Studio Website                                  | Beginner       | ⏳ Planned  | Class schedule table, Bootstrap responsive tables                                                                     |
| 13  | Bookstore Homepage                                   | Beginner       | ⏳ Planned  | Book covers with SASS transform hover zoom, CSS transitions                                                           |
| 14  | Weather App UI (Static)                              | Beginner       | ⏳ Planned  | City cards, Bootstrap icons integration                                                                               |
| 15  | Event Ticket Booking Landing                         | Beginner       | ⏳ Planned  | Countdown timer + Bootstrap progress bars, basic JavaScript integration                                               |
| 16  | Recipe Finder Homepage                               | Beginner       | ⏳ Planned  | Recipe cards, search bar, Bootstrap form controls                                                                     |
| 17  | Crypto Dashboard UI (Static)                         | Beginner       | ⏳ Planned  | Price cards, SASS linear gradients                                                                                    |
| 18  | Fashion Store Landing Page                           | Beginner       | ⏳ Planned  | Lookbook with Bootstrap carousel, custom SASS breakpoints                                                             |
| 19  | Online Course Landing Page                           | Beginner       | ⏳ Planned  | Video thumbnail grid, Bootstrap ratio utility for responsive video                                                    |
| 20  | Pet Adoption Website                                 | Beginner       | ⏳ Planned  | Adoptable pet cards, SASS maps for categories                                                                         |
| 21  | Hotel Booking Homepage                               | Beginner       | ⏳ Planned  | Room types + Bootstrap modal booking form, SASS form validation styling                                               |
| 22  | News Portal Homepage                                 | Beginner       | ⏳ Planned  | Top stories + category pills, Bootstrap badges & pills                                                                |
| 23  | Fitness Tracker Dashboard (Static)                   | Beginner       | ⏳ Planned  | Progress rings with CSS, conic-gradient in SASS                                                                       |
| 24  | Resume Builder Landing Page                          | Beginner       | ⏳ Planned  | Template previews, clean SASS architecture (_base, _components, _layout)                                              |
| 25  | Charity Donation Landing Page                        | Beginner       | ⏳ Planned  | Impact counters + Bootstrap progress bars, basic counter animation with JS + SASS                                     |

**Beginner Projects (1–25) completed on Day 25**  
**Intermediate Projects start on Day 26**

| Day | Project / Topic                                      | Level          | Status       | Key Learnings / Deliverables                                                                                          |
|-----|------------------------------------------------------|----------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
| 26  | Multi-page Agency Website                            | Intermediate   | ⏳ Planned  | Home + Services + Portfolio + Contact using SASS 7-1 pattern, Bootstrap custom theme, SASS @use                       |
| 27  | Interactive Quiz App UI                              | Intermediate   | ⏳ Planned  | Progress bar, radio buttons styled with SASS, Bootstrap forms + custom checkbox/radio                                 |
| 28  | SaaS Product Landing Page                            | Intermediate   | ⏳ Planned  | Pricing toggle (monthly/yearly), animated stats, SASS mixins for reusable buttons & cards                             |
| 29  | Admin Dashboard Template                             | Intermediate   | ⏳ Planned  | Sidebar, topbar, data tables, Bootstrap offcanvas + custom SASS variables override                                    |
| 30  | E-commerce Product Detail Page                       | Intermediate   | ⏳ Planned  | Image gallery, size selector, quantity & add to cart, Bootstrap tabs + SASS hover states                              |
| 31  | Social Media Dashboard                               | Intermediate   | ⏳ Planned  | Feed, stories, post composer, infinite scroll simulation + SASS animations                                            |
| 32  | Job Portal with Filters                              | Intermediate   | ⏳ Planned  | Advanced filtering with Bootstrap dropdowns + JS, data attributes + custom SASS filters                               |
| 33  | Online Learning Platform                             | Intermediate   | ⏳ Planned  | Course grid with search/filters, video modal, Bootstrap modal + SASS component library                                |
| 34  | Banking App UI                                       | Intermediate   | ⏳ Planned  | Account overview, transaction history, transfer form, custom Bootstrap theme (colors, fonts)                          |
| 35  | Real Estate Marketplace                              | Intermediate   | ⏳ Planned  | Property map placeholder + advanced filters, Bootstrap range slider styling with SASS                                 |
| 36  | Food Delivery App UI                                 | Intermediate   | ⏳ Planned  | Restaurant list + cart sidebar (offcanvas), SASS functions for dynamic pricing                                        |
| 37  | Crypto Trading Dashboard                             | Intermediate   | ⏳ Planned  | Charts placeholder + live price cards, Bootstrap grid mastery + SASS loops                                            |
| 38  | Hotel Booking Engine                                 | Intermediate   | ⏳ Planned  | Date picker UI, room selection, multi-step form with Bootstrap + SASS                                                 |
| 39  | Freelancer Marketplace                               | Intermediate   | ⏳ Planned  | Gig cards with rating system, star rating with pure CSS/SASS                                                          |
| 40  | News Magazine Layout                                 | Intermediate   | ⏳ Planned  | Mega menu, infinite scroll simulation, advanced SASS dark mode with @media                                            |
| 41  | Task Management App (Trello clone UI)                | Intermediate   | ⏳ Planned  | Kanban boards with drag simulation, Bootstrap grid + custom drag CSS                                                  |
| 42  | Fitness App Dashboard                                | Intermediate   | ⏳ Planned  | Workout plans, progress tracking UI, circular progress with SASS + conic-gradient                                     |
| 43  | Music Streaming UI (Spotify-like)                    | Intermediate   | ⏳ Planned  | Player at bottom, playlist, album art, responsive player bar with SASS                                                |
| 44  | Event Management Dashboard                           | Intermediate   | ⏳ Planned  | Calendar view + event cards, Bootstrap accordion + custom calendar CSS                                                |
| 45  | Medical Appointment Booking                          | Intermediate   | ⏳ Planned  | Doctor search, slot selection, confirmation, advanced form styling with SASS                                          |
| 46  | Stock Market Portfolio Tracker UI                    | Intermediate   | ⏳ Planned  | Portfolio allocation pie (CSS), CSS clip-path + SASS variables                                                        |
| 47  | Travel Booking Platform                              | Intermediate   | ⏳ Planned  | Flight/hotel search with results grid, multi-filter system with Bootstrap                                             |
| 48  | Blog Platform with Reading Mode                      | Intermediate   | ⏳ Planned  | Article page + related posts, typography system in SASS                                                               |
| 49  | E-learning Quiz Platform                             | Intermediate   | ⏳ Planned  | Timed quiz with score tracking, progress tracking with Bootstrap + SASS                                               |
| 50  | Non-Profit Organization Website                      | Intermediate   | ⏳ Planned  | Full multi-page with donation flow, complete SASS architecture + Bootstrap overrides                                  |

**Intermediate Projects (26–50) completed on Day 50**  
**Advanced Projects start on Day 51**

| Day | Project / Topic                                      | Level          | Status       | Key Learnings / Deliverables                                                                                          |
|-----|------------------------------------------------------|----------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
| 51  | 3D Product Configurator UI                           | Advanced       | ⏳ Planned  | Car/sneaker customizer with perspective CSS + SASS, advanced SASS 3D transforms + light Three.js integration          |
| 52  | Neumorphic/Frosted Glass Admin Dashboard             | Advanced       | ⏳ Planned  | Full theme with SASS variables, glassmorphism using backdrop-filter + custom Bootstrap                                |
| 53  | Interactive 3D Portfolio Website                     | Advanced       | ⏳ Planned  | Card tilt effects (Vanilla-tilt) + scroll animations, GSAP + Bootstrap + advanced SASS mixins                         |
| 54  | AI SaaS Landing Page with Parallax                   | Advanced       | ⏳ Planned  | Multi-layer parallax + animated stats, full custom Bootstrap theme + SASS functions                                   |
| 55  | Fintech Banking App (Full Flow)                      | Advanced       | ⏳ Planned  | Dashboard + transfer + cards management, complex state simulation + dark/light mode                                   |
| 56  | Virtual Reality Experience Landing (2D/3D hybrid)    | Advanced       | ⏳ Planned  | Immersive hero with CSS 3D, Bootstrap + SASS 3D scenes                                                                |
| 57  | Advanced E-commerce Store                            | Advanced       | ⏳ Planned  | Cart, wishlist, filters, product zoom (lens effect), micro-interactions with SASS + Bootstrap                         |
| 58  | 3D Isometric Dashboard                               | Advanced       | ⏳ Planned  | Isometric grid layout for analytics, CSS isometric transforms + Bootstrap components                                  |
| 59  | Creative Agency Portfolio with Horizontal Scroll     | Advanced       | ⏳ Planned  | Full-screen sections, Locomotive Scroll or GSAP + custom SASS                                                         |
| 60  | Health & Fitness SaaS Platform                       | Advanced       | ⏳ Planned  | Personalized dashboard with charts (Chart.js), data visualization + Bootstrap + SASS                                  |
| 61  | Metaverse Landing Page                               | Advanced       | ⏳ Planned  | 3D hero + NFT gallery with hover 3D tilt, Bootstrap 5 + advanced SASS + CSS perspective                               |
| 62  | Enterprise HR Management UI                          | Advanced       | ⏳ Planned  | Employee directory, leave management, analytics, role-based UI simulation + complex tables                            |
| 63  | Real-time Collaboration Tool UI (Notion-like)        | Advanced       | ⏳ Planned  | Editable blocks, contenteditable + SASS styling                                                                       |
| 64  | Luxury Watch E-commerce                              | Advanced       | ⏳ Planned  | 360° product view simulation + configurator, advanced image handling + SASS animations                                |
| 65  | Climate Change Awareness Platform                    | Advanced       | ⏳ Planned  | Interactive globe (CSS 3D) + data viz, Bootstrap + SASS + minimal Three.js                                            |
| 66  | Gaming Portal Dashboard                              | Advanced       | ⏳ Planned  | Leaderboard, tournaments, profile with neon effects, cyberpunk theme with SASS                                        |
| 67  | Telemedicine Platform                                | Advanced       | ⏳ Planned  | Video call UI simulation + patient records, full responsive + accessibility focus                                     |
| 68  | Smart City Dashboard                                 | Advanced       | ⏳ Planned  | 3D map placeholder + live stats, CSS 3D city blocks + Bootstrap                                                       |
| 69  | Fashion Lookbook with 3D Model Viewer Placeholder    | Advanced       | ⏳ Planned  | Outfit builder, layered 3D CSS + SASS variables                                                                       |
| 70  | Crypto NFT Marketplace                               | Advanced       | ⏳ Planned  | Collection grid, detail page, bidding system, glassmorphism + advanced filters                                        |
| 71  | AI-Powered Resume Builder                            | Advanced       | ⏳ Planned  | Drag-drop sections with live preview, SortableJS + custom SASS components                                             |
| 72  | Immersive Storytelling Website                       | Advanced       | ⏳ Planned  | Scroll-driven 2D/3D narrative, GSAP ScrollTrigger + Bootstrap + SASS                                                  |
| 73  | Enterprise Analytics Platform                        | Advanced       | ⏳ Planned  | Multiple dashboards with dark theme, reusable component library in SASS                                               |
| 74  | Architecture Firm Portfolio                          | Advanced       | ⏳ Planned  | 3D building walkthrough simulation (CSS), advanced perspective + Bootstrap navigation                                 |
| 75  | Future-Tech Product Launch Page                      | Advanced       | ⏳ Planned  | Full 3D hero + interactive specs, complete professional SASS + Bootstrap ecosystem                                    |

**Advanced Projects (51–75) completed on Day 75**  
**Professional / Real-World Demos start on Day 76**

| Day | Project / Topic                                      | Level          | Status       | Key Learnings / Deliverables                                                                                          |
|-----|------------------------------------------------------|----------------|--------------|-----------------------------------------------------------------------------------------------------------------------|
| 76  | Full SaaS Product Website + Dashboard                | Professional   | ⏳ Planned  | Landing + authenticated dashboard (simulation), Figma → SASS/Bootstrap → GitHub repo with issues & PRs                |
| 77  | Complete E-commerce Platform                         | Professional   | ⏳ Planned  | Shop, cart, checkout, user account (multi-page), full cart flow + payment UI                                          |
| 78  | Modern Digital Agency Portfolio                      | Professional   | ⏳ Planned  | Services, case studies, contact with form validation, Bootstrap + custom 7-1 SASS + GSAP                              |
| 79  | Fintech Neo-Bank Full UI                             | Professional   | ⏳ Planned  | All screens: login, dashboard, cards, transfers, investments, professional README with screenshots & live demo link   |
| 80  | Educational LMS Platform                             | Professional   | ⏳ Planned  | Student & instructor dashboards, course pages, role-based design system                                               |
| 81  | Travel & Booking Engine                              | Professional   | ⏳ Planned  | Flights, hotels, tours with advanced search, responsive across all devices + PWA ready                                 |
| 82  | HealthTech Patient Portal                            | Professional   | ⏳ Planned  | Records, appointments, teleconsult UI, HIPAA-style clean & accessible design                                          |
| 83  | Creative Studio Website with 3D Interactions         | Professional   | ⏳ Planned  | Case studies in 3D cards, Bootstrap + SASS + CSS 3D + Scroll animations                                               |
| 84  | NFT & Web3 Marketplace Full Demo                     | Professional   | ⏳ Planned  | Explore, create, profile, wallet connect UI, dark theme + glassmorphism                                               |
| 85  | Enterprise Corporate Dashboard                       | Professional   | ⏳ Planned  | Analytics, team, projects, reports, component library + design tokens in SASS                                         |
| 86  | Luxury Real Estate Platform                          | Professional   | ⏳ Planned  | Property search, virtual tours (placeholder), booking, high-end animations + professional typography                  |
| 87  | Fitness & Wellness App Full Suite                    | Professional   | ⏳ Planned  | Workouts, nutrition, community feed, progress tracking + social features UI                                           |
| 88  | News & Magazine Platform                             | Professional   | ⏳ Planned  | Editor’s pick, categories, live updates simulation, mega menu + infinite scroll                                       |
| 89  | AI Startup Landing + Tool Dashboard                  | Professional   | ⏳ Planned  | Product pages + interactive AI demo UI, advanced SASS architecture                                                    |
| 90  | Gaming Esports Portal                                | Professional   | ⏳ Planned  | Tournaments, live streams UI, player profiles, neon + gradient heavy SASS                                             |
| 91  | Sustainability & Climate Platform                    | Professional   | ⏳ Planned  | Impact calculator + interactive maps, 2D/3D data visualization                                                        |
| 92  | Freelance Marketplace Full UI                        | Professional   | ⏳ Planned  | Post gig, browse gigs, messaging simulation, multi-user role design                                                   |
| 93  | Medical & Hospital Management System UI              | Professional   | ⏳ Planned  | Patient, doctor, admin panels, accessibility AA compliant                                                             |
| 94  | Music & Podcast Platform                             | Professional   | ⏳ Planned  | Library, player, artist pages, playlists, bottom navigation + immersive player                                        |
| 95  | Smart Home IoT Dashboard                             | Professional   | ⏳ Planned  | Device control with 3D room view simulation, Bootstrap + advanced CSS 3D                                              |
| 96  | Online Banking & Finance Portal                      | Professional   | ⏳ Planned  | Complete user journey, security-focused clean UI                                                                      |
| 97  | Architecture & Interior Design Portfolio             | Professional   | ⏳ Planned  | 3D project showcases, project filtering + lightbox                                                                    |
| 98  | E-learning Academy with Certification Flow           | Professional   | ⏳ Planned  | Full student experience, progress tracking + certificate preview                                                      |
| 99  | Metaverse / Web3 Landing + Dashboard                 | Professional   | ⏳ Planned  | Immersive hero + user hub, 3D CSS + Bootstrap hybrid                                                                  |
| 100 | Personal Brand / Developer Portfolio Pro             | Professional   | ⏳ Planned  | 3D hero, projects with case studies, blog, contact form + resume download (central live website with backend)          |

**All 100 demos completed on Day 100**

**Note**: Full detailed daily progress with screenshots, Figma links, challenges, and GitHub folder references is available in the [`docs/progress/`](docs/progress/) folder.

---

## Table of Progress

| Level          | Demos | Focus                                      | Status         |
|----------------|-------|--------------------------------------------|----------------|
| **Beginner**   | 1–25  | Core SASS + Bootstrap                      | ⏳ Planned     |
| **Intermediate**| 26–50 | Advanced SASS + interactivity              | ⏳ Planned     |
| **Advanced**   | 51–75 | 2D/3D + GSAP + performance                 | ⏳ Planned     |
| **Professional**| 76–100| Full apps + Demo-100 live website          | ⏳ Planned     |

Detailed per-demo docs → [docs/progress/](docs/progress/)

---

## Backend & Deployment Strategy

All demos 1–99 → **100% frontend** with mock data.  
Only **Demo-100** gets real backend so it becomes your professional live portfolio website.

**Chosen Options (2026)**:

- **Primary Recommendation**: **Supabase** (PostgreSQL + Auth + Storage + Realtime) – fast setup, generous free tier.
- **Alternative (Zero cloud)**: **PocketBase** – single executable binary, full control, SQLite.

Both integrate with **~10 lines of code** in the contact form and demo tracking.

**Deployment** (one-command focus on frontend):

- Frontend (Demo-100) → **Vercel** (free, instant previews)
- Supabase → Hosted dashboard (2-minute setup)
- PocketBase → Render / Railway free tier or local binary

This saves weeks — you maintain **one live site** while the entire 100-demo collection lives in one repo.

---

## Getting Started

```bash
git clone https://github.com/OdeToTheWind/frontend-engineering-sass-bootstrap.git
cd frontend-engineering-sass-bootstrap
npm install
```
## Run any demo (example: central portfolio):
```bash
cd src/professional/demo-100-developer-portfolio-pro/frontend
npm run dev
```
## Build for production:
```bash
npm run build
```
---


## Demo-100 – Ultimate Developer Portfolio Pro (Capstone)

**Features**:

- 3D interactive hero (CSS 3D + Three.js skills globe)
- Interactive gallery of all 100 demos with live links
- Case studies with Figma + code + learnings
- Blog section + contact form (real backend)
- Resume live preview + download tracking
- Dark/light mode + theme switcher
- Lighthouse 100/100, PWA-ready

**Backend Integration**:

- Contact form saves to database
- Optional simple auth for protected section
- Demo view counter (optional analytics)

See detailed files in `src/professional/demo-100-developer-portfolio-pro/` (Supabase + PocketBase folders included).

## Key Features & Engineering Practices

- 7-1 SASS architecture + custom Bootstrap theme
- Mobile-first, dark/light mode, accessibility-first
- 2D/3D effects (CSS perspective, GSAP, light Three.js)
- Component library shared across advanced demos
- GitHub Actions CI/CD + Lighthouse checks
- Figma traceability for every demo
- Professional READMEs, conventional commits, PR templates


## Contributing
This is a personal challenge repository, but issues, suggestions, and thoughtful discussions are welcome.


## License

MIT License – see [LICENSE](LICENSE). You may use any demo in your portfolio (credit appreciated).

**Built with ❤️ in Bengaluru** by **respin**
