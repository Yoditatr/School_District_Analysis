# School_District_Analysis

Overview of the school district analysis: 

The school board has notified Maria and her supervisor that the data shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to me for help. Hence, in doing the analysis, I have replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact to show how these changes affect the overall analysis.
The analysis tries to answer the follwing questions. 
1. How is the district summary affected?

The new district summary for average math scores, average reading scores  and percenatages have dicreased by less than half percentage. 

![alt text](https://github.com/Yoditatr/School_District_Analysis/blob/main/Resources/pycityshool%20challenge%20district%20summary.PNG?raw=true)

2. How is the school summary affected?

On the previous analysis  Thomas High School was the second among the top five ranking schools in the district based on overall passing score, with the new school summary, after removing the 9th grade scores due to academic dishonesty, Thomas High School was still at the seccond level in the rank, but with relatively less percentage of passing scores.

![alt text](https://github.com/Yoditatr/School_District_Analysis/blob/main/Resources/pycityshool%20challenge%20perschool%20summary.PNG?raw=true)

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

As discribed above, replacing the ninth graders' score, affected the school performance intermms of passing scores. 

4. How does replacing the ninth-grade scores affect the following:

Attached images of dataframes to show how the below have been affected by replacing the ninth grade data.  

- Math and reading scores by grade

![alt text](https://github.com/Yoditatr/School_District_Analysis/blob/main/Resources/pycityshool%20challenge%20math%20score%20by%20grade.PNG?raw=true)



![alt text](https://github.com/Yoditatr/School_District_Analysis/blob/main/Resources/pycityshool%20challenge%20reading%20score%20by%20grade.PNG?raw=true)

- Scores by school spending and school size

![alt text](https://github.com/Yoditatr/School_District_Analysis/blob/main/Resources/pycityshool%20challenge%20school%20spending.PNG?raw=true)

- Scores by school type

![alt text](https://github.com/Yoditatr/School_District_Analysis/blob/main/Resources/pycityshool%20challenge%20school%20type.PNG?raw=true)


Listed below are the four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- The average math schore by charter, and district school type for the updated analysis have increased by 0.5% and 0.34% respectively.
- Overall percentage passing for the updated analysis based of spending and school size have decreased by less than 0.4%. 
- Percentage passing math and reading have also decreased for the updated analysis 
- Math and reading scores by grade have remained unchanged. 
