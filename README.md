# PDF Merger: Secure, Client-Side Document Manipulation

An elegant, single-file web application designed to merge PDF documents with maximum efficiency and zero data harvesting. 

This tool relies on client-side processing. By leveraging `pdf-lib`, all algorithmic heavy lifting happens strictly within your browser's execution environment. Your data remains yours; it never touches a server.

## 🚀 Core Capabilities

* **Absolute Data Privacy:** 100% client-side execution. No server uploads, no data transit, and no digital footprint.
* **Tactile Document Management:** Intuitive drag-and-drop interface. Seamlessly reorder the execution queue by dragging list items before merging.
* **Adaptive Aesthetics:** Built-in Light and Dark modes with state persistence via `localStorage`.
* **Algorithmic Transparency:** Real-time progress tracking with computationally derived time-remaining estimates, preventing UI blocking during heavy DOM operations.
* **Smart Output Naming:** Dynamically generates the output filename based on the nomenclature of the input files.
* **Architectural Minimalism:** Fully encapsulated in a single `.html` file.

## 🛠️ Technical Architecture

* **HTML5 / CSS3:** Semantic structure and responsive design utilizing CSS variables for frictionless theme switching.
* **Vanilla JavaScript:** ES6+ syntax for logic, state management, and DOM manipulation.
* **[pdf-lib](https://pdf-lib.js.org/):** An objective, robust library for creating and modifying PDF documents in JavaScript (fetched via unpkg CDN).
* **FontAwesome:** Scalable vector icons for a polished user interface (fetched via cdnjs).

## 💻 Usage & Deployment

Because the application is entirely static and single-file, deployment and execution are exceptionally straightforward.

**To run locally:**
1. Clone this repository or simply download the `index.html` file.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Drag and drop your PDFs, arrange them in the desired sequence, and click **Merge PDFs**.
