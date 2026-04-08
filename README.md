# Personal Portfolio

A clean, minimal, and responsive personal portfolio website built with pure **HTML, CSS, and JavaScript**. Designed to showcase my projects, skills, and experience as an aspiring Software Developer.

---

## 🌐 Live Demo
(https://codeheaveportfolio.netlify.app/)

---

## ✨ Features

- **Responsive Design** — Works seamlessly on desktop, tablet, and mobile
- **Smooth Scroll Navigation** — Active nav link highlights based on current section
- **Scroll Reveal Animations** — Sections fade in as you scroll down
- **Contact Form** — Functional email form powered by [EmailJS](https://www.emailjs.com/)
- **Project Showcase** — Clickable project cards linking to live demos
- **Clean Minimal UI** — Editorial-style typography with IBM Plex Sans & Playfair Display

---

## 📁 Project Structure

```
portfolio/
├── index.html       # Main HTML file (entire site)
├── favicon.png      # Website tab icon
├── Email.gif        # Email icon used in contact section
├── linkedin.gif     # LinkedIn icon used in contact section
├── caution.gif      # Warning icon for form validation
└── README.md        # Project documentation
```

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Structure & semantic markup |
| CSS3 | Styling, layout, animations |
| JavaScript (ES6+) | Interactivity, scroll effects |
| EmailJS | Contact form email delivery |
| Google Fonts | Typography (Playfair Display, IBM Plex Sans, IBM Plex Mono) |

---

## 📬 Contact Form Setup (EmailJS)

The contact form uses EmailJS to send messages directly to your inbox without a backend.

1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Create a **Service** and **Email Template**
3. Replace the following values in `index.html`:

```js
emailjs.init("YOUR_PUBLIC_KEY");

emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", { ... });
```

---

## 🚀 Getting Started

No build tools or dependencies needed. Just open the file:

```bash
# Clone the repository
git clone https://github.com/Maynkbisht/your-portfolio-repo.git

# Open in browser
open index.html
```

Or simply drag and drop `index.html` into your browser.

---

## 📌 Sections

| # | Section | Description |
|---|---|---|
| 01 | About | Brief intro, location, education, focus areas |
| 02 | Projects | Featured projects with links to live demos |
| 03 | Skills & Tools | Languages, frontend frameworks, tools |
| 04 | Experience | Self-learning, LeetCode, and education |
| 05 | Contact | Email form + social links |

---

## 🔗 Connect

- 📧 Email: [ibishtmayank@gmail.com](mailto:ibishtmayank@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/mayank-bisht-405a30376](https://www.linkedin.com/in/mayank-bisht-405a30376/)
- 🐙 GitHub: [github.com/Maynkbisht](https://github.com/Maynkbisht)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with focus, discipline, and continuous learning. — Mayank Bisht
