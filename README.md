# School_District_Analysis
School test score analysis using Anaconda, Python and Jupyter

## Overview
Task is prepping standardized test data for analysis, reporting and presentation to provide insight into performance trends and patterns to inform discussions and aid with strategic decision-making. Analyze data on funding and test scores. Looking at Math and Reading scores based on schools attended. Aggregate the data and showcase trends in school performance to assist school board and superintendent in making decisions regarding school budgets and priorities.

While looking at the data, there is suspicion that the ninth grade math and reading scores at Thomas High School show academic dishonesty so in order to uphold state-testing standards, the analysis was modified and rerun.

### Results

* How is the district summary affected?
The school district summary showed minor changes in % Passing Math and % Passing Reading and realitively no change in % Overall Passing.

![orig dist sum](https://user-images.githubusercontent.com/96350410/150653173-6bc909d5-0a70-4280-b14d-523ce5d5012a.png)

![mod dist sum](https://user-images.githubusercontent.com/96350410/150653174-1df587d3-0a13-4640-871e-9c93a3455606.png)

* How is the school summary affected?
  -The school summary for Thomas High School showed the average math score dropped from 83.41 to 83.35 and percent passing going from 93.27% to 93.19%.
  -The average reading scores increased from 83.85 to 83.90 with percent passing going from 97.31% to 97.02%. 
  -The overall passing percent showed a slight decrease from 90.95% to 90.63%.

![orig school sum](https://user-images.githubusercontent.com/96350410/150653557-6cf16da3-81ee-4a34-85a2-ba403f39edc6.png)
![mod school sum2](https://user-images.githubusercontent.com/96350410/150653770-0697b91c-52b6-4edd-8472-fb489c3477b2.png)

* How does replacing the ninth-graders' math and reading scores affect Thomas High School's performance relative to other schools?
Replacing the ninth grade math and reading scores definitely shows that Thomas High School performed a bit worse than previously thought.

* How does replacing the ninth-grade scores affect the following:

    1. Math and reading scores by grade.
    The math and reading scores for 9th grade were removed but the scores for 10-12 grades should stay the same.
    
    ![orig math score](https://user-images.githubusercontent.com/96350410/150654002-2096708f-1288-405e-ab62-40d06970e2d9.png)
    ![mod math score](https://user-images.githubusercontent.com/96350410/150654006-b3270c5f-9a58-419b-b3c8-f6694821d8b5.png)
    
    ![orig read score](https://user-images.githubusercontent.com/96350410/150654015-fd12717c-da07-481f-b3d0-aedd00dd97ca.png)
    ![mod read score](https://user-images.githubusercontent.com/96350410/150654018-4094e108-b107-4cb8-86ce-db0190f52ae4.png)

    2. Scores by school spending.
    The modified scores as outlined above but did not impact spending range per student.
    ![orig score by spending](https://user-images.githubusercontent.com/96350410/150654269-1c00d56e-6f84-49f9-a47d-9323b972d912.png)
    ![mod score by spending](https://user-images.githubusercontent.com/96350410/150654197-8f7945a4-2333-4e65-b6d4-17ddc44618d6.png)

    3. Scores by school size.
    The scores based on school size are the same for both data sets.
    ![scores by size](https://user-images.githubusercontent.com/96350410/150654356-0269b0f2-45a7-45db-b488-a2e33d09ec46.png)

    4. Scores by School type
    The scores by school type are the same for both data sets so were not impacted.
    ![scores by type](https://user-images.githubusercontent.com/96350410/150654413-1430e9c5-ef26-4836-a485-e9fb7ef52e1e.png)

#### Summary
While there may have been some issues with the ninth grade math and reading tests, overall it didn't change the position of Thomas High School within the district rankings. There was a slight decrease in the math score and passing percent for Thomas High School. There was a slight increase in the reading score for Thomas High School. There was also a slight decrease in the overall passing percentage. However, the changes in scores were insignficant when looking at the district as a whole.
