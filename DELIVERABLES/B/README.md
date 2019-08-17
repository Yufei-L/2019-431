431 Deliverable B
================
Thomas E. Love
Due **2018-09-06** at 2 PM.

This is Version: 2019-08-16 23:17:20

# General Instructions

Deliverable B includes seven questions. Be sure to respond to each of
them.

## The Data for Deliverable B

Deliverable B uses data from the `midwest` data set, which is part of
the `ggplot2` package (which is part of the `tidyverse`) so by loading
the `tidyverse` package, we will have direct access to the `midwest`
data by typing `midwest`. The `midwest` data describe demographic
information for 437 counties in the midwestern United States. You might
use `?midwest` to obtain a little bit of additional information about
these data, and/or use `View(midwest)` to get a look at a “spreadsheet”
view of the data. We will focus on just four variables in Homework 1
from this data set:

  - `county` = the name of the county
  - `state` = the name of the state (each county is contained in a
    single state)
  - `percollege` = the percentage of adult residents of the county who
    have completed a college degree
  - `inmetro` = an indicator variable, which takes the value 1 if the
    county is contained in a metropolitan area, and 0 if it is not

# Question 1

Write a piece of R code that counts the number of observations
(counties) in the data set within each state. Your result should also
specify the states which are included in these data. Hint: The `count`
function and the pipe `%>%` should be a big part of your code.

# Question 2

Use the `filter` and `select` functions in R to obtain a result which
specifies the `percollege` and `inmetro` status of Cuyahoga County in
the state of Ohio.

# Question 3

Use the tools we’ve been learning in the `ggplot2` package to build a
histogram of the `percollege` results across all 437 counties
represented in the data. Create appropriate (that is to say, meaningful)
titles for each axis and for the graph as a whole (don’t simply use the
default choices.) We encourage you to use something you find more
attractive than the default gray fill in the histogram.

# Question 4

Based on your results in Questions 2 and 3, write a short description
(2-3 sentences) of Cuyahoga County’s position relative to the full
distribution of counties in terms of `percollege`.

# Question 5

Use `ggplot2` to build a single plot (a pair of histograms after
faceting would be one approach, or perhaps a comparison boxplot) which
nicely compares the `percollege` distribution for counties within
metropolitan areas to counties outside of metropolitan areas. Again,
make an effort to build and incorporate useful titles and labels so that
the resulting plot stands on its own, rather than just accepting all of
the defaults that appear.

# Question 6

Write a short description of where Cuyahoga County falls within the plot
you built in Question 5. the position of Cuyahoga County in terms of
`percollege` relative to the other counties within its `inmetro`
category.

# Question 7

Ask one question of Dr. Love about this course (ideally one that you
haven’t asked us already) that interests you.

It can be a question about the syllabus, the readings, the project, the
homework assignments, the course notes, anything big or small, but it
shouldn’t be a fact that you can find already in the [Course
Syllabus](https://thomaselove.github.io/2019-431-syllabus/).

# Submitting your Response

Submit your response as an R Markdown file, and either an HTML, PDF or
Word document that results from that R Markdown file, to
<https://canvas.case.edu/> in the Deliverable B section. Again, the
deadline is 2019-09-06 at 2 PM.

# A Few Tips

You are welcome to discuss Deliverable B with Dr. Love, the teaching
assistants or your colleagues, but your answer must be prepared by you
alone. Don’t be afraid to ask questions, either of Professor Love, or of
the teaching assistants, either in person at office hours or
before/after class, or email **431-help at case dot edu**.

## Grading Rubric

Deliverable B will be graded on a 0-100 scale, where you will receive 10
points per question for making a reasonable effort to build a good
response, and an additional 5 points on Questions 1-6 if your response
is (essentially) correct and you’ve written any text using complete
English sentences.
