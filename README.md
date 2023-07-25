# Overview:

This project utilizes Python and pandas to analyze school district data in the education sector. The objective is to assist the school board and mayor in making strategic decisions related to future school budgets and priorities. Two CSV datasets are employed for this analysis: "schools_complete.csv" and "students_complete.csv."

# Details:

The "schools_complete.csv" file contains essential details about schools, such as Student ID, school name, type, size, and budget. On the other hand, the "students_complete.csv" file comprises information about students, including Student ID, student name, gender, grade, school name, reading score, and math score.

To perform the analysis, both datasets are imported and merged using Python pandas. The aggregate data is then presented in pandas dataframes. The project is documented and presented using Jupyter Notebook to showcase and communicate the analysis results. To access the analysis report, please follow this link: Jupyter Notebook Viewer.

# PyCitySchool Obersvations:

- This Data in general interprets that Charter Schools have better quality of education as compare to District Schools. They have less number of students, so they have better focus on each students learning cycle. 
whereas, District schools get alot budgets/funding but due to the number of students or may be other reasons not mentioned in the dataset, there is less quality of education.

- The dataset includes information from a total of 15 schools and 39,170 students. On average, students scored higher in reading (average score of 81.87) than in math (average score of 78.98). The passing rate for reading (85.80%) was higher than for math (74.98%), resulting in an overall passing rate of 65.17%. This indicates that students generally perform better in reading than in math.

- Upon analyzing the school summary, it was found that among the 15 schools, 7 were classified as district level schools, while the other 8 were charter schools. The student population in schools ranged from 427 students at Holden High School to 4976 students at Bailey High School. The data also revealed that district schools have a larger student population compared to charter schools, likely due to their geographical coverage.

- The school summary also displayed the total budget for each school. Bailey High School had the highest budget ($3,124,928.00), while Holden High School had the lowest budget ($248,087.00). Interestingly, Bailey High School, despite having a high budget, did not perform as one of the top schools. Schools like Huang High School, with a higher budget per student, and Wilson High School, with a lower budget per student, may need to focus on improving their educational quality.

- Comparing district and charter schools, the total budget for district schools ($17,347,923.00) was higher than for charter schools ($7,301,505.00). However, when considering the budget per student, charter schools allocated more funds ($4,796.00) compared to district schools ($4,505.00), likely due to the smaller number of students in charter schools.

- The analysis indicated that in all metrics (average, percent, and overall) for both reading and math scores, charter schools outperformed district schools. Pena High School stood out with the highest average math score (83.839917), percent of students passing math (94.59%), and average reading score (84.044699), reflecting its strong reputation for teaching math and reading. Conversely, Huang High School had a lower average math score (76.842711) and a lower percentage of students passing math (65.683922). Thomas High School had the highest percentage of students passing reading (97.30%), while Rodriguez High School had a lower average reading score (80.744686), and Ford High School had a lower percentage of students passing reading.

- Holden High School's Grade 11 students achieved the highest average math score (85) across all schools and grades, while Grade 12 students at Holden High School obtained the highest average reading score (84.698795).

- An interesting observation from the analysis was that as the budget per student increased, the average math and reading scores, as well as the percentage of passing math, passing reading, and overall passing rates, decreased. This finding warrants further investigation into the true drivers of academic achievement.

- Moreover, the data indicated that as the number of students in schools increased, the average math and reading scores, as well as the passing rates for math, reading, and overall, decreased. This highlights the negative impact of larger student populations on student achievement. Schools, cities, districts, and charters should address student sizes in schools and classes, as it directly affects student achievement for various reasons.




