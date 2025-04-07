# About Project

Questions to Analyze:

1. What skills are most in demand for data analysts?
2. Which skills are associated with higher salaries?
3. What are the most optimal skills to learn?

# Tools Used

- SQL
- PostgreSQL
- Visual Studio Code
- Git & GitHub

# The Analysis

### 1. In-Demand Skills for Data Analysts

This query helped identify the skills most frequently requested in job postings, directing focus to areas with high demand.

[SQL Query](/queries_sql/)

| Skills   | Demand Count |
| -------- | ------------ |
| SQL      | 7291         |
| Excel    | 4611         |
| Python   | 4330         |
| Tableau  | 3745         |
| Power BI | 2609         |

- **SQL** and **Excel** remain fundamental, emphasizing the need for strong foundational skills in data processing and spreadsheet manipulation.
- Programming and Visualization Tools like **Python**, **Tableau**, and **Power BI** are essential, pointing towards the increasing importance of technical skills in data storytelling and decision support.

### 2. Skills Based on Salary

Exploring the average salaries associated with different skills revealed which skills are the highest paying.

[SQL Query](/queries_sql/)

| Skills    | Average Salary ($) |
| --------- | -----------------: |
| pyspark   |            208,172 |
| bitbucket |            189,155 |
| couchbase |            160,515 |
| watson    |            160,515 |
| datarobot |            155,486 |

- **PySpark** leads the list with the highest salary, reflecting the high demand for big data processing skills.

- **Bitbucket** ranks second, showing that expertise in version control and DevOps tools is valuable for Data Analysts.

- **Couchbase, Watson, and DataRobot** emphasize the growing importance of NoSQL databases, AI platforms, and automated machine learning in data roles.

### 3. Most Optimal Skills to Learn

Combining insights from demand and salary data, this query aimed to pinpoint skills that are both in high demand and have high salaries, offering a strategic focus for skill development.

[SQL Query](/queries_sql/)

| Skills     | Demand Count | Average Salary ($) |
| ---------- | ------------ | -----------------: |
| go         | 27           |            115,320 |
| confluence | 11           |            114,210 |
| hadoop     | 22           |            113,193 |
| snowflake  | 37           |            112,948 |
| azure      | 34           |            111,225 |

- **Go** stands out with the highest salary ($115K) and strong demand (27 job postings), indicating it's a highly sought-after skill in the Data Analyst field.

- **Confluence** ranks second, with 11 job postings and an average salary of $114K. It suggests that companies value collaboration and documentation tools, especially for remote teams.

- **Hadoop**, a widely used big data framework, is also in demand (22 job postings) and offers a competitive salary of $113K, highlighting the need for big data expertise.

- **Snowflake** and **Azure** are highly demanded skills (37 and 34 job postings, respectively) with salaries close to $113K and $111K, underscoring the growing importance of cloud-based data platforms and services.
