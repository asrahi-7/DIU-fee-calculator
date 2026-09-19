# DIU CSE Semester Fee Calculator 🎓

A modern, interactive web application designed for students of the Department of Computer Science and Engineering (CSE) at Daffodil International University (DIU). This tool helps students accurately calculate their final exam clearance fees by factoring in core credits, GED credits, labs, retakes, waivers, and previously paid installments.

**🌐 Live Demo:** [https://asrahi-7.github.io/DIU-fee-calculator/](https://asrahi-7.github.io/DIU-fee-calculator/?utm_source=gemini)

## ✨ Features

* **Smart Waiver Logic:** Automatically applies waiver percentages to regular courses while properly excluding retake credits (as per university policy).
* **Course Reference Guide:** Built-in reference list of common GED and Core courses to help you identify credit types.
* **Modern UI & VFX:** Glassmorphism aesthetic, floating background particles, glowing interactive inputs, and animated number counting for a premium user experience.
* **Real-time Breakdown:** Instant calculation with a detailed, itemized view of gross fees, waivers, and deductions.

## ⚙️ How It Works

The calculator processes your semester data through a step-by-step logic flow to determine the exact amount needed to clear your final exam block:

1. **Enter Regular Credits:** Input the number of new Core, GED, and Lab credits you are taking this semester.
2. **Enter Retakes:** Input any retake credits in the second section. *The system automatically isolates these so waivers are not applied to them.*
3. **Verify Fee Rates:** The per-credit rates are pre-filled with standard CSE department fees (5,100 Tk for Core, 3,500 Tk for GED, 5,800 Tk for Labs) but can be manually adjusted if your specific fee structure differs.
4. **Apply Deductions:** Enter your university waiver percentage and verify the amounts you have already paid (Registration Fee + initial 4 credits).
5. **Calculate:** Click the calculation button. The system computes the gross total, applies the waiver strictly to regular credits, adds retake fees at full price, subtracts your initial payments, and outputs the final exact amount due before exams.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and modal integration.
* **CSS3:** Custom animations, keyframes, flexbox/grid layouts, and glassmorphism styling.
* **Vanilla JavaScript:** DOM manipulation, mathematical calculation logic, and custom number-counting visual effects without external libraries.
