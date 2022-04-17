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
  
  ![orig district analysis](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/schoolSummary_Old.png)

  Updated District Analysis Data Frame
  
  ![updated district analysis](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/districtAnalysis_New.png)
  
- School Summary: Average scores stayed relatively the same but passing percentages decreased significantly
  Original Summary for Thomas High School
  
  ![orig school summary](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/schoolSummary_Old.png)

  Updated Summary for Thomas High School
  
  ![new school summary](https://github.com/mein0819/School_District_Analysis/blob/main/readMe_Images/schoolSummary_New.png)
  
