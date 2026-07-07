# NITT ICE — Section A Timetable 🗃️

A high-performance, dark cyber-neon glassmorphism web viewer for the Section A (B.Tech, ICE) flexible curriculum timetable. Built so classmates can track schedules, monitor attendance, and navigate classes seamlessly without digging through cluttered PDFs.

🔗 **Live Site:** [keogodexe.github.io/nitt-ice-timetable](https://keogodexe.github.io/nitt-ice-timetable)

---

## ⚡ What's Inside

* **🧠 Micro-Attendance Dashboard Engine:** Every active subject cell functions as an independent, interactive tracking widget. Classmates can increment/decrement attended ($A$) and total ($T$) classes on the fly with custom logical safety checks (attended classes cannot outpace total counts).
* **💾 LocalStorage State Persistence:** Integrated client-side hydration. Attendance counters seamlessly cache data inside the browser's `localStorage` layer, persisting counts across sessions and site refreshes.
* **📊 Live Percentage Readout:** Dynamically calculates current attendance using:
  $$P = \left( \frac{A}{T} \right) \times 100$$
  Includes safe error-handling for division-by-zero states (`--`) and conditional low-attendance warnings (automatically highlighting sub-75% fields in a sharp crimson glow).
* **↕️ Continuous UI & Optimized Layout:** Displays the full weekly schedule in a hardware-accelerated, single-stretch layout per day. Fully fluid, mobile-optimized, and isolated using CSS `will-change: transform` properties to maximize canvas rendering performance.
* **🌸 Advanced Interactive Aesthetics:**
    * Smooth real-time digital clock synchronized down to the second.
    * Real-time auto-highlighting of the current day's row upon page DOM load.
    * Cursor-following radial glass glow tracking.
    * Isolated structural ripple animations on slot card hover that do not interfere with attendance button interactions.
    * Custom multi-layer background shifting blobs and floating cherry blossom petal physics.
    * Custom glowing, conic-gradient cycling RGB link matrices for social channels.
* **📦 Zero Bloat Infrastructure:** Completely packed into a self-contained, standalone single code file. No frameworks, zero build steps, and zero production runtime dependencies.

---

## 🧬 Course Slot Key & Faculty Mapping

| Slot | Code | Course | Faculty | Credits |
| :--- | :--- | :--- | :--- | :--- |
| **A** | ICPC12 | Electronic Circuits | Dr. Shiraz Sohail | 4 |
| **B** | ICPC13 | Signals and Systems | Dr. A. Ramakalyan | 4 |
| **C** | ICPC14 | Sensors and Transducers | Dr. G. Uma | 3 |
| **D** | MAIR34 | Probability and Distribution Theory | Dr. R. Gowthami | 4 |
| **E** | ICPE64 | Thermodynamics & Fluid Mechanics | Dr. Hemachandran E (Mech) | 3 |
| **F** | ICPC15 | Digital Electronics | Dr. K. Dhanalakshmi | 3 |
| **P1** | ICLR11 | Electric Circuits Laboratory | Dr. K. Dhanalakshmi | 2 |
| **P2** | ICLR12 | Electronic Circuits Laboratory | Dr. Shiraz Sohail | 2 |

---

## 🛠️ Tech Stack

* **Frontend Architecture:** Vanilla HTML5, Advanced CSS3 (Modern Flexbox, CSS Grid, `@property` Houdini animations), and Modern Vanilla ECMAScript (ES6+).
* **Storage Layer:** Browser Native Web Storage API (`localStorage`).
* **Deployment Platform:** GitHub Pages (Static Hosting edge nodes).

---

## 🛡️ Security & Vulnerability Reporting

This platform is strictly maintained for the functional convenience and optimization of the ICE Dept at **National Institute of Technology, Tiruchirappalli**. 

If you are exploring the underlying DOM architecture, scripting mechanisms, local storage state flows, or identify edge cases in the application, please handle findings responsibly. Document any bugs, logical performance bottlenecks, or storage anomalies and submit them directly to the repository maintainer.
