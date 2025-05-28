# 📄 Topic: Semantic HTML Tags

- Semantic tags describe the meaning of content on a page.    
- Helps with SEO, accessibility, and organized structure.    

---

## 🔍 Key Tags & Purpose (Short Note)

- `<header>` → Top section of page (title, logo).    
- `<nav>` → Navigation links (menu).    
- `<main>` → Main content area.    
- `<section>` → Groups related content.    
- `<article>` → Self-contained content like posts.    
- `<aside>` → Side info or related content.    
- `<footer>` → Bottom area (copyright/info).

> - Use `<aside>` when the content is **related but not part of the main content flow**, like tips, author info, or ads. In raw html, there is no visual difference of `<aside>` 
> - Use semantic tags instead of plain `<div>` to add clear meaning to the structure.

---

🔗 **Practice code**: https://github.com/sumayaakter533/Frontend-Bootcamp/blob/8d7bf816ce2e6e47d472c38c5516ab1c89bc61f2/html-css/html/07-semantic-tags.html

```ad-todo
title: Demo code output

<header>
  <h1>My Blog</h1>
</header>

<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Articles</a></li>
  </ul>
</nav>

<main>
  <section>
    <article>
      <h2>Post Title</h2>
      <p>This is a blog post.</p>
    </article>
  </section>

  <aside>
    <p>Author bio or related links.</p>
  </aside>
</main>

<footer>
  <p>&copy; 2025 Sumaya</p>
</footer>
```

---

> 🧠 _Tip_: Semantic tags make it easier for screen readers and search engines to understand your layout.