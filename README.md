# 🎨 CSS– From Basics to Advanced

Welcome to the **CSS Learning Repository**!  
This guide is designed to take you from beginner to pro in CSS (Cascading Style Sheets), the language that gives life to your HTML.

---

## 🧩 Section 1: CSS Basics

### 🖋️ What is CSS?

CSS (Cascading Style Sheets) is a stylesheet language used to describe the **presentation of a web page** written in HTML. It controls colors, fonts, layouts, spacing, responsiveness, and even animations.

### 📦 Types of CSS

| Type         | Description                                      | Example                     |
|--------------|--------------------------------------------------|-----------------------------|
| Inline CSS   | Inside HTML tags using `style=""`                | `<h1 style="color:red">`    |
| Internal CSS | Inside `<style>` tags in HTML `<head>`          | `<style>p {color: blue;}</style>` |
| External CSS | In separate `.css` file linked via `<link>` tag | `<link rel="stylesheet" href="style.css">` |

---

### 📚 Basic Syntax

selector {
  property: value;
}

h1 {
  color: blue;
  font-size: 32px;
}


🎯 Common Properties

| Property     | Use                                         |
| ------------ | ------------------------------------------- |
| `color`      | Text color                                  |
| `background` | Background color or image                   |
| `font-size`  | Size of the text                            |
| `margin`     | Space outside an element                    |
| `padding`    | Space inside an element                     |
| `border`     | Border styling                              |
| `text-align` | Align text (left, center, right)            |
| `display`    | Layout behavior (block, inline, flex, grid) |


🧠 Selectors in CSS

| Selector  | Usage                                 |
| --------- | ------------------------------------- |
| `*`       | Selects all elements                  |
| `p`       | Selects all `<p>` tags                |
| `.class`  | Selects elements with class           |
| `#id`     | Selects element with specific ID      |
| `div > p` | Selects `<p>` directly inside `<div>` |


Advanced CSS Concepts


📱 Responsive Web Design--

@media (max-width: 768px) {
  body {
    font-size: 14px;
    background: #eee;
  }
}

💠 Flexbox--

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}


🔳 CSS Grid--

@keyframes slideIn {
  from { transform: translateX(-100%); }
  to { transform: translateX(0); }
}

.box {
  animation: slideIn 1s ease-in-out;
}


🛡️ Best Practices for Writing CSS
Use external CSS for scalability.

Name classes seantically (.btn-primary, .header, etc.)
Follow DRY principle: Don’t Repeat Yourself.
Use variables with preprocessors like SCSS if needed.
Group related styles together.



🧭 Learning Resources


MDN Web Docs – CSS
W3Schools – CSS
Flexbox Froggy Game
CSS Grid Garden Game


🙌 Author
Made with ❤️ by Abhijeet Ghosh
Beginner-friendly | Clean code | Real-world examples
