# STA 323 / 523 :: Homework 4

## Introduction

In your repository you will find a directory named `data/` that contains four
CSV files with information on pet owners, their pets, and their pets' procedure
details and history. These CSV files have been added to the sqlite database
`vet.sqlite`. Use the database and CSV files to complete the following tasks.

Before you begin Homework 4, watch 
[Getting Started on Homework 4](https://warpwire.duke.edu/w/c9kDAA/).

## Tasks

Tasks 2 - 6 exclusively should use SQL code chunks along with SQL commands to 
complete the task. Rename necessary fields so there is a consistent naming 
scheme in your final table outputs.

#### Task 1

In an R chunk with R code, list all tables and their fields that exist in 
`vet.sqlite`.

#### Task 2

How many of each kind of pet exist? Only output a table with the type of
pet and the respective count.

#### Task 3

Which procedure types had an average price exceed $20? Sort them in descending
order. Only output a table with the procedure types and their 
average price.

#### Task 4

Which owners have multiple pets? Sort your table so the count is in descending
order. Only output a table with the owners' name,
surname and number of pets.

#### Task 5

Which pet under the age of 10 had the most procedures according to the
procedure history? Only return a table with the pet's name, kind, age, and 
number of procedures.

#### Task 6

Get a table that contains the owner id, owner name, owner surname, owner city,
and the total price they spent on procedures corresponding to procedure sub
code 05. Only consider those owners from Lansing, Detroit, and Grand Rapids.
Sort your table in ascending order by city and descending order by the total
price within each city.

#### Task 7

Use the necessary CSV files in `data/` to redo Task 4 using only `dplyr` 
functions in an R code chunk.

#### Task 8

Construct an SQL query that outputs a table you can then use to create a 
single visualization, with `ggplot2`or any extension packages, that depicts 
something about the data in the vet database. Your visualization should be 
well-polished with a title that tells a story, and aesthetics, font size, 
and style should be carefully chosen. You may construct this visualization with 
the mindset that it would appear in a presentation. 

Use SQL chunk option `output.var="name_of_R_object"`, where in quotes you can 
specify the name of the resulting table and use that name as a reference in 
R code chunks.

## Essential details

#### Deadline and submission

<b>The deadline to submit Homework 4 is 11:59am ET on Monday, June 22.</b>
Only your final commit and code in the master branch will be graded. 
To get your work into the master branch (the only branch that will be graded), 
initiate a pull request on GitHub. This will then merge your work into the 
master branch upon approval by you or one of your teammates.

#### Help

- Post your questions in the #hw4 channel on Slack. Explain your error / problem
  in as much detail as possible or give a reproducible example that generates 
  the same error. Make use of the code snippet option available in Slack.

- Visit the instructor or TAs in Zoom office hours.

- The instructor and TAs will not answer any questions within 6 hours of the
  deadline.

#### Academic integrity

This is a team assignment. You should not communicate with other
teams. As a reminder, any code you use directly or as inspiration must be cited.

*Undergraduate:*

To uphold the Duke Community Standard:

- I will not lie, cheat, or steal in my academic endeavors;
- I will conduct myself honorably in all my endeavors; and
- I will act if the Standard is compromised.

*Graduate:*

Duke University is a community dedicated to scholarship, leadership, and 
service and to the principles of honesty, fairness, respect, and accountability.
Citizens of this community commit to reflect upon and uphold these principles in
all academic and non-academic endeavors, and to protect and promote a culture of
integrity. Cheating on exams and quizzes, plagiarism on homework assignments and
projects, lying about an illness or absence and other forms of academic 
dishonesty are a breach of trust with classmates and faculty, violate the Duke
Community Standard, and will not be tolerated. Such incidences will result in a 
0 grade for all parties involved as well as being reported to the University
Judicial Board. Additionally, there may be penalties to your final class grade.
Please review Duke’s Standards of Conduct.

#### Grading

| **Topic** | **Points** |
|-----------|------------|
| Task 1    | 1          |
| Task 2    | 2          |
| Task 3    | 4          |
| Task 4    | 5          |
| Task 5    | 5          |
| Task 6    | 6          |
| Task 7    | 3          |
| Task 8    | 4          |
| **Total** | **30**     |
 
*Documents that fail to knit after minimal intervention will receive a 0*.
