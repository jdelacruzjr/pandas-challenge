# PyCitySchools
# School District Standardized Test Analysis

# I created a new GitHub repository called 'pandas-challenge' for this project

# I uploaded a folder named 'PyCitySchools' to that repository which contains my Jupyter Notebook and pushed changes to my GitHub repository. 

# The 'PyCitySchools' folder contains the Jupyter Notebook which contains my main script to run for analysis

# I uploaded this README.md file to my 'pandas-challenge' repository to accompany my submission

## Background

# This project brings together a Python/Pandas solution to the education sector to analyze & present data from district-wide standardized testing results. This report will use testing results data to provide valuable higher-level insight and showcase various trends in key metrics that will aid the school board and the mayor while making strategic decisions regarding future budgeting and prioritization. The source data used in this analysis comes from two datasets in csv format titled 'schools_complete.csv' and 'students_complete.csv'. The csv files contain information in columns (Student ID, school_name, type, size, budget) and (Student ID, student_name, gender, grade, school_name, reading_score, math_score), respectively. To generate my report, these datasets were imported, merged, and the aggregated data was displayed into Python/Pandas dataframes. The main script is conducted in Juptyer notebook to better communicate the analysis report.

## Observable Trends

# The dataset encompasses a total of 39,170 students across 15 schools in total. The average reading score of 81.87 is higher than the average math score of 78.98. One significant observation is that while independently the percentage of students passing reading (85.80%) and the percentage of students passing math (74.98%) are above 70 percent, the percentage of students passing both reading and math is only 65.17%.

# The metrics from the data clearly show that by all measures of performance (average, percent and overall) reading and math scores, charter schools have much higher scores than district schools. Furthermore, the top 5 performing schools (by overall passing %) are charter schools, and the bottom 5 performing schools (by overall passing %) are district schools and the differences between their overall passing percentages is quite significant. To emphasize this disparity, the highest overall passing percentage representing district schools is Johnson High School at 53.53% and the lowest overall passing percentage representing charter schools is Pena High School at 90.54%.

# An interesting correlation between total school budget and overall passing percentage displays itself within the data findings. The data reveals that the greater the per student budget is, the lower the average, percent and overall scores are for both reading and math. For example, when the spending range is between $645-680, the overall passing percentage is 53.53%. On the other end of the budget spectrum, we see that when spending is less than $585, the overall passing percentage is 90.37%.

# Another correlation is found between the size of schools (number of students) and their overall passing scores. Looking at the performances of schools when they have between 2,000-5,000 students, the percentage of passing overall is only 58.28% as opposed to smaller schools that have less than 1,000 students attaining an overall passing percentage of 89.88%.

# I created this shareable link to my repository <https://github.com/jdelacruzjr/pandas-challenge.git> and submitted that to <https://bootcampspot-v2.com>
