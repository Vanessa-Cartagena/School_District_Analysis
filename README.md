# School_District_Analysis

## Overview 

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The school board has asked Maria for assistance even though they are unaware of the full degree of the academic dishonesty. They want to uphold state testing requirements despite this. She has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Maria wants us to repeat the school district analysis we completed in this lesson after we've updated the math and reading scores, and then write up a report outlining how these modifications influenced the analysis as a whole.

### Resources 
Data Source: schools_complete.csv, student_complete.csv, clean_student_complete.csv
Jupyter Notebook, PythonData Environment, Pandas 

## Results
### How is the district summary affected? 
The results for the district summary comparison reveals a minimal change. 
  - The average math score decreased by 0.1% 
  - The percent of students who passed math decreased by 0.2% 
  - The percent of students who passed reading decreased by 0.3%
  - The overall percent of students passing math and reading decreased by 0.1% 

Original analysis
<img width="926" alt="District Summary 1" src="https://user-images.githubusercontent.com/105958160/176816764-abeb8881-b9a9-421b-9545-700c7e4c0d48.png">
Updated analysis
<img width="928" alt="Distric Summary 2" src="https://user-images.githubusercontent.com/105958160/176816778-f22cce64-ca0f-4a58-9e98-9b6771b30264.png">

### How is the school summary affected?
The results for the school summary comparison reveals more of a change in the percentage of students who passed math and reading in Thomas High School compared to the district summary. 
  - The average math score decreased by 0.067412% 
  - The percent of students who passed math decreased by 26.360856% 
  - The percent of students who passed reading decreased by 27.64526%
  - The overall percent of students passing math and reading decreased by 25.871559% 

<img width="992" alt="School Summary 1" src="https://user-images.githubusercontent.com/105958160/176828299-b5643eeb-a15c-48b2-9244-f28d8ef4eec2.png">

<img width="981" alt="School Summary 2" src="https://user-images.githubusercontent.com/105958160/176828309-f7fc4f8a-f293-4e44-8471-7a78cfc60664.png">

### How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?
Thomas High School's performance ranking fell from having the second highest overall passing percentage of 90.948012% to having the eighth lowest overall passing percentage of 65.076453%, in the district, when the ninth graders' math and reading scores were replaced.

### How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade: 
Original analysis
<img width="425" alt="Math Scores by Grades 1" src="https://user-images.githubusercontent.com/105958160/176832487-1c5355d1-5656-4dc4-99bd-040a8fd9b3aa.png">
<img width="430" alt="Reading Scores by Grades 1" src="https://user-images.githubusercontent.com/105958160/176832513-72304772-6cea-4f5c-b45d-fe5e4944430a.png">
Updated analysis
<img width="312" alt="Math Scores by Grades 2" src="https://user-images.githubusercontent.com/105958160/176833055-53914761-d4dc-4fc6-91e0-c4fc5c0b40bd.png">
<img width="301" alt="Reading Scores by Grades 2" src="https://user-images.githubusercontent.com/105958160/176833240-f9e26acf-0d5e-4444-a0d1-497d22de2912.png">

- Scores by school spending:
Original analysis
<img width="839" alt="School Spending Summary 1 png " src="https://user-images.githubusercontent.com/105958160/176826175-f85dbe89-478d-4748-bf1d-64307e9f7a3b.png">
Updated analysis
<img width="816" alt="School Spending Summary 2" src="https://user-images.githubusercontent.com/105958160/176826538-7c29eb06-d0bf-4ce9-80ff-033b59be62e4.png">

- Scores by school size:
Original analysis
<img width="768" alt="School Size Summary 1" src="https://user-images.githubusercontent.com/105958160/176826509-187aad9c-2a08-4a9b-a352-9531edfd4363.png">
Updated analysis
<img width="753" alt="School Size Summary 2" src="https://user-images.githubusercontent.com/105958160/176825856-e31f11f7-2338-4539-8d98-1775148b7efd.png">

- Scores by school type:
Original analysis 
<img width="708" alt="School Type Summary 1" src="https://user-images.githubusercontent.com/105958160/176825821-7110b085-4f9f-47ab-8fb3-607829f52c55.png">
Updated analysis
<img width="729" alt="School Type Summary 2" src="https://user-images.githubusercontent.com/105958160/176825645-9800643c-8948-4989-9233-7481221450b8.png">

## Summary 
We can see a few modifications occurred after substituting the math and reading results for Thomas High School with NaNs while keeping the rest of the data the same. Overall, their passing rate dropped significantly from 91 to 65 percent. They shifted from being ranked second to being ranked eighth in the district as a result of this adjustment. The per-student spending ranges at the schools did not change. Compared to district schools, charter schools have a greater passing rate. According to school size, the percentage of children passing math and reading decreased by within the medium school size bracket.  
