# almaX: Parametric Diamond Scheme Generator

**almaX** is a high-precision, web-based tool for RBC proportions estimation and visualizing 2D diamond schemes. Designed with a focus on geometric accuracy and optical physics, it allows users to simulate the internal reflections and structural proportions of round brilliant diamonds.

## ✨ Core Features

* **Real-Time Parametric Modeling:** Adjust core diamond parameters including Table Width, Crown Angle, Pavilion Angle, and Girdle Thickness via an interactive dashboard.
* **Optical Physics Engine:**
* **Hearts & Arrows (H&A) Visualization:** Simulates "Ideal" black extinction patterns using Snell's Law and crown refraction physics.
* **Ray-Tracing Calculations:** Automatically calculates internal reflection radii and total depth percentages.
* **Proportion Analysis:** Provides instant feedback on Crown Height, Pavilion Depth, and Arrowhead reflection limits.


* **Overlay & Alignment Tools:**
* **Image/Video Underlay:** Upload images, paste from clipboard, or use a live camera feed to compare diagrams against real stones.
* **3-Point Circle Alignment:** A specialized tool to mathematically align the parametric diagram to a circular object in an image or video feed.
* **Dual-View Interface:** Simultaneous rendering of **Profile View** and **Crown View** (Plan View).


* **Advanced Image Processing:** Integrated with **OpenCV.js** for potential future auto-fitting and live tracking capabilities.

## 🛠️ Technical Implementation

* **Rendering:** Dual-canvas system using the HTML5 Canvas API for high-DPI schematic rendering.
* **Physics Logic:** Implements refractive index constants ($n = 2.417$ for Diamond) to calculate geometric "V" half-angles and light behavior.
* **Frontend:** Pure vanilla JavaScript, CSS3 (with backdrop filters for a modern UI), and HTML5.
* **Responsive Design:** Fully adaptive layout that shifts control panels for mobile and tablet usage.
