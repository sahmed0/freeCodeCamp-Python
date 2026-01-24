# Demographic Data Analyzer

This project is the solution to the "Demographic Data Analyzer" challenge, the second project in the **freeCodeCamp Data Analysis with Python** certification.

## Project Description

This programme uses the **Pandas** library to analyse demographic data from the 1994 Census database. The goal is to extract specific insights regarding age, education, work hours, and native country, and to determine how these factors correlate with salary (specifically, whether a person earns >50K).

## Dataset

The project utilises the `adult.data.csv` file. The dataset contains the following columns:
-   `age`
-   `workclass`
-   `fnlwgt`
-   `education`
-   `education-num`
-   `marital-status`
-   `occupation`
-   `relationship`
-   `race`
-   `sex`
-   `capital-gain`
-   `capital-loss`
-   `hours-per-week`
-   `native-country`
-   `salary`

## Key Questions Answered

The script performs data analysis to answer the following questions:
1.  How many people of each race are represented in this dataset?
2.  What is the average age of men?
3.  What is the percentage of people who have a Bachelor's degree?
4.  What percentage of people with advanced education (`Bachelors`, `Masters`, or `Doctorate`) make more than 50K?
5.  What percentage of people without advanced education make more than 50K?
6.  What is the minimum number of hours a person works per week?
7.  What percentage of the people who work the minimum number of hours per week have a salary of >50K?
8.  Which country has the highest percentage of people who earn >50K?
9.  What is the most popular occupation for those who earn >50K in India?

## Technologies Used

-   **Python 3**
-   **Pandas**

## Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/sahmed0/demographic-data-analyser.git]
    ```
2.  Navigate to the directory:
    ```bash
    cd demographic-data-analyser
    ```
3.  Install the required dependency:
    ```bash
    pip install pandas
    ```

## Usage

Ensure the `adult.data.csv` file is in the same directory as the script. You can import the function and run it as follows:

```python
import demographic_data_analyser

# Calculate and print the data
demographic_data_analyser.calculate_demographic_data()

