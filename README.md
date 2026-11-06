# Consumer Confidence & Survey Analytics Dashboard

An interactive, single-page web application built to analyze consumer survey data from Jan–Feb 2024. This dashboard provides actionable insights into consumer confidence, sentiment, and buying behavior across different demographics and regions in India.

##  Key Features
- **Interactive Filtering:** Click on any chart bar, pie slice, or table row to filter the entire dashboard dynamically.
- **Executive Summary:** High-level KPIs including a custom Weighted Consumer Confidence Index (CCI), Average Happiness, and Purchase Intent.
- **Demographic Analysis:** Visual breakdowns by Age Group, Product Category, and State.
- **Data Governance:** A dedicated tab showcasing the data cleaning and standardization rules applied (handling duplicates, out-of-bounds scores, and inconsistent naming conventions).
- **Modern UI/UX:** Built with a professional, responsive corporate color palette using Plotly.js and custom CSS.

##  Tech Stack
- **HTML5/CSS3:** For the layout, typography (Inter font), and responsive design.
- **JavaScript (Vanilla):** For state management, data filtering, and dynamic DOM updates.
- **Plotly.js:** For rendering highly interactive and responsive data visualizations.
- **GitHub Pages:** For free, reliable hosting.

##  About the Data
The dataset consists of survey responses spanning two months. To ensure accuracy, the data went through a rigorous cleaning process:
- Removed exact duplicates (`R0006`, `R0026`).
- Nullified out-of-bounds satisfaction scores (e.g., `R0040` had a score of 11 on a 10-point scale).
- Standardized 14 variants of state names into 7 clean regions.
- Handled missing survey dates.

##  Key Insights
1. **The 26–35 Cohort:** This group has the highest buying intent but mid-level satisfaction, representing the biggest opportunity for product experience improvement.
2. **Conversion Gaps:** States like West Bengal and Gujarat show high awareness but lower purchase intent, indicating a need for targeted local interventions.
3. **Electronics:** While average satisfaction is high, lower-end scores suggest a need for better after-sales support.

---
*Created as part of a data analytics portfolio project.*
