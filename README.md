COMPANY NAME :CODETECH IT

NAME:Mithun R K

ID:CT04DG797

DURATION:08-06-2025 TO 08-07-2025

MENTOR:NEELA SANTHOSH KUMAR

Description of the Code:

Automated Sales Report Generation using Pandas and Matplotlib

This Python script demonstrates automated data visualization by generating a line chart from sales data and saving it as a PDF report. It uses two key libraries: pandas for data handling and matplotlib for plotting.

 Line-by-Line Explanation

Import necessary libraries
import pandas as pd import matplotlib.pyplot as plt

pandas: used for managing and analyzing tabular data.

matplotlib.pyplot: used for creating plots and charts.

Create a sample dataset
data = { 'Day': ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun'], 'Sales': [200, 150, 300, 280, 500, 700, 650] }

A dictionary with days of the week and corresponding sales values is defined.

Convert the data into a DataFrame
df = pd.DataFrame(data)

This converts the dictionary into a pandas DataFrame for easy data handling and plotting.

Set the plotting style
plt.style.use('ggplot')

Sets a predefined plotting style for better visual appearance. 'ggplot' gives a grid and soft color palette.

Create the plot
plt.figure(figsize=(10, 6)) plt.plot(df['Day'], df['Sales'], marker='o', linestyle='-', color='blue')

Initializes a figure of size 10x6 inches.

Plots sales data with blue lines and circular markers.

Add chart titles and labels
plt.title('Weekly Sales Report', fontsize=16) plt.xlabel('Day of the Week') plt.ylabel('Sales') plt.grid(True)

Adds a title and labels for X and Y axes.

Enables the grid for easier data reading.

Save and display the chart
plt.savefig("sales_report.pdf") plt.show()

Saves the plot as a PDF named sales_report.pdf.

Displays the chart in a window.

 Purpose of the Code

This is a basic automated report generation script.

It visualizes weekly sales performance and outputs it as a PDF chart.

Useful for sales monitoring, performance dashboards, and business reports.

OUTPUT:

![Image](https://github.com/user-attachments/assets/5ada7649-ffab-4944-83da-d1e9fa75bd56)
