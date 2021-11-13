# School_District_Analysis

## Overview of the school district analysis
- The school board has come to find evidence of academic dishonesty for reading and math scores of ninth graders for Thomas High School. Not knowing the full extent of academic dishonesty, the school board would like to uphold the state-testing standards. Orders were given to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and repeat the school district analysis.


## Results
-How is the district summary affected?
When replacing the values for the ninth graders reading and math scores, the district summary was not affected greatly but the averages and percentage of passing decreased very slighty.
![original_district_summary](https://user-images.githubusercontent.com/90146132/141600694-82b16955-7525-45fc-9624-a0da3aa11729.PNG) *Original District Summary*
![new_district_summary](https://user-images.githubusercontent.com/90146132/141600719-c3acb449-3ff5-4b24-9ba8-91d92c99aa39.PNG) 
*New District Summary*

-How is the school summary affected?
The change in the percentage of passing reading and math changed significantly but the change of averages of math and reading scores were not very noticable.
![og_school_sumarry](https://user-images.githubusercontent.com/90146132/141601916-048dfd79-f992-4439-918a-23d409ad0f65.PNG)
*Original School Summmary*
![new_school_summary](https://user-images.githubusercontent.com/90146132/141601939-2456add2-7262-4ea4-8e46-1f8dc7a90ee5.PNG)
*New School Summary*

-How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
Relative to other schools, replacing the ninth graders' math and reading scores were negatively impacted due to inserting NaNs in places fo missing reading and math scores for the ninth graders.

- How does replacing the ninth-graders scores affect the following
  - Math and reading scores by grade.
    The math and reading scores affect the other grades in a negative way where most of the other reading and math scores decrease    following the change to the ninth graders' grades.
    ![old_reading_scores](https://user-images.githubusercontent.com/90146132/141602302-8c300af7-2d68-4a47-bac4-98dae15273f8.PNG)
   *Old Reading scores*
  ![new_reading_scores](https://user-images.githubusercontent.com/90146132/141602316-4baf7af4-85a0-433d-b92b-c2445df54d0e.PNG)
   *New Reading scores*

  - Scores by school spending.
    The scores by school spending didnt seem to change a significant amount compared to the original. The schools with largers         school budgets did seem to have lower % Passing Math, which also tended to be the larger schools as well.
    
  - Scores by School Size 
    The scores by school size seemed to be relatively the same as well, with having a slight decrease
    
  - Scores by School Type
    The scores by school type also seemed to be relatively similar only with a slightly smaller value.
    
## Summary
- The four main changes that occurred in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs include the average math scores decrease slight, both percentage of passing math and reading decreased slightlty and the overall percentage of passing decreased.
