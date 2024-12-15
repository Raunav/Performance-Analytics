# Performance-Analytics

# Performance Analytics: Parsing HTML Tables & Linear Regression Analysis

## Project Overview
This project is part of the **Performance Analytics** course and consists of two tasks:

1. **Task A:** Parsing performance data from HTML tables and automating the extraction process.
2. **Task B:** Analyzing correlations among variables using scatter plots and simple linear regression.

The aim is to demonstrate the ability to:
- Parse structured data (HTML tables).
- Automate data extraction for multiple HTML files.
- Analyze relationships between variables through visualizations and regression analysis.
- Use Python programming and Jupyter Notebooks to implement the tasks.

---

## Task A: Parsing HTML Data
### Objective
The goal of Task A is to extract relevant performance data from downloaded HTML pages containing structured tables.

### Key Steps
1. **Load HTML Files**: Import and read saved HTML files from the disk to avoid repeated server requests.
2. **Identify the Table**: Parse the HTML structure to locate tables with relevant data.
3. **Extract Data**: Select specific rows and columns from the identified table.
4. **Automate Extraction**: Implement a loop to process multiple HTML files with similar structures.

### Libraries Used
- **BeautifulSoup**: Parse and navigate the HTML structure.
- **Pandas**: Store and manage extracted table data in a structured format.
- **os**: Automate reading multiple files from a directory.

### Output
- Cleaned, structured dataset ready for analysis (e.g., saved as a CSV file or Pandas DataFrame).

---

## Task B: Scatter Plots & Linear Regression Analysis
### Objective
Task B focuses on analyzing relationships among variables using scatter plots and simple linear regression.

### Key Steps
1. **Generate Scatter Plots**: Create two scatter plots for selected variables to study correlations.
2. **Linear Regression**: Fit a linear regression model for each scatter plot to analyze trends.
3. **Visualize Results**: Display the scatter plots with the best-fit regression line.
4. **Multi-Panel Visualization**: Combine both scatter plots into a single figure with two panels.
5. **Interpret Results**: Provide insights on variable relationships and correlation patterns.

### Libraries Used
- **Matplotlib**: Create scatter plots and visualizations.
- **Scipy**: Fit linear regression models and calculate best-fit lines.
- **Pandas**: Manage and process data.

### Output
- Two scatter plots with regression lines overlaid.
- A multi-panel figure containing both scatter plots.
- A brief analysis of the correlations observed.

---

## File Structure
The repository contains the following files:
```
Performance_Analytics/
|-- README.md              # Project description and details
|-- Assignment_P2.ipynb    # Jupyter Notebook implementing Task A & Task B
|-- data/                  # Folder containing HTML files (not included)
|-- results/               # Folder for outputs, such as visualizations
```

---

## Instructions to Run the Code
1. **Dependencies**:
   Ensure the following libraries are installed:
   ```bash
   pip install beautifulsoup4 pandas matplotlib scipy
   ```
2. **Download the Notebook**:
   - Clone the repository.
   - Open the `Assignment_P2.ipynb` file in Jupyter Notebook.
3. **Prepare Data**:
   - Place your HTML files in a folder named `data`.
4. **Run the Notebook**:
   - Execute the cells step-by-step to parse data and generate visualizations.
5. **View Results**:
   - Scatter plots and regression lines are displayed inline.
   - Outputs are saved in the `results/` folder.

---

## Sample Visualizations
Here are examples of scatter plots generated by the notebook:

1. **Scatter Plot 1: Variable A vs. Variable B**
2. **Scatter Plot 2: Variable X vs. Variable Y**

Both plots include:
- Data points.
- Best-fit linear regression line.
- Axes labels and titles.

---

## Conclusion
This project demonstrates how to:
- Automate HTML table parsing using Python.
- Analyze performance data with scatter plots and regression models.
- Visualize and interpret correlations between variables.

For any questions or feedback, feel free to reach out!

---

### Author
**Raunav Sharma**

---

### License
This project is licensed under the MIT License.
