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
    - Combine daily spending and step count data for analysis.
    - Identify whether there is a correletion between spending and physical activity levels.

<br><br>
**Step-by-Step Plan**
<br><br>

***1. Data Collection***

- Bank Account Statements

  - Use pyhton to automate the extraction of data (e.g., date and amount spent) from PDF bank account statements. Then save the extracted data in a .csv file for further processing.
  
- Step Count Data
  
  - Export daily step count data from the **iPhone Health app**. Then format data into .csv files for integration with     spending data.

***2. Data Cleaning and Preparation***

- Clean missing or incorrect entries.
- Ensure consistency in date formats between the two datasets.
- Align spending and step count data within the same data range.

***3. Data Analysis and Visualization***

- Perfom a correlation analysis between spending and step count data.
- Visualize spending and step count trends using plots, graphs etc.

***4. Reporting Results***

- Report the findings.
- Write conclusions about the relationship between physical activity and daily expenses.


## **Data Source**

I have two main sources of data:
- **Bank Account Statements**:
  My bank provides detailed account statements in PDF format. I will automate the extraction of transaction data (such as        transaction dates and amounts) using Python. Then I will use this extracted data.
- **Step Count Data**:
  My daily step count data (such as number of steps on a specific day) is sourced from the **iPhone Health app**. Here I will    retrieve the data and integrate it into the project for analysis.

<br>


**Bank Account Statement**
<br><br>

![image](https://github.com/user-attachments/assets/ecbaa844-5c44-4a58-a1c2-ca24a9b9facc)

<br>

- As it can be seen on the statement it includes the date, place and the amount of money that I spent in that place and time. Some parts of this statement is not necessary in my analysis (such as place), so I will only retrieve usefull and necessary parts which are dates and expenditures.

<br>

**Step Count Data**
<br><br>

![image](https://github.com/user-attachments/assets/1999c35d-02aa-4144-a32b-1b63f44e406c)

<br>

- In the app the the amount of steps for each day is stored, so I will retrieve those data to compare my amount of steps and my spending on the same day.

