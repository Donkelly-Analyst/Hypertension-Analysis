# **Hypertension-Analysis**
The hypertension dataset report presents patient records with details such as age, gender, blood pressure levels, cholesterol, body mass index, and lifestyle habits. It highlights trends, risk factors, and correlations that help identify individuals at higher risk of developing hypertension.


- [Project Overview](#poject-overveiw)
- [Data Sources](#Data-Sources)
- [Column headers](#Column-headers)
- [Sample Preview](#Sample-Preview)
- [Tools](#tools)
- [Data Cleaning/Preparation](#Data-Cleaning/Preparation)
- [Exploration Data Analysis (EDA)](Exploration-Data-Analysis(EDA))
- [Data Analysis](Data-Analysis)
- [Key Insights](Key-Insights)
- [Recommendations](Recommendations)
- [Limitations]( Limitations)
- [Future Work](Future-Work)



### *Project Overveiw*

This project analyzes hypertension risk using a dataset containing key health and lifestyle factors such as age, salt intake, stress score, sleep duration, and body mass index. It also includes medical and behavioral attributes like blood pressure history, medication use, exercise level, smoking status, and family history. The goal is to identify patterns and correlations that influence hypertension, understand how lifestyle choices affect blood pressure, and develop predictive insights for early intervention. By exploring these variables, the project provides a foundation for data-driven health recommendations that can help reduce hypertension risks and promote long-term cardiovascular wellness.



<img width="1326" height="766" alt="Screenshot 2025-11-14 011639" src="https://github.com/user-attachments/assets/f41b6d8e-4fab-4a81-a74f-27132ddebf50" />

<img width="1313" height="761" alt="Screenshot 2025-11-14 011738" src="https://github.com/user-attachments/assets/c28fb311-9bc1-48cf-b043-f7d23ffaee6d" />

### *Data Sources*


The primary dataset used for this analysis is the “Hypertension Analysis.csv” file, containing detailed information on individual health and lifestyle factors such as age, salt intake, stress score, sleep duration, BMI, exercise level, medications, smoking status, and family history. These variables help in identifying potential risk factors and patterns associated with hypertension. The dataset supports exploratory analysis and predictive modeling to understand how various habits and physiological attributes influence blood pressure. By examining correlations within these features, the study aims to provide valuable insights for improving hypertension management and preventive healthcare strategies.



### *Column headers*

|Age|Age Grade|Salt Intake|Stress Score|BP History-ID|Sleep Duration|BMI|Medications|Family History|Exercise Level|Smoking Status|Has Hypertension|  
|---|---------|-----------|------------|-------------|--------------|---|------------|--------------|--------------|--------------|----------------|

### *Sample Preview*


|69|8.0|9|Normal|6.4|25.8|None|Yes|Low|Non-Smoker|Yes|
|--|---|-|------|---|----|----|---|---|----------|----|
|32|11.7|10|Normal|5.4|23.4|None|No|Low|Non-Smoker|No|                                                                                                                        



### *Tools*

- Excel - Data Cleaning
  - [Download here](https://Microsoft.com)
- MY SQL - Data Analysis
- Power BI - Creating Reports


  ### *Data Cleaning/Preparation*


1. The hypertension analysis project was performed using Microsoft Excel.
2. The dataset “Hypertension Analysis.csv” was imported for processing.
3. Headers were promoted to improve clarity and ensure proper column labeling.
4. The dataset was inspected to understand its structure and key variables.
5. Missing or invalid entries were identified and removed for data accuracy.
6. Filters were applied to focus on relevant and valid records.
7. Additional columns were added to support calculated fields and insights.
8. Queries from multiple data sources were merged for completeness.
9. Data transformations were applied to standardize formats and values.
10. The cleaned and structured dataset was finalized for detailed hypertension analysis.


###  *Exploration Data Analysis (EDA)*


Exploratory Data Analysis (EDA) was performed to understand the distribution, relationships, and trends within the hypertension dataset. Statistical summaries and visualizations were used to identify key patterns, detect outliers, and explore correlations among factors such as age, BMI, salt intake, stress score, and hypertension risk levels.


### *Data Analysis*




### *Key Insights*



- Among 568 smokers, 71.83 percent have hypertension, showing a high association between smoking and high blood pressure.
- Among 1,417 non smokers, 44.04 percent have hypertension, which is significantly lower than in smokers.
- Smoking is strongly linked to higher hypertension rates.
- Sixty three point eighteen percent of individuals with hypertension also have a family history of high blood pressure.
- Family history is an important predictor and contributing factor to hypertension.
- People with normal blood pressure record the highest sleep duration at about five point zero nine thousand hours.
- Individuals with prehypertension and hypertension sleep less, with sleep duration dropping to four point zero thousand and three point seventy two thousand hours respectively.



###  *Recommendations*


1. Among 568 smokers, 71.83 percent have hypertension, showing a strong link between smoking and high blood pressure.
2. Among 1,417 non smokers, 44.04 percent have hypertension, which is much lower than in smokers.
3. Smoking remains a major contributor to higher hypertension rates.
4. Sixty three point eighteen percent of people with hypertension also have a family history of high blood pressure.
5. Family history shows a strong influence on the likelihood of developing hypertension.



 ### *Limitations*

 The hypertension analysis faced limitations such as missing or incomplete data that reduced accuracy, limited variables that restricted deeper insights, and possible reporting errors in lifestyle factors like smoking and sleep. The dataset size and lack of clinical measurements also prevented stronger conclusions and limited the ability to generalize findings.


### *Future Work*


For future work, the analysis can be expanded by collecting more comprehensive and longitudinal data, including detailed dietary habits, physical activity intensity, and stress management metrics. Advanced predictive models like machine learning could be applied to identify high-risk individuals. Integrating clinical measurements and wearable device data would improve accuracy and support personalized hypertension prevention strategies.








