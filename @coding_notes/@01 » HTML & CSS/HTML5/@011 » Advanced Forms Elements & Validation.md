# 📄 Topic: Advanced Form Inputs & Validation

- Enhances form usability, accessibility, and data validation.    
- Includes file uploads, sliders, color pickers, dropdowns, and grouped fields.

---

## 🔍 Key Tags & Purpose (Short Note)

- `type="number"` → Only accepts numbers    
- `type="date"` → Select a date from calendar    
- `type="range"` → Choose a value with a slider    
- `type="color"` → Opens color picker    
- `type="file"` → Upload files (e.g., PDF)    
- `datalist` → Suggest options while typing    
- `select` → Dropdown menu to choose from    
- `radio` → Choose one option from a group    
- `checkbox` → Toggle option on/off    
- `textarea` → Enter longer text (like comments)    
- `min`, `max`, `maxlength` → Limit value/characters    
- `pattern` → Custom validation using regex    
- `<fieldset>` → Groups related inputs    
- `<legend>` → Title inside a fieldset

---

🔗 **Practice code**: https://github.com/sumayaakter533/Frontend-Bootcamp/blob/bd26a398ab1df7bed85b0affca8f80c367cfa0ba/html-css/html/11-advanced-form-elements.html

```ad-todo
title: Demo code output

<form action="/submit" method="POST">
  <fieldset>
    <legend>Account Setup</legend>
    <label for="username">Username:</label>
    <input type="text" id="username" pattern="[a-zA-Z0-9]+" required />
    <br><br>
    <label for="password">Password:</label>
    <input type="password" id="password" minlength="6" required />
  </fieldset>
  <label for="resume">Upload Resume:</label>
  <input type="file" id="resume" accept="application/pdf" />
  <br><br>
  <label for="skill">Top Skill:</label>
  <input list="skills" id="skill" name="skill" />
  <datalist id="skills">
    <option value="HTML" />
    <option value="CSS" />
  </datalist>
  <br><br>
  <label for="level">Skill Level:</label>
  <select id="level" required>
    <option value="">-- Select --</option>
    <option value="beginner">Beginner</option>
  </select>
  <br><br>
  <fieldset>
    <legend>Contact Method</legend>
    <input type="radio" name="contact" value="email" required /> Email
    <input type="radio" name="contact" value="phone" /> Phone
  </fieldset>
  <br><br>
  <label>
    <input type="checkbox" name="subscribe" />
    Subscribe to newsletter
  </label>
  <br><br>
  <label for="comments">Comments:</label>
  <textarea id="comments" rows="4" cols="40"></textarea>
  <br><br>
  <button type="submit">Submit</button>
</form>
```

---

> 🧠 _Tip_: Use `datalist` for typing suggestions and `select` for dropdowns. Combine `fieldset` and `legend` to group related inputs and improve accessibility.