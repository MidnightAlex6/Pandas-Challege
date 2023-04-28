# Pandas-Challege


![education](https://user-images.githubusercontent.com/126301312/228122394-0446cab2-755f-4083-84e7-56098d6a3b65.png)


In this assignment, I created and manipulate Pandas DataFrames to analyze school and standardized test data.

## Backgroud

I am anew Chief Data Scientist for a city's school district. I'm helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

My first first task, I have been asked to analyze the district-wide standardized test results. I was given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance.

Using Pandas and Jupyter Notebook, I created a report that includes the following data. My report also includes a written description of at least two observable trends based on the data.

## District Summary

I Performed the necessary calculations and then created a high-level snapshot of the district's key metrics in a DataFrame.
This included:

•	Total number of unique schools

•	Total students

•	Total budget

•	Average math score

•	Average reading score

•	% passing math (the percentage of students who passed math)

•	% passing reading (the percentage of students who passed reading)

•	% overall passing (the percentage of students who passed math AND reading)

## School Summary

I Performed the necessary calculations and then created a DataFrame that summarizes key metrics about each school.

This includes the following:

Include the following:

•	School name

•	School type

•	Total students

•	Total school budget

•	Per student budget

•	Average math score

•	Average reading score

•	% passing math (the percentage of students who passed math)

•	% passing reading (the percentage of students who passed reading)

•	% overall passing (the percentage of students who passed math AND reading)

## Highest-Performing Schools (by % Overall Passing)

I Sorted the schools by % Overall Passing in descending order and display the top 5 rows.
I saved the results in a DataFrame called "top_schools".

## Lowest-Performing Schools (by % Overall Passing)

I sorted the schools by % Overall Passing in ascending order and display the top 5 rows.
I saved the results in a DataFrame called "bottom_schools".

## Math Scores by Grade

I performed the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Reading Scores by Grade

Created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Scores by School Spending

Created a table that breaks down school performance based on average spending ranges (per student).
Used the code provided below to create four bins with reasonable cutoff values to group school spending.



Used pd.cut to categorize spending based on the bins.
Used the following code to then calculate mean scores per spending range.




I used the scores above to create a DataFrame called spending_summary.
And includeed the following metrics in the table:

•	Average math score

•	Average reading score

•	% passing math (the percentage of students who passed math)

•	% passing reading (the percentage of students who passed reading)

•	% overall passing (the percentage of students who passed math AND reading)

## Scores by School Size

I used the following code to bin the per_school_summary.




I use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
And createed a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

## Scores by School Type

I used the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
This new DataFrame should show school performance based on the "School Type".

## Written Report






