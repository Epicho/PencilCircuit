# ✏️ PencilCircuit

PencilCircuit is a lightweight, web-based circuit diagram generator that exports perfectly formatted, hand-drawn (or professional) schematics straight to your clipboard. 

It is designed specifically for analog filter design, making it incredibly easy to generate textbook-accurate diagrams for documentation, lab reports, or web tools like Filter Master.

## ✨ Features

* **Interactive Blueprints:** dynamically generate schematics for passive (RC, RLC) and active (Sallen-Key Low Pass / High Pass) filters.
* **Sketch vs. Pro Mode:** Toggle between a hand-drawn, "engineering sketchbook" aesthetic and a clean, LaTeX-style professional render.
* **Smart Canvas:** The SVG canvas and viewBox automatically resize to perfectly fit complex operational amplifier topologies without clipping.
* **One-Click Export:** Instantly renders the dynamic SVG into a PNG and copies it to your clipboard for seamless pasting into notes or reports.
* **Zero Dependencies:** Built with pure HTML, CSS, and Vanilla JavaScript. No frameworks or build tools required.

## 🛠️ Usage

Since this is a Single Page Application (SPA) contained entirely in one file, running it locally is as easy as it gets:

1. Clone or download this repository.
2. Double-click the `index.html` file to open it in any modern web browser.
3. Select a filter topology from the gallery.
4. Enter your specific component values (Voltage, Resistance, Capacitance).
5. Click **Export Image** and paste your new schematic wherever you need it!

## 🧰 Technologies Used

* **HTML5 / CSS3** for the responsive, grid-based UI.
* **Vanilla JavaScript** for DOM manipulation, SVG path generation, and clipboard API integration.
* **Computer Modern Font** for professional LaTeX-style rendering.
* **Architects Daughter & Gloria Hallelujah** (Google Fonts) for the sketchbook aesthetic.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
