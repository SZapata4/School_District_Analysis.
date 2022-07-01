# School District Analysis

## Overview of the school district analysis
 The purpose of the is project was to analyze the data of a school district given to us by a member of the school board. The goal was to be able to present each school’s budget and testing scores using pandas to present them in data frames. Due to potential academic dishonesty by the ninth-grade students of Thomas High School we have been tasked with replacing those math and reding scores with NaNs and redo the analysis.

## Results

After re-running the analysis, we are going to look at the effects on the results.

![District_Summary](https://github.com/SZapata4/School_District_Analysis./blob/main/Resources/District_Summary.png)
 
o Looking at the above District Summary compared to the old one not much has changed. Most of the statistics changed by less than .5 percentage points or points. 

o However, this drastically changed the Thomas High School summary. The overall passing percentage dropped approximately from 91% to 65%. The % Passing reading dropped from approximately 96.5% to 70% and the % Passing Math approximately dropped from 94% to 67%.

o It also causes Thomas High School to drop out of the top 5 schools for overall percentage of passing students.

o After omitting the ninth-grade data from Thomas Highschool let’s look at how it affects the following:
  * Math and reading scores by grade do not change at all except that 9th grade reading and math for Thomas Highschool is now Nan.
  * Scores by school spending does not increase as spending
  increases. As you can see below the overall passing 
  percentage drops as spending increases. 

  ![school_by_spending](https://github.com/SZapata4/School_District_Analysis./blob/main/Resources/school_by_spending.png)

  * Scores by school size data frame below is interesting because the 
  small and medium schools have almost the same overall passing percentage being separated by 1 percentage point at 90 and 91 percent. While the large
  schools have a drastically lower overall passing percentage of 58.

  ![school_by_size]( https://github.com/SZapata4/School_District_Analysis./blob/main/Resources/school_by_spending.png)

  * Scores by school type data frame reveals that charter schools 
  Better than district schools in every category and by 36% in overall passing percentage

  ![school_by_type]( https://github.com/SZapata4/School_District_Analysis./blob/main/Resources/school_by_type.png)


# Summary

Replacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to drop drastically. The district also had its average math and reading scores decrease, as well as the overall passing percentage for students. Also, Thomas High School lost its placement as a top five school within this District. However, once I updated the total student counts to exclude the Thomas High School ninth graders and omitted their scores from the dataset, Thomas High School regained its place as the number two school in the district when it comes to overall passing percentage. 
