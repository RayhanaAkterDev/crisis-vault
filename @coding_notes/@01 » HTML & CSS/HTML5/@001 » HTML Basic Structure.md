# 📄 Topic: HTML Basic Structure

- HTML » _Hypertext Markup Language_.
- Used to build structure/layout (*not logic or behavior*) of web pages.
- Not a programming language — but a **markup** language.

---

## 🔍 Key Tags & Purpose

- `<!DOCTYPE html>` → Declares document type — HTML5 version.
- `<html>` → Root container of the document.
	- `<html lang="en">` - Sets page language (here, English).
- `<head>` → Metadata *(like title, character encoding, and viewport settings)* not visible on page
- `<meta>` → Encoding + responsiveness
	- `<meta charset="UTF-8">` – Ensures proper character display.   
	- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` – Makes the layout responsive on mobile devices.
- `<title>` → Title in browser tab.
- `<body>` → Visible page content.
  
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Metadata section -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Structure of HTML Document</title>
  </head>
  <body>
    <!-- Main content -->
    <h1>Hello, World!</h1>
    <p>This is a basic HTML5 document.</p>
  </body>
</html>
```

---

> 🧠 _Tip: Focus on structure before diving into styling or interactivity._

