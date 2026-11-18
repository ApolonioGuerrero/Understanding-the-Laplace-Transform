# Laplace Explorer 2.0: From Differential Equations to Algebra

**GitHub Description:** A highly interactive, visual web laboratory for understanding the Laplace Transform. Connects the time domain to the s-domain through real-time graphs and animated physical models to demystify differential equations.

## Overview
The **Laplace Explorer** is a self-contained, interactive educational web application designed to help students bridge the conceptual gap between calculus (the time domain, $t$) and algebra (the frequency domain, $s$). 

Instead of treating the Laplace transform as a black-box formula, this tool visually breaks down the improper integral $\int_0^\infty f(t)e^{-st}dt$ step-by-step, showing exactly how the exponential weighting kernel tames growing signals and transforms derivatives into simple algebraic polynomials.

## Key Features
* **Synchronized 4-Graph Laboratory:** Drag a slider on the $s$-axis and watch how the weighting kernel $e^{-st}$ instantly updates the time-domain product and the running integral accumulation.
* **Interactive ODE Walkthroughs:** Step-by-step visual proofs showing how Initial Value Problems (IVPs) are converted from differential equations to algebraic equations and back.
* **Animated Physical Models:** Live HTML5 canvas animations of unbounded growth and mass-spring-damper systems that dynamically sync with the selected differential equations.
* **Prerequisite Review Center:** Built-in interactive modules to help students refresh their understanding of exponential decay, infinite areas, and integration by parts.
* **Publication-Quality Math:** Fully integrated with MathJax 3 for crisp, dynamic rendering of all equations and mathematical notation.

## Tech Stack
* **Frontend:** Vanilla JavaScript, HTML5 Canvas API
* **Styling:** Tailwind CSS (via CDN)
* **Typesetting:** MathJax 3

## Usage
This project is entirely self-contained in a single HTML file. There are no build steps, dependencies, or local servers required.

1. Clone or download the repository.
2. Double-click `index.html` to open it in any modern web browser.
3. Start exploring!

## Target Audience
This tool is perfect for undergraduate engineering, physics, and mathematics students currently enrolled in an introductory Ordinary Differential Equations (ODE) or Signals and Systems course, as well as educators looking for interactive visual aids.