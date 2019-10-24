# School_District_Analysis_ADominguez
Analyzing data on student funding and students standardized test scores: aggregate data and showcase trends and school performance.
Using Pandas & amp; Jupyter Notebook.


  # PyCitySchools_Challenge Analysis
  Background: The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent               of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.
              After assessing the situation with the school superintendent and Maria, you decide the best approach is to:
              •	Remove the ninth-grade math and reading scores from Thomas High School.
              •	Keep all other data associated with the ninth-grade students and Thomas High School intact.
              
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
             
             Removing math & reading scores for 9th graders from Thomas High School will change the overall district summary data, in   
             that the original data was based on all students from all grades in 15 schools. With the math and reading scores for 9th   
             removed the average math and reading, passing math and passing reading percentages, as well as the overall passing 
             percentage values would be smaller. This may suggest the district is not performing as well as initially believed.
             
             • How is the school summary affected?
             
             Similar to the impact on the district summary, the updated school summary would be less representative of the true picture              of the overall school’s performance in math and reading. This is because the initial summary data shows scores from all                  grades including the 9th graders, upon which average and percentage scores were computed. Therefore, removing the 9th grade              math and reading scores will change the average and percentage scores as well, hence impacting the true academic image of                the school.
             
             • How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the   
             other schools?
             
             Thomas High School is the second highest-performing school with high average and percentage scores in math and reading.  
             With the removal of 9th grade scores that would change the averages and percentages for the school, and may likely show                  that other schools perform better than Thomas High School.
             
             • How does removing the ninth-grade scores affect the Math and Reading Scores by Grade.
             
             The change would affect the 9th graders more than it would impact other grades, since the grade removal is specific to the              9th grade.
             
            
             • Scores by School Spending, Scores by School Size, and Scores by School Type? 
              
             Scores by School Spending: Because the school’s scores are directly related to school spending per student, a change in    
             scores up or down, would mean a change up or down in spending. 
             
             Scores by School Size: The school size is determined by the student count; so, if 9th grade scores are removed, (though                  their associated data remains), the scores by the school size will be reduced. 

             Scores by School Type: A change in scores should have no direct impact on scores by school type.
 

    
    
