# R-tiny-project-
Analysis of Student Academic Performance
Project Overview
This project analyzes student academic performance using R Programming and R Markdown.
The project uses student data containing:
Student ID
Gender
Attendance
Study Hours
Assignment Score
Exam Marks
Result
The purpose is to understand how attendance, study hours, assignments, and other factors relate to students' exam performance.
Technologies Used
R
R Markdown
CSV Dataset
Base R plotting functions
Dataset
The project reads the dataset from:
student_data <- read.csv("student_performance.csv")
student_data
The dataset contains 30 student records.
Data Analysis Performed
The R Markdown report performs the following operations:
Imports the CSV file.
Displays the student data.
Shows the first few records using head().
Generates a statistical summary using summary().
Checks the structure of the dataset using str().
Checks for missing values using colSums(is.na()).
Checks for duplicate records using sum(duplicated()).
Calculates the median and mean of exam marks.
Finds minimum and maximum exam marks.
Creates a frequency table of student results.
Creates bar charts and a pie chart.
Compares study hours with exam marks.
Compares attendance with exam marks.
Calculates average exam marks by gender.
Visualizations
The report includes:
Pass and Fail Student bar chart
Student Pass and Fail Distribution pie chart
Exam Marks of Students bar chart
Student Attendance bar chart
Study Hours vs Exam Marks scatter plot
Attendance vs Exam Marks scatter plot
Average Exam Marks by Gender bar chart
Key Results
According to the report:
There are 30 students in the dataset.
All 30 students have the result Pass.
Exam marks range from 45 to 96.
The median exam mark is 79.5.
The mean exam mark is approximately 75.73.
The report shows a positive relationship between study hours and exam marks.
The report also shows a positive relationship between attendance and exam marks.
The calculated average exam marks are approximately:
Female: 83.6
Male: 67.87
Project Structure
Student-Academic-Performance/
│
├── README.md
├── student_performance.csv
├── Student-Academic.html
└── Student-Academic.Rmd
How to Run the Project
Step 1: Install R
Install R on your computer.
Step 2: Install RStudio
Open the project in RStudio.
Step 3: Keep the Files Together
Keep the CSV file and R Markdown file in the same project folder.
Step 4: Run the R Markdown File
Open the .Rmd file in RStudio and click Knit.
The R Markdown document can generate an HTML/PDF report containing the R code, analysis, results, and graphs.
Conclusion
This project demonstrates how R can be used to import, clean, analyze, and visualize student academic data. The charts and statistical analysis help identify patterns between attendance, study hours, and exam marks.
Author
Tejas Jadhav
Project Title
Analysis of Student Academic Performance
