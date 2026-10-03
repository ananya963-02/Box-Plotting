CSS Box Plotting

A simple HTML and CSS project that visually demonstrates the CSS Box Model using nested boxes. The project shows the relationship between Margin, Border, Padding, and Content.

Features

- 📦 Visual representation of the CSS Box Model
- 🎨 Different colors for each box layer
- 📐 Demonstrates margin, border, padding, width, and height
- 🎯 Centered layout using CSS Flexbox
- 📝 Labels for Margin, Border, Padding, and Content
- 💡 Beginner-friendly CSS example

Technologies Used

- HTML5
- CSS3

Project Structure

CSS-Box-Plotting/
│
├── index.html
└── README.md

How to Run

1. Download or clone the project.
2. Open the project folder.
3. Open "index.html" in a web browser.
4. You will see the visual representation of the CSS Box Model.

CSS Box Model

The CSS Box Model consists of four main parts:

+-----------------------------+
|           Margin            |
|   +---------------------+   |
|   |       Border        |   |
|   |  +---------------+  |   |
|   |  |    Padding    |  |   |
|   |  |  +---------+  |  |   |
|   |  |  | Content |  |  |   |
|   |  |  +---------+  |  |   |
|   |  +---------------+  |   |
|   +---------------------+   |
+-----------------------------+

1. Margin

Margin is the space outside the border of an element.

In this project:

margin: 20px 20px 20px 40px;

2. Border

The border surrounds the padding and content.

In this project:

border: 20px solid navy;

3. Padding

Padding is the space between the border and the content.

In this project:

padding: 55px 20px 20px 80px;

4. Content

Content is the actual information inside the element. In this project, the orange box represents the content area.

.box2 {
    background-color: orange;
    text-align: center;
}

Main Container

The ".con" class creates the main container:

.con {
    height: 500px;
    width: 800px;
    background-color: teal;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
}

Flexbox is used to center the inner elements horizontally and vertically.

Box Structure

The project uses nested "<div>" elements:

<div class="con">
    <div class="box">
        <div class="box1">
            <div class="box2">
                <p>Content</p>
            </div>
        </div>
    </div>
</div>

The nesting visually represents the different layers of the CSS Box Model.

Color Representation

Element| Color| Represents
".con"| Teal| Outer container
".box"| Sky Blue| Outer box area
".box1"| Blue| Border/padding area
Border| Navy| Border
".box2"| Orange| Content

Learning Objectives

This project helps beginners understand:

- CSS "margin"
- CSS "border"
- CSS "padding"
- CSS "width" and "height"
- CSS Flexbox
- Nested HTML elements
- How different CSS box-model properties affect an element's layout

Important CSS Concepts

The basic CSS Box Model can be remembered as:

Content → Padding → Border → Margin

Understanding these four properties is essential for controlling spacing and layout in CSS.

Note

This project is created for learning and demonstration purposes. The labels use absolute positioning, so the layout may require adjustments on different screen sizes.

License

This project is free to use for learning and personal projects.# Box-Plotting
