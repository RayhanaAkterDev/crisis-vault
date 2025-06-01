# 📄 Topic: Selectors & Specificity

- **Selectors** » target HTML elements to apply CSS styles    
- **Specificity** » decides which rule wins if multiple styles apply    
- Helps control **which CSS rule gets applied**    

---

## 🔍 Key Tags & Purpose

- `p {}` → **Type selector**: targets all `<p>` tags    
- `.highlight {}` → **Class selector**: targets elements with class    
- `#unique {}` → **ID selector**: targets element with unique ID    
- `input[type="text"] {}` → **Attribute selector**: selects by attribute    
- `a:hover {}` → **Pseudo-class**: styles on interaction (like hover)    
- `div span {}` → **Descendant selector**: targets elements inside others    
- `ul > li {}` → **Child selector**: direct child elements    
- `p, a {}` → **Group selector**: styles multiple tags together    
- **Specificity order** → Inline (1000) > ID (100) > Class/Attr/Pseudo (10) > Type (1)    

---

🔗 **Practice code**:  

```ad-todo
title: Code example with output

<style>
  p { color: darkblue; }
  .highlight { background-color: yellow; }
  #unique { font-weight: bold; color: red; }
  input[type="text"] { border: 2px solid green; }
  a:hover { color: orange; }
  div span { font-style: italic; }
  ul > li { list-style-type: square; }
  p, a { font-family: Arial, sans-serif; }
  .test { color: purple; }
  #test { color: teal; }
</style>
<h1>CSS Selectors and Specificity Demo</h1>
<p>This paragraph uses a type selector (<code>p</code>) with dark blue text.</p>
<p class="highlight">This paragraph has a class selector and a yellow background.</p>
<p id="unique">This paragraph uses an ID selector and appears bold red.</p>
<input type="text" placeholder="Text input with attribute selector" />
<br><br>
<a href="#">Hover over this link to see pseudo-class effect</a>
<div>
  <span>This span inside a div is italic using descendant selector.</span>
</div>
<ul>
  <li>First list item with child selector square bullet</li>
  <li>Second list item</li>
</ul>
<p class="test" id="test" style="color: orange;">
  This paragraph has class, ID, and inline style. Inline style (orange) overrides others.
</p>
<p>This paragraph shares font style with the link below using group selector.</p>
<a href="#">I’m part of the group too!</a>
```

---

> 🧠 _Tip: Start with internal and inline CSS for experiments, then use external CSS for real projects._
