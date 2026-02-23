

# Inferential Statistics

In this week's tutorial, we will use the techniques from the previous lecture to complete a mini-project. You should save any files you work on as spreadsheets, so you can refer back to them later.

```{exercise}
:label: infst-ex1

(a) Load this [Sampling Distribution Simulator](https://onlinestatbook.com/stat_sim/sampling_dist/) in a browser window, then arrange it so you can see it alongside this page. Click the 'Begin' button in the top left so a yellow page loads.

(b) The top chart shows a normal distribution. Click and drag on the grey part of that chart to make a distribtion of your own design, of any shape.

(c) Click the 'Animated' button on the section below to take a sample of size 5 from your distribution and add its mean to the plot of sample means below. Repeat this a few times. Using the '5' button will add 5 samples at a time (without showing the individual values dropping in).

(c) Once you have become bored with doing this 5 samples at a time, click the '10,000' button to add 10,000 sample means, and observe that the distribution of sample means approximates a normal distribution. Compare the mean of this distribution to the mean of your original population.

(d) Design a different distribution in the top plot using the mouse, and try this again.

```

```{exercise}
:label: infst-ex2

Type your answers to this question into a text file or document, and save it alongside your other files from this module. Discuss your answers with the people nearby before writing your own answer.

(a) A college manager wants to survey students’ opinions of enrichment activities. She decides to survey the students on the courses summarised in the table below.

| *Course* | *Number of students enrolled* |
|---|---|
|Leisure and Sport | 420 |
|Information Technology | 337 |
|Health and Social Care | 200 |
|Media Studies | 43 |
 
Each student takes only one course.

The manager has access to the college’s information system that holds full details of each of the enrolled students including name, address, telephone number and their course of study. She wants to compare the opinions of students on each course and has a generous budget to pay for the cost of the survey.

Give one advantage and one disadvantage of carrying out this survey using

&emsp;(i) judgemental sampling,

&emsp;(ii) proportional stratified sampling.

(b) The data about the students is stored in a spreadsheet. Describe, in words, how you could obtain a proportional stratified sample of 100 students from this data, using a spreadsheet.

```

```{exercise}
:label: infst-ex3

(a) Download the CSV file linked below, and import it into a spreadsheet. The data shows the number of hire bikes used each day in Washington DC in 2011/12 (credit: [https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset](Hadi Fanaee-T)).

[![CSV icon](../_images/csv-icon-sq.png)](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut4-data1.csv) [tut4-data1.csv](https://katiesteckles.github.io/MFDS-Tutorials/resources/tut4-data1.csv)

(b) Use one of the functions below to extract random samples of size 5 from the data, by pasting it in a cell somewhere nearby:

`=INDEX($A$1:$A$1000,RANDARRAY(5, 1, 1, COUNTA($A$1:$A$1000), TRUE))` (Excel)

`=ARRAY_CONSTRAIN(SORT(FILTER($A$1:$A1000,$A$1:$A1000<>""),RANDARRAY(COUNTA($A$1:$A1000),1),1),5,1)` (Google Sheets)

*Note:* since these formulae contain 'random' functions, they will recalculate whenever you make any change to the spreadsheet. If you wish to retain a particular set of data at any point, you will need to copy the cells and Paste > Values only.

(c) Drag this formula to fill horizontally to create 100 samples. Calculare the mean of each sample. Plot their means on a curve and observe the normal distribution.

(d) Extend this to 1000 samples (be aware that the formula puts data into the cell it's in and the four cells below it, so you won't be able to just drag to extend it vertically) and compare the plot.

(e) Repeat this with a larger sample size, and compare the plots.

```