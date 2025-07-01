# 🚗 ParkEasy - Smart Parking Frontend

**ParkEasy** is a modern, front-end-only smart parking solution that allows users to explore parking services, view reservations, and track parking history. It includes Google OAuth login (no backend required) and a responsive, elegant UI built with HTML, Bootstrap, and Font Awesome.

---

## 📸 Demo Preview

![ParkEasy Screenshot](preview.png)

---

## 🔧 Tech Stack

- **HTML5** - Semantic layout
- **Bootstrap 5** - Responsive and clean UI
- **Font Awesome** - Icon support
- **JavaScript (Vanilla)** - Light interactivity
- **Google OAuth 2.0** - Sign-in system

---

## 🚀 Features

- ✅ Responsive layout (Mobile/Desktop)
- ✅ Animated buttons (hover effect)
- ✅ Google Sign-in (OAuth 2.0)
- ✅ Functional alerts:
  - `Find Parking` → Prompts sign-in
  - `View History` → Alerts no data
  - `Learn More` → Shows app overview

---

## ⚙️ Getting Started

1. **Clone this repo or copy HTML file**

2. **Replace Google OAuth Client ID** in this section:
```html
<div id="g_id_onload"
     data-client_id="YOUR_GOOGLE_CLIENT_ID"
     data-login_uri=""
     data-auto_prompt="false">
</div>
