# School_District_Analysis
Module 4 - Python/Pandas/Jupyter - School district analysis

## Overview of the School District Analysis
### Background
I am assisting Maria, the superintendant of PyCitySchool district in analysis on passing percentages among different schools in the district across different factors.
Once the original analysis was complete, it was decided to retract all Thomas High School 9th grade - grades with Nan as the data does not seem reliable to use and make decisions on.
With that being said, all THS 9th grades were replaced with Nan and the rest of the data remains as is.

### Resources
Python and Panda
this analysis was perfomed in Jupyter notebooks

### Objectives
1. Replace ninth-grade reading and math scores
2. Repeat the school district analysis
3. Analyze 7 different School metrics : Top 5 Performing Schools, Bottom 5 Performing Schools, Average Math Scores, Average Reading Scores, Scores by School Spending, Scores bu School Size, Scores by School Type
4. Analyze the changes in the outcomes/key metrics between the two disctrict analysis files and effects of roming Thomas High School 9th graders

## Results
Please step through each of the metrics to see the difference in outputs with removing THS 9th graders. andything with "new" in the beginning of the image does NOT include THS 9th graders

### Top 5 Performing Schools
New Dataset: Images/new_top_5_schools.png
![New_top_5_schools](https://user-images.githubusercontent.com/94019661/149845376-be40fb5d-464e-4b24-870c-20831bd237f7.png)

Original dataset: Images/top_5_schools.png
![top_5_schools](https://user-images.githubusercontent.com/94019661/149845426-f65b6d4d-1227-4177-add0-c4eb5f90671a.png)

As you can see there were no changes to the top five schools in changing the data

### Bottom 5 Performing Schools
New Dataset: Images/New_bottom_5_schools.png
![New_bottom_5_schools](https://user-images.githubusercontent.com/94019661/149845452-85a2a115-0649-436f-89d9-b734a053647d.png)

Original dataset: Images/bottom_5_schools.png
![bottom_5_schools](https://user-images.githubusercontent.com/94019661/149845481-4543ff0d-22df-4141-850c-320172f8fc53.png)

There was also no effect in between the 2 data sets for the bottom 5 schools, similarly to the top 5.

### Average Math Scores
New Dataset: Images/New_math_scores.png
![New_math_scores](https://user-images.githubusercontent.com/94019661/149845509-7a686548-de7e-4805-99da-54371d03fc56.png)

Original dataset: Images/math_scores.png
![math_scores](https://user-images.githubusercontent.com/94019661/149845582-8a7d2550-91ea-4be8-a585-14ca8d92f8a0.png)

The main difference between the two datasets for this, is that you can see that all math grades were removed and changed to NaN.

### Average Reading Scores
New Dataset: Images/New_reading_scores.png
![New_reading_scores](https://user-images.githubusercontent.com/94019661/149845527-a6ed46fe-e97a-447b-9338-02c09c575341.png)

Original dataset: Images/reading_scores.png
![reading_scores](https://user-images.githubusercontent.com/94019661/149845620-2e81ebc2-a23e-4bac-aa9c-bf205f173037.png)

Similarily to above, the main difference between the two datasets for this, is that you can see that all reading grades were removed and changed to NaN.

### Scores by School Spending
New Dataset: 
![image](https://user-images.githubusercontent.com/94019661/149849988-bf568b79-e6a0-4c39-87dc-30c3e05fd429.png)

Original dataset: 
![image](https://user-images.githubusercontent.com/94019661/149849994-797b3db0-f30e-464a-b812-77f50e469d1a.png)

By removing THS data you can see the effect is reducing the % passing for math, reading and overall for the school spending group of $630-644. Everything else remains the same. You can see that the falsified grades for THS 9th greaders raised that groupings passing % ~10%.

### Scores by School Size
New Dataset: 
![image](https://user-images.githubusercontent.com/94019661/149850013-481dcb30-bfa8-4618-a4fe-3121b7356f72.png)

Original dataset: 
![image](https://user-images.githubusercontent.com/94019661/149850018-0909746f-bbf2-40ed-bcf5-d54c2a4ad2e7.png)

By removing THS 9th grades you can see it only slightly decreased all of the passing %.

### Scores by School Type
New Dataset: 
![image](https://user-images.githubusercontent.com/94019661/149850105-f1af7dff-f4b2-4d70-a908-1cb7d00181ec.png)

Original dataset: 
![image](https://user-images.githubusercontent.com/94019661/149850110-2e5df5ae-8ab2-494a-9a61-9fdbadf47147.png)

Similarily to the trends above, the effect of the new code is a slight decrease in passing %s for charter schools.

## Summary
Overall the effects of removing Thomas High School 9th graders is minimal. I belice it is better than providing artificial stats to the superintendant as that is not accurate.

the 4 main changes cause from the code chage (aside from what has been preiously mentioned) are as follows:
New Dataset:
![image](https://user-images.githubusercontent.com/94019661/149850280-30376ec3-1696-48c4-a42f-6e5b9cf59efc.png)

Old Dataset:
![image](https://user-images.githubusercontent.com/94019661/149850288-e92730e4-2084-4381-be5e-75d9d2aed05b.png)

1. Thomas High School avg math scores decreased by 0.067
2. THS avg reading scores increased by 0.047
3. THS Passing math % decreased by 0.086
4. THS passing reading % decreased by 0.29
5. Overall THS passing % decreased more than anything else by 0.32

