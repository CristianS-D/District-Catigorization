# District Categorization on Various Demographic Indicators
#### Multidimensional Peer Grouping for School District Benchmarking
1. Objective

The goal of this project is to develop a more accurate benchmarking system for school district performance. Current models often rely on state averages or geographic neighbors as points of comparison. However, these benchmarks are often flawed because they ignore vast disparities in socioeconomic status (SES) and internal district logistics.

2. Hypothesis

I hypothesize that school district outcomes are more accurately predicted and compared by grouping districts based on socioeconomic and demographic homogeneity rather than location. Specifically, relationships I anticipate seeing:

    Teacher Compensation and Student-Staff Ethnic Homogeneity will be primary drivers of performance variance.

3. Methodology: K-Nearest Neighbors (KNN) & Clustering

To define these "statistical peers," I intend to utilize a K-Nearest Neighbors (KNN) or similar clustering algorithm. By plotting districts in a multi-dimensional space, we can identify the "nearest" districts based on:

    Economic Disadvantage Percentage: The ratio of students qualifying for free/reduced lunch. 

    Ethnic Homogeneity Index: The alignment between student demographics and staff demographics.

    Teacher Salary Scales: Adjusted for regional cost of living.

    Funding per Student: Total operational expenditures.

4. Considerations

    Consider districts who fall under Community eligibility provision or cep to skew / under report eco-dis numbers. due to not needing students to report ego disc for free or reduced lunch For now, I will. Assume data is reported accurately identifying the outliers and move forward. future goal would be to identify Local Economic factors to more accurate represent a District's eco-dis percentages.