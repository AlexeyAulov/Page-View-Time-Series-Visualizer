# Page-View-Time-Series-Visualizer
Visualized time series data using a line chart, bar chart, and box plots. I used Pandas, Matplotlib, and Seaborn to visualize the dataset containing the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03.

•Used Pandas to import the data from "fcc-forum-pageviews.csv". Set the index to the date column.

•Cleaned the data by filtering out days when the page views were in the top 2.5% of the dataset or bottom 2.5% of the dataset.

•Created a draw_line_plot function that uses Matplotlib to draw a line chart similar to "examples/Figure_1.png". The title should be Daily freeCodeCamp Forum Page Views 5/2016-12/2019. The label on the x axis would be Date and the label on the y axis would be Page Views.

•Created a draw_bar_plot function that draws a bar chart similar to "examples/Figure_2.png". It would show average daily page views for each month grouped by year. The legend should show month labels and have a title of Months. On the chart, the label on the x axis should be Years and the label on the y axis should be Average Page Views.

•Created a draw_box_plot function that uses Seaborn to draw two adjacent box plots similar to "examples/Figure_3.png". These box plots would show how the values are distributed within a given year or month and how it compares over time. The title of the first chart should be Year-wise Box Plot (Trend) and the title of the second chart would be Month-wise Box Plot (Seasonality). Made sure the month labels on bottom start at Jan and the x and y axis are labeled correctly. 
