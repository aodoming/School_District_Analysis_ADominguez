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
             Removing math & reading scores for 9th graders from Thomas High School, has an almost negligible
             but negative impact nonetheless on the overall district summary. The average math and reading scores
             for eg. dropped from 78.98 to 78.00 and 81.87 to 80.89, respectively. Because the %overall changeis very minimal, 
             from 80.39 - 79.26 after the 9th grade scores have ben removed, it is safe to say that the overall district summary
             was not impacted. 
             
             • How is the school summary affected?
             
             Unlike the district summary, the school summary was greatly inpacted, The average math and reading scores went from 
             83.41 to 59.8 and 83.84 to 60.24, respectively, after the removal of the scores for 9th grade. 
             This in turn negatively impacts the overall performance of the school.
             
                        
             • How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the   
              other schools?
             
              Prior to the removal of 9th grade math and reading scores, Thomas High School (THS) was the second top-performing
              school. After the removal it could be considered as one of the low-performing schools, while Pena High School taking
              it's place as 2nd top-performing high school.
                          
             • How does removing the ninth-grade scores affect the Math and Reading Scores by Grade.
             
              The THS 9th graders received a math & reading score of "0" from previously, 83.6
              All other grades, 10th, 11th & 12th maintained their scores.
              
                   
              • Scores by School Spending, Scores by School Size, and Scores by School Type? 
               A change in scores should have no direct impact on the following:
 
               Scores by School Spending: No change there
             
               Scores by School Size: No change there

               Scores by School Type: No change there 

    
    
