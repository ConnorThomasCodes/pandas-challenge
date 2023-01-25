# pandas-challenge

In this repository, we have set up a Python program to import two .csv files (schools_complete.csv and students_complete.csv) with testing data from a given school district and then perform some aggregations and analysis on that data.

* To begin our analysis, we merge our school and student data into a single data frame for some overall information about the district. This includes the total number of schools, students, and budget across the district along with average math and reading scores and also the percentage of students passing math, reading, or both classes.

* After this, we aggregate our data by high school and perform many of the same calculations for each individual school, this time including school type (district vs charter), total students, total budget, per student budget, and the average math/reading scores along with the percentage of students passing math, reading, or both classes. We additionally sort this aggregation by the percent of students passing both classes to find some of the top and bottom performing schools in the district.

* Continuing on, we then aggregate our data by grade level and find average math and reading scores for the different grades (9th, 10th, 11th, and 12th) across each indiviudal high school

* Next, we perform three more aggregations on our data. First by the per student budget, creating bins (<585, 585-630, 630-645, 645-680) for the different per student budgets across the district and then sorting accordingly. Then by school size, again creating bins ( Small (<1000), Medium (1000-2000), Large (2000-5000) ) and sorting each school accordingly. Finally we aggregated by school type (district or charter). Will all of these final 3 aggregations, we were interested in the average math and reading scores along with the percentage of students passing math, reading, or both classes.
