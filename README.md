# School Standardized Testing Analysis


I've been asked to analyze the district-wide standardized test results. I was given access to every student's math and reading scores, as well as various information on the schools they attend. My task is to aggregate the data to showcase obvious trends in school performance.

Using Python, Pandas and Jupyter Notebook, I created a report that included the following data:


### District Summary

Created a high-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary

Created a DataFrame that summarizes key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)

Created a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Included the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)


### Lowest-Performing Schools (by % Overall Passing)

Created a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Included the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math Scores by Grade

Created a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

Created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

Created a table that breaks down school performance based on average spending ranges (per student). I used my own judgment to create four bins with reasonable cutoff values to group school spending. Included the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size

Created a table that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type

Created a table that breaks down school performance based on type of school (district or charter).

# Analysis
### Report at least two observable trends based on the data

If you refer to the scores of the chart "Scores by School Type," you will see that scores are higher at Charter Schools than District Schools across the board. There is a huge disparity in the % Overall Passing, with Charter schools having over a 90% passing rate and District schools at about a 54% passing rate.

If you refer to the scores of the chart "Scores by School Spending," you will see a trend that the less the school spends per student, the higher the test scores. As the budget increases per student, the test scores go down. This reflects a higher budget and more money does not always equal a better education.

If you refer to the scores of the chart "Scores by School Size," you will see schools with less than 2,000 students perform significantly better than schools with more than 2,000 students.
