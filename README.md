# School_District_Analysis
Analysis of School District Using Python
## Overview of School District Analysis
The purpose of our analysis was to determine the average math scores, average reading scores, overall passing scores, and budgets per school and per student across the school district.
In addition to this analysis, we went back and corrected some data to account for academic dishonesty from Thomas High School in order to get a more accurate analysis.
## Results
1. The district summary is not affected at all by the changes made to the analysis. Below are images from both PyCitySchools and PyCitySchools_Challenge respectively.
![image](https://user-images.githubusercontent.com/95394598/150703463-5d4b646c-fbde-42fc-b26d-e086b1ad179c.png)
![image](https://user-images.githubusercontent.com/95394598/150703389-cf70446d-2d5b-4ca6-825b-e1d2777e69bd.png)
2. The school summary is hardly affected by the changes. The below images are comparisons from both the PyCitySchools and PyCitySchools_Challenge.
![image](https://user-images.githubusercontent.com/95394598/150703145-3b48fdfb-3382-4123-8c29-566b5c38b12d.png)
![image](https://user-images.githubusercontent.com/95394598/150703191-19da28d7-fb12-44af-84b8-c0741be60fe7.png)
3. Replacing the ninth graders' reading and math scores from Thomas High School does not really affect the overall scores. Due to information regarding academic dishonesty, we redid our analysis taking out the ninth graders' scores to determine more accurate scores.
4. Replacing the ninth-grade scores affects the math and reading scores by grade in no way other than the ninth-grade scores showing NaN.
5. Replacing the ninth-grade scores affects scores by school spending minimally because the scores for the ninth-grades are NaN.
6. Replacing the ninth-grade scores affects scores by school size in no way. These scores stay the same.
7. Replacing the ninth-grade scores affects scores by school type in no way as well. 
## Summary
After updating the school district analysis after removing reading and math scores for ninth grade at Thomas High School and replacing them with NaNs, there are only a few changes. The overall scores for Thomas High School are affected by about 0.3%. The percentage of students passing math at Thomas High School has dropped by 0.087%. The percentage of students passing reading at Thomas High School has dropped by about 0.29%. 
