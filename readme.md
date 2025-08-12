Trading Dashboard
Overview
This project is a static implementation of a trading dashboard based on a provided Figma design. The goal was to replicate the layout as closely as possible, following the provided specifications. The layout includes a sidebar, header, navigation, market data tables, candlestick chart, and trading panel.

Approach
HTML Structure:

Used semantic HTML5 tags (header, main, section, nav, aside, form) for better accessibility and structure.

Organized markup using clear, descriptive class names inspired by the BEM methodology for scalability.

Styling:

Implemented layout with CSS Grid and Flexbox for precise alignment and spacing.

Used SCSS for maintainable styling with variables for colors, typography, and breakpoints.

Followed the original design’s typography, spacing, and color scheme.

Chart Implementation:

Integrated the Lightweight Charts library for rendering the candlestick chart.

Configured chart styles to match the design (colors, grid lines, scale borders).

Assumptions & Deviations
The Figma file did not provide interactive behavior; therefore, all elements are static.

For the chart, sample data was hardcoded for demonstration purposes.

Minor adjustments in spacing and font sizes were made for better readability on various screen sizes while keeping close to the design.

Breakpoints for responsive behavior were based on standard desktop/tablet/mobile sizes, as they were not explicitly defined in the design.

How to Run
This project is static HTML/CSS/JS and does not require a build process.

Clone the repository:

bash
Copy
Edit
git clone <repository_url>
cd trading-dashboard
Open the index.html file in your browser.

Alternatively, use a local development server for better performance with assets:

bash
Copy
Edit

# Using VS Code Live Server extension

Right-click index.html → Open with Live Server
No additional dependencies or build scripts are required.
