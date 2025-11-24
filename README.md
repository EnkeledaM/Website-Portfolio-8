# Portfolio Exercise 1.8 – CSS Preprocessors, CSS Variables & SCSS

Overview
This project was created as part of the **CareerFoundry Intro to Software Engineering** course, Exercise **1.8**.  
The goal of this exercise was to practice using **SCSS preprocessors**, understand the difference between **preprocessors** and **postprocessors**, and implement **CSS variables** in a real portfolio project.


## 🧩 Part 1 – SCSS Practice (CodePen)
In this step, I converted the provided CSS into **SCSS**, applying the required features:

- SCSS **variables** for colors and spacing  
- Color functions **`darken()`** and **`lighten()`**  
- **Nesting** to create cleaner CSS structure  
- **`@extend`** using a shared placeholder selector  
- Nested **`:hover`** state to remove the box-shadow on hover  

**SCSS CodePen link:**  
https://codepen.io/EnkeledaM/pen/empxooX


## 🖥️ Part 2 – Portfolio Project with CSS Variables
In my portfolio, I replaced all repeated values with **CSS custom properties** and created a full production workflow.

### Implemented:
1. Added CSS variables (`--primary`, `--secondary`, `--text`, etc.) in `styles.css`.  
2. Replaced all repeated colors, spacing, radii, fonts, and shadows with variables.  
3. Used **Autoprefixer / PostCSS** to generate a browser-compatible stylesheet.  
4. Created **style.production.css** and linked it in all HTML files.  
5. Verified correct display of `logo.png` and `avatar.jpg`.  
6. Added **8 responsive project cards** on the Work page.

## ⭐ Bonus Task 1 – Form Validation (Portfolio Website)
As part of Bonus Task 1, I implemented **custom JavaScript form validation** in my `contact.html` page.

The validation includes:
- Checking required fields (name, email, message)  
- Validating email format with RegEx  
- Showing inline error messages  
- Removing errors once the input becomes valid  

Files included:
- `portfolio-8/contact.html`  
- `portfolio-8/js/contact-validation.js`

## Key Learnings
- How to use SCSS to create more maintainable and modular styles  
- The difference between **preprocessors** (SCSS) and **postprocessors** (Autoprefixer)  
- When to use CSS variables vs. SCSS variables  
- How to build a **production-ready CSS workflow**  
- Implementing real **form validation** with JavaScript  

## Deliverables
- SCSS CodePen: https://codepen.io/EnkeledaM/pen/empxooX  
- Full project ZIP  
- Portfolio pages styled with variables and production CSS  
- JS form validation (Bonus Task 1)

---

** CareerFoundry – Intro to Software Engineering (Exercise 1.8)  

