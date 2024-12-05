# Cholera Outbreak Visualization Redesign Project

## Overview

This project is a modern redesign of the iconic 1854 cholera outbreak map created by Dr. John Snow. By leveraging contemporary data visualization and interactive techniques, this project aims to provide new insights and perspectives into the historical data, illustrating the relationship between cholera cases and water sources. The interactive visualizations bring the story to life, making it easier to understand how data-driven insights can drive public health initiatives.

## Key Features

- **Historical Context**: Revisits the cholera outbreak and maps deaths geographically to uncover patterns.
- **Interactive Visualizations**: Redesigns classical data into modern interactive formats.
- **Story Component**: Adds descriptive insights to each visualization to highlight the implications of the findings.
- **Data-Driven Insights**: Extracts meaningful conclusions through graphical representation and storytelling.

## Data Pipeline

1. **Data Collection**: Historical cholera outbreak data, including locations and number of deaths.
2. **Data Preparation**:
   - **Cleaning**: Preprocess data to ensure consistency and accuracy.
   - **Transformation**: Add geospatial coordinates and categorize data for visualization.
3. **Visualization Creation**:
   - Leverage Python libraries (e.g., Matplotlib, Seaborn, Plotly) to create compelling graphs and maps.
4. **Output**: Interactive visualizations highlighting spatial relationships and trends.

## Visualizations

### Example 1: Cholera Death Density Map

![Cholera Death Density Map](Screenshot%202024-12-05%20123918.png)

**Description**: This map visualizes the density of cholera deaths across different regions. The clustering around a specific water pump clearly indicates the source of contamination, reinforcing Dr. John Snow’s hypothesis.

---

### Example 2: Time-Series Analysis of Deaths

![Time-Series Analysis](Screenshot%202024-12-05%20124255.png)

**Description**: A time-series analysis displaying the progression of cholera deaths over time. Peaks correspond to periods of high contamination levels.

---

### Example 3: Counterfactual Analysis of Water Sources

![Counterfactual Analysis](Screenshot%202024-12-05%20124323.png)

**Description**: This bar chart analyzes deaths associated with various water sources, highlighting the impact of different water quality scenarios on cholera mortality rates.

---

### Example 4: Comparative Mortality by Proximity to Water Sources

![Comparative Mortality](Screenshot%202024-12-05%20175355.png)

**Description**: This grouped bar chart compares cholera deaths by proximity to different water sources, providing insights into how spatial factors influenced mortality.

---

### Example 5: Social Network Diagram of Cholera Spread

![Social Network Diagram](Screenshot%202024-12-05%20175411.png)

**Description**: A hypothetical social network diagram depicting potential pathways of cholera transmission based on proximity and interactions.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - Matplotlib
  - Seaborn
  - Plotly
- **Tools**: Jupyter Notebook for code execution and visualization development.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cholera-visualization-redesign.git
   cd cholera-visualization-redesign
