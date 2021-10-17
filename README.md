# School District Analysis

## Overview
The purpose of this analysis is to provide key metrics for the school district.  And in light of the issue with 9th grade test scores for Thomas High School (THS), to exclude that data when running the code and completing the analysis.  The following sections will cover the key metrics and observations regarding the the effect of excluding the 9th grade Thomas High School data. 

## Results

### Top 5
The top 5 performing schools (% Overall Passing) did not change after the THS data was ignored.  THS is still the second highest performing school, although, their overall passing percentage did drop slightly.  See the images below for the change in average.

![Top 5 - Pre](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Top%205%20-%20Pre-Exclusion.PNG)
![Top 5 - Post](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Top%205%20-%20Post-Exclusion.PNG)

### Bottom 5
The bottom 5 performing schools (% Overall Passing) was not affected by the exclusion of THS data.

![Bottom 5](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Bottom%205%20-%20Post-Exclusion.PNG)

### Math Scores by Grade Level
The images below show that the math scores from THS 9th grade were converted to NANs, thus excluding it from the data.  

![Math By Grade - Pre](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Math%20Scores%20By%20Grade%20-%20Pre-Exclusion.PNG)
![Math By Grade - Post](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Math%20Scores%20By%20Grade%20-%20Post-Exclusion.PNG)

### Reading Scores by Grade Level
The images below show that the reading scores from THS 9th grade were converted to NANs, thus excluding it from the data.    

![Reading By Grade - Pre](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Reading%20Scores%20By%20Grade%20-%20Pre-Exclusion.PNG)
![Reading By Grade - Post](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Reading%20Scores%20By%20Grade%20-%20Post-Exclusion.PNG)
### School Performance - Budget per Student
The math and reading performance was better amongst schools that had a lower per student budget.  This correlation does not mean that there is a causation.  Further analysis, including the data in the next sections, would need to be done in order to determine how budget and peformance are related. 

![Per Student Budget](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Budget%20Per%20Student.PNG)

### School Performance - Size
Smaller schools performed better than larger schools.  These smaller schools are also Charter schools, as can be seen in the next section. Futher analysis into school size should be done to determine how it affects performance. 

![School Size](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Scores%20By%20School%20Size.PNG)

### School Performance - Type of School
Charter schools outperformed District schools, as seen in the image below. Futher analysis into school size should be done to determine how it affects performance. 

![School Type](https://github.com/cflavallee/School_District_Analysis/blob/main/Resources/Scores%20By%20School%20Type.PNG)



## Summary

The 9th grade reading and math scores for THS were replaced with NANs, however, THS was still the 2nd highest performing school after negating the 9th grade data.  Their average scores for reading, math, and overall passing went down, but not a significant amount. Overall, these four changes did not significantly affect the data.     

Further investigation should be done into why smaller charter schools, with a lower budget outperformed the larger district schools, where spending per student is higher.  

