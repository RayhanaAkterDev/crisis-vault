# 📄 Topic: HTML Forms

- Forms collect user input (like name, email, message).    
- Used in contact pages, sign-up, search, etc.    

---

## 🔍 Key Tags & Purpose (Short Note)

- `<form>` → Wraps all form elements, sends data somewhere.    
- `action` → URL where form sends data (e.g., /submit)    
- `<label>` → Text that describes each input box    
- `for` → Connects label with input field by `id`    
- `<input>` → Single-line input field    
    - `type="text"` → for names        
    - `type="email"` → for emails        
    - `required` → must be filled before submitting        
- `<textarea>` → Multi-line input box for messages    
- `<button>` → Creates the submit button    

---

🔗 **Practice code**: https://github.com/sumayaakter533/Frontend-Bootcamp/blob/ecb92007214197672eaac99626746b1db5f78b89/html-css/html/06-forms.html

```ad-todo
title: Demo code output

<form action="/submit">

  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required />
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required />
  
  <label for="message">Message:</label>
  <textarea id="message" name="message"></textarea>
  
  <button type="submit">Submit</button>
</form>
```

---

> 🧠 _Tip_: Always use `label` for accessibility and `required` to make fields mandatory.