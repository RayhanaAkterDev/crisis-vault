# 📄 Topic: HTML Tables

- Tables are used to organize data in rows and columns.    
- Semantic tags make tables easier to read and more accessible.    

---

## 🔍 Key Tags & Purpose (Short Note)

- `<table>` → Creates a table    
- `<caption>` → Adds a title above the table    
- `<thead>` → Table header section (top row)    
- `<tbody>` → Table body (main content)    
- `<tr>` → Table row    
- `<th>` → Table header cell (bold + centered by default)    
- `<td>` → Table data cell (normal cell)    

---

🔗 **Practice code**: https://github.com/sumayaakter533/Frontend-Bootcamp/blob/58fd25c3a3ce5c0542e81713638b0e40e5564af5/html-css/html/05-tables.html

```ad-todo
title: Demo code output

<table>
  <caption>Fruit Inventory</caption>
  <thead>
    <tr>
      <th>Item</th>
      <th>Quantity</th>
      <th>Price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Apples</td>
      <td>10</td>
      <td>$5.00</td>
    </tr>
    <tr>
      <td>Bananas</td>
      <td>6</td>
      <td>$3.00</td>
    </tr>
  </tbody>
</table>
```

---

> 🧠 _Tip_: Always use `<thead>`, `<tbody>`, and `<caption>` in real projects for better clarity and screen reader support. 