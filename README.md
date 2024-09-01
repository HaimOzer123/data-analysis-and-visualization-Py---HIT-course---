# Haim Ozer - 316063569 

## Project Overview:
This project contains Python code that performs data manipulation, analysis, and visualization. 
The code is designed to read data from Excel files, compute Pearson correlation coefficients between datasets, and visualize the relationships between different variables. 
The files provided include a Python script (e6_s316063569.py) and a Jupyter Notebook (E6_S316063569.ipynb).

### e6_s316063569.py:
**Purpose**: This script includes the main functions used to process the data, calculate correlations, and generate plots.
**Key Functions**:
ReadData(Str, Tpl): Reads data from an Excel file specified by Str and converts selected columns (as per Tpl) into a NumPy array.
PearsonCorrelation(X, Y): Computes the Pearson correlation coefficient between two arrays X and Y.
PlotMyData(Mat, List_num, List_names): Generates plots to visualize the relationship between different variables in Mat based on the indices specified in List_num and names in List_names.

### E6_S316063569.ipynb:
**Purpose**: This Jupyter Notebook file likely contains the interactive implementation of the code, allowing for easier manipulation, testing, and visualization of the data.
It would include similar functions to those in the Python script but within an interactive environment.

### Summary of the Workflow:
Data Reading: The script starts by reading data from Excel files using the ReadData function, which extracts the necessary columns into a NumPy array.
Correlation Calculation: The PearsonCorrelation function calculates the correlation between pairs of variables to assess the strength and direction of their relationship.
Data Visualization: The PlotMyData function plots the data for visual analysis, displaying the correlation coefficient on the plots to facilitate the interpretation of the relationships.

## How to Use:
Ensure that the necessary Excel files (data_1.xlsx, data_2.xlsx) are available in the working directory.
Run the Python script or execute the cells in the Jupyter Notebook to read the data, calculate correlations, and generate plots.
Modify the input parameters as needed to analyze different datasets or visualize other variable combinations.
