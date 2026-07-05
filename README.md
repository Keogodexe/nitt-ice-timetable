# NITT ICE — Section A Timetable

A clean, dark glassy web view of the Section A (B.Tech, ICE) flexible curriculum timetable — built so classmates can check their schedule without squinting at a PDF.

🔗 **Live site:** [keogodexe.github.io/nitt-ice-timetable](https://keogodexe.github.io/nitt-ice-timetable)

## What's inside

* **Continuous UI:** Full weekly timetable in one continuous stretch per day — morning through evening, no separate tables.
* **Integrated Labs:** Lab schedule (P / Q / X slots) woven directly into the same row.
* **Quick Reference:** Color-coded subject legend and course reference cards with faculty names and credits.
* **Glassmorphism Design:** Frosted blur, glowing gradient borders, animated background blobs, and floating cherry blossoms.
* **JavaScript Interactivity:**
    * Live clock in the header (updates every second).
    * Live page visit counter pulling from namespace API.
    * Today's day-row auto-highlights on load.
    * Cursor-following glass glow effect.
    * Cursor-entry ripple animation on hover for every subject card.
    * Glowing RGB-cycling social links (Instagram, GitHub) at the bottom of the page.
* **Zero Bloat:** Single self-contained `index.html` — no build step, no dependencies.

## Course Slot Key

| Slot | Code | Course | Faculty |
| :--- | :--- | :--- | :--- |
| **A** | ICPC12 | Electronic Circuits | Dr. Shiraz Sohail |
| **B** | MAIR34 | Probability & Distribution Theory | Maths Dept |
| **C** | ICPC14 | Sensors & Transducers | Dr. G. Uma |
| **D** | ICPC13 | Signals & Systems | Dr A Ramakalyan |
| **E** | ICPE64 | Thermodynamics & Fluid Mechanics | Mech. Dept. |
| **F** | ICPC15 | Digital Electronics | Dr. K. Dhanalakshmi |
| **P** | ICLR11 | Electric Circuits Laboratory | Dr. K. Dhanalakshmi |
| **Q** | ICLR12 | Electronic Circuits Laboratory | Dr. Shiraz Sohail |

## Tech Stack
Plain HTML/CSS/JavaScript, hosted free via GitHub Pages. No frameworks, no build tools, no dependencies.

## Security & Vulnerability Reporting
This system is maintained for the convenience of ICE Dept · NIT Tiruchirappalli students. If you intend to poke around the source, test the live count API, or identify any vulnerabilities in the DOM/hosting implementation, do not exploit them. Please document your findings and report them directly to me.
