# **School District Analysis**

## **Overview**
The purpose of this project was to show how dropping data from the dataset affects 
overall analysis. In this project high school students' reading and math scores were analyzed 
so that high-level overview of the district's key metrics as well as the key metrics for each
school were presented in a table format. After the complete analysis of the school district dataset,
the math and reading scores for Thomas High School were replaced with NaNs and the same analysis
was completed. In the repeated analysis, Pandas *loc* method with conditional statements
and comparison and logical operators was used to select the ninth-grade reading and math scores
for Thomas High School. Then, with the help of Pandas NumPy module, the reading and math scores
were changed to NaN.


## **Results**
- The district summary is affected by at most 0.3% reduction of the percentage of students passing 
  math and reading and of the overall passing percentage. 

- The school summary for Thomas High School was affected significantly when scores were
  replaced by NaNs and passing rates were calculated with the original student count.
  -%Passing Math changed    from 93.3% to 66.9 % 
  -%Passing Reading changed from 97.3% to 69.7% 
  -%Overall Passing changed from 90.9% to 65.1%
  
  [Thomas High School school summary] ( )

- Replacing the ninth graders' math and reading scores does not affect Thomas
High School's performance significantly relative to the other schools. THS is 
still the second highest performing school in the district with a 90.6% overall
 passing percentage instead of a 90.9%. 


- Math and reading scores by grade did not change except for that the 9th grade 
  in Thomas High School did not have grades. 
  
- Scores by school spending were affected, they became lower for the second and third 
  bins.
 [scores by school spending] ( )
 
 - Scores by school size were not affected
 
 - Scores by school type were not affected


## **Summary**

- Thomas High School is still the second highest performing school
- Once the student count without grade were removed the school summary was not significantly
  affected.
- Scores by school type and size were not affected at all. 
- The math and reading scores by grade did not change.






 
