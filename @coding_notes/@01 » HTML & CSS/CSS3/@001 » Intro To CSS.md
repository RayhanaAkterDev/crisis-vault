# 📄 Topic: Intro to CSS

- **CSS** » _Cascading Style Sheets_    
- Adds **style** (colors, layouts, spacing, etc.) to HTML elements    
- Not a programming language — a **style sheet language**    

---

## 🔍 Key Tags & Purpose

- `style=""` → **Inline CSS**: applied directly in the HTML tag    
- `<style>` → **Internal CSS**: placed inside `<head>`    
- `<link rel="stylesheet">` → **External CSS**: links to `.css` file    
- `selector { property: value; }` → Basic CSS syntax    
    - `h1 { color: red; }` – Makes all `<h1>` text red

---

🔗 **Practice code**: https://github.com/RayhanaAkterDev/Frontend-Bootcamp/blob/07e2742f76b9da9aa0a396d22e95b1d731f648f4/01-html-css/02-css/css-demos/01-intro-to-css.html

```html
<!-- Inline Example -->
<h2 style="color: green;">Inline Styled Heading</h2>

<!-- Internal Example -->
<style>
  .box {
    border: 1px solid #aaa;
    padding: 10px;
  }
</style>

<!-- External Example -->
<link rel="stylesheet" href="../stylesheets/01-intro-to-css.css" />
```

---

> 🧠 _Tip: Start with internal and inline CSS for experiments, then use external CSS for real projects._
