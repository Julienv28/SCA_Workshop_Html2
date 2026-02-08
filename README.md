# SCA_Workshop_Html2

## 📌 Linktree Project

This repository contains a **Linktree-style personal webpage** created as part of a pedagogical workshop for students at **Sciences Po**.

The goal is to learn the basics of **HTML & CSS** by building a simple, responsive landing page that centralizes personal links.

---

## 🚀 Objectives

* Understand the structure of an HTML project
* Learn how to link CSS to HTML
* Use images and assets correctly
* Create a responsive webpage
* Publish a simple website

---

## 📁 Project Structure

```text
├── LICENSE
├── README.md
├── index.html
├── style.css
└── pics
    ├── Photo_profil.jpg
    └── logos
        ├── facebook.png
        ├── github.png
        ├── instagram.png
        └── linkedin.png
```

---

## 🛠️ How to Use This Repository

### 1. Clone the project

```bash
git clone https://github.com/your-username/SCA_Workshop_Html2.git
cd SCA_Workshop_Html2
```

### 2. Customize your profile

Edit `index.html` and update:

* Your name / username
* Your biography
* Your social media links

Example:

```html
<h1>@YourName</h1>
```

---

### 3. Replace images

In the `pics/` folder:

* Replace `Photo_profil.jpg` with your own profile picture
* Replace logos if needed

Keep the same filenames to avoid breaking paths.

---

### 4. Customize the design

Edit `style.css` to:

* Change colors
* Modify fonts
* Adjust spacing
* Add animations

---

### 5. Open locally

Open `index.html` in your browser:

* Double-click the file
* Or use Live Server (VS Code extension)

---

## 🧩 Understanding the Project Structure (Beginner Guide)

This section explains **how the project is organized** and **why each file exists**. It is designed for students with **no prior web development experience**.

---

### 📄 1. `index.html` — The Structure of the Website

This is the **main file** of the project. It contains the content of the webpage.

When you open the website, your browser reads this file first.

#### ➤ Role of `index.html`

It defines:

* The text
* The images
* The buttons
* The links
* The general structure

Think of it as the **skeleton** of the website.

---

#### ➤ Basic Structure of an HTML File

Every HTML file follows this structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Information for the browser -->
  </head>

  <body>
    <!-- Content visible on the page -->
  </body>
</html>
```

Explanation:

* `<!DOCTYPE html>` → tells the browser this is HTML5
* `<html>` → main container
* `<head>` → configuration (title, CSS, encoding)
* `<body>` → everything the user sees

---

#### ➤ Important Elements in `index.html`

Example:

```html
<img src="pics/Photo_profil.jpg">
<h1>@YourName</h1>
<a href="https://github.com">GitHub</a>
```

Meaning:

* `<img>` → displays an image
* `<h1>` → main title
* `<a>` → link (anchor)
* `src` → file path
* `href` → website link

---

### 🎨 2. `style.css` — The Design of the Website

This file controls the **appearance** of the website.

It defines:

* Colors
* Fonts
* Sizes
* Layout
* Animations

Think of it as the **clothes and makeup** of the website.

---

#### ➤ How HTML and CSS Work Together

In `index.html`, this line connects CSS:

```html
<link rel="stylesheet" href="style.css">
```

It means:

➡️ “Use the design rules from style.css.”

Without this line, the site has no styling.

---

#### ➤ Structure of `style.css`

A CSS rule looks like this:

```css
selector {
    property: value;
}
```

Example:

```css
h1 {
    color: white;
    font-size: 26px;
}
```

Meaning:

* `h1` → target the title
* `color` → text color
* `font-size` → text size

---

#### ➤ Classes in CSS

Example in HTML:

```html
<img class="profile-img">
```

Example in CSS:

```css
.profile-img {
    border-radius: 50%;
}
```

Explanation:

* `class` links HTML and CSS
* `.` in CSS means “class”
* Allows custom styling

---

### 🖼️ 3. `pics/` Folder — Images and Assets

This folder stores all images.

Structure:

```
pics/
 ├── Photo_profil.jpg
 └── logos/
```

Purpose:

* Keeps files organized
* Avoids mixing images and code
* Makes paths easier

---

#### ➤ File Paths

Example:

```html
<img src="pics/logos/github.png">
```

Meaning:

* `pics/` → go to folder
* `logos/` → subfolder
* `github.png` → file

Wrong paths = image not displayed ❌

---

### 📂 4. `README.md` — Project Documentation

This file explains:

* What the project is
* How to use it
* How to modify it

It is written in **Markdown**, a simple text format.

It is displayed automatically on GitHub.

---

### ⚖️ 5. `LICENSE` — Usage Rights

This file defines how others can use your project.

MIT License means:

✔️ Anyone can reuse it
✔️ Anyone can modify it
✔️ Credit is appreciated

---

### 🧠 6. How Everything Works Together

Simplified view:

```
index.html  → Structure
style.css   → Design
pics/       → Images
README.md   → Explanation
LICENSE     → Rights
```

Process:

1. Browser opens `index.html`
2. Loads `style.css`
3. Loads images from `pics/`
4. Displays final page

---

### ✅ 7. Common Beginner Mistakes

❌ Wrong file path
❌ Missing `style.css` link
❌ Typos in class names
❌ Forgetting quotes
❌ Deleting folders

Tip: Always check spelling carefully.

---

### 🏁 8. Learning Progression

Students should learn in this order:

1️⃣ Understand HTML structure
2️⃣ Learn basic tags
3️⃣ Understand CSS rules
4️⃣ Use classes
5️⃣ Organize files
6️⃣ Publish online

---

## 🌐 Deployment (Optional)

You can publish your Linktree online using:

* GitHub Pages
* Netlify
* Vercel

Example with GitHub Pages:

1. Push your project to GitHub
2. Go to **Settings → Pages**
3. Select `main` branch
4. Save

Your site will be available online.

---

## 📚 Learning Resources

* MDN Web Docs: [https://developer.mozilla.org/fr/docs/Web](https://developer.mozilla.org/fr/docs/Web)
* Linktree Templates: [https://linktr.ee/s/templates](https://linktr.ee/s/templates)
* GitHub Inspiration: [https://github.com/vitor-antoni/linktree-template](https://github.com/vitor-antoni/linktree-template)
* W3Schools Tutorial: [https://www.w3schools.com/howto/howto_website_create_linktree.asp](https://www.w3schools.com/howto/howto_website_create_linktree.asp)

---

## 📄 License

This project is distributed under the MIT License. See `LICENSE` for more information.

---

## ✨ Author

Workshop organized for students at **Sciences Po**.

Feel free to fork, customize, and improve this project.
