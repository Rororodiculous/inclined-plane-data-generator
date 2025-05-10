# Inclined Plane Data Generator

This simple web-based tool simulates position data for an object moving down an inclined plane. It is designed for educational use, allowing students to generate a realistic set of position-time data with built-in physics and randomness.

## Features
- Uses the equation:  
  **y(t) = -1/2 * g * sin(theta) * t^2 + initial height**
- Random angle (theta) between **20° and 40°**
- Position values are scaled to start at **1.5 meters** at time zero
- Adds normally distributed noise with standard deviation <8% of the position value
- Outputs 25 evenly spaced data points across a suitable time range (to keep all values positive)
- Data is formatted as **CSV** for easy pasting into Excel or Google Sheets

## Format of Output
