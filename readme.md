# Assignment 6 - CIS2C

## Overview
This project solves a problem where a function (`primitiveMultiply`) sometimes fails. We create another function (`reliableMultiply`) to keep trying until it works.

## Files
- **index.html**: Basic HTML structure.
- **script.js**: JavaScript code with the solution.
- **README.md**: Explanation of the project.

## How It Works
- **primitiveMultiply(a, b)**:
  - Multiplies two numbers (works 20% of the time).
  - Throws an error (`MultiplicatorUnitFailure`) 80% of the time.
  
- **reliableMultiply(a, b)**:
  - Keeps trying `primitiveMultiply` until it succeeds.

## Usage
Open `index.html` in a browser and check the console for results.

### Example
```javascript
console.log(reliableMultiply(8, 8)); // Outputs: 64
