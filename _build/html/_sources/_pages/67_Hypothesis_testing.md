

# Hypothesis Testing

In this week's tutorial, we will use the techniques from the previous lecture to complete a mini-project. You should save any files you work on as spreadsheets, so you can refer back to them later.

```{exercise}
:label: hypte-ex1

Complete the following example by hand, then use a spreadsheet to check your answer. You can use the `=NORMDIST()` function to compute the area under a normal distribution to the left of a given value, remembering to set the 'cumulative' variable to TRUE.

(a) A judo instructor, Anna, claims that the mean time spent by students in the dojo is 170 minutes. The times, in minutes, spent in the dojo by a random sample of 9 judo students were:
	
	191 134 218 164 201 196 107 228 294

&emsp; (i) Test Anna’s claim, using the 5% significance level. Assume that the data come from a normal distribution with standard deviation of 45 minutes.

Further investigation revealed that the times in the sample were not the times from arriving in the dojo, but the times from arrivals being recorded by the judo club receptionist, which happened after they had gone inside. The effect of this is that each of the times in the sample should be increased by 5 minutes.

&emsp;(ii) How, if at all, does this further information affect your conclusion in part (i)?

```

```{exercise}
:label: hypte-ex2

Complete the example below by hand, then use a spreadsheet to check your answer. you can use the `=CHISQ()` function, passing it a 2-by-2 array of observed values and a 2-by-2 array of expected values. Compare the exact probability to the value given by the table.

(a) Two groups of patients took part in a clinical trial for a new drug for a certain medical condition. One of the two groups was given the drug whilst the other group was given a placebo, a “fake” drug that has no physical effect in the medical condition.

The results are summarized in the table below.

| | *Placebo* | *Drug* |
|---|---|---|
| Condition Improved | 16 | 37 |
| Condition Not Improved | 43 | 24 |

Use a $\chi^2$ test at the 5% level of significance to investigate whether there is any association between the type of drug patient were given and the improvement or not in their condition. 

```