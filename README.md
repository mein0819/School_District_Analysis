# School_District_Analysis

## Project Overview

The purpose of this project is to analyze testing scores in relation to school district data and to replace
possibly corrupt data while keeping the clean original data intact. 
The analysis provides the following:
- Comprehensive data frames for the entire district, each school within the district and every student within the district
- Data frames that show math, reading and overall passing percentages based on specified criteria:
    - Grade level
    - Per student spending
    - School Size
    - School type
- Corrupt data has been replaced for all 9th grade students at Thomas High School with NaNs

## Resources
- Data Sources: schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, Pandas 1.3.4, Jupyter Notebook 6.4.5

## Analysis

Replacing math and reading scores for 9th grade students at Thomas High School with NaNs showed the following results:
- District Summary: Removing scores from 461 students showed a small decrease in the overall scores for the district <br/>
  
  Original District Analysis Data Frame
  
  ![orig district analysis](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/districtAnalysis_Old.png)

  Updated District Analysis Data Frame
  
  ![updated district analysis](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/districtAnalysis_New.png)
  
- School Summary: All of the metrics had slight decreases, either a few tenths or hundredths of a percent
  Original Summary for Thomas High School
  
  ![orig school summary](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/schoolSummary_Old.png)

  Updated Summary for Thomas High School
  
  ![new school summary](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/schoolSummary_New.png)
  
- Performance relative to other schools: Thomas High School's updated metrics weren't enough to change their <br/>
  position in relation to other schools, they're still ranked second among top performing schools.
- Math and Reading scores by grade: 10th thru 12th average scores stayed the same, but 9th grade scores were <br/>
  replaced by 'nan' and that's the value placed in the data frames
  
  Math Scores by Grade:
  
  ![grade scores](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/mathGrade_New.png)
  
  Reading Scores by Grade:
  
  ![reading scores](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/readingGrade_New.png)
  
- Scores by School Spending: Dropping the 9th grade scores from Thomas High School had no noticable effect on the <br/>
  metrics for the spending ranges per student for the district. Thomas High School falls in the $631-645 range.
  
  Original Spending Range Metrics
  
  ![spending range old](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/spending_Old.png)
  
  Updated Spending Range Metrics
  
  ![spending range new](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/spending_New.png)
  
- Scores by School Size: Dropping the 9th grade scores from Thomas High School had no noticable effect on the <br/>
  metrics for school size in the district. Thomas High School falls into the Medium range
  
  Original School Size Metrics
  
  ![original size](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/size_Old.png)
  
  Updated School Size Metrics
  
  ![updated size](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/size_New.png)
  
- Scores by School Type: Dropping the 9th grade scrores from Thomas High School had no noticable effect on the <br/>
  metrics for school type in the district. Thomas High School is a charter school
  
  Orignal School Type Metrics
  
  ![orignal type](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/type_Old.png)
  
  Updated School Type Metrics
  
  ![updated type](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/type_New.png)
  
## Summary
### Effects of dropping 9th grade scores from Thomas High School

1. Overall District passing percentages dropped:
    - Percentage Passing Math dropped from 74.9 to 74.8
    - Percentage Passing Reading dropped from 85.8 to 85.7
    - Percentage passing both Math and Reading dropped from 65.2 to 64.9
2. School percentages dropped for Thomas High School
    - Average Math Score dropped from 83.4 to 83.3
    - Percentage Passing Math dropped from 93.2 to 93.1
    - Percentage Passing Reading dropped from 97.3 to 97.0
    - Percentage Passing both Math and Reading dropped from 90.9 to 90.6
3. 
