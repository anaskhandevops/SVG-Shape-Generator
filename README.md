# 📐 SVG Shape Generator

A versatile web tool for generating various SVG shapes (Polygons, Stars, Circles, Ellipses, Rectangles, Lines) with customizable parameters and live preview. ✨

---

## ✨ Features

* 🎨 **Multiple Shape Types:** Generate:
    * Polygons (Regular)
    * Stars
    * Circles
    * Ellipses
    * Rectangles
    * Rounded Rectangles
    * Lines
* 🎛️ **Customizable Parameters:** Adjust shape-specific properties:
    * Points/Sides (Polygon, Star)
    * Outer Radius (Polygon, Star)
    * Inner Radius (Star)
    * Radius (Circle)
    * Radius X/Y (Ellipse)
    * Width/Height (Rectangle)
    * Corner Radius RX/RY (Rounded Rectangle)
    * Start/End Coordinates (Line)
    * Center Coordinates (Circle, Ellipse)
    * Top-Left Coordinates (Rectangle)
* 🎨 **Appearance Controls:**
    * Fill Color (Not applicable for Line)
    * Stroke Color
    * Stroke Width
* 👁️ **Live Preview:** See the generated SVG shape update instantly as you change parameters.
* 💻 **Code Generation:** Displays the complete, formatted SVG code for the generated shape.
* 🖱️ **Click-to-Copy:** Easily copy the generated SVG code.
* 📱 **Responsive Design:** Basic responsive layout.
* 💬 **User Feedback:** Displays messages for success (e.g., "SVG code copied!") or errors.

---

## 🚀 How to Use

1.  Clone this repository or download the `index.html` file.
2.  Open `index.html` in your web browser.
3.  Select the desired **Shape Type** from the dropdown menu.
4.  The relevant controls for the selected shape will appear.
5.  Adjust the sliders and color pickers to customize the shape and its appearance.
6.  The **Preview** area will update in real-time. 🔥
7.  The **Generated SVG Code** box shows the code for the current shape.
8.  Click the **Copy SVG Code** button to copy the code to your clipboard. 📋

---

## 💻 Technology Stack

* **HTML:** Page structure and controls.
* **CSS (Tailwind CSS):** Styling & layout (via CDN).
* **JavaScript:**
    * Handles user input from sliders, dropdowns, and color pickers.
    * Calculates shape geometry (points, coordinates, radii).
    * Dynamically generates SVG element strings.
    * Updates the live preview and code output areas.
    * Manages control visibility based on selected shape type.
    * Implements copy-to-clipboard functionality.

---

## 🤝 Contributing

Contributions are welcome! 🎉 Whether it's bug fixes, adding new shapes, improving the UI, or enhancing features, please feel free to contribute.

**How to Contribute:**

1.  **Fork the Repository:** Click the 'Fork' button.
2.  **Clone Your Fork:**
3.  **Create a New Branch:**
    ```bash
    git checkout -b feature/add-path-shape
    # or
    git checkout -b fix/star-calculation-bug
    ```
4.  **Make Your Changes.**
5.  **Test Your Changes.**
6.  **Commit Your Changes** (Consider [Conventional Commits](https://www.conventionalcommits.org/)):
    ```bash
    git add .
    git commit -m "feat: Add support for SVG <path> element"
    # or
    git commit -m "fix: Correct inner radius calculation for stars"
    ```
7.  **Push to Your Fork:**
    ```bash
    git push origin feature/add-path-shape
    ```
8.  **Open a Pull Request (PR):** Go to the original repository and open a PR.
    * Provide a clear title and description.
    * Link any relevant issues.

**Reporting Bugs:**

* Use the GitHub Issues tab.
* Provide a clear title, description, and steps to reproduce.

**Suggesting Enhancements:**

* Use the GitHub Issues tab.
* Provide a clear title and detailed description.

---

## 💡 Potential Enhancements

* **More Shapes:** Add support for `<path>` elements (e.g., arcs, curves), `<text>`, or more complex predefined shapes.
* **Transformations:** Add controls for `rotate`, `scale`, `skew` transformations.
* **Gradients/Patterns:** Allow using gradients or patterns for fills/strokes.
* **ViewBox Control:** Allow users to adjust the SVG `viewBox`.
* **Export Options:** Add options to download the generated SVG as a `.svg` file.
* **Code Formatting Options:** Allow choosing different SVG code formatting styles.
* **UI/UX:** Improve slider precision, add input fields for exact values, enhance visual design.

---

Happy Generating! 📐
