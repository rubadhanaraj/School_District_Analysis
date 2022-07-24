# School_District_Analysis

## Overviw of the project
The purpose of this project is to analyze the data of an entire School District, based on the grades of the students and the budget of each school and provide insights  on each school's performance. However, the analysis had to be conduced twice due to a potential academic dishonesty. The analyses show the impact in the results of the performnaces of schools after the potential academic dishonest data is modified.
### Resources
Software : Python 4.7.6, Anaconda 4.12.0, Jupyter Notebook

## Results
For school district analysis, we had two sets of data, schools_complete.csv and students_complete.csv. The data were cleaned and sorted for the analysis of school district. The delivarables for the analysis were, 
* Finding the district's key metrics. 
* Overview of key metrics for each school,
* Top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score received by students in each grade level at each school
* The average reading score received by students in each grade level at each school
* School performance based on the budget per student
* School performance based on the school size 
* School performance based on the type of school
The anlaysis with the original data set has been done with the above mentioned deliverables. However, as per the school board's requirement, the math and reading scores for Thomas High School have been replaced with NaNs, while keeping the rest of the data intact,due to a potential academic dishonesty. Once the math and reading scores of Thomas High School have been removed, the analysis was repeated for the school district and a report is attached to describe how these changes affected the overall analysis.

### Impact on District Summary analysis
The changes made to the math scores and reading scores for 9th graders in Thomas high school didn't create much of an impact in district summary analysis. As there are only 461 students in 9th grade in Thomas high school and the total student count is 39170, the percentage of grade 9 students to the total student count would be significantly less. So removing their math and reading scores didn't impact much on district summary analysis. 
#### District Summary - Original
![image](https://user-images.githubusercontent.com/108298416/180651736-2783204a-c363-4045-b753-c1642a1a474c.png)
#### District summary - Updated
![image](https://user-images.githubusercontent.com/108298416/180651811-c39f121b-63a5-42d1-bead-9957cee428d4.png)

### Impact  on School summary analysis
#### School summary
![image](https://user-images.githubusercontent.com/108298416/180653806-b2c13f9a-dd8c-4eee-bdee-aa62d1ae6f84.png)
Even after, the math and reading scores of Thomas high school has been removed for 9th graders, the school summary analysis results didn't change much like the district summary. 
### Impact on Thomas High School's relative perfomance to the other schools
The ranking of top five schools in the original analysis and updated analysis remain the same. Even though the average math and reading scores were changed, the changes were not enough to make changes in the relative ranking.
#### Top five schools - Original
![image](https://user-images.githubusercontent.com/108298416/180654952-34279f60-9678-43b7-8cdf-7e398c8bde68.png)
#### Top five schools - Updated
![image](https://user-images.githubusercontent.com/108298416/180654992-a4407b2a-b22c-4032-b607-d94378ad5dbb.png)
The bottom five schools ranking remains the same in original and updated school district analysis
#### Bottom five schools - Original
![image](https://user-images.githubusercontent.com/108298416/180655599-fda85df3-065e-4633-93fd-5d20858450b7.png)
#### Bottom five schools - Updated
![image](https://user-images.githubusercontent.com/108298416/180655694-702cae78-b05f-4db3-8a69-bb1dad073506.png)

### Impact on Math and Reading scores by grade
The math and reading scores in in updated analysis is 'NaN' for 9th graders in Thomas high school, as the school board needed the analysis by removing 9th grade math and reading scores.
#### Math scores by grade - Original & Updated
![image](https://user-images.githubusercontent.com/108298416/180656796-79457ce1-7a58-4749-90f7-60a93204fad5.png) ![image](https://user-images.githubusercontent.com/108298416/180656819-c3edcdbe-cd93-4cbc-8817-78c00951fab8.png)
#### Reading scores by grade - Original & Updated
![image](https://user-images.githubusercontent.com/108298416/180656837-8a976c4c-bef8-4c2c-a44b-3f5a584b7787.png) ![image](https://user-images.githubusercontent.com/108298416/180656864-2f87f45f-7623-441b-adf6-9ae2a8ed4a96.png)

### Impact on Scores by school spending
Thomas High school is grouped into $630-$644 spending category and there is a small change in scores by school spending. However the impact is not high as the changes in scores are less than 0.1%
#### Scores by school spending - original
![image](https://user-images.githubusercontent.com/108298416/180658012-d23836c4-109f-4ac6-8a75-e25a9e6914e7.png)
#### Scores by school spending - Updated
![image](https://user-images.githubusercontent.com/108298416/180657898-ad8e493c-76b9-463c-8904-d2b5074bef39.png)

### Impact on Scores by school size
The changes made to Thomas high school's Math and reading scores had very small impact on scores by school size. The scores on Medium size bin(1000-1999) was changed by 0.1% in the updated analysis
#### Scores by school size - Original
![image](https://user-images.githubusercontent.com/108298416/180657998-45f768df-9e1d-435b-8f73-1bc00931960a.png)
#### Scores by school size - Updated
![image](https://user-images.githubusercontent.com/108298416/180657929-fc89c446-26e9-41ea-aaad-642b833a73de.png)

### Impact on Scores by school type
The impact on scores by school type was very negligible (< 0.1%) in the charter type schools, as Thomas High school is a charter type school and the district type schools are not affected by the changees made.
#### Scores by school type - Original
![image](https://user-images.githubusercontent.com/108298416/180657971-252ea0ab-6abc-4922-afbe-c8f958395c85.png)
#### Scores by school type - Updated
![image](https://user-images.githubusercontent.com/108298416/180657947-ca49b513-eb10-416d-93f5-5cfcf15523cd.png)

## Summary
* Math and reading scores by grade results changed from original analysis because the math and reading scores of Thomas High School has been replaced with NaNs.
* Scores by school spending has a slight change in metric,less than 0.1% in $630 -$644 spending bin category, as Thomas High school was grouped into this category.
* Scores by school Size results were impacted little by the changes in updated analysis. Scores on Medium (1000-1999) bin  changed  by less than 0.1 percentage.
* Scores by school Type changed less than 0.1% in charter type schools, after replacing math and reading scores of Thomas High school by NaNs.












