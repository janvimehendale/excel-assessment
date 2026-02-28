For this assessment, you've been provided school-level data from the Tennessee Department of Education on the ACT standardized test.

Note that there are three sheets in the workbook that hold that data that you'll need, ACT_school_suppressed, schools, and districts and there are two sheets where you'll fill in answers, answers and Davidson County.

1. Each school is identified using the SCHOOL_ID column. Use this column to retrieve from the schools sheet the school name and city for each school to fill in columns B and C of the ACT_school_suppressed table.

2. In the answers sheet, find the largest and smallest average composite scores. Then use a formula which retrieves the school name of the school with those average composite scores.

3. In the answers sheet, there is a table with the 4 largest cities in Tennessee. 
	a. Use a formula to find the total number of valid tests for each of these cities and and the total number of tests scoring 21 or over for schools in each of the 4 cities.
	b. Write a formula to calculate the Percent Scoring 21 or Over for each city. Format this as a percent.
	c. Create a bar chart showing the percent scoring 21 or Over for each city.

4. Using the FILTER function, pull in the rows for all Davidson County schools into the Davidson County sheet. 

5. Use a pivot table to count the number of schools per district. Which district has the most schools? 

6. a. In column Q, "Average Composite At Least 20", write a formula which checks whether the Average composite score for a school is at least 20. If it does, this column should display "At least 20" and if not, it should display "Below 20".
b. In column R, "All Areas At Least 20", write a formula which checks whether the Average score for English, Math, Reading, and Science are all at least 20. If so, this should display "All at least 20" and if not, it should display "Not all at least 20".
c. Create a pivot table. In this pivot table, compare the average number of valid tests for schools which had an average composite of at least 20 to those which did not. What do you find?