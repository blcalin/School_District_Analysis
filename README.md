# School_District_Analysis

## Overview of Project
### Purpose
The purpose of this project was to utilize Jupyter Notebook with Python, Pandas and Numpy to analyze school district performance.

### Data
Data presented includes student ID, student name, gender, grade, school name, and reading/math scores.

## Results and Analysis
The school board indicated that test results were altered, and needed to be updated. Focusing on Thomas High School, replacing math and reading scores with "NaN", representing "Not a Number", we were able to better analyze the data provided.  
1.School District Summary
![image](https://user-images.githubusercontent.com/109991916/188177140-65f5c60b-2838-4b3c-a9ef-2fd67a1f669e.png)

Focusing on the 15 schools in the district, average math score dropped by .1, while the average reading score did not change. Passing math, reading, and overall passing rate dropped around 1% respectively.

2.School Summary
![image](https://user-images.githubusercontent.com/109991916/188178957-c8209672-37d1-42fa-b806-2c129fde1c37.png)

3.Top Five Performing Schools
![image](https://user-images.githubusercontent.com/109991916/188179766-84e11996-9306-4641-bab6-eede13304147.png)

4.Bottom Five Performing Schools
![image](https://user-images.githubusercontent.com/109991916/188179920-35093277-782e-4a51-9c02-cb9a1c0ea07f.png)

5.Replacing Math and Reading Scores & Math/Reading Scores by Grade
![image](https://user-images.githubusercontent.com/109991916/188181299-7fb17402-66bd-4c13-8cf5-54788af99a74.png)

![image](https://user-images.githubusercontent.com/109991916/188180858-1bd30dc0-9bdc-4053-81e5-ae8896e35de3.png)

Through analyzing each school in the dataframe format, we were able to narrow down results to top 5 and bottom performing schools. In comparison to all schools in the district, Thomas High School does not fall in the top or bottom five at 65% overall passing rate. Results by replacing math and reading scores indicate that grade did not impact math and reading scores by grade. Thomas High School displays "NaN" for 9th grade when replacing 9th grade scores, where the remaining data set was not changed.

6.Scores by School Spending
![image](https://user-images.githubusercontent.com/109991916/188182113-6715d3ea-9d2c-4ba4-938d-d81997e3e46d.png)

![image](https://user-images.githubusercontent.com/109991916/188182199-498ef0e6-2800-4692-a832-f69cad77a244.png)
Spending ranges did not impact average math or reading scores. Spending ranges for passing percentages were impacted, as percent passing math decreased 6%, passing reading decreased 7%, and overall passing decreased 6%.

7.Scores by School Size
![image](https://user-images.githubusercontent.com/109991916/188183441-2ce7202f-22c8-4fcf-a6bd-720a38101e51.png)

![image](https://user-images.githubusercontent.com/109991916/188183529-fd2fda42-5c9d-4b11-94b7-d697c2740fb2.png)

Replacing ninth grade scores did not affect average reading and math scores, but impacted overall passing percentage. Results indicate that schools in the medium category with 1000-2000 students have the highest overall passing percentage.

8.Scores by School Type
![image](https://user-images.githubusercontent.com/109991916/188185331-a5ca7753-44e7-4240-b195-4b1c718494c3.png)
Results indicate that charter schools have a significantly higher overall passing percentage rate at 90%, whereas district schools had a passing percentage of 54%. 

## Summary

Overall, Thomas High School's passing rate dropped from 91% to 65%, ranking dropped from 2nd to 8th in the district, data for 9th graders will be shown as "NaN", and math/reading average percentages changed as a result of replacing 9th grade reading and math scores.
