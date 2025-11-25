# -Aura-Graph-Plotter---A-Modern-Web-Based-Graphing-Calculator
Aura Graph Plotter is an advanced, feature-rich, and interactive graphing calculator built with modern web technologies.

# Aura Graph Plotter - A Modern Web-Based Graphing Calculator

## Description

Aura Graph Plotter is an advanced, feature-rich, and interactive graphing calculator built with modern web technologies. It provides a seamless and intuitive user experience with a stunning, futuristic interface. This powerful tool supports multiple plotting modes, including Cartesian, polar, function transformations, and intersection analysis, making it ideal for students, educators, and professionals.

The application is a single, self-contained HTML file, requiring no backend or complex setup. It leverages powerful JavaScript libraries like Chart.js for rendering, math.js for complex calculations, and Tailwind CSS for a sleek, responsive design.

---

## ✨ Features

*   **Multi-Mode Plotting**:
    *   **Standard (Cartesian)**: Plot functions in the form `f(x)`.
    *   **Polar Coordinates**: Visualize polar equations in the form `r(t)`.
    *   **Transformation Simulator**: Interactively see how parameters `a, b, c, d` in `g(x) = a * f(b * (x - c)) + d` transform a base function.
    *   **Intersection Finder**: Plot two functions simultaneously and automatically find and mark their intersection points.

*   **Advanced Function Analysis**:
    *   Calculate and plot the **derivative** (`f'(x)`) of a function.
    *   Plot the symbolic **integral** (`∫f(x)dx`).
    *   Perform a full analysis to find **roots (zeros)**, **extrema (min/max)**, and the **area under the curve** within a given range.

*   **Interactive Chart Experience**:
    *   **Zoom**: Use the mouse wheel or pinch gestures to zoom in and out.
    *   **Pan**: Click and drag to move the viewing window.
    *   **Crosshair & Tooltips**: Hover over the graph to see precise point coordinates.
    *   **Reset View**: Double-click the chart to reset the zoom and pan.

*   **Sleek & Modern User Interface**:
    *   A stunning dark theme with a "glassmorphism" aesthetic.
    *   Smooth animations, including a unique startup loading sequence with a 3D spinning cube and constellation background.
    *   Fully responsive design that works on desktops, tablets, and mobile devices.

*   **User-Friendly Utilities**:
    *   **Export to PNG**: Save your graph, including legends and analysis data, as a high-quality PNG image.
    *   **Function History**: A dropdown menu saves your recent equations for quick access.
    *   **Grid Toggle**: Easily show or hide the chart's grid lines.
    *   **In-App Help Guide**: A comprehensive modal explains all features and modes.

---

## 🚀 How to Use

1.  **Download the `plotter.html` file.**
2.  **Open it in any modern web browser** (like Chrome, Firefox, or Edge).
3.  That's it! The application is ready to use.

#### **Plotting a Graph:**
1.  **Select a Mode** from the left-hand menu (e.g., "Standard (Cartesian)").
2.  **Enter your function** in the input box.
    *   Use `x` as the variable for Cartesian modes (e.g., `sin(x) * x`).
    *   Use `t` as the variable for Polar mode (e.g., `1 + cos(t)`).
3.  **Adjust the Range** (X-Min, X-Max, Step) if needed.
4.  **Click the "Plot Graph" button** or press `Enter`.

---

## 🛠️ Technical Stack

*   **Charting**: [Chart.js](https://www.chartjs.org/) with plugins for zoom ([`chartjs-plugin-zoom`](https://www.chartjs.org/chartjs-plugin-zoom/)) and crosshairs ([`chartjs-plugin-crosshair`](https://github.com/abelheinsbroek/chartjs-plugin-crosshair)).
*   **Mathematical Parsing & Calculation**: [math.js](https://mathjs.org/)
*   **Styling**: [Tailwind CSS](https://tailwindcss.com/) (used via CDN).
*   **Icons**: [Font Awesome](https://fontawesome.com/)

---

## 👨‍💻 Developer

*   **Sadeepa Lakshan**
*   **GitHub**: [@sadeepas](https://github.com/sadeepas)
*   **LinkedIn**: [sadeepa-lakshan](https://www.linkedin.com/in/sadeepa-lakshan/)
*   **Email**: [sadeepapemasiri2@gmail.com](mailto:sadeepapemasiri2@gmail.com)
