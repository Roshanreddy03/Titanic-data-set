# Titanic-data-set
Analysis on titanic dataset downloaded from Kaggle


🚢 Titanic Survival Analysis (EDA)

Project Overview

This project explores the famous Titanic dataset to answer the question:

“What kind of passengers were more likely to survive?”

Using Python and data analysis techniques, we perform exploratory data analysis (EDA) to uncover patterns and insights from the dataset.

Link to Project Page: https://roadmap.sh/projects/titanic-eda-python

Dataset

Source: Kaggle Titanic Dataset

File used: titanic.csv

------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

------------------------------------------------------------------------------------------------------------------------------------------------------------

🔍 Data Exploration Steps

- Inspected dataset structure using .shape, .info()

- Identified and handled missing values

- Analyzed survival rates across different features:

  - Gender
  - Passenger Class
  - Age Groups

- Used relative frequencies for fair comparison

- Visualized data using bar plots and histograms

------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Key Insights

1. Gender
- Females had a significantly higher survival rate than males
- Suggests “women first” evacuation policy

2. Passenger Class
- 1st class passengers had the highest survival rate
- 3rd class passengers had the lowest
- Indicates socioeconomic impact on survival

3. Age
- Children had better survival chances
- Older passengers were less likely to survive

4. Combined Factors
- 1st class females had the highest survival rate
- 3rd class males had the lowest survival rate

------------------------------------------------------------------------------------------------------------------------------------------------------------

Visualizations

The notebook includes:

- Bar plots (Count of Survivors)
- Histogram (Distribution of Ages)
- Bar Plot: Survival by Gender (Categorical)
- Bar Plot: Survival by Passenger Class (Categorical)
- Bar Plot: Survival by both class and gender

------------------------------------------------------------------------------------------------------------------------------------------------------------

Conclusion

Survival on the Titanic was strongly influenced by:

- Gender (female priority)
- Social class (passenger class)
- Age (children had better chances)

------------------------------------------------------------------------------------------------------------------------------------------------------------

Future Improvements        

- Feature engineering (family size, title extraction)
- Machine learning model for survival prediction
- More advanced visualizations

