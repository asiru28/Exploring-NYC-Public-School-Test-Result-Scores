# Exploring-NYC-Public-School-Test-Result-Scores

# Overview/Introduction
Every year, American high school students take the SAT, a standardized test that measures literacy, numeracy, and writing skills. The test is divided into three sections: reading, math, and writing, each with a maximum score of 800 points. SAT scores play a pivotal role in college admissions, making school performance analysis crucial for stakeholders like policymakers, educators, researchers, and parents.

This project analyzes SAT performance data from New York City (NYC) public schools to identify top-performing schools, borough-level trends, and insights into student achievement.

# Objectives

1. Identify the top-performing schools in math and overall SAT scores.
2. Analyze borough-level SAT performance, including average scores and variability.
3. Provide insights into school performance to help stakeholders make informed decisions.

# Data Source

The dataset, schools.csv, contains the following columns:
  - school_name: Name of the school.
  - borough: The borough where the school is located (e.g., Manhattan, Brooklyn).
  - building_code: Unique code for the school building.
  - average_math: Average math score of the school.
  - average_reading: Average reading score of the school.
  - average_writing: Average writing score of the school.
  - percent_tested: Percentage of students tested (may contain missing values).

#Tools Used

  - Python Libraries: Pandas, NumPy
  - Data Analysis: Grouping, sorting, and aggregating data to derive insights.

# Insights

1. Top Math Schools:
    - Schools with an average math score of 640 or higher were identified as top performers.
    - Stuyvesant High School leads with an average math score of 754, followed by Bronx High School of Science (714) and Staten Island Technical High School (711).
  
      ![d3](https://github.com/user-attachments/assets/9ca9da7e-c9b9-4642-bbff-1a97f3f4f7fc)

2. Top 10 Schools by Total SAT Scores:
    - Stuyvesant High School has the highest total SAT score (2144), followed by Bronx High School of Science and Staten Island Technical High School (both with 2041).
  
      ![d5](https://github.com/user-attachments/assets/bf73da0a-61d7-4208-aab2-51fbb2bfdf19)

3. Borough-Level Analysis:
    - Manhattan has the highest variability in SAT scores (standard deviation of 230.29), indicating a wide range of performance levels among its schools.
    - The borough also has the highest number of schools (89) included in the dataset.
  
      ![d4](https://github.com/user-attachments/assets/567daea8-339c-4384-89fd-c2cfd57d3685)


# Key Findings

1. Top Math Schools:
    - The top 5 schools with the highest average math scores are:
        1. Stuyvesant High School (754)
        2. Bronx High School of Science (714)
        3. Staten Island Technical High School (711)
        4. Queens High School for the Sciences at York College (701)
        5. High School for Mathematics, Science, and Engineering at City College (683).
2. Top 10 Schools by Total SAT Scores:
    - The top 10 schools have total SAT scores ranging from 1889 to 2144.
3. Borough-Level Variability:
    - Manhattan has the highest standard deviation in SAT scores, indicating significant differences in performance across its schools.

# Recommendations

1. Resource Allocation:
    - Schools with lower SAT scores, particularly in boroughs with high variability like Manhattan, may benefit from additional resources and support.
2. Best Practices Sharing:
    - Top-performing schools like Stuyvesant High School and Bronx High School of Science could share best practices with other schools to improve overall performance.
3. Parental Decision-Making:
    - Parents can use this analysis to identify high-performing schools for their children, especially in boroughs with consistent performance.
4. Further Research:
    - Investigate factors contributing to high variability in Manhattan and explore strategies to reduce performance gaps.

# How to Use This Repository

1. Clone the repository.
2. Install the required Python libraries (pandas, numpy).
3. Run the Jupyter Notebook (Exploring NYC Public School Test Result Scores.ipynb) to reproduce the analysis.
4. Explore the dataset and modify the code to conduct further analysis or generate additional insights.
