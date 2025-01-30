# Data Science 2
Thursday, January 30th 2025

## Plotting Stock Quotes

**AIM:** How can we plot data and in what ways can we customize plots?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TYS66T.3</ins>: Refine, manipulate, and visualize data.

**SUCCESS CRITERIA:**
- [ ] I can use `matplotlib.pyplot` to plot data.
- [ ] I can use `matplotlib.pyplot` to customize plots.

|DO NOW|
|---|
|Open the tickers for the six stocks you selected.<br><br>How have you stocks performed over the last day? week? month? etc.<br><br>Have you noticed anything interesting and/or intriguing about any of your stocks?|

**AGENDA:**
1. Stock Share Out
2. Code-Along
    * Configure .csv Files
    * Import Stock Data
    * Set Indices of Stock Data
    * Slice Stock Data
    * Plot Stock Data
    * Customize Our Plots  

**ASSIGNMENT:** 
<br>[Unit 0 Assignment 02 - Stock Quote Plots](https://github.com/MrJSwotinsky/Data_Science_2_Spring_2025/blob/main/Unit_0_Introduction_to_Data_Visualization/Assignments/02_Stock_Quote_Plots.md)

## Resources
**Course 8: Introduction to Data Visualization with Matplotlib:** <br>
[Chapter 1: Introduction to Matplotlib > Video 1: Introduction to Data Visualization with MatPlotLib](https://campus.datacamp.com/courses/introduction-to-data-visualization-with-matplotlib/introduction-to-matplotlib?ex=1)<br>
[Chapter 1: Introduction to Matplotlib > Video 2: Customizing Your Plots](https://campus.datacamp.com/courses/introduction-to-data-visualization-with-matplotlib/introduction-to-matplotlib?ex=4)

**Pandas Code Reference:** <br>
|Code|Description|
|---|---|
|`my_dataframe = read_csv('my_file.csv')`|imports data from `'my_file.csv'` as a dataframe assigned to `'my_dataframe'`.|
|`my_dataframe = my_dataframe.set_index('my_column')`|sets `'my_column'` as the index of `my_dataframe`.|
|`my_slice = my_dataframe.loc['start_index':'end_index']`|generates a horizontal slice of `my_dataframe` containing all rows from `'start_index'` to `'end_index'`.<br><br>**Note:** `my_slice = my_dataframe.loc['start_index':]` generates a horizontal slice of `my_dataframe` containing all rows from `'start_index'` to the last row of the dataframe.<br><br>**Note:** `my_slice = my_dataframe.loc[:'end_index']` generates a horizontal slice of `my_dataframe` containing all rows from the first row of the dataframe to `'end_index'`.|

**Pyplot Code Reference:** <br>
|Code|Description|
|---|---|
|`fig, ax = plt.subplots()`|generates figure and axes objects to hold a plot.|
|`plt.show()`|displays a plot.|
|`ax.plot(my_dataframe['x_column'], my_dataframe['y_column'])`|generates a line plot from data in `'x_column'` and `'y_column'` of `my_dataframe`.<br><br>**Note 1:** `'x_column'` and `'y_column'` may represent any two columns.<br><br>**Note 2:** `my_dataframe.index` can replace `my_dataframe['x_column']` to use indices instead of column values for the x-axis.|

**Customization** <br>
|Code|Description|
|---|---|
|`ax.plot()` parameters|`color = 'plot_color'` sets the color of the plot to `'plot_color'`.<br><br>`linestyle = 'plot_linestyle'` sets the linestyle of the plot to `'plot_linestyle'`.<br>(`'_'` for a solid line, `'--'` for a dashed line, `'-.'` for a dash-dot line, `':'` for a dotted line, or `'None'` for no line).<br><br>`markers = 'plot_marker'` adds `plot_marker` style markers to the plot. [Click here for a list of marker styles.](https://matplotlib.org/stable/gallery/lines_bars_and_markers/marker_reference.html)<br><br>`label = 'plot_label'` sets the label of the plot to `'plot_label'`.|
|`ax.legend()`|displays a legend.<br><br>**Note:** The `ax.plot()` `label` parameter(s) must be set to display a legend.|
|`ax.set_xlabel('x-axis label')`|adds the label, `'x-axis label'` to the x-axis.|
|`ax.set_ylabel('y-axis label')`|adds the label, `'y-axis label'` to the y-axis.|
|`ax.set_title('plot title')`|adds the title, `'plot title'` to the plot.|
|`plt.xticks()` parameters|`rotation = deg` rotates the tickmarks along the x-axis `deg` degrees.<br><br>`ha = 'alignment'` sets the horizontal alignment of the tickmarks along the x-axis to `alignment`.<br>(`'left'`,`'center'`, or `'right'`).|
