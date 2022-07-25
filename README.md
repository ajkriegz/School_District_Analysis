# School_District_Analysis
This analysis was performed using Python 3.7.13, conda 4.13.0, and Jupyter notebook.

## Overview 
The previous analysis for the school district was performed with seemingly altered data. In light of this, to uphold state-testing standards and academic integrity, math and reading scores for Thomas High School's 9th grade class have been omitted while keeping the rest of the data intact. The changes have been compared and analyzed.

## Results
The results from the previous analysis will be compared with the results of the latest analysis to determine how the altered data affected the district's metrics. The following questions will guide this comparison.

* How is the district summary affected?
   Below are the new summary for schools in the district and the previous summary, respectively. Note especially the data labeled "Average Math Score," "% Passing Math," and "% Passing Reading."

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/district_summary_new.png "New District Summary")

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_district_summary.png "Previous District Summary")
   
   With the data for Thomas High School's 9th grade removed, the average math score for the district went down by 0.1, while the percentage of students passing math and the percentage of students passing reading went down about 1%.

* How is the school summary affected?
   Below are the dataframes containing data for each school in the district. The first table is from the latest analysis and the second table is from the previous analysis. Note especially the last five columns as we look at the data for Thomas High School.

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/school_summary_new.png "New School Summary")

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_school_summary.png "Previous School Summary")

   Every category containing the average scores and percentages of students passing is lower for Thomas High School in the newer dataframe.
   
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   Below is the ranking of the top five high schools in the district: the first from the new analysis, the second from the previous.

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/top_schools_new.png "New List of Top Schools")

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_top_schools.png "Previous List of Top Schools")

   While the ranking order of the schools did not change, note that overall the scores from the more recent analysis are lower for Thomas High School than before.

* How does replacing the ninth-grade scores affect the following:
   - Math and reading scores by grade
      First, we compare the math scores. Note that the second table has NaN ("Not a Number") in place of Thomas High School's average of math scores for the 9th grade.
      
    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_math_scores.png "Previous Math Scores") ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/math_scores_new.png "New Math Scores")

      The average for the 9th grade as a whole based on the previous analysis is 80.35 but with Thomas High School's grade omitted the average comes out to 80.12 instead. Next, reading scores.

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_reading_scores.png "Previous Reading Scores") ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/reading_scores_new.png "New Reading Scores")

      The overall average for 9th grade reading scores changes from 82.51 to 82.43 when Thomas High School's reported average is omitted.

   - Scores by school spending
      Below are the latest summary and previous summary, respectively, based on school spending per student.

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/spending_summary_new.png "New Spending Summary") 

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_spending_summary.png "Previous Spending Summary")

     This data set was not impacted by the change in reported data.

   - Scores by school size
      Below are the latest summary and previous summary, respectively, based on school size.

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/size_summary_new.png "New Size Summary")

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_size_summary.png "Previous Size Summary")

      This data set was not impacted by the change in reported data.

   - Scores by school type
      Below are the latest summary and previous summary, respectively, based on school type.

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/type_summary_new.png "New Type Summary")

    ![alt text](https://github.com/ajkriegz/School_District_Analysis/blob/main/Resources/old_type_summary.png "Previous Type Summary")

      This data set was not impacted by the change in reported data.

## Summary: 

* The summary data for the district was minorly impacted. With the data for Thomas High School's 9th grade removed, the average math score for the district went down by 0.1, while the percentage of students passing math and the percentage of students passing reading went down about 1%.

* Thomas High School's ranking within the district did not change, but their actual metrics were not so near to the top school's metrics as initially reported.

* Thomas High School reported scores and percentages of students passing are lower in every category, as shown on the School Summary Dataframe.

* The district-wide average for 9th grade as a whole in both math and reading went down when the altered data was removed.