# School_District_Analysis

## Overview of the school district analysis: 
This analysis will provide an overview of school district data that has been disected through the use of Python and the Pandas Library. Through the ananlysis of this data can trends be uncovered and presented about school preformance. Key metrics for each school will be created, these metrics will include: Top 5 and bottom 5 preforming schools, based on overall passing rate; The average math and reading scores recieved by students in each grade level at each school; and school preformance based on: budget per student, school size, and type of school. in addition, evidence of academic dishonesty is suspected within "Thomas High School", and the task of replacing Ninth Grade math and reading scores within "Thomas High School" to "NaN" is at hand. Afterwards a comparison of the data will be established.

## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions.
 - How is the district summary affected?
 
 figure 1.1 - District Summary Original:
 ![District_Summary_Original](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/District%20Summary%20images/District_Summary_Original.png)
 
 in figure 1.1 The Original District Summary is shown and presents the follow statistics:
 - Total Schools: 15
 - Total Students: 39,170
 - Total Budget: $24,649,428.00
 - Average Math Score: 79.0
 - Average Reading Score: 81.9
 - % Passing Math: 75.0
 - % Passing Reading: 85.8
 - % Overall Passing: 65.2
 
 From figure 1.1, it should be acknowledge that the Overall passing Percentage seems to fall fairly low, summing up to be a 65.2%.
 
 figure 1.2 - District Summary Edited:
 ![District_Summary_Edited](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/District%20Summary%20images/District_Summary_Edited.png)
 
 in figure 1.2 The Edited District Summary is shown and presents the following Statistics:
 - Total Schools: 15
 - Total Students: 39,170
 - Total Budget: $24,649,428.00
 - Average Math Score: 78.9
 - Average Reading Score: 81.9
 - % Passing Math: 74.8
 - % Passing Reading: 85.7
 - % Overall Passing: 64.9
 
 Looking at the highlighted areas in each District Summary Images illustrates the changes that occured after the removal of "academically dishonest" 
 data. The "Average math Score" has dropped by 0.1%. The "% Passing Math" has dropped by 0.2%. The "% Passing reading" has dropped by 0.1%. The "% Overall Passing" has the largest impact, dropping by 0.3%. The changes that have occured are miniscule, but still present.  
 
 - How is the school summary affected?
 
 figure 2.1 - Per School Summary Original:
 ![Per_School_Summary_Original](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/Per%20School%20Summary%20Images/Per_School_Summary_Original.png)
 
 in figure 2.1 The Per School Summary is shown. taking a closer look at "Thomas High School", the following statistics are presented:
 - School Type: Charter
 - Total Students: 1635
 - Total School Budget: $1,043,130.00 
 - Per Student Budget: $638.00
 - Average Math Score: 83.418349
 - Average reading Score: 83.848930
 - % Passing Math: 93.272171
 - % Passing Reading: 97.308869
 - % Overall Passing: 90.948012
 
 figure 2.2 - Per School Summary Edited:
 ![Per_School_Summary_Edited](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/Per%20School%20Summary%20Images/Per_School_Summary_Edited.png)
 
  in figure 2.2 The Edited Per School Summary is shown. taking a closer look at "Thomas High School", the following statistics are presented:
 - School Type: Charter
 - Total Students: 1635
 - Total School Budget: $1,043,130.00 
 - Per Student Budget: $638.00
 - Average Math Score: 83.350937
 - Average reading Score: 83.896082
 - % Passing Math: 93.185690
 - % Passing Reading: 97.018739
 - % Overall Passing: 90.630324
 
 Looking at the highlighted areas in each Per School Summary Images illustrates the changes that occured after the removal of "academically dishonest" 
 data. The "Average math Score" has dropped by roughly 0.067%. The "Average reading Score" has increased by roughly 0.047%. The "% Passing Math" has dropped by roughly 0.086%. The "% Passing reading" has dropped by roughly 0.29%. The "% Overall Passing" has dropped by roughly 0.32%. 
 
 further analysis from the Per School Summary data elucidates how the "total School Budget" does not necessarily correlate with a higher overall passing Percentage. In fact, schools with a a poor overall passing percentage seem to have a higher total School Budget, giving insight that money may not be the issue at had for poor preformance. 
 
 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 
 figure 3.1 - Top Preforming Schools Original:
 ![Top_Preforming_Schools_Original](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/Top%20Preforming%20Schools%20Images/Top_Preforming_schools_Original.png)
 
 in figure 3.1 The original top preforming Schools are shown. Thomas High School appears as the second highest preforming school, following right behind Cabrera High School. 
 
  figure 3.2 - Top Preforming Schools Edited:
 ![Top_Preforming_Schools_Edited](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/Top%20Preforming%20Schools%20Images/Top_Preforming_Schools_Edited.png)
 
 in figure 3.2 The Edited Top preforming Schools are shown. The Placement of Thomas High Schools is unchanged, showing that even after removing Ninth Grade data is does not affect the overall preformance enough to change the postion amongst other schools. 
 
 # How does replacing the ninth-grade scores affect the following:
 
 - Math and reading scores by grade:
 
 figure 4.1 - Math Scores by Grade Original:
 
 ![Math_Scores_By_Grade_Original](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/Scores%20By%20Grade%20Images/Math_Scores_By_Grade_Original.png)
 
 figure 4.2 - Math Scores by Grade Edited:
 
 ![Math_Scores_By_Grade_Edited](https://github.com/Calebmkelly/School_District_Analysis/blob/main/Resources/Scores%20By%20Grade%20Images/Math_Scores_by_Grade_Edited.png)
 
 above are figures 4.1 and 4.2 illustrating the Math Scores by grade both Original and Edited. The only change that occurs between the data is in figure 4.2, where the 9th Grade values for Thomas High School are shown as "nan" or Not a Number. This is at the result of removing that data.
 
 - Scores by school spending:
 
 - Scores by school size:
 
 - Scores by school type:
 
## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
