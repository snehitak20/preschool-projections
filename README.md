# Preschool Capacity Projections

An interactive, real-time financial and staffing projection dashboard for preschools operating under California Title 22 childcare regulations. 

🌐 **Live Website:** [https://snehitak20.github.io/preschool-projections/](https://snehitak20.github.io/preschool-projections/)

---

## Overview

This tool helps preschool directors, operators, and prospective owners model the financials and staffing levels of their childcare facility. It dynamically calculates staffing ratios, payroll costs, operational overhead, and debt servicing across multiple enrollment scenarios (from 60% to 100% capacity) and compares them against current actual figures.

Built strictly in compliance with **California Title 22** childcare regulations, the application ensures that staffing recommendations and calculations meet the legally mandated adult-to-child ratios for both infant and preschool-aged classrooms.

---

## Key Features

- **Interactive Modeling Side-Panel:** Adjust tuition rates (infant & preschool), staff compensation (base rates, qualifications premium, aide wages), overhead operations, payroll burdens, and capacity targets in real time.
- **Scenario Comparison:** View a side-by-side projection table contrasting 60%, 70%, 80%, 90%, and 100% capacity scenarios against your current actual figures.
- **Staffing Detail Breakdowns:**
  - Dynamic teacher/aide allocation logic based on CA Title 22 ratios (1:4 for infants, 1:12 for preschoolers).
  - Room-by-room staffing calculations.
  - Qualification adjustments (including infant-qualified premium pay).
- **Financial Analysis & Visualization:**
  - Real-time SVGs charting Revenue vs. Expenses across projection tiers.
  - Marginal revenue analysis per added child.
  - Staffing step-up break-even thresholds (how many kids are needed to justify adding another employee).
- **SBA 7(a) Loan Integration:** Calculate monthly principal & interest, annual debt service, and total repayment costs for site acquisition or renovations.
- **Mobile Responsive Design:** Accessible on-the-go with custom drawer layouts, mobile touch overlays, and responsive tables.

---

## Technical Architecture

The application is built entirely as a single-page app (SPA) without external database dependencies or server-side requirements:

- **HTML5:** Semantic layouts and clean interactive structure.
- **CSS3:** Responsive layout using CSS Grid, Flexbox, and Media Queries. Styled with a modern, high-contrast palette (Navy & Slate with vibrant Accent styling).
- **Vanilla JavaScript:** Fast, client-side state machine. All dynamic updates, SVG chart drawing, math projections, and slider rendering are performed in real-time on value changes.

---

## Regulations Supported

- **Infants (0-24 Months):** Staff-to-child ratio of **1:4** (Title 22 California).
- **Preschoolers (2-5 Years):** Staff-to-child ratio of **1:12** (Title 22 California).

---

## How to Run & Deploy

### Local Development
To run the dashboard locally:
1. Clone this repository:
   ```bash
   git clone https://github.com/snehitak20/preschool-projections.git
   ```
2. Navigate into the folder:
   ```bash
   cd preschool-projections
   ```
3. Open the `index.html` file in your preferred web browser.

### Hosting on GitHub Pages
This project is configured to run out-of-the-box on GitHub Pages. Any changes pushed to the `main` branch will automatically update the live site at:
[https://snehitak20.github.io/preschool-projections/](https://snehitak20.github.io/preschool-projections/)
