# 📄 Topic: Web Accessibility in HTML

- Accessibility ensures websites are usable for all, including people with disabilities.    
- Semantic tags, labels, and attributes help screen readers and assistive tech.    

---

## 🔍 Key Tags & Purpose (Short Note)

- `alt` (on `<img>`) → Text alternative for images.    
- `<label for="">` → Connects label to input for screen readers.    
- `aria-label` → Adds hidden label for screen readers.    
- `role` → Describes element purpose (e.g., `role="button"`).    
- `tabindex` → Controls keyboard navigation order.

> Use clear labels and alt texts so screen readers can describe your content properly.

---

🔗 **Practice code**: https://github.com/sumayaakter533/Frontend-Bootcamp/blob/aeb097cdbd44b5218bbc854276d5c5f1a7f12ec3/html-css/html/09-accessibility-demo.html

```ad-todo
<!-- Image with alt text -->
<img src="logo.png" alt="Company Logo" />

<!-- Label associated with input -->
<label for="email">Email:</label>
<input type="email" id="email" name="email" />

<!-- Accessible button with role and aria-label -->
<div role="button" tabindex="0" aria-label="Close menu">
  X
</div>
```

---

> 🧠 _Tip_: Accessibility improves user experience for everyone, not just those with disabilities. It's also important for legal compliance and inclusive design.

