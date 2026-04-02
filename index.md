---
layout: default
title: Pizza Paradise
---

# 🍕 Pizza Paradise

Welcome to **Pizza Paradise** — your ultimate guide to delicious pizza!

---

## 📞 Order Your Pizza

<!-- 🍕 Pizza Button -->
<a href="{{ '/order.html' | relative_url }}" class="order-btn">
  🍕 Order Now
</a>

<!-- 🍣 Sushi Button (ONLY for Valerija) -->
<a id="sushi-btn" href="{{ '/sushi.html' | relative_url }}" class="order-btn"
   style="display:none; background:#2a9d8f;">
  🍣 Order Sushi
</a>

<script>
  // Get URL parameter
  const params = new URLSearchParams(window.location.search);
  const user = params.get("user");

  // Show sushi button only for Valerija
  if (user && user.toLowerCase() === "valerija") {
    document.getElementById("sushi-btn").style.display = "inline-block";
  }
</script>

---

## 🧀 About Pizza

Pizza is one of the most popular foods in the world. It originated in **Italy** and has become a global favorite with countless variations.

---

## 🍕 Popular Types of Pizza

### Margherita
- Tomato sauce  
- Fresh mozzarella  
- Basil  

### Pepperoni
- Tomato sauce  
- Mozzarella  
- Pepperoni slices  

### Hawaiian
- Ham  
- Pineapple  

---

## 📸 Pizza Gallery

![Delicious Pizza](https://images.unsplash.com/photo-1601924928584-8c8b9c8c7b0b)

---

*Made with ❤️ and lots of cheese*
