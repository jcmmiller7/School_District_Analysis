# School_District_Analysis
## Project Overview
The purpose of the school district analysis was to clean the students_complete.csv dataset for more accurate analysis and to preserve data integrity. The school board suspects that there might have been some academic dishonesty concerning ninth grade reading and math scores at the Thomas high school. This analysis replaces the NaN scores within the original data set to accurately reflect the standardized test scores and the school district analysis is repetated within the clean data in order to provide new percentages for Thomas high school. The importance of data integrity is shown to have an effect on school ranking. 

## Results
### District Summary
Before the data was cleaned, the data for the school district analysis conveys the following (refer to screenshot below):
- Average math score = 79.0 %
- Average reading score = 81.9%
- Math pass rate = 75%
- Reading pass rate = 86 %
- Overall pass rate = 65%
<img width="1126" alt="Screen Shot 2021-07-24 at 8 35 13 PM" src="https://user-images.githubusercontent.com/85506567/126884148-55d16bb5-a3d0-4026-ab7b-5cb2381f30e9.png">

After the data was cleaned, the school district analysis conveys the following:

- Average math score = 78.9%
- Average reading score =  81.9%
- Math Pass rate = 74.8%
- Reading Pass rate =  85.7%
- Overall Pass rate = 64.9%
-
<img width="1052" alt="Screen Shot 2021-07-24 at 8 39 35 PM" src="https://user-images.githubusercontent.com/85506567/126884201-7661aef1-fbad-4c46-98ea-7f454317ef90.png">

Thus, there were some slight changes in math scores and passing rates as a result of removing some of the Thomas high school students with NaN scores from the analysis.

### School Summary

The overall pass rate for Thomas HS before clean up was 90.94% (second overall in district). After data cleaning, Thomas High School fell near the bottom with an overall pass rate of just 65.07%. Refer to screenshots below:

Before:
<img width="1159" alt="Screen Shot 2021-07-24 at 8 48 07 PM" src="https://user-images.githubusercontent.com/85506567/126884279-e6389f8b-0a1e-48e7-8de8-7f36ffbef07a.png">
After:
<img width="1116" alt="Screen Shot 2021-07-24 at 8 49 27 PM" src="https://user-images.githubusercontent.com/85506567/126884301-48851887-0bc0-4d6a-a39b-6ec36c44a17e.png">


Thus, changing the scores for Thomas High School drops their ranking in the district by several spots. This shows the importance of data integrity as it can drastically affect a school ranking, which can mislead the community.

Replacing the math and reading scroes for the Thomas high school ninth graders indicates they all failed the exam (ie. cheating) because the school count decreased from 1635 to 1174. (Refer to calculation in step 5 for proof)

<img width="868" alt="Screen Shot 2021-07-24 at 8 55 18 PM" src="https://user-images.githubusercontent.com/85506567/126884390-58bbb2b7-c5c8-42d5-bbea-9d40186528e4.png">
Further, after data cleaning, removing ninth grade Thomas High School students drops math and reading pass rates in terms of school size, spending, and  type as well. 
<img width="1061" alt="Screen Shot 2021-07-24 at 9 00 05 PM" src="https://user-images.githubusercontent.com/85506567/126884448-32ccd62d-0528-4082-b4fd-e36fddaaa7e2.png">
<img width="1121" alt="Screen Shot 2021-07-24 at 9 01 21 PM" src="https://user-images.githubusercontent.com/85506567/126884467-92784be8-7861-4c87-9d7b-a433d83e5b2f.png">

### Summary
