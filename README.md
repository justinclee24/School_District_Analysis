# School District Analysis

## Overview of the School District Analysis
The purpose of this analysis is to gauge the performance of each school in the district as well as how each grade level performed, based on a variety of factors including per capita school spending (<$584, $585-629, $630-644, $645-675), school size (Small [<1000], Medium [1000-2000], Large [2000-5000]), and school type (District, Charter). Once the school board was made aware of academic dishonesty within the 9th grade level of Thomas High School, a reanalysis had to be performed giving all students previosuly mentioned a "NaN" score so that the integrtity of the analysis was upheld. 

## Results
- Regarding the overall district summary, it is somewhat affected by the refactoring performed. The modified district summary relative to the original is roughly     two-tenths of a percent lower in all percentage categories (% Passing Math, Reading, and Overall). 
- In dealing with the school summary for Thomas High School, the effects were also somewhat moderate. All percentage categories had a decrease of about three-tenths   of a percent compared to the original analysis.
- In comparison to the other schools, Thomas High School's relative position in performance did not move. While there were changes to the passing percentages, they   were not enough to move the school into a different ranking.
  - Replacing the ninth-grade math and reading scores affected only the Thomas High School ninth-grade values (giving these data points the input "NaN"), as the 
    dataframe that was created grouped these values by school as well.
  - Replacing the ninth-grade math and reading scores for Thomas High School left the table of scores by school spending unaffected.
  - Replacing the ninth-grade math and reading scores for Thomas High School left the table of scores by school size unaffected.
  - Replacing the ninth-grade math and reading scores for Thomas High School left the table of scores by school type unaffected.

## Summary
Overall, thankfully, the modifications to the analysis did not change much to the summaries. However, Thomas High School's passing percentages were decreased. The math passing percentage changed from 93.272171% to 93.18569%. The reading passing percentage changed from 97.308869% to 97.018739%. The overall passing percentage changed from 90.948012% to 90.630324%. To add, in the school summary chart, along the Thomas High School row, the average math and reading score for 9th grade is now "NaN". Finally, the overall district summary was affected due to the modification of ninth grade scores at Thomas High School. All of the passing percentages decreased by roughly two-tenths of a percent for the whole district. 
