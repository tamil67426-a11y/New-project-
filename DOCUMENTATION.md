# TechNova Solutions — Project Documentation

**B.Tech Information Technology — 15-Day Internship Mini Project**

---

## 1. Abstract

This mini project presents **TechNova Solutions**, a responsive multi-page business website developed to demonstrate practical front-end web development skills acquired during a 15-day Information Technology internship. The website is built using HTML5, CSS3, JavaScript (ES6), and the Bootstrap 5 framework. It includes a responsive navigation bar, a hero section, service listings, a testimonial slider, an FAQ accordion, dark/light theme switching, scroll-triggered animations, and a fully validated contact form — all implemented without any backend or external dependencies beyond CDN-hosted fonts and Bootstrap. The project follows a clean, modular folder structure suitable for version control with Git and deployment via GitHub Pages.

## 2. Objectives

1. Design and build a fully responsive website using HTML5, CSS3 and Bootstrap 5.
2. Implement JavaScript-based interactivity: form validation, scroll animation, image/testimonial slider, dark mode, and FAQ accordion.
3. Maintain clean, well-commented, and logically organised code across separate HTML, CSS and JS files.
4. Apply real-world UI/UX patterns — sticky navigation, hero sections, card layouts, pricing tables, and footers.
5. Use Git for version control with meaningful, incremental commit messages.
6. Deploy the finished project as a live website using GitHub Pages.

## 3. Problem Statement

Many student and small-business websites remain static single pages that are not responsive, lack interactive feedback, and mix structure/style/behaviour in a single file. This makes them difficult to maintain, unfriendly on mobile devices, and a poor demonstration of modern front-end practice. There is a need for a compact, well-structured reference website that a B.Tech IT student can build within a short internship timeframe while covering the essential concepts examined in a viva: responsive layout, DOM scripting, form validation, and deployment.

## 4. Existing System

Typical existing/example systems used in similar student projects show these limitations:

- Single static HTML page with inline or embedded CSS, no separation of concerns.
- No responsive breakpoints — layout breaks or requires horizontal scrolling on mobile.
- No client-side form validation; forms either don't work or submit without any checks.
- No visual feedback for user interactions (no hover states, no animations).
- No version control history — a single uploaded ZIP file rather than a tracked Git project.
- No live deployment; the project can only be viewed locally.

## 5. Proposed System

The proposed system addresses each limitation above:

| Existing System Gap | Proposed System Solution |
|---|---|
| No separation of concerns | Dedicated `css/style.css` and `js/script.js` files, semantic HTML |
| Not responsive | Mobile-first CSS with Flexbox/Grid + Bootstrap 5 grid utilities |
| No form validation | Real-time client-side validation with regex and inline error messages |
| No interactivity | Scroll-reveal animation, testimonial slider, FAQ accordion, dark mode |
| No version control | Git repository with feature-based, meaningful commits |
| No deployment | Hosted live via GitHub Pages with a public URL |

## 6. Software Requirements

| Component | Requirement |
|---|---|
| Operating System | Windows 10/11, macOS, or Linux (any) |
| Code Editor | Visual Studio Code (recommended) |
| Browser | Google Chrome / Microsoft Edge / Firefox (latest version) |
| Version Control | Git 2.x, GitHub account |
| Framework/Library | Bootstrap 5.3 (via CDN) |
| Fonts | Google Fonts — Space Grotesk, Inter, JetBrains Mono (via CDN) |
| Optional Tooling | Live Server extension (VS Code) for local preview |

## 7. Hardware Requirements

| Component | Minimum Specification |
|---|---|
| Processor | Dual-core 1.6 GHz or higher |
| RAM | 4 GB (8 GB recommended) |
| Storage | 500 MB free disk space |
| Display | 1024×768 resolution or higher |
| Internet | Required for CDN assets (Bootstrap, fonts) and GitHub push/deploy |

## 8. Module Description

**Module 1 — Navigation & Layout**
Sticky responsive navbar with a hamburger menu on mobile, active-link highlighting, and a shared footer across all pages.

**Module 2 — Home Page**
Hero section with an animated terminal illustration, service preview cards, a stats band, a "why choose us" timeline, and an embedded testimonial slider.

**Module 3 — About Page**
Presents the project's abstract, problem statement, existing system, proposed system, objectives, and a sample team-structure section — doubling as in-page documentation.

**Module 4 — Services Page**
Service cards, a three-tier sample pricing table, and an FAQ accordion built with vanilla JavaScript (no Bootstrap JS accordion dependency).

**Module 5 — Contact Page**
A contact form with real-time client-side validation for name, email, phone and message fields, including success/error status banners.

**Module 6 — Theme Engine**
A dark/light mode toggle implemented with CSS custom properties (`data-theme` attribute) and OS-preference detection via `prefers-color-scheme`.

**Module 7 — Scroll Animation**
An `IntersectionObserver`-based reveal system (`.reveal` / `.in-view` classes) that fades and lifts sections into view as the user scrolls.

## 9. Folder Structure

```
New-project-/
├── index.html              # Home page
├── about.html               # About page (also contains abstract/objectives content)
├── services.html            # Services page
├── contact.html              # Contact page with validated form
├── README.md                 # Project overview & setup instructions
├── css/
│   └── style.css             # All custom styles, design tokens, responsive rules
├── js/
│   └── script.js              # Navigation, dark mode, slider, accordion, validation, animation
└── docs/
    └── DOCUMENTATION.md       # This file — full internship documentation
```

## 10. Testing

Manual testing was carried out for the following cases:

| Test Case | Steps | Expected Result | Status |
|---|---|---|---|
| Responsive layout | Resize viewport from 1440px → 360px | Layout reflows without overlap or horizontal scroll | Pass |
| Navigation menu (mobile) | Click hamburger icon on small screen | Menu opens/closes, links navigate correctly | Pass |
| Dark mode toggle | Click theme icon in navbar | Colors switch instantly across the whole page | Pass |
| Scroll animation | Scroll down any page | Sections fade/slide into view once in viewport | Pass |
| Testimonial slider | Click next/prev arrows and dots | Slide transitions smoothly, dot state updates | Pass |
| FAQ accordion | Click a question on Services page | Panel expands, others collapse | Pass |
| Empty form submit | Submit contact form with all fields blank | All required fields show inline error messages | Pass |
| Invalid email | Enter `abc@` and submit | Email field shows "valid email address" error | Pass |
| Valid form submit | Fill all fields correctly and submit | Success banner shown, form resets | Pass |
| Cross-browser check | Open site in Chrome, Edge, Firefox | Consistent appearance and behaviour | Pass |

## 11. Future Enhancements

- Connect the contact form to a real backend (Node.js/PHP + email service or a form API such as Formspree).
- Add a blog/portfolio module with dynamic content loaded from a JSON file or headless CMS.
- Introduce multilingual support (English/Tamil) using a simple JS i18n layer.
- Add unit tests for the validation logic using Jest.
- Integrate a CI/CD workflow (GitHub Actions) for automatic linting and deployment.
- Replace placeholder pricing/team data with real client-provided content when adapted for production use.

## 12. Conclusion

The TechNova Solutions mini project successfully demonstrates the core competencies expected from a B.Tech Information Technology front-end internship: responsive design, DOM-driven interactivity, form validation, and a clean, deployable project structure. Built entirely with HTML, CSS, JavaScript and Bootstrap over a 15-day timeline, it is structured to be easy to explain feature-by-feature in a viva, with each module directly traceable to a specific file, function, or CSS component.

---
*Prepared as part of a 15-day B.Tech IT internship deliverable.*
