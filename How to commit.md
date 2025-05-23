# ✅ How to Write Good Commit Messages

A good commit message should be:

- **Clear**: Describe what was changed    
- **Concise**: Avoid long explanations    
- **Consistent**: Follow a uniform style    

---

## 🧩 Format Structure

```csharp
[scope] type: short message describing the change
```

---

### 🔹 Scope (optional but helpful)

Indicates _what part of the repo_ the commit affects. Can be:

- A **folder**: `[html]`, `[css]`, `[responsive-design]`    
- A **combo**: `[html/css]`, `[js/projects]`    
- A **specific file** (only if useful): `[HTML/forms.html]`    

### 🔹 Type

Follows conventional commits style:

| Type       | Use when you...                          |
| ---------- | ---------------------------------------- |
| `feat`     | Add a new feature or content             |
| `fix`      | Fix a bug or issue                       |
| `docs`     | Change only documentation                |
| `style`    | Update styling, formatting, spacing      |
| `refactor` | Restructure code (no change in behavior) |
| `chore`    | Minor changes (e.g., gitignore, folders) |

---

### ✍️ Examples for Your Repo

#### 🔸 Single file changes:

```bash
[html] feat: add semantic tags demo page [css] style: apply basic text styling in typography.css
```

#### 🔸 Multiple related files (HTML + CSS together):

```bash
[html/css] feat: add and style list elements [responsive-design] feat: implement flexbox layout demo
```

#### 🔸 Documentation:

```bash
[docs] add README » overview, folder structure, learning roadmap [html] docs: update HTML cheatsheet with semantic tags
```


#### 🔸 Organizational:

```bash
[chore] setup folder structure for css and responsive-design [chore] add .gitignore and license files
```

---

### 🔁 Best Practices

- Commit often, but with **meaningful chunks** of work    
- Group related changes into a single commit    
- **Don't mix** unrelated changes in one commit    
- Always write the message in **present tense**    

---

### 💡 Bonus Tip: Keep a Reference List

In your `README.md` or notes, you can keep a reference like:

```csharp
[html] = HTML content [css] = CSS styles [responsive-design] = Media queries, flex, grid [docs] = Markdown files, README, notes
```

---


