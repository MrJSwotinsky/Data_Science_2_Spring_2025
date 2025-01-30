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
|Open the tickers for the six stocks you selected.<br><br>How have you stocks performed over the last day? week? month? etc.<br><br>Have you noticed anything noteworthy about any of your stocks?<br><br>What do you wonder?|

**AGENDA:**
1. Stock Share Out
2.

**ASSIGNMENT:** 
<br>[Unit 0 Assignment 02 - Stock Quote Plots](https://github.com/MrJSwotinsky/Data_Science_2_Spring_2025/blob/main/Unit_0_Introduction_to_Data_Visualization/Assignments/02_Stock_Quote_Plots.md)

## Resources
**Pandas Code Reference:** <br>
|Code|Description|
|---|---|
|`my_dataframe = read_csv('my_file.csv')`|imports data from `'my_file.csv'` as a dataframe assigned to `'my_dataframe'`.|
|`my_dataframe = my_dataframe.set_index('my_column')`|sets `'my_column'` as the index of `my_dataframe`.|
|`my_slice = my_dataframe.loc['start_index':'end_index']`|generates a horizontal slice of `my_dataframe` containing all rows from `start_index` to `end_index`.<br><br>**Note:** `my_slice = my_dataframe.loc['start_index':]` generates a horizontal slice of `my_dataframe` containing all rows from `start_index` to the last row of the dataframe.<br><br>**Note:** `my_slice = my_dataframe.loc[:'end_index']` generates a horizontal slice of `my_dataframe` containing all rows from the first row of the dataframe to `end_index`.|
