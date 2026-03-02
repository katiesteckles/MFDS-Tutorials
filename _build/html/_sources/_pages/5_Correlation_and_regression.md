

# Correlation and Regression

In this week's tutorial, we will use the techniques from the previous lecture to complete a mini-project. You should save any files you work on as spreadsheets, so you can refer back to them later.

```{exercise}
:label: correg-ex1

For each of the datasets below, calculate the covariance - first by hand, then using a table in a spreadsheet (with columns for $x$, $x-\bar{x}$, $y$ and $y-\bar{y}$). Then check using the `COVARIANCE.S()` function.

(a)

 | *X* | *Y* |
|---|---|
|5 | 1| 
 |  7 | 2| 
 |  8 | 3| 
 |  2 | 3| 
 |  3 | 1| 
 |  3 | 3|
   
---

(b)

 | *X* | *Y* |
|---|---|
|7 | 9| 
 |  9 | 7| 
 |  7 | 4| 
 |  7 | 6| 
 |  2 | 1| 
 |  3 | 6|
      
---
       
(c)

 | *X* | *Y* |
|---|---|
|9 | 7| 
 |  4 | 8| 
 |  1 | 8| 
 |  2 | 1| 
 |  7 | 4| 
 |  6 | 4|

---  
             
(d)

 | *X* | *Y* |
|---|---|
|6 | 10| 
 |  5 | 8| 
 |  7 | 7| 
 |  8 | 1| 
 |  8 | 9| 
 |  9 | 6|
   
---
              
(e) 

 | *X* | *Y* |
|---|---|
|3 | 8| 
 |  3 | 7| 
 |  8 | 3| 
 |  1 | 10| 
 |  2 | 8| 
 |  5 | 5|

```


```{exercise}
:label: correg-ex2

(a) Choose your favourite example from the [Tyler Vigen Spurious Correlations website](https://www.tylervigen.com/spurious-correlations) (you can use the 'Random' link to generate a random entry, or scroll down the full list).

(b) Load the full page, and scroll down to the table of data. Copy and paste the data into a spreadsheet, and plot it on a scatter plot.

(c) Use the `=LINEST()` function to calculate the paramaters of the regression line for the data. The first of these two numbers is the value of $b$. Check if it's positive or negative, and see if this matches what you'd expect for the data.

(d) Click on the chart, and use 'Add Chart Element > Trendline > Linear' to add a regression line to the plot.

(e) The second of your `=LINEST()` outputs is the value of $a$. Verify that this is where you would expect your trendline to cross the $y$-axis if it were extended to the left.

```

```{exercise}
:label: correg-ex3

For each of the datasets in Exercise 18, the values of $a$ and $b$ are given (for the regression line $y = a + bx$). Which way round are the two values? Examine the data and make a prediction, then plot the data in Excel on a scatter plot, and use the `=LINEST()` function to check.

(a) 2.113, 0.0113

(b) 0.638, 1.778

(c) 0.0498, 5.0925

(d) 14, -1

(e) -0.968 10.38

```