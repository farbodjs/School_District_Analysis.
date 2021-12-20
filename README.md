# School_District_Analysis.

## Summary
The purpose of this analysis is to calculate the existence of a correlation with the budget per student and overall score in math and reading. We realized that some of the test scores from the 9th grade at Thomas High School are missing for both math and reading. Since we realized that these values are missing , we refactored our code and elliminated the data of 9th graders from the calculations so that it doesn't affect our overall numbers.

## How is the district summary affected?

After taking a look at both district summaries from pycityschools and pycityschools_challenge there is not a change.

## How is the school summary affected?
Overally speaking, there is not a significant change in school summary after elliminating 9th graders from calculations. 
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![image](https://user-images.githubusercontent.com/86033316/146695585-d989e276-9274-4928-9f75-9974f466ed34.png)
![image](https://user-images.githubusercontent.com/86033316/146696029-51f6bacd-c828-4b6f-b3e7-0e66d0c2c82e.png)

The overall passing for Thomas High School was 90.95% in pycityschools, with the 9th graders taken out the overall passing decresed to 90.63 and  shrinked by 0.3 %.


## How does replacing the ninth-grade scores affect the following: 

### Math and reading scores by grade

The difference in math and reading average is very minimal between these two models.
#Scores by school spending

The numbers stay nearly identical after the 9th graders are elliminated from the statistics. Average math score decreased from 83.42 to 83.35 which is a minor change.


### Scores by school size

![image](https://user-images.githubusercontent.com/86033316/146698269-f8e53eec-f3e8-4423-915c-1b73cbca3a65.png)
From the table above which is extracted from PyCitySchools_Challenge, we can see that there is no significant difference between small (<1000) and medium (1000-2000) schools. but it is clear that large schools have lower student performance.

### Scores by school type

![image](https://user-images.githubusercontent.com/86033316/146698398-20995e4d-e081-4183-b6a2-75b519a51dfa.png)
WE can see from table above that Charter schools have a better student's performance compared to District type.
## Conclusion

After we have replaced the scores of the 9th grade students we learn that not much has changed. We have nullified the values that we felt would alter size,district, spending and overall passing percentage of the students.
