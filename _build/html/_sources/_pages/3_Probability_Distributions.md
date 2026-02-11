

# Probability Distributions

In this week's tutorial, we will use the techniques from the previous lecture to complete a mini-project. You should save any files you work on as spreadsheets, so you can refer back to them later.

```{exercise}
:label: dist-ex1

(a) Open a blank spreadsheet, and create cells containing the numbers 0 and 1 (labelling them 'mu' and 'sigma'). Create a column of values ranging from -5 to 5, in increments of 0.25. Use the `=NORM.DIST()` function to create a column next to your first one, which calculates the height of the normal distribution for each value in your column, using the values of $\mu$ and $\sigma$ in the cells. Recall that `NORM.DIST` takes as inputs $x$, $\mu$, $\sigma$ (the standard deviation, not the variance!) and a `TRUE`/`FALSE` value for whether or not you want a cumulative distribution.

Hint: you will want to use dollars to fix the cell reference, so you can use the same cell for $\mu$ and $\sigma$ in each row.

(b) Create a plot of these values (with your values from -5 to 5 on the $x$-axis, and the normal distribution values on the $y$-axis). Use a scatter plot with smooth lines, so you can see the curve. Try changing the values of mu and sigma to see how this varies the plot.

(c) Create another column that calculates the same distribution but with the cumulative value set to `TRUE` instead. Plot these values on a separate scatter plot and observe how it changes as you change the statistics $\mu$ and $\sigma$.

(d) On a separate sheet within your spreadsheet, plot a column chart of the binomial distribution using the `=BINOM.DIST()` function, using whole number input values from 0 to 50, with cells for your values of $n$ and $p$ (setting these initially to $10$ and $0.5$). Set the gap width for the bars to be around 10%.

(e) Modify the values of $n$ and $p$ to see how this varies the distribution.

(f) Create another plot of a normal distribution that approximates this binomial distribution (calculating the values of $\mu$ and $\sigma$ as described in the notes - being careful that the spreadsheet formula will be looking for $\sigma$, not $\sigma^2$). Compare this to your binomial plot (you may need to specify the length of the axes so they both show the same range of values).

(g) Copy the series from your normal curve plot by selecting it and using the Copy command, then paste it onto your binomial plot. (It may initially convert the bar chart to a curve, but if you change the chart type to 'combined' it will show both overlaid). Observe what the plots look like when $n<20$, and when $p$ is close to 0 or 1. When is it a good approximation, and when is it less good?

(h) Reset the values to $n=50$ and $p=0.5$, and look closely at the bar for $x=20$. Imagine a vertical line going down through the middle of this bar, and consider the area to the left of this line. How does the area of the binomial bar compare to the area under the curve? If you were to instead consider the area to the left of the line at 20.5 (the right-hand end of the bar), would this more closely match the area under the curve? This is why we use continuity corrections.

```

```{exercise}
:label: dist-ex2

(a) Which of the following datasets might you expect to follow a normal distribution?

* Number of dollars spent annually by customers of a wholesale distributor, in thousands
* Scores attained by students from two different school sets on a test
* Length of raisins, in mm
* Number sold in December 2010 for each item available in an online shop, sold in packs of 4
* Relative performance of the FTSE index on the Istanbul Stock Exchange, each day in 2009
* Heart rates of patients at a maternity clinic in rural Bangladesh

(b) Download the CSV file linked below, and import it into a spreadsheet.

[![CSV icon](../_images/csv-icon-sq.png)](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut3-data1.csv) [tut3-data1.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut3-data1.csv)

(c) For each dataset, plot the data on a histogram and decide whether you think this data is normally distributed. Can you match up the datasets to the list above?

```

```{exercise}
:label: dist-ex3

(a) X ∼ N(31, 2.12). Using the table, then checking your answer with a spreadsheet formula, find:

&emsp;(i) $P(X < 28.8)$

&emsp;(ii) $P(X > 31.5)$

&emsp;(iii) $P(X \leq 33)$

&emsp;(iv) $P(28 \leq X < 29)$


(b) X ∼ N(88, 13.72). Using the table, then checking your answer with a spreadsheet formula, find:

&emsp;(i) $P(X < 84.7)$

&emsp;(ii) $P(X > 84)$

&emsp;(iii) $P(X \leq 89)$

&emsp;(iv) $P(87.4 \leq X < 88.1)$

```