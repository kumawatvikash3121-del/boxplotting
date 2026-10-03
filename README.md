# 📦 CSS Box Model

This project demonstrates the **CSS Box Model** using HTML and CSS. It visually represents the four main parts of the box model:

* **Content**
* **Padding**
* **Border**
* **Margin**

## 🌐 Project Preview

The webpage creates a nested box structure where each layer represents a different part of the CSS Box Model.

### Box Model Structure

```text
┌──────────────────────────────────────────┐
│                  Margin                  │
│   ┌──────────────────────────────────┐   │
│   │              Border              │   │
│   │   ┌──────────────────────────┐   │   │
│   │   │         Padding          │   │   │
│   │   │   ┌──────────────────┐   │   │   │
│   │   │   │     Content      │   │   │   │
│   │   │   └──────────────────┘   │   │   │
│   │   └──────────────────────────┘   │   │
│   └──────────────────────────────────┘   │
└──────────────────────────────────────────┘
```

## 🛠️ Technologies Used

* HTML5
* CSS3
* Flexbox
* CSS Box Model
* Positioning

## 📁 Project Structure

```text
Box-Model/
│
├── index.html
└── README.md
```

## 🎨 CSS Features

### Container

The `.con` class creates the main container:

```css
.con {
    height: 500px;
    width: 800px;
    background-color: teal;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: center;
}
```

It uses **Flexbox** to center the inner box.

### Margin

The `.box1` element uses margin to create space outside the border:

```css
margin: 40px 30px 30px 60px;
```

### Border

A navy-colored border is used to demonstrate the border area:

```css
border: 20px solid navy;
```

### Padding

Padding creates space between the border and the content:

```css
padding: 60px 10px 20px 80px;
```

### Content

The `.box2` represents the actual content area:

```css
.box2 {
    background-color: orange;
    text-align: center;
    color: white;
    font-size: 40px;
}
```

## 📚 CSS Box Model

Every HTML element can be understood as a rectangular box consisting of:

| Part        | Description                                |
| ----------- | ------------------------------------------ |
| **Content** | The actual text or elements inside the box |
| **Padding** | Space between content and border           |
| **Border**  | Line surrounding the padding and content   |
| **Margin**  | Space outside the border                   |

### Box Model Formula

```text
Total Width =
Content Width + Left Padding + Right Padding
+ Left Border + Right Border
+ Left Margin + Right Margin
```

```text
Total Height =
Content Height + Top Padding + Bottom Padding
+ Top Border + Bottom Border
+ Top Margin + Bottom Margin
```

## ▶️ How to Run

1. Save the HTML code in a file named `index.html`.
2. Save this documentation as `README.md`.
3. Open `index.html` in any modern web browser.
4. The CSS Box Model demonstration will appear on the screen.

## 🎯 Learning Objectives

This project helps beginners understand:

* How the CSS Box Model works
* Difference between margin and padding
* How borders affect an element
* How content is positioned inside a box
* Basic Flexbox alignment
* CSS dimensions and spacing

## 👨‍💻 Author

Created as a beginner-friendly **HTML & CSS Box Model** practice project.
