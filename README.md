# School_District_Analysis

## Overview of the school district analysis: 
In this school district analysis exercise, I've been tasked with re-calculating school district math and reading test totals due academic dishonesty (altered grades) discovered for Thomas High School ninth graders.  To uphold the state-testing standards, I needed to remove the math and reading scores for Thomas High School ninth graders from the calculations.

My code to fulfill this exercise can be accessed here: [https://github.com/legeren/School_District_Analysis/blob/34dec4291b0ec8cd638a0b1e2aee27b5449481e5/PyCitySchools_Challenge.ipynb]

## Results: 
The following summarizes how the removal of Thomas High School 9th graders' reading and math scores affected the state-testing results.

- How is the district summary affected?
  - The district summary showed a lower score overall until the removal of Thomas High School 9th grader's reading and math scores.

- How is the school summary affected? Thomas High School summary was skewed after removing the 9th graders' test results, lowering the school's average (see before image).  By fixing the totals and removing the 9th graders' test results from the equation, the passing % were normalized.
  - Before: ![image](https://user-images.githubusercontent.com/100737452/161179745-48ef3777-3a93-4221-ba23-40fd0b9a49ac.png)
  - After: ![image](https://user-images.githubusercontent.com/100737452/161179811-e5146619-3c40-43a2-87b9-a36c2df68ff5.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - By removing Thomas High School's 9th graders' scores, the % passing for math, reading and overall put Thomas High School more at par with the other schools.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade - Before replacing Thomas High School's 9th grade scores with Nan, the scores put Thomas High School in the top 5 overall schools 

  - Scores by school spending - Considering Thomas High School is in the mid-to-top spend range per student ($631-645), replacing the 9th grade scores showed better results for the school overall when only 10th to 12th graders were taken into consideration.

  - Scores by school size - Thomas High School is middle of the pack (medium school size).  Replacing of 9th grade scores from this school still showed that the school overall fared better than larger school sizes.
  
  - Scores by school type: Charter schools still showed higher overall scoring than district school types whether/not Thomas High School's 9th grade scores were replaced.
    

## Summary: 
In summary, the following changes resulted in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. The % passing scores for Thomas High School needed to be recalculated to remove the 9th grade counts.
2. The % passing scores for the district needed to be recalculated to remove Thomas High School 9th grade counts.
3. Thomas High School overall scores put them outside the Top 5 schools after the ninth grade scores were replaced with NaN.
4. Thomas High School did get back inside the Top 5 schools after the ninth grade scores were taken out of consideration (i.e., only 10th to 12th grades counted)

