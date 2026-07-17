# TechNova Solutions — Mini Web Development Project

A responsive, multi-page business website built with **HTML5, CSS3, JavaScript (ES6) and Bootstrap 5**, developed as a mini project for a **15-day B.Tech Information Technology internship**.

🔗 **Live Demo:** _add your GitHub Pages URL here after enabling Pages — e.g. `https://tamil67426-a11y.github.io/New-project-/`_

---

## ✨ Features

- Fully responsive layout (mobile, tablet, desktop)
- Sticky, collapsible navigation bar with active-link highlighting
- Hero section with an animated "terminal" signature element
- Home, About, Services and Contact pages
- Testimonial slider (auto-play + manual controls)
- FAQ accordion (vanilla JavaScript, no dependencies)
- Dark mode / light mode toggle with OS-preference detection
- Scroll-triggered reveal animations (`IntersectionObserver`)
- Client-side contact form validation (name, email, phone, message)
- Clean folder structure separating HTML, CSS, JS and documentation

## 🛠️ Built With

- HTML5
- CSS3 (custom properties, Flexbox, Grid)
- JavaScript (ES6, vanilla — no frameworks)
- [Bootstrap 5.3](https://getbootstrap.com/) (CDN)
- Google Fonts — Space Grotesk, Inter, JetBrains Mono

## 📁 Folder Structure

```
New-project-/
├── index.html
├── about.html
├── services.html
├── contact.html
├── README.md
├── css/
│   └── style.css
├── js/
│   └── script.js
└── docs/
    └── DOCUMENTATION.md   # Abstract, objectives, module description, testing, etc.
```

## 🚀 Getting Started

### Run locally
1. Clone the repository:
   ```bash
   git clone https://github.com/tamil67426-a11y/New-project-.git
   cd New-project-
   ```
2. Open `index.html` directly in your browser, **or** serve it with a local server (recommended, e.g. VS Code "Live Server" extension) so relative paths behave exactly as they will in production.

### Deploy with GitHub Pages
1. Push this project to the `main` branch of the repository.
2. Go to **Settings → Pages** on GitHub.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. GitHub will publish the site at:
   `https://tamil67426-a11y.github.io/New-project-/`
5. It can take 1–2 minutes for the first deployment to go live.

## 📖 Documentation

Full project write-up — abstract, objectives, problem statement, existing/proposed system, software & hardware requirements, module description, testing table, future enhancements and conclusion — is available in [`docs/DOCUMENTATION.md`](docs/DOCUMENTATION.md).

## 🧪 Testing

Manually tested across Chrome, Edge and Firefox at breakpoints from 360px to 1440px. See the testing table in the documentation for the full test matrix.

## 🔮 Future Enhancements

- Backend integration for the contact form (email service / API)
- Blog or portfolio module with dynamic content
- Multilingual support
- Automated testing (Jest) and CI/CD (GitHub Actions)

## 📄 License

This project is built for academic/demonstration purposes as part of a B.Tech IT internship.

---
*Developed as a 15-day internship deliverable.*
