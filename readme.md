# Trading Dashboard
## Overview
This project is a static implementation of a trading dashboard based on a provided Figma design. The goal was to replicate the layout as closely as possible, following the provided specifications. The layout includes a sidebar, header, navigation, market data tables, candlestick chart, and trading panel.

<img width="1452" height="663" alt="2025-08-13_00-57-38" src="https://github.com/user-attachments/assets/af38c9f3-b96d-48ce-a2a5-e101939c73f0" />

## Approach
### HTML Structure:
- Used semantic HTML5 tags (`header`, `main`, `section`, `nav`, `aside`, `form`) for better accessibility and structure.
- Organized markup using clear, descriptive class names inspired by the BEM methodology for scalability.
### Styling:
- Implemented layout with CSS Grid and Flexbox for precise alignment and spacing.
- Used SCSS for maintainable styling with variables for colors, typography, and breakpoints.
- Followed the original design’s typography, spacing, and color scheme.
### Chart Implementation:
- Integrated the Lightweight Charts library for rendering the candlestick chart.
- Configured chart styles to match the design (colors, grid lines, scale borders).

## Assumptions & Deviations
- The Figma file did not provide interactive behavior; therefore, all elements are static.
- For the chart, sample data was hardcoded for demonstration purposes.
- Minor adjustments in spacing and font sizes were made for better readability on various screen sizes while keeping close to the design.
- Breakpoints for responsive behavior were based on standard desktop/tablet/mobile sizes, as they were not explicitly defined in the design.

## How to Run
This project is static HTML/CSS/JS and does not require a build process.

```bash
git clone https://github.com/your-username/trading-dashboard.git
cd trading-dashboard
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
