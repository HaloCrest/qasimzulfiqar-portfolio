# Qasim Zulfiqar – Developer Portfolio

A clean, dynamic, and fully responsive personal developer portfolio built using HTML, CSS, and JavaScript. This project showcases an interactive single-page layout that includes a dynamic hero section, animated background elements, skill highlights, project previews, and a fully functional contact form powered by EmailJS and secured with reCAPTCHA v3.

---

## ✨ Features

- **Dynamic Hero Section**: Includes typing animation with role switching.
- **Geometric Animated Background**: Custom CSS-based animations (triangles, hexagons, zigzags, cubes, and parallax effects).
- **Smooth Section Navigation**: Scroll-based animations and auto-highlighted nav links.
- **About and Skills Section**: Structured overview of expertise and interests.
- **Projects Showcase**: Displays project cards with smooth slider/transition.
- **Responsive Contact Form**:
  - Field validation (name, email, message)
  - Error and success handling via closable dialog popups
  - Email delivery using EmailJS
  - Spam protection via Google reCAPTCHA v3

---

## 🧱 Built With

- **HTML5** – Semantic layout structure
- **CSS3** – Custom styles, animations, media queries
- **JavaScript (Vanilla)** – Interactivity, validation, effects
- **EmailJS** – Client-side email integration
- **Google reCAPTCHA v3** – Bot/spam protection
- **Intersection Observer API** – Scroll-based animations
- **Flexbox/Grid** – Responsive layout techniques

---

## 🛠 Functional Highlights

- **Typing Effect**: Reusable typing loop with custom text array.
- **Scroll Animation**: Elements become visible with `IntersectionObserver`.
- **Contact Form Logic**:
  - Real-time and on-submit validation
  - Email sending via EmailJS (with `serviceID`, `templateID`, and public key)
  - Google reCAPTCHA token verification before submission
  - Dialog-based notification system with timed close
- **Fully Responsive**: Optimized for all screen sizes and devices.

---

## 🔐 Security Notes

- Email form submissions are protected via:
  - Input validation (length, format)
  - Google reCAPTCHA v3 (`grecaptcha.execute`)
- No sensitive keys are stored in the frontend code. Public EmailJS keys are used appropriately.

---

## 📌 Usage

1. Clone the repository
2. Add your EmailJS service/template/public key in `main.js`
3. Add your Google reCAPTCHA v3 site key in the appropriate place
4. Customize content (projects, skills, text) in `index.html`
5. Run locally or deploy via GitHub Pages, Netlify, or Vercel

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Designed with precision and performance in mind – for developers who care about both form and function.
