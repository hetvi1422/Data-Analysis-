🦠 COVID-19 India Data Analysis
📌 Overview

This project performs an exploratory data analysis (EDA) on the COVID-19 India dataset to understand the spread, impact, 
and recovery trends of COVID-19 across different Indian states and over time.
The analysis focuses on state-wise and time-based patterns using Python data analysis libraries.

📊 Dataset

Source: Kaggle

Dataset Name: COVID-19 in India

Link: https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-india

The dataset contains daily records of confirmed, recovered, and death cases across Indian states.

🛠️ Tools & Technologies Used

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib – data visualization

Jupyter Notebook

🧹 Data Preprocessing

The following steps were performed to clean and prepare the data:

Converted the date column into a proper datetime format

Extracted Day, Month, and Year from the date column

Removed unnecessary columns

Handled grouped and aggregated values for analysis

🔍 Analysis Performed

The project includes the following key analyses:

State-wise total confirmed COVID-19 cases

Identification of the most affected state

Identification of the least affected states

Month-wise trend of COVID-19 cases

Worst month based on total confirmed cases

First wave vs second wave comparison

Active cases analysis

Death rate analysis by state

Recovery rate analysis by state

Recovery vs death comparison (visualized)

📂 Project Structure


📈 Key Insights

Maharashtra was the most affected state with the highest number of confirmed cases.

COVID-19 cases showed clear monthly waves, indicating peak periods.

A small number of states contributed the majority of total cases.

Recovery cases were consistently much higher than death cases across most states.

Active case analysis highlighted periods of maximum healthcare burden.

🧠 Conclusion

This analysis shows that COVID-19 had an uneven impact across Indian states, with clear variations over time.
Despite high infection rates during peak periods, recovery trends remained strong compared to mortality.
The project demonstrates how effective data cleaning, aggregation, and visualization can help derive meaningful insights from real-world public health data.
