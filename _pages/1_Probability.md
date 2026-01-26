
# Week 2 - Probability

In this week's tutorial, we will use techniques from probability to complete a mini-project.

The `=COUNTIF()` function takes two inputs: the range you are counting over, and a statement to compare to, such as `"4"` to check whether each entry in the range is equal to 4, or `">2"` to check if the entry is greater than 2. The function will count how many entries in the range match the criterion.

For example, `=COUNTIF(A1:A4, ">3")` will tell me how many of the entries in the range `A1:A4` are greater than 3. You can also use `">=3"` for 'greater than or equal to three'.

```{exercise}
:label: prob-ex1

(a) Create a blank spreadsheet, and type in a list of random values, including numbers and text. Some of them should be the same as each other.

(b) Use the `=COUNTIF()` function to count the number of entries in your list which match a particular value, or lie in a numerical range. Verify the outputs are correct by counting.

```

```{exercise}
:label: prob-ex2

(a) Download the CSV file linked below, and import it into a spreadsheet.

[![CSV icon](../_images/csv-icon.png)tut0-data1.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut1-data1.csv)

The data contains a list of stops on the Manchester Metrolink, with their station codes, fare zone and date of opening.

(b) Use a `=COUNTIF()` function or a filter to answer the following questions.

i) If I pick a tram stop on the Metrolink at random, what is the probability that it is in Zone 1?

ii) If I pick a tram stop on the Metrolink at random, what is the probability that it was opened before the start of the year 2000?

```
The `=COUNTIFS()` function allows you to combine multiple sets of ranges/criteria, and it will go through all the ranges at the same time, counting a row if the equivalent entries in the ranges all match.

```{figure} /_images/tut1-countifex.png
:name: COUNTIF example
:width: 700

To check if how many rows in this table have the entries in both columns positive, we would use `=COUNTIFS(A1:A10,">0", B2:B10,">0")`. This would return 3, since this is true of rows 2, 5 and 10.
```

```{exercise}
:label: prob-ex3

(a) Download the CSV file linked below, and import it into a spreadsheet.

[![CSV icon](../_images/csv-icon.png)tut0-data2.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut1-data2.csv)

The data contains details of the weather in Manchester, for the hour from noon to 1pm on each day in 2024 (which had 366 days).

(b) Use a `=COUNTIF()` function or a filter to obtain the values listed below:

(i) The number of days in 2024 on which the temperature at noon was more than 18 degrees.

(ii) The number of days in 2024 on which there was any non-zero amount of rainfall at noon.

(iii) The number of days in 2024 on which the wind speed at noon was more than 10kmph.

(c) For each pair out of these three measurements, use a `=COUNTIFS()` function to find the number of days that both were true.

(d) For each of the three pairs, calculate the joint probability of both happening (given your original values from part (b), which give the number of times out of 366 that each individual event happened) by multiplying them together.

(e) If the events were independent, what would you expect these values to be? Do any of the pairs of events seem to display independence?

```


```{exercise}
:label: prob-ex4

(a) Search online to find out information about lotteries in different countries. For each one, determine how many numbers are used, how many balls are drawn, how frequently draws operate, and how many numbers you need to match to win the jackpot.

For a lottery with $n$ numbers to choose from, of which you need to match $k$ to win the jackpot, the number of possible combinations that could be drawn is "$n$ choose $k$", which can be calculated using the `=COMBIN()` function (which takes as inputs $n$ and $k$). The probability of winning the jackpot is 1 divided by the number of combinations (as exactly one of them will be the winning set of numbers).

(b) For each country's lottery, calculate the probability of winning the jackpot having bought a single ticket, and how likely a person buying a ticket in every draw for a week is to win on a given week (by multiplying the probability of winning on a given draw by the number of draws in a week).

(c) Compile your data into a spreadsheet and format it. Which country has the best odds of winning the lottery?

```


