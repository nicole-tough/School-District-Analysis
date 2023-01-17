# School District Analysis

## Project Overview 
The purpose of this project is to assist Maria, the Chief Data Scientist for a city school district, prepare data on student funding and students' standardized test scores for high schools in her school district. The overall task is to the aggregate data and showcase trends in school performance. In this project, we handled highly sensitive data such as student names and test scores. 

We created several data frames to aggregate the data with all of the student test scores provided to us. However, after the analysis was complete, we were made aware that test scores from 9th graders at Thomas High School showed evidence of academic dishonesty. After this came to light, we removed those test scores and re-created our data results.

## Results 
The following results will address how our data was changed once we removed the 9th grade test scores from Thomas High School. The changes can be observed in our data frame below. 
- District Summary: The District Summary changed slightly with the removal of these test scores. The number of schools, students, and budget remained the same as those were unaffected. The average reading and math scores along with the math, reading, and overall passing percentages decreseased slightly. 

- School Summary: While most of the school summary remained the same, the average test scores passing percentages for Thomas High School were replaced with new data. The average reading and math scores in addition to the math, reading, and overall passing percentages decreased slighlty for Thomas High School. All other data remained the same.

- Thomas High School Relative Performance: Thomas High Schools' relative performance remained the same. In both analyses, they were the second to top performing school when it comes to overall passing percentages. 

- Math and Reading Scores by Grade: As only the 9th grade test scores from Thomas High School were removed, that is the only category of data that was affected in our analysis of math and reading scores by grade. All data remained the same, but the 9th grade Thomas High School data reads Nan in the new data frame. 

- Scores by School Spending: The average scores by spending was not affected by the removal of the test scores. The average scores in this data set were rounded to the nearest 0.1%, and the difference in average scores is too slight to be seen. 

- Scores by School Size: The average scores by school size was not affected by the removal of the test scores. The average scores in this data set were rounded to the nearest 0.1%, and the difference in average scores is too slight to be seen. 

- Scores by School Type: The average scores by school type was not affected by the removal of the test scores. The average scores in this data set were rounded to the nearest 0.1%, and the difference in average scores is too slight to be seen. 

![OriginalSchoolSummary](https://github.com/nicole-tough/School_District_Analysis/blob/main/School_Summary_1.PNG)
*School Summary With All Test Scores*

![UpdatedSchoolSummary](https://github.com/nicole-tough/School_District_Analysis/blob/main/School_Summary_2.PNG)
*Updated School Summary with removal of Thomas High School 9th Grade Test Scores*

## Summary
The following changes to the school district analysis after reading and math scores have been replaced were observed:
1. Thomas High Schools' average math scores decreseased. 
2. Thomas High Schools' average reading scores decreased
3. Thomas High Schools' math and reading passing percentages decreased.
4. Thomas High Schools' overall passing percentage decreased. 
