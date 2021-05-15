# School District Analysis

## Overview of the school district analysis

The purpose of this project was to determine trends and patterns in school performing and evaluate why students in some schools perfom better than in antoher, I made this research analyzing through two dataset, one of which has over 39,000 rows and contain students information and the other one containing schools information. 

## Results
After we started this project we recieved information about that the students dataset shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The following is the analysis of how the Data Frames were affected due to elimination of this suspicious data:


- How is the district summary affected?

The disctict summary containing the information of all students was like this: 

![District_summary_before](https://user-images.githubusercontent.com/81272629/118374021-70085380-b57f-11eb-9514-f93f56ae236c.png)

Due that we had to eliminate the suspicious data the district summary changed: 

![District_summary_after](https://user-images.githubusercontent.com/81272629/118374104-f15fe600-b57f-11eb-84f0-49d92f6bef6d.png)

We can see  that the total student count dicrease from 39,170 to 38,709 which indicate that 461 were take out from the analysis, we can also see a dicrease in the passing rates, with an Overall Passing dicrease from 65,1% to 64,9% which indicate that the suspicious students grades were high.

- How is the school summary affected?

As the suspicious data were all from Thomas High School, only this school were affected by the elimination of that data, this is how the summary looked before:

![School_summary_before](https://user-images.githubusercontent.com/81272629/118375028-ab595100-b584-11eb-9267-da1fb880da02.png)

Due that we had to eliminate the suspicious data the school summary changed:

![School_summary_after](https://user-images.githubusercontent.com/81272629/118375030-b0b69b80-b584-11eb-9c01-c0bcd5847ff3.png)

We can notice the same dicrease in the student count, anda similar dicrease in average scores and passing rates, which confirm that the elimination of the suspicious data affected negatively the school's performance.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The top 3 schools based on Overall Passing Rate with all students looks as follow: 

![Top3_schools_before](https://user-images.githubusercontent.com/81272629/118375411-27ed2f00-b587-11eb-9515-6f352bf2ff43.png)

After eliminate the suspicious data, the summary looks as follow: 

![Top3_schools_after](https://user-images.githubusercontent.com/81272629/118375428-3a676880-b587-11eb-997b-0e745b3ec06c.png)

As we can see, although the Thomas High School performance decreased, it remains as the top 2 school with better performance based on overall passing rate.

- How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade

The summary table of  math scores by grade with all students looks as follow: 

![grade_before](https://user-images.githubusercontent.com/81272629/118376128-b95ea000-b58b-11eb-9fb7-e9a84b039f87.png)

After eliminate the suspicious data, the summary looks as follow: 

![grade_after](https://user-images.githubusercontent.com/81272629/118376134-c11e4480-b58b-11eb-8f22-785c836d3147.png)

As we can see all the data remain the same except the scores for the 9th grade of Thomas High School which is the suspicious data.

### Scores by school spending

The summary table of scores by school spending with all students looks as follow:

![spending_before](https://user-images.githubusercontent.com/81272629/118376010-08f09c00-b58b-11eb-9a49-7d65ec9f9c08.png)

After eliminate the suspicious data, the summary looks as follow: 

![spending_after](https://user-images.githubusercontent.com/81272629/118376020-16a62180-b58b-11eb-8d5b-fa049cb6b435.png)

As we can see, there is no difference between the tables, this is because we would need to format the values to show to the hundredth to see any changes, which indicate that there wasn't a big impact to the table summary

### Scores by school size

The summary table of scores by school size with all students looks as follow:

![size_before](https://user-images.githubusercontent.com/81272629/118376448-8fa67880-b58d-11eb-9a6d-a49b1b297e20.png)

After eliminate the suspicious data, the summary looks as follow: 

![size_after](https://user-images.githubusercontent.com/81272629/118376467-9fbe5800-b58d-11eb-87c2-25f975e0fbc8.png)

As we can see, there is no difference between the tables, this is because we would need to format the values to show to the hundredth to see any changes, which indicate that there wasn't a big impact to the table summary

### Scores by school type

The summary table of scores by school typt with all students looks as follow:

![type_before](https://user-images.githubusercontent.com/81272629/118376538-2410db00-b58e-11eb-9116-fc796dd59a26.png)

After eliminate the suspicious data, the summary looks as follow: 

![type_after](https://user-images.githubusercontent.com/81272629/118376535-22471780-b58e-11eb-91a5-8c9209feea7b.png)


As we can see, there is no difference between the tables, this is because we would need to format the values to show to the hundredth to see any changes, which indicate that there wasn't a big impact to the table summary

## Summary 

After doing a complete analysis of all the data before (with all students) and after (without the suspicious data) we can extract the following conclusions:

- There was a decrease in the district Overall Passing Rate from 65,1% to 64,9% which indicate that with the suspicious data more students approved.
- The Thomas High School has a top performance with or without the suspicious data
- As we have a large dataset, the suspicious data doesn't have a big impact in the summary tables
- 461 students were take out from the analysis
- The Thomas High School has a worse performance after eliminate the suspicious data wihich indicate the grades of that students was higher
