# School_District_Analysis_ADominguez
Analyzing data on student funding and students standardized test scores: aggregate data and showcase trends and school performance.
Using Pandas & amp; Jupyter Notebook.


  # PyCitySchools_Challenge Analysis
  Background: The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent               of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.
              After assessing the situation with the school superintendent and Maria, you decide the best approach is to:
              •	Remove the ninth-grade math and reading scores from Thomas High School.
              •	Keep all other data associated with the ninth-grade students and Thomas High School intact
                          
  Objectives: The goals of this challenge are for you to:
              •	Filter DataFrames using logical operators.
              •	Replace the incorrect values with NaN.
              •	Explain how your PyCitySchools analysis changes after you handle the incorrect data.  

  Instructions:
              1.	Create a duplicate of PyCitySchools.ipynb and rename it PyCitySchools_Challenge.ipynb.
              2.	Correct the students' names so there are no professional prefixes or suffixes.
              3.	Replace the reading and math scores for ninth graders at Thomas High School with NaN.
                  o	Use loc on the student_data_df DataFrame to select the columns by condition.
                  o	Set the column you want equal to "NaN" by using np.nan for the reading and math scores separately. (Hint: Read the  
                  Pandas documentation on the loc method (Links to an external site.).)
              4.	Merge the clean student data with the school dataset.
              5.	After removing the reading and math scores, answer the following questions:

  Analysis:
             
             • How is the district summary affected?
            
             Removing math & reading scores for 9th graders from Thomas High School(THS), has an almost negligible
             but negative impact nonetheless on the overall district summary. The average math and reading scores
             for eg. dropped from 78.98 to 78.00 and 81.87 to 80.89, respectively. Because the %overall changeis very minimal, 
             from 80.39 - 79.26 after the 9th grade scores have ben removed, it is safe to say that the overall district summary
             was not hugely impacted. 
             
             • How is the school summary affected?
             
             Unlike the district summary, the school summary was greatly inpacted. For THS, the average math and reading scores went                  from 83.41 to 59.85 and 83.84 to 60.24, respectively, after the removal of the scores for 9th graders. As a result,the                  %Passing Math and reading scored for THS went from 93.27 to 66.9 and 93.31 to 69.66, though the %Overall Passing did not                change.
                
             • How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the   
              other schools?
             
              Prior to the removal of 9th grade math and reading scores, Thomas High School (THS) was the second top-performing
              school. After the removal and average scores in math and reading going from 83.41 to 59.84 and 83.84 to 60.24                           respectively, THS is the lowest performing school. While Pena HS rose to number1 top-performing school.
                                       
             • How does removing the ninth-grade scores affect the Math and Reading Scores by Grade.
             
              The THS 9th graders received a math & reading score of "0" from previously, 83.6
              All other grades, 10th, 11th & 12th in THS maintained their scores.
              All other grades, 9th, 10th, 111th, 12th in all the other schools were not impacted.
              
                   
              • Scores by School Spending, Scores by School Size, and Scores by School Type? 
                
               Scores by School Spending:
                  Before: Avg_math    Avg_Reading   %Passing_Reading
                            83.41       83.84           97.31
                  After:    59.84       60.24           69.66
                  The above shows a change in scores by school spending
               
            
               Scores by School Size: 
                  THS is in school size bin Medium(1000-2000). Before the change the scores by medium schoool size were:
                  Before: Avg_math    Avg_Reading   %Passing_Reading    %Passing_math   %Overall Passing
                            83.37       83.86           96.79             93.60             94.82
                  After the change the scores by medium schoool size were:
                  After:    78.7        79.1            91                 88               90
           

               Scores by School Type:
                  Before:  School Type  Avg_math    Avg_Reading   %Passing_Reading
                              Charter      83.5         83.9           97
                  After:      Charter      80.5         80.9           93
                  
                  No changes occured in the District type schools
                  
                  Conclusion: All scores by (school spending, school size, school type) were all impacted/dropped due to the  the                         removal of the THS 9th grade matha nd reading scores.
                  
                  
                  
    
