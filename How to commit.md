# ✅ How to Write Good Commit Messages (Professional Approach)

To maintain clarity and consistency — especially when building a portfolio or working in teams — follow the **Conventional Commit** style:

## 🔧 Commit Message Format:

```cpp
type(scope): message
```

---

### 🔑 Common Commit Types:

- `feat` – for adding a new feature    
- `fix` – for bug fixes    
- `docs` – for documentation changes    
- `style` – for formatting (white-space, missing semi-colons, etc.)    
- `refactor` – for code changes that neither fix a bug nor add a feature    
- `test` – for adding or updating tests    
- `chore` – for routine tasks like config updates, package installs, etc.    

### 🗂 Common Scopes (based on your repo):

- `html` – changes to HTML files    
- `css` – changes to CSS files    
- `responsive-design` – flexbox, grid, media queries    
- `mini-projects` – small application files    
- `docs` – documentation or README updates    

### ✅ Examples:

- `feat(html): add typography.html for text and heading tags`    
- `style(css): improve spacing and font styles in typography.css`    
- `docs(html-css): add README with topic overview and folder structure`    
- `refactor(responsive-design): optimize flexbox layout for mobile`    

---
## 🤝 Best Practices:

- Use **present tense**: “add”, not “added” or “adds”    
- Keep it **short and meaningful**    
- Group changes under one commit per logical task (avoid “multi-topic” commits)    
- Prefer clarity over creativity in professional repos    

---

### ❌ Bad example (multi-topic commit — not ideal):

```bash
docs(html-css): add new form layout and fix font size in typography.css
```

🔎 This mixes two unrelated tasks:

- Adding a new layout (a feature)    
- Fixing font size (a bugfix or styling tweak)

### ✅ Good example (separated logical commits):

```bash
docs(html-css/forms)[html-css/forms] feat: add new form layout structure  
[html-css/css] fix: correct font size in typography.css
```

Now each commit is focused and clear.

---

> This approach improves collaboration, allows better changelogs, and signals professionalism to recruiters and team leads.