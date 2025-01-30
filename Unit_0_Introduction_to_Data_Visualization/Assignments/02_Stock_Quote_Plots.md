# Unit 0, Assignment 02: Stock Quote Plots
Due: Friday, January 31st 2025

## DataCamp
**Course 8: Introduction to Data Visualization with Matplotlib:** <br>
[Chapter 1: Introduction to Matplotlib > Video 1: Introduction to Data Visualization with MatPlotLib](https://campus.datacamp.com/courses/introduction-to-data-visualization-with-matplotlib/introduction-to-matplotlib?ex=1) + Exercises<br>
[Chapter 1: Introduction to Matplotlib > Video 2: Customizing Your Plots](https://campus.datacamp.com/courses/introduction-to-data-visualization-with-matplotlib/introduction-to-matplotlib?ex=4) + Exercises

## Assignmment
**Reminder:** As you work, remember to comment, run, save, commit, and revise frequently.
1. Configure .csv files...

   For each file:
     * Format all cells in column A as Dates (YYYY-MM-DD).
     * Format all cells in columns B, D, E, and F as Currency.
     * Sort your data by column A (ascending)
     * Save, upload, and commit.
       
2. Create a new Jupyter Notebook file in your `Stock_Market_Project` folder titled, `LastNameFirstInitial_Stock_Market_Project.ipynb`.  
3. Import pandas and pyplot.
4. Select two stocks and import the data from their .csv files as dataframes.
5. For each data frame, set the `'Date'` column as the index.
6. Generate a slice of each data frame containing the most recent month of stock quote data.
7. Generate figure and axes objects to hold your plot.
8. Plot the most recent month of stock quote data for one of your stocks, using the index (date) for the x-axis and the closing price for the y-axis.
9. Write a command to display your plot.  As you continue to code, remember to leave this line of code at the bottom of your code.
10. On the same set of axes, plot the most recent month of stock quote data for your other stock.
11. Customize your plots:
       * Rotate and adjust the alignment of the x-ticks to make them visible.
       * Add labels to each axis, and a title to your chart.
       * Set a color and linestyle for each plot.
       * Add markers to each plot.
       * Add a legend.
