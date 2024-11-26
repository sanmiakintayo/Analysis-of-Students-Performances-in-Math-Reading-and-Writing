# Students Performance Analysis
## Project Overview
This comprehensive analysis aims to evaluate student performance in Maths, Reading, and Writing based on various socio-demographic factors, including gender, parental education level, lunch type, race, and completion of preparation courses. The goal is to identify trends, disparities, and areas for targeted educational interventions to improve student outcomes.
![Screenshot 2024-11-26 003033x](https://github.com/user-attachments/assets/99c77d91-8751-44fb-899f-af8203065c2e)
## Objectives
This analysis aims to evaluate the impact of various socio-demographic factors on student performance in Math, Reading, and Writing. Specifically, the study aims to:
- Assess Performance Disparities: Identify and quantify any disparities in test scores based on gender, parents' education level, and lunch type (standard vs. reduced).
- Examine Preparation Courses Impact: Determine whether completion of preparation courses significantly influences student performance across the three subjects.
- Analyze Interactions: Explore potential interactions between socio-demographic factors and their combined effect on student performance.
- Provide Insights for Educational Interventions: Generate actionable insights that can inform educational interventions aimed at improving student outcomes and promoting equity in education.
## Methods
-	Data was obtained from Data.gov
-	Data cleaning and transformation were done with PowerQuery
-	Data modelling was done in PowerBI
-	Data analyses were done with Excel,  PowerBI, SQL
-	Data visualisation, reports and dashboards were done with PowerBI

### Example SQL Queries 
#### Query to determine the highest score in each of the three subjects
![Screenshot 2024-11-26 141728xx](https://github.com/user-attachments/assets/89a41c92-7724-41d5-87f8-210e05c17c16)
![Screenshot 2024-11-26 141728xxx](https://github.com/user-attachments/assets/3c8c4462-68a2-4b6e-9093-381d657dc5f4)
#### Query to retrieve the list of students who scored 98 or above in Maths 
- And their scores in Reading and Writing as well as information about their StudentID, Gender, Race/Ethnicity and Parents' education level.

![Screenshot 2024-11-26 142949xx](https://github.com/user-attachments/assets/40cf4197-0afb-4b90-92d7-b3051acf6106)
## Key Insights
### Average Performance
![Screenshot 2024-11-26 003127x](https://github.com/user-attachments/assets/027c83e9-034d-42e9-855c-ab566fed1e71)
- Maths: The average score is 67.9.
- Reading: The average score is 70.5.
- Writing: The average score is 69.5.
### High Pass Rate
- Maths: 89.5% of students passed.
- Reading: 93.4% of students passed.
- Writing: 91.3% of students passed.
![Screenshot 2024-11-26 003148x](https://github.com/user-attachments/assets/2dbadf76-61b4-42a8-aada-eece7be8dc7b)
### Gender Disparities
- Performance Trends: Male students tend to score higher in Math, while female students generally perform better in Reading and Writing.
- Variability: The difference in scores between genders is more pronounced in Reading and Writing compared to Math.
### Parental Education Level
- Correlation with Scores: Higher parental education levels are strongly correlated with better student performance across all subjects. Students with parents holding a Bachelor’s or Master’s Degree tend to perform better but are fewer in number. Lower pass rates among students with parent having high school education or below, indicate a significant correlation between parental education level and student performance.
- Impact Magnitude: The most significant improvements are seen in Reading and Writing scores for students whose parents have a college degree or higher.
### Impact of Lunch Type (Socio-Economic Indicator)
- Students receiving reduced lunch (an indicator of lower socio-economic status) tend to score lower on average in all subjects compared to those receiving standard lunch.
- Disparity Analysis: The gap is most evident in Math scores, suggesting a potential area for targeted support.
### Preparation Courses
- Effectiveness: Students who completed preparation courses show a marked improvement in test scores, particularly in Math and Writing.
- Participation Rates: There's a notable disparity in preparation course completion rates based on socio-economic status, with fewer students on reduced lunch participating.
- Interaction Effects:
- Compound Benefits: Students with higher parental education levels who also complete preparation courses perform exceptionally well, indicating that multiple support systems can compound positively.
- Gender and Socio-Economic Status: Female students from lower socio-economic backgrounds show significant improvement in Reading and Writing when enrolled in preparation courses, suggesting targeted intervention 
  could mitigate socio-economic disadvantages.
### Race and Ethnicity
The following charts provided insights into student performance in Maths, Reading, and Writing categorized by race and ethnicity groups.

![Screenshot 2024-11-26 131322x](https://github.com/user-attachments/assets/90dce127-4c2b-4999-a238-5e1cb1e25f00)
#### Consistent Top Performers
- Group C consistently has the highest number of students passing across all three subjects.
#### Second Highest
- Group D remains the second highest performer across Maths, Reading, and Writing.
#### Lowest Performers
- Group A consistently shows the lowest number of students passing in all subjects, indicating a potential need for targeted support and interventions.
- These insights highlight significant performance disparities among different racial and ethnic groups. 
## Recommendations
- Targeted Interventions: Implement additional support and resources for students from lower socio-economic backgrounds, especially in Reading and Writing.
- Support for Students on Reduced Lunch: Implement programs to assist these students, as they consistently have lower pass rates.
- Encourage Participation: Increase accessibility and encouragement for preparation courses, particularly for students receiving reduced lunch.
- Parental Involvement: Engage parents in the educational process, emphasizing the impact of higher education aspirations on student performance. Highlight the importance of parental education and involvement in student success.
- Support for Students on Reduced Lunch: Implement programs to assist these students, as they consistently have lower pass rates.
- Focus on Female Students: Leverage the strength in Reading and Writing while addressing the near parity in Maths to further enhance performance.
- The consistent high performance of Race and Ethnicity Groups C and D and the lower performance of Group A suggest that educational strategies should be tailored to support underperforming groups effectively.
These insights can help in forming strategies to enhance student performance and ensure equitable educational opportunities.
