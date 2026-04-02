---
layout: default
title: Order Pizza
permalink: /order.html
---

# 🍕 Order Your Pizza

Choose your favorite pizza and place your order!

---

## 🛒 Order Form

<form>
  <label>Your Name:</label>
  <input type="text" name="name" required>

  <label>Select Pizza:</label>
  <select name="pizza">
    <option>Margherita</option>
    <option>Pepperoni</option>
    <option>Hawaiian</option>
  </select>

  <label>Quantity:</label>
  <input type="number" value="1" min="1">

  <br><br>
  <button type="submit" class="order-btn">✅ Place Order</button>
</form>

---

<a href="{{ '/' | relative_url }}" class="order-btn">⬅ Back to Home</a>
