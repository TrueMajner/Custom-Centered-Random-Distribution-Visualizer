### Custom-Centered Random Distribution Visualizer

This project provides a visual representation of a random distribution centered at a custom point within a specified range.

#### Overview
This web application generates a bar chart illustrating the frequency distribution of random values within a user-defined range, with the center point adjustable by the user.

#### How to Use
1. Open the HTML file (`index.html`) in a web browser.
2. Use the sliders to adjust the minimum value, maximum value, and center point.
3. The bar chart will dynamically update to reflect the frequency distribution based on the selected parameters.

#### Dependencies
- Plotly.js: The Plotly JavaScript library is used to create the interactive bar chart.

#### Project Structure
- `index.html`: Contains the HTML structure of the web application, including sliders for user input and a container for the chart.
- Inline JavaScript: Includes functions for generating random numbers, calculating frequencies, and updating the chart based on user input.

#### Functionality
- The `f(x)` function defines the mathematical function used to generate random numbers.
- The `generateNumber()` function generates a random number within a specified range, centered at a given point.
- The `calculateFrequency()` function calculates the frequency distribution of the generated numbers.
- The `updateChart()` function updates the bar chart based on the user's input from the sliders.
