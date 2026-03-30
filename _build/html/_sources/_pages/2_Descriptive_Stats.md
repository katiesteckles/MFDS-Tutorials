

# Descriptive Statistics

In this week's tutorial, we will use techniques from statistics to complete a mini-project. You should save any files you work on as spreadsheets, so you can refer back to them later.

In the below, where you are asked to calculate 'by hand', you can use a calculator, but should work it out yourself rather than asking the spreadsheet to calculate it.


```{exercise}
:label: desc-ex1

(a) Download the CSV file linked below, and import it into a spreadsheet.

[![CSV icon](../_images/csv-icon-sq.png)](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data1.csv) [tut2-data1.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data1.csv)

(b) Select one whole column from the data, and use **Insert > Scatter Plot** to create a chart of the data. Use **Switch Row/Column** to make it into a one-dimensional plot showing the values on a single line. (Remember that multiple points with the same value will show as a single point.)

(c) Where do you think the mean of this dataset will be? First estimate by looking at the plot (and type your estimate into a cell in the spreadsheet), then calculate it by hand, and then use the `=AVERAGE()` function to check your answer.

(d) Repeat this for each of the other columns in the data: creating separate charts for each, and estimating then calculating the mean. (You could also create one chart using all the columns, and then **Switch Row/Column** will show each as a separate line.)

(e) Which of the datasets do you think has the largest and smallest standard deviation? Make an estimate by looking at the charts, then calculate them (first by hand, then check using the `=STDEV.S()`(Excel) / `=STDEV()` (Sheets) function.)

```

```{exercise}
:label: desc-ex2

(a) Download the CSV file linked below, and import it into a spreadsheet. The data records measurements of the sizes of the petals and sepals of a particular species of iris.

[![CSV icon](../_images/csv-icon-sq.png)](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data2a.csv) [tut2-data2a.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data2a.csv)

(b) Calculate the mean, median, mode, variance and standard deviation for each of the datasets.

(c) What do these statistics tell you about the different data sets? Comment on the similarities and differences. (Type your answers into a cell in the spreadsheet, so you have a record of it.)

(d) Download the CSV file linked below, and import it into a spreadsheet. The data records the same measurements as the first, but for a different species of iris.

[![CSV icon](../_images/csv-icon-sq.png)](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data2b.csv) [tut2-data2b.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data2b.csv)

(e) From looking at the table, which of the datasets would you expect to have the smallest/largest mean and smallest/largest standard deviation? (Make notes in the spreadsheet to record your predictions.)

(f) Calculate an estimate for the mean, median, mode, variance and standard deviation for each of the datasets, and compare these to your predictions.

(g) Explain why, given this data, you can only estimate the mean and not calculate it
precisely. (Type your answer into a cell in the spreadsheet, so you have a record of it.)

(h) How might you calculate the largest and smallest possible values the mean could take for each dataset?

Data: Fisher, R. (1936). Iris [Dataset]. UCI Machine Learning Repository. [https://doi.org/10.24432/C56C76](https://doi.org/10.24432/C56C76).


```

```{exercise}
:label: desc-ex3

(a) Download the CSV file linked below, and import it into a spreadsheet.

[![CSV icon](../_images/csv-icon-sq.png)](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data3.csv) [tut2-data3.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut2-data3.csv)

(b) Pick 4 of the datasets (including $x$ and $y$ data) from the 13 sets, and for each one, create a scatter plot of the $x$ and $y$ values against each other on a pair of axes, by creating a chart in Excel.

(c) For each of the pairs you have chosen, calculate (and round to two decimal places using the function `=ROUND(x,2)`) the mean and sample variance of the $x$ values, and the mean and sample variance of the $y$ values. What do you notice?

(d) Extend this to the rest of the datasets.

```

**Further reading:**

* [The Datasaurus Dozen](https://en.wikipedia.org/wiki/Datasaurus_dozen)
* [The Databet](https://mscroggs.co.uk/blog/101)