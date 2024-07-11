# SQL_Projects
# Analyze Students' Mental Health
## Level: Beginner
## Task: Explore and analyze the students data to see how the length of stay (stay) impacts the average mental health diagnostic scores of the international students present in the study.
- Return a table with nine rows and five columns.
- The five columns should be aliased as: stay, count_int, average_phq, average_scs, and average_as, in that order.
- The average columns should contain the average of the todep (PHQ-9 test), tosc (SCS test), and toas (ASISS test) columns for each length of stay, rounded to two decimal places.
- The count_int column should be the number of international students for each length of stay.
- Sort the results by the length of stay in descending order.

# Analyze International Debt Statistics
## Level: Beginner
## Task: Write SQL queries to answer interesting questions about international debt using data from The World Bank.
- What is the number of distinct countries present in the database? The output should be single row and column aliased as total_distinct_countries.
- What country has the highest amount of debt? Your output should contain two columns: country_name and total_debt and one row.
- What country has the lowest amount of principal repayments (indicated by the "DT.AMT.DLXF.CD" indicator code)?
