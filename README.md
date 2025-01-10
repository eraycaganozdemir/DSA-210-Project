# DSA-210-Project
# **Daily Spending and Step Count Analysis**

## **Project Description**

I am Eray Çağan Özdemir (32136) and my project aims to analyze the relationship between my daily spending from my bank account and my daily step count. By doing so, I will try to determine the impact of my spending habits on my physical activity or vice versa.

## **Table of Contents**

- [Motivation](#motivation)
- [Hypothesis](#hypothesis)
- [Plan](#plan)
- [Data Source](#data-source)

## **Motivation**

While thinking about a project I seek to answer the question: "Are there days when my higher spending coincides with my lower pyhsical activity or is there a positive correlation between my increased physical activity and daily spending?" This curiosity led me to explore the relationship between my personal spending and physical activity.

This project is motivated by a desire to gain better understanding of my personal habits. By analyzing my bank account spendings and daily step counts, I aim to uncover patterns in my behaviour that I might not be consciously aware of.

## **Hypothesis**

My hypothesis is that there is a negative correlation between my daily physical activity (step count) and my spending habits. Specifically, I believe that:
- On days when I walk less, I tend to spend more money.
- This behavior might stem from factors such as travelling with car, relying more on online shopping or food delivery etc.

By analyzing the data, I aim to test this hypothesis and determine if there is a measurable relationship between my daily step count and spending patterns. This exploration will help uncover whether reduced physical activity directly or indirectly influences higher expenditures.


## **Plan**

**Project Objectives**
- What do I aim to achieve?

    - Automate the processing of bank account statements.
    - Integrate and align daily spending and step count data for correlation analysis.
    - Identify whether there is a correletion between spending and physical activity levels.

<br><br>
**Step-by-Step Plan**
<br><br>

***1. Data Collection***

- Bank Account Statements

  - Use Python to automate the extraction of data (e.g., date and amount spent) from PDF bank account statements. Then save the extracted data in a .csv file for further processing.
  
- Step Count Data
  
  - Export daily step count data from the **iPhone Health app**. Then format data into .csv files for integration with     spending data.

***2. Data Cleaning and Preparation***

- Clean missing or incorrect entries.
- Ensure consistency in date formats between the two datasets.
- Align spending and step count data within the same data range.

***3. Data Analysis and Visualization***

- Perform a correlation analysis between spending and step count data.
- Visualize spending and step count trends using plots, graphs etc.

***4. Hypothesis Testing***

- To validate or reject the hypothesis that "There is a negative correlation between my daily physical activity (step count) and my spending habits,":
  
  - H₀: There is no significant relationship between daily step count and spending.
  - H₁: There is a negative correlation between daily step count and spending.
- Analyze the test results to determine if the null hypothesis can be rejected.

***5. Reporting Results***

- Report the findings.
- Write conclusions about the relationship between physical activity and daily expenses.


## **Data Source**

I have two main sources of data:
- **Bank Account Statements**:
  My bank provides detailed account statements in PDF format, including information such as transaction dates, amounts, and places of purchase. Using Python, I will automate the extraction of transaction dates and     
  amounts, which are the key elements for my analysis. Non-essential details, such as transaction locations, will be excluded during preprocessing.
  
- **Step Count Data**:
  My daily step count data is sourced from the iPhone Health app. This data provides the number of steps recorded for each day. I will export and format this data into .csv files to align with the spending data for 
  comparative analysis.

<br>


**Bank Account Statement**
<br><br>

![image](https://github.com/user-attachments/assets/ecbaa844-5c44-4a58-a1c2-ca24a9b9facc)

<br>

- The statements contain details about my spending, including the date, location, and amount. For this project, I will extract only the relevant details: dates and amounts. This data will be processed to align with my 
  step count data for meaningful analysis.

<br>

**Step Count Data**
<br><br>

![image](https://github.com/user-attachments/assets/1999c35d-02aa-4144-a32b-1b63f44e406c)

<br>

- The iPhone Health app stores the number of steps taken each day. I will retrieve and format this data for comparison with my spending habits to explore potential correlations.

