Gender Pay Analysis


Problem Statement

This project focuses on analyzing gender pay disparities across various levels in an organization. The main objective is to understand the salary distribution between males and females at different job levels.

1. What is the average salary for males and females overall?
2. Within each level (e.g., IC3, IC4, IC5, IC6, M1, Others), who earns more, males or females?
3. Which level has the highest gender pay disparity?
4. Are females underrepresented in higher-paying levels (e.g., IC6 or M1)?
5. Does any level show near-equal pay between males and females?
   
Answers

What is the average salary for males and females overall?

Male: $162,110
Female: $147,961


Within each level (e.g., IC3, IC4, IC5, IC6, M1, Others), who earns more, males or females?

IC3: Female
IC4: Male
IC5: Male
IC6: Male
M1: Female
Others: Male


Which level has the highest gender pay disparity?

Level: Others
Male: $163,431
Female: $119,601

Are females underrepresented in higher-paying levels (e.g., IC6 or M1)?

At the M1 level, females receive higher pay compared to their male counterparts.

Does any level show near-equal pay between males and females?

Yes, at the IC3 level, females receive slightly higher pay compared to males.

Steps Taken

Handling Missing Values
Ensured all missing or null values were handled appropriately.

Categorization of Levels
I have various level categories, which I have organized into 6 main sections for easier understanding.

Cumulative Sum
Implemented a cumulative sum to analyze data over time and across levels.

Creating Revised Levels (6)
Revised the level categories to group them into 6 sections for better analysis.

Use of Quartiles for Salary (IQR)

Interquartile Range (IQR) was calculated to understand the spread of the salary distribution.
Upper and Lower Thresholds were defined based on IQR to identify salary outliers.
Winsorizing - Delete Outliers
Applied Winsorizing to reduce the effect of outliers in the salary data.

Functions Used

AVERAGEIFS: To calculate the average salary based on certain conditions.
COUNTIFS: To count the number of males and females in each level.
