# CSS-learing

# 🎨 CSS (Cascading Style Sheets) Introduction

CSS (Cascading Style Sheets) is used to style and layout web pages — for example, to change the font, color, size, and spacing of your content, split it into multiple columns, or add animations and responsive design.

## 📌 Why Use CSS?

- Separate content from design
- Make websites look beautiful
- Improve user experience (UX)
- Responsive for mobile and tablet devices

## 🧠 Types of CSS

1. **Inline CSS** – Written inside an HTML tag  
2. **Internal CSS** – Written inside `<style>` tag within HTML file  
3. **External CSS** – Written in a separate `.css` file and linked to HTML

## 🔤 CSS Syntax Example

css


selector {
  property: value;
}


| Property     | Description                    |
| ------------ | ------------------------------ |
| `color`      | Text color                     |
| `background` | Background color or image      |
| `margin`     | Space outside element          |
| `padding`    | Space inside element           |
| `border`     | Border around element          |
| `font-size`  | Size of the text               |
| `display`    | Layout behavior (block, flex…) |



Media Query Example:

@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
}

