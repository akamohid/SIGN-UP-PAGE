# 🌐 Web Sign-Up Page 

Welcome to the **Web Sign-Up Page** project! This repository contains a simple, static HTML-based sign-in page with a clean design, intended for beginners to learn how to structure and style an HTML form. Below is an overview of everything included, instructions to run the page, and ideas for customization.

---

## 🚀 Project Overview

This project is a **static** (front-end only) sign-in page for a website. It includes:

- A **login form** with fields for username and password.
- A **“Remember me”** checkbox.
- Links for **“Sign Up”** and **“Forgot password?”** to simulate a typical authentication flow.
- **Social media icons** at the bottom (Facebook, WhatsApp, Twitter, Instagram).
- Styling is done **entirely in CSS** (embedded in `<style>` tags).

There is **no backend**; this is purely a visual and structural demonstration. You can extend it by adding CSS files, JavaScript validation, or connecting to a real server.

---

## 📁 Repository Structure

```
SIGN-UP-PAGE/
├── assets/               ← Image assets used in the page
│   ├── sss.jpg           ← Main logo/profile picture placeholder
│   ├── fb.jpg            ← Facebook icon
│   ├── WhatsApp.png      ← WhatsApp icon
│   ├── twitter.png       ← Twitter icon
│   └── download.jpeg     ← Instagram icon
├── h111.html             ← Main HTML file (sign-in page)
├── README.md             ← This detailed overview
├── LICENSE               ← MIT License (free to use)
└── .gitignore            ← Git ignore rules for any temp files
```

---

## 🔧 How to Run the Page

No server or special setup is needed:

1. **Clone or download** this repository:
   ```
   git clone https://github.com/akamohid/SIGN-UP-PAGE.git
   cd SIGN-UP-PAGE
   ```
2. Open the file `h111.html` in any modern web browser:
   - On **Windows**, double-click the file or right-click → “Open with” → “Your Browser”.
   - On **Mac/Linux**, you can run:
     ```bash
     open h111.html
     ```
3. That’s it! You should see the styled sign-in form appear.

---

## 🎨 Detailed Code Explanation

#### 1. HTML Structure (`h111.html`)

```html
<!DOCTYPE html>
<html>
<head>
    <title>sign-in_page</title>
    <style>
        /* CSS styles here */
    </style>
</head>
<body>
    <div class="container">
        <!-- Profile/Logo Image -->
        <img src="assets/sss.jpg" width="100" height="100" class="main-image">

        <!-- Form Container -->
        <div class="form-container">
            <h1> Login </h1>
            <form>
                <input type="text" placeholder="Username">
                <input type="password" placeholder="Password">
                <input type="checkbox" id="remember" name="remember">
                <label for="remember">Remember me</label><br>
                <input type="submit" value="Sign in">
            </form>
            <p class="sign-up-link">
                Don't have an account? <a href="signup.html">Sign Up</a>
            </p>
            <p class="forgot-password">
                <a href="forgot-password.css">Forgot password?</a>
            </p>
        </div>

        <!-- Social Icons -->
        <div class="social-icons">
            <a href="#"><img src="assets/fb.jpg" alt="Facebook" width="40" height="40"></a>
            <a href="#"><img src="assets/WhatsApp.png" alt="WhatsApp" width="40" height="40"></a>
            <a href="#"><img src="assets/twitter.png" alt="Twitter" width="40" height="40"></a>
            <a href="#"><img src="assets/download.jpeg" alt="Instagram" width="40" height="40"></a>
        </div>
    </div>
</body>
</html>
```

- The `<style>` section provides all CSS styles:
  - **`.container`**: Centers content, adds padding and rounded corners.
  - **`.main-image`**: Rounds the top image to look like a profile/logo circle.
  - **`.form-container`**: White box for the login form with rounded corners, fixed width, and scroll if content overflows.
  - **Input fields**: Styled for username/password with padding, border, and margin.
  - **Submit button**: Colored with hover effect.
  - **Links and social icons**: Simple color changes on hover.

#### 2. Assets Folder

All image files referenced in `h111.html` are stored in `assets/`. You can replace these placeholder images with real ones (company logo, user avatar, or social media icons).

---

## 🔄 Customization Ideas

1. **External CSS File**  
   Move the `<style>` section into a separate `styles.css` file and link it:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

2. **JavaScript Validation**  
   Add a `script.js` to validate:
   ```html
   <script src="script.js"></script>
   ```

3. **Responsive Design**  
   Use media queries to adjust form size on mobile devices.

4. **Real Backend Connection**  
   Change `<form>` to submit to a server endpoint and handle authentication.

5. **Sign-Up & Forgot Password Pages**  
   Create `signup.html` and `forgot-password.html` to complete the user flow.

---

## 🛠 Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari).
- No need for Node.js, Python, or any other runtime. Totally static!

---

## 📄 License

```
MIT License

Copyright (c) 2025 Mohid Arshad

Permission is hereby granted, free of charge, to any person obtaining a copy
...
```
(See full text in `LICENSE`)

Feel free to copy, modify, and share this project.

---

## 📞 Contact and Feedback

Made by **Mohid Arshad**.  
GitHub: [akamohid](https://github.com/akamohid)  
Email: "akamohid@gmail.com"
Live Repo: [https://github.com/akamohid/SIGN-UP-PAGE](https://github.com/akamohid/SIGN-UP-PAGE)

---

Enjoy building and customizing your own sign-up page! 🎉
