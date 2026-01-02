# United States GDP Bar Chart (D3.js)

![Bar Chart Preview](https://via.placeholder.com/900x500.png?text=US+GDP+Bar+Chart)  
*(Interactive bar chart showing quarterly US GDP growth over time – hover for details)*

## Description

This project is an interactive **bar chart** created with **D3.js** that visualizes the Gross Domestic Product (GDP) of the United States over time (quarterly data from 1947 onwards).

It completes the freeCodeCamp "Visualize Data with a Bar Chart" project in the Data Visualization certification.

### Features
- Vertical bar chart displaying US GDP in billions of dollars
- X-axis: Time (years and quarters)
- Y-axis: GDP value (in billions)
- Bars change color on hover
- Tooltip on hover showing exact date and GDP value
- Clean, responsive styling with shadow and centered layout

## Live Demo
[View the live project here](https://your-hosted-url.example.com) <!-- Replace with your actual link (e.g., GitHub Pages, CodePen) -->

## Technologies Used
- HTML5
- CSS3 (inline styles)
- JavaScript
- [D3.js v7](https://d3js.org/)

## Data Source
- GDP data: `https://cdn.freecodecamp.org/testable-projects-fcc/data/bar-chart/gdp.json`  
  Source: U.S. Bureau of Economic Analysis (via Federal Reserve Economic Data - FRED)

## Project Structure
├── index.html      # Main HTML file with inline CSS
├── script.js       # D3.js logic for loading data, scales, axes, bars, and tooltip
└── README.md       # This file

## How to Run Locally
1. Save the provided HTML code as `index.html`.
2. Create a separate `script.js` file with your D3 code.
3. Open `index.html` in any modern browser.
4. The chart loads data directly from the remote JSON source – no server needed.

## freeCodeCamp User Stories Completed
- Title element with `id="title"`
- SVG with appropriate width and height
- Bars with `class="bar"` and correct `data-date` / `data-gdp` attributes
- Axes properly scaled and labeled
- Tooltip with `id="tooltip"` showing date and GDP on hover (with `data-date` attribute)
- At least 4px padding between bars
- All freeCodeCamp tests pass

## Screenshot
![Chart Screenshot](https://via.placeholder.com/900x500.png?text=US+GDP+Bar+Chart+Screenshot)  
*(Replace placeholders with your actual screenshots)*

## License
MIT License – free to use, modify, and share!
