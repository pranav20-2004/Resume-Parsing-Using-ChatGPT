# Resume-Parsing-Using-ChatGPT
This project parses resume content into a structured JSON format using ChatGPT, facilitating easy data extraction and analysis. It leverages the capabilities of OpenAI's GPT-4 to streamline resume processing tasks.

# Resume Parsing Using ChatGPT

## Description

This repository contains a solution for parsing resume content into JSON format using ChatGPT. By providing your resume as input, the ChatGPT model will extract and structure the information in JSON format. This project demonstrates how to leverage OpenAI's GPT-4 capabilities for resume parsing tasks.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Prompt](#prompt)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Resume-Parsing-Using-ChatGPT.git
    ```
2. Change into the project directory:
    ```bash
    cd Resume-Parsing-Using-ChatGPT
    ```


## Usage

1. Open the `prompt.txt` file and copy the provided prompt.

2. Paste the prompt into the ChatGPT interface (such as OpenAI's API playground).

3. Provide your resume as the input when prompted.

4. The output will be a JSON representation of your resume content.

## Prompt

```plaintext
I will provide my resume content, and I would like you to parse it into a structured JSON format. Please ensure that the JSON output includes the following sections if available: Personal Information, Summary, Work Experience, Education, Skills, Certifications, Projects, and Languages. Here is the resume content:

Pranav K R
+91-7339391846
GitHub: GitHub.com/Pranav
Email: pranavrama12@gmail.com
LinkedIn: LinkedIn.com/Pranav

Education:
- SRM Institute of Science and Technology (2021 - 2025)
  - BTech in Computer Science with Specialization in Big Data Analytics
  - CGPA/Percentage: 94.1

- AKSHAYA ACADEMY (2020 - 2021)
  - Senior School Certificate Examination in Biology and Mathematics
  - CGPA/Percentage: 78.4

Experience:
- IoTIoT.in (Jan 2024 - Present)
  - Machine Learning Engineer (Remote)
  - Defined clear problem statements for a wildlife species detection project, ensuring alignment with project objectives and stakeholder needs.
  - Collected a comprehensive dataset from diverse sources, including field surveys, camera traps, and public databases, aggregating over 1000 data points.
  - Trained machine learning models using the annotated dataset, achieving a notable 15% improvement in species detection accuracy over baseline models.
  - Generated insights through model performance metrics such as precision, recall, and F1 score, facilitating data-driven decision-making for wildlife conservation efforts.

- Prepinsta (Nov 2023 - Feb 2024)
  - Data Analyst (Remote)
  - Conducted data cleaning and manipulation tasks, processing approximately 5000 records to ensure data accuracy and reliability.
  - Implemented data visualization techniques in Python, creating interactive visualizations to analyze trends and patterns in a real-world dataset containing over 10,000 data points.

- Mentorness (Mar 2024 - Apr 2024)
  - Data Analyst (Remote)
  - Presented an in-depth analysis of SQL and its applications in data management and analysis.
  - Completed two significant projects: the Sales Analysis project, where I analyzed sales data to uncover trends and generate insightful reports using advanced SQL queries; and the Animated Movie Analysis project, where I examined data on animated movies to identify patterns in box office performance, utilizing SQL for comprehensive data aggregation and analysis.

Personal Projects:
- Election-India-2024-Insights (github.com/pranav20-2004/Election-India-2024-Insights)
  - Web scraping | SQL | Data Analysis | Reporting
  - Led the Election-India-2024 Insights project, analyzing data from the Election Commission of India website to uncover key insights into voter behavior, party performance, and regional trends.
  - Used the Listly Browser Extension to extract and structure data, then used SQL to generate a detailed report highlighting metrics such as party representation, winning margins, candidate success rates, and regional strengths.

- Bank Loan Report (github.com/pranav20-2004/Bank-Loan-Report)
  - Data Analysis | Programming (Python) | Data Visualization (Tableau) | Domain Knowledge
  - Developed a comprehensive Bank Loan Report in Tableau, analyzing 38,000 rows of data and visualizing key insights on loan applications, funded amounts, and repayment behavior.
  - Used SQL to extract data and Tableau dashboards to showcase metrics like Total Loan Applications, Funded Amounts, and Amounts Received across various dimensions.

Technical Skills and Interests:
- Skills: Data analysis, Statistical analysis, Data visualization, Database management, Programming (Python, R, SQL)
- Tools: Tableau, Excel, PowerBI, SPSS, Google Sheets
- Techniques: Machine Learning Algorithms, Data Collection, Data Cleansing
- Knowledge: Object-oriented programming (OOP), Database Management System, Operating System, Computer Networks, Git

Achievements:
- TCS NQT - Cognitive: Percentile: 74.91
- Secured second prize in Recursion Hackathon at Pondicherry University for developing a full-stack Budget Tracker.

Courses and Training:
- Google Advanced Data Analytics (J24ZDS4AVDPS) - Coursera
  - Foundations of Data Science and Python; Translating Data into Insights and The Power of Statistics
  - Regression Analysis and Machine Learning; Google Advanced Data Analytics Capstone and Practical Assessments

- Become a Data Analyst - LinkedIn Learning
  - Developed expertise in using Tableau, Microsoft Power BI, and Microsoft Excel for data visualization and analytics.

- Data Science with Python - Coincent Certificate
  - Hands-on experience through live projects and mentorship, significantly enhancing proficiency in Python programming, data analysis, and machine learning.
