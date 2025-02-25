# Final Exam - EDGE 213902127 - Mahin - 25/02/2025

This Jupyter Notebook contains the final exam submission for the course **EDGE 213902127** by **Mahin**, dated **25/02/2025**. The notebook demonstrates various data analysis and manipulation tasks using **Pandas** and **NumPy** libraries in Python.

## Overview

The notebook is divided into several sections, each focusing on a specific task related to data analysis, array manipulation, and statistical calculations. Below is a summary of the tasks performed:

### 1. **Pandas and NumPy Installation**
   - The notebook begins by installing the necessary libraries (`pandas` and `numpy`) using `pip`.

### 2. **Employee Data Analysis**
   - The dataset `employees_large.csv` is loaded using Pandas.
   - The average salary per department is calculated.
   - The department with the highest average salary is identified.

### 3. **Sales Data Analysis**
   - The dataset `sales_large.csv` is loaded using Pandas.
   - Total sales per product per region are calculated.
   - The product with the highest total sales is identified.

### 4. **Array Manipulation with NumPy**
   - Two 3x3 matrices (`A` and `B`) are created using NumPy.
   - Element-wise sum and product of the matrices are computed.
   - The dot product of matrix `A` and the transpose of matrix `B` is calculated.
   - The determinant of matrix `A` is computed.

### 5. **Statistical Analysis with NumPy**
   - A random dataset of 10,000 values is generated using NumPy.
   - Basic statistical measures (mean, median, standard deviation, min, max) are calculated.
   - The number of values greater than the mean is counted.
   - The data is normalized and a sample of the normalized data is displayed.

### 6. **Temperature Data Analysis**
   - A list of temperatures is provided.
   - Temperatures above 32°C are filtered.
   - Each temperature is classified as "Hot", "Warm", or "Cool".
   - The monthly average temperature is calculated.
   - The difference between each temperature and the monthly average is computed.

## Key Takeaways

- **Pandas** is used for data manipulation and analysis, particularly for handling CSV files and performing group-by operations.
- **NumPy** is used for numerical computations, including array operations, matrix manipulations, and statistical calculations.
- The notebook demonstrates how to perform basic data analysis tasks such as calculating averages, sums, and statistical measures.
- The temperature analysis section shows how to filter, classify, and compute differences in a dataset.

## How to Run the Notebook

1. Ensure that Python 3.x is installed on your system.
2. Install the required libraries using the following commands:
   ```bash
   pip install pandas
   pip install numpy
   ```
3. Download the datasets (`employees_large.csv` and `sales_large.csv`) and place them in the appropriate directory.
4. Open the Jupyter Notebook and run each cell sequentially to reproduce the results.

## Conclusion

This notebook serves as a comprehensive example of how to use Python for data analysis and manipulation. It covers a wide range of tasks, from basic data loading and aggregation to advanced statistical and numerical computations. The code is well-structured and can be easily adapted for similar datasets and tasks.

---

**Author:** Mahin  
**Date:** 25/02/2025  
**Course:** EDGE 213902127
