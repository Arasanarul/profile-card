# User Profile Card

A small, beginner-friendly project that builds a simple **User Profile Card** using plain HTML and CSS. You created this while learning basic layout and styling concepts.

---

## 🔎 Project Overview

This project displays a centered profile card with:

* Profile image
* Name, role, and company
* Social/emoji line
* A small contact header

It's a good exercise to practice layout, inline-block elements, and basic styling rules.

---

## 📁 Project Structure

```
user-profile-card/
├── index.html      # Profile card markup
├── style.css       # Simple styles for layout and appearance
└── README.md       # This file
```

---

## ▶️ How to run

1. Save `index.html` and `style.css` in the same folder.
2. Open `index.html` in any web browser (Chrome, Firefox, Edge, etc.).

No build tools or server required — it runs directly in the browser.

---

## 🛠 What you used / learned

* Basic HTML structure (`<img>`, headings, paragraphs)
* Linking an external stylesheet (`<link rel="stylesheet">`)
* Simple CSS selectors and properties (`background-color`, `display`, `width`, `height`)
* Using `display: inline-block` to create a centered card

---

## ✅ Suggestions & Next Steps

Here are a few small improvements you can try to make the card more polished and robust:

* **Make it responsive**: use `max-width` instead of fixed `width`, and add padding so the card looks good on small screens.
* **Improve accessibility**: add descriptive `alt` text to the image (e.g. `alt="Profile photo of Virat Kohli"`).
* **Replace external image URL**: download the image to an `img/` folder and reference `img/filename.jpg` so the card still works offline.
* **Use semantic HTML**: wrap the card in an `<article>` or `<section>` and use `<header>` for the heading area.
* **Add simple styling**: center content with Flexbox, add `border-radius` for rounded corners, and `box-shadow` for depth.
* **Add contact links**: change the contact heading to include clickable `mailto:` and phone links.

Example quick CSS tweaks you can try in `style.css`:

```css
body{
  display:flex;
  align-items:center;
  justify-content:center;
  min-height:100vh;
  background: linear-gradient(135deg,#2ecc71,#27ae60);
}
.one{
  max-width:320px;
  padding:20px;
  background:#fff;
  border-radius:12px;
  box-shadow:0 8px 24px rgba(0,0,0,0.15);
  text-align:center;
}
.one img{
  width:120px;
  height:120px;
  border-radius:50%;
  object-fit:cover;
}
```

---

## 📝 Credits

Created by you while learning HTML and CSS. If you want, I can:

* Convert this into a responsive component
* Add CSS variables and comments
* Make a reusable component (HTML + CSS) you can copy into other projects

---
