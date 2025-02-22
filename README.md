# Economic Complexity and Export Diversification Dashboard

## Overview
This interactive dashboard provides insights into the trade relationship between the USA and China, focusing on export and import trends. Users can explore how different trade categories have evolved over time and analyze significant trade patterns using interactive visualizations.

## Features
- **User Inputs**: The dashboard allows users to filter data by:
  - Export or Import mode
  - Harmonized System (HS) Code for trade categories
  - Start and End Year for historical analysis
- **Visualizations**:
  - Time-series trends of trade values
  - Export value vs. export share scatterplots
  - Tree maps for category-wise analysis
  - Comparative bar charts
- **Interactivity**:
  - Drop-down selections for real-time updates
  - Hover tooltips for detailed insights
 
## Preview
![image](https://github.com/user-attachments/assets/aebf41a3-96af-48ec-8fef-7f671c548854)
![image](https://github.com/user-attachments/assets/c2593654-f7b9-448a-a67e-8a297968241d)
![image](https://github.com/user-attachments/assets/857dfa1c-ff8e-4fec-86f2-c7842e2593fd)


## Installation
To run the dashboard locally, ensure you have the following dependencies installed:

```bash
pip install dash plotly pandas
```

## Running the Dashboard
To start the dashboard, simply execute the Jupyter Notebook ```Dashboard.ipynb``` file present in the code.

Once the server is running, open your browser and go to:
```
http://127.0.0.1:8050/
```

## Use Case Example: Analyzing Significant Import Categories
### Exploratory Questions:
1. Which import categories are most significant?
2. How have these categories changed over time?
3. What types of goods dominate the import landscape?

### Steps to Explore the Dashboard:
1. **Select 'Import' Mode**: Choose "Import" from the dropdown menu to focus on incoming trade.
2. **Filter by HS Code**: Select specific product categories or leave it at "All" to analyze all imports.
3. **Set the Time Range**: Choose a start and end year to analyze trends over a specific period.
4. **Interpret the Charts**:
   - The tree map provides an overview of the largest import categories.
   - The line chart shows historical trends for each category.
   - The scatterplot of export value vs. export share reveals concentration patterns.
5. **Draw Insights**: Identify key trends, such as shifts in major imports or changes in market dynamics.

## Technologies Used
- **Qlik** (if applicable) or **Dash (Plotly)** for dashboard development
- **Pandas** for data processing
- **Plotly** for interactive visualizations
- **Python** for backend logic

## Future Enhancements
- Incorporating machine learning to predict future trade trends
- Adding more country-wise comparisons
- Improving UI for enhanced user experience

---

### Credits and Authorship
This was done as a group project for the Data Visualization Course at Penn State University.
