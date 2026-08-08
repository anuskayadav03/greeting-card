# 🎉 Greeting Card Project

A simple and interactive **Birthday Greeting Card** built using **HTML & CSS**.
This project demonstrates basic frontend concepts like layout design, hover effects, and section navigation using `:target`.

---

## 🚀 Features

* 🎂 Beautiful birthday card UI
* ✨ Hover animation (card zoom & color change)
* 🔗 Interactive links (Send Card & Share)
* 🎯 Section-based navigation using `:target`
* 🎨 Styled buttons with hover, active, focus & visited states
* 📱 Clean and responsive layout

---

## 🛠️ Technologies Used

* HTML5
* CSS3 (Flexbox, Transitions, Pseudo-classes, Pseudo-elements)

---

## 📂 Project Structure

```
📁 greeting-card
 ┣ 📄 index.html
 ┣ 📄 card.css
```

---

## 📸 Preview

* Main card displays a birthday message 🎉
* Clicking **Send Card** shows confirmation section
* Clicking **Share on Social Media** shows sharing message

---

## ⚡ How It Works

* The links (`#send`, `#share`) target specific `<section>` elements
* By default, sections are hidden using:

  ```css
  display: none;
  ```
* When a link is clicked, `section:target` makes it visible:

  ```css
  section:target {
    display: block;
  }
  ```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open `index.html` in your browser
3. Interact with the buttons to see effects

---

## 🎯 Learning Outcomes

* Understanding of **CSS Flexbox**
* Usage of **pseudo-classes** like `:hover`, `:active`, `:focus`, `:visited`
* Implementation of **:target selector for navigation**
* Creating smooth UI with **transitions and transforms**

---

## 💡 Future Improvements

* Add JavaScript for real sharing functionality
* Improve responsiveness for mobile devices
* Add animations or sound effects 🎶

---

## ⭐ Support

If you like this project, feel free to **star ⭐ the repository**!

---
