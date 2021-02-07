# Panda-PyCitySchools Challenge
##  

![Education](Images/education.png)

## Background

We will be helping a school board make strategic decisions regarding future school budgets and priorities.

by analyzing the district-wide standardized test results. Youhave access to every student's math and reading
scores, as well as various information on the schools they attend. Using the pandas library and Jupyter Notebook. 
We are going to aggregate the data to showcase obvious trends in school performance.

## Analysis

our final report include each of the following:

### District Summary

* Created a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

```text

Total Schools  Total Students  Total Budget   Average Math Score  Average Reading Score  %Passing Math  %Passing Reading  %Over all Passing
    15	          39,170       $24,649,428.00	   78.99	         81.88	             74.98 %	    85.81 %	     65.17 %
```

### School Summary

* Created an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

```
School Name	    School Type	 Total Students	Total School Budget  Per Student Budget	Average Math Score  Average Reading Score  %Passing Math  %Passing Reading  %Overall Passing
Bailey High School	District    4976	  $3,124,928.00	     $628.00	          77.05	             81.03	            66.68 %	   81.93 %	     54.64 %
Cabrera High School	Charter	    1858	  $1,081,356.00	     $582.00	          83.06	             83.98	            94.13 %	   97.04 %	     91.33 %
Figueroa High School	District	
```

### Top Performing Schools (By % Overall Passing)

* Created a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

### Bottom Performing Schools (By % Overall Passing)

* Create a table that highlights the bottom 5 performing schools based on % Overall Passing. 
Include all of the same metrics as above.

### Math Scores by Grade\*\*

* Created a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

#### <a id="school-spending"></a>School Spending

![school spending](../Images/spending.png)

### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

#### <a id="school-size"></a>School Size

![school size](../Images/size.png)

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).

#### <a id="school-type"></a>School Type

![school type](../Images/type.png)

## Conclusion

Looking at the the plots created after each analysis, it is obvious that:

 * Spending more money per-student did not improve grades at all. Schools with smaller budgets (585 per student)
 dramatically out-performed schools with higher spending (645-675 per student) on overall passing percentage (90% passing vs 53%).

 * Small class size means better grades and that is why smaller and medium sized schools dramatically 
out-performed large sized schools on overall passing percentage (90% passing vs 58%).

 * Charter schools grade-average way better than District or public schools, this is very clear when 
we look at top five performing schools"all Charters" vs bottom five ones"all District".

 * Charter schools kids out perform their District counterpart by 37% points when it comes to the 
overall percentage of passing both math and reading (90% vs 53%).


