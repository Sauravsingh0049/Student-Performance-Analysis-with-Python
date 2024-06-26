# Student-Performance-Analysis-with-Python

## Problem Statement
An analysis of the data of the students's scores in different subject with respect with the other factor that affect the scores or performance of the students. 
## Objectives
We want to analyse the data of students's score and how the other factors affecting the scores of the students in different subjects.
## Dataset Used
A historical dataset with 30641 rows and 13 columns spanning 1 year. Data is stored in a single table.

## Analyses derived from the dataset
first steps for analysing the data is to import all the import python libraries which will be used in this analysis process. In this analysis, we will be using Numpy, Pandas, Matplotlib and seaborn libraries.
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/0cd7a6f6-ef85-460e-89e1-a304675a5b6b)

Then will import the dataset on which we have to analyze.
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/c0d6351a-19eb-4f61-8eb1-8d20b5a7f79f)

Then we will run df.shape to get no. of rows and columns in the datasets.
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/c636916f-7014-4e3d-a7f8-981ddcc47be1)

Run df.head() to get information top 5 rows of the datasets.
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/a2a81dc7-2da7-4dde-8421-22a770f7d930)

run df.isnull().sum() to get the sum of the null values in the datasets.
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/1e9992ff-5dbb-46fb-9a0c-1a61c0759d51)

Now, We have noticed that Unnamed column is useless in the data.
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/3af9526d-5f57-4cf5-9073-a5742825400c)

In column weeklyhours, we have changed 10-may to 5-10 to make the data more meaninfull or significant.
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/b7e9c467-b802-4139-a348-c668219dd8cf)


-Now We will Analyse the Dataset

- Analysis of Gender distribution in the class

![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/ba0bccbe-98bb-46a8-9858-2076eba6cd2b)

- Analysis of Impact of the Parent's education on the scores.
  
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/206ea448-812f-4efd-860f-02c25a2dd81d)


from the above the chart we have concluded that the education of parent have big effect on the score of the students.

-	Analysis of Impact of parents' marital status on the scores.

![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/3ddd9abe-f170-489a-b2b8-fb5a9a6a5192)

-	Analysis of Scores by the students in the different subject through boxplot diagram.
-	
![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/d803b7c1-8f57-4f07-96be-08403e05d14f)

![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/d0eff258-06bd-4556-a97f-f7da8e0eb2ba)

![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/b60d1906-2e4e-486d-9d53-f05e38f0df65)

From these diagrams, we conclude that scores ranges in the maths is smaller than the other subjects. Thats means students are not able to score high marks in mathematics or mathematics is difficult subject for the student.

-	Analysis of the distribution of the Ethnic groups.

![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/db17c6f1-7460-45cf-94d1-27ea3c881a5d)

![image](https://github.com/Sauravsingh0049/Student-Performance-Analysis-with-Python/assets/155745836/c6e209b2-4757-471f-969b-5b12478d8315)

From this, we conclude that class have the high no. of students which are lies under the Ethnic Group C which consist of 28.55% followed by Group E and D.  

## Tools Used
![images](https://github.com/Sauravsingh0049/Vrinda-Store-Data-Analysis-and-Dashboard-Creation-Projec/assets/155745836/3cf4ac9f-2674-409e-9110-dfb4815bf8b7)

- Python is a high-level, general-purpose, and very popular programming language. Python programming language (latest Python 3) is being used in web development, and Machine Learning applications, along with all cutting-edge technology in Software Industry. Python language is being used by almost all tech-giant companies like – Google, Amazon, Facebook, Instagram, Dropbox, Uber… etc.

## Sample Insight
- Class consist have more boys then the girls.
- Impact of parents's education level on score is significant high thats means who scores high score likely to have highly education qualified parents.
- There is no high impact of parent's marital on the score.
- class consist of high no. of students who belongs to group C.
- Mathematics is difficult subjects for the students to high scores.



