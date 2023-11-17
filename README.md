# Topic
Student Mental Health Factors.

# Context
Mental health becomes increasingly important with more and more people suffering from depression. So far, approximately 280 million people in the world have depression, according to the World Health Organization. Students are at high risk of mental disorders due to many reasons, such as biological factors, personality and psychological state, school experience, and lifestyle (Liu et al., 2022). These categories consist of more specified factors that do harm to mental health, such as insufficient social support, unsatisfactory academic performance, Low family socioeconomic status, poor sleep quality, and so on. Figuring out what has a great impact on depression is conducive to the prevention of mental illness for young people. 

# Research Question and Hypothesis
RQ: 
Among sleep quality, living conditions, academic performance, and social support, which factor has a dominant influence on depression?

Hypothesis: 
Academic performance is the most significant factor. On one hand, students are likely to be forced to fulfill their parents’ expectations. On the other hand, they are also eager to be the best ones with high grades because that’s the easiest access to social success in the future and it makes academic performance way more important than others, which is hazardous to mental health.

# Variables to be Included
| Header | Description | Data Type |
| ------ | ----------- | --------- |
| Depression | Level of depression | number |
| Sleep Quality | Level of Sleep Quality | number |
| Living Conditions | Level of Living Conditions | number |
| Academic Performance | Level of Academic Performance | number |
| Social Support | Level of Social Support | number |

# Creator and Source of Data
The creator is called Chhabii, and the source of data comes from his dataset “Student Stress Factors: A Comprehensive Analysis” on the website “Kaggle”.  (https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis)

# Analysis Plan
According to the dataset, each row represents a certain student’s health condition. The level of depression is related to the level of sleep quality, living conditions, academic performance, and social support. To find which factor has the greatest impact on depression, we can compare their correlation coefficients with depression. First, we need to filter out unnecessary columns and regard the table with useful data as a Dataframe. Second, we will apply corr() function to each factor with depression in Python. For example, the correlation coefficient of depression and sleep quality can be calculated by "df['depression'].corr(df['sleep quality'])". The higher the score is, the stronger the relationship is. At last, we can draw a conclusion after comparing the final results.  
