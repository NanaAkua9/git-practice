The dataset used for this analysis was taken from Kaggle under the name "Fertility Dataset".
The dataset is from UCI Machine learning repository (University of California, Irvine). The archive was created as an ftp archive in 1987 by UCI PhD student David Aha. Dataset collected from 100 volunteers provide a semen sample analysed according to the WHO 2010 criteria. Sperm concentrations are related to socio-demographic data, environmental factors, health status, and life habits in UC Irvine machine learning repository which consists of 100 instances and 10 attributes with the class stating normal or altered. The attributes which are identified, which consist of the season, age, childish diseases, accident or serious trauma, surgical intervention, high fevers in the last year, frequency of alcohol consumption, smoking habit, number of hours spent sitting per day, diagnosis.

Number of men in each Age Range:
![Image](https://github.com/user-attachments/assets/4ede1aba-b6d2-46d3-bc12-cbd39f58f3a4)

Participants' Diagnosis Distribution:
![Image](https://github.com/user-attachments/assets/158ae27d-e52c-4695-8fe0-aba84cfd5d65)

For the purpose of this analysis, frequencies of alcohol consumption were encoded into numerical data as;
Frequency of Alcohol Consumption - [hardly ever or never: 0, once a week: 1, several times a week: 2, every day: 3, several times a day: 4]

**Key Observations**
 Normal Seminal Parameters (Diagnosis):
•	Higher overall alcohol intake across all smoking frequencies and age groups.
•	In the 27–29 age group, smokers (both occasional and daily) have higher alcohol consumption (10) than non-smokers (7).
•	In 30–32, a gradual decrease in alcohol intake is observed with increasing smoking frequency:
o	Non-smokers: 14 → Occasional: 9 → Daily: 6.
•	In 33–36, the pattern continues: Alcohol intake drops as smoking increases:
o	Non-smokers: 9 → Occasional: 3 → Daily: 2.

![Image](https://github.com/user-attachments/assets/2df3dc21-609f-48d2-a51a-51220d15b88c)
![Image](https://github.com/user-attachments/assets/8bbc0fbc-9ad3-4f78-af05-faff1a7e437f)
![Image](https://github.com/user-attachments/assets/2619cb53-19ef-4d05-8198-d4d12b8b3b1f)

Altered Seminal Parameters (Diagnosis):
•	Across all age groups, alcohol consumption is significantly lower than in the normal group.
•	In 30–32, the drop is steep: from 7 (non-smokers) → 1 (daily smokers).
•	In 27–29 and 33–36, total alcohol intake barely exceeds 1, regardless of smoking level.

![Image](https://github.com/user-attachments/assets/d81d51a0-78ec-49cc-a2c1-b530a8295bf8)
![Image](https://github.com/user-attachments/assets/9c6191fe-eec9-44c9-a44c-b224bc7ee5c8)
![Image](https://github.com/user-attachments/assets/62f327af-f160-415b-90a2-5b77a4a223dc)

**Interpretation & Insights**
1.	Alcohol-Sperm Quality Link:
o	Men with normal semen quality tend to report higher alcohol consumption than those with altered parameters, particularly in younger age groups.
o	This suggests that moderate alcohol intake alone may not be a strong predictor of semen quality decline in this sample.
2.	Smoking as a Potential Risk Factor:
o	In both diagnosis groups, increased smoking frequency correlates with lower alcohol intake, which may imply an independent or stronger negative effect of smoking on semen quality.
3.	Age-Based Patterns:
o	In the normal group, alcohol intake consistently decreases with age and smoking, but values remain relatively high.
o	In the altered group, alcohol intake is low across the board, especially for smokers — suggesting that combined exposure (age + smoking + low/no alcohol) may relate more to reduced semen quality.
4.	Possible Protective Behaviours:
o	Men diagnosed with altered parameters might have reduced or modified their alcohol intake, either after diagnosis or due to pre-existing health concerns.

**Summary of Insights**
Men with normal semen parameters generally consumed more alcohol than those with altered parameters, suggesting that alcohol alone may not strongly predict reduced semen quality. Across all age groups, smoking frequency was inversely related to alcohol intake, with the sharpest decline seen in the 30–32 age group among men with altered parameters. Interestingly, the normal group maintained higher alcohol intake even among smokers, particularly in the 27–29 age bracket. In contrast, the altered group consistently showed low alcohol intake regardless of smoking level. These patterns indicate that smoking may be a stronger negative factor for semen quality than alcohol. Moreover, the data suggests that the combined effects of smoking, age, and lower alcohol intake may be associated with poorer seminal health outcomes.

**Conclusion**
While high alcohol intake alone doesn’t appear to strongly predict altered semen quality, smoking—especially in combination with age—may play a more consistent role in diminished seminal parameters.

**Skills Used in this Project**
1.	Data Cleaning & Preparation: Removing inconsistencies, handling missing data, and structuring raw inputs for analysis.
2.	Descriptive Statistics: Calculating totals, averages, frequencies, and distributions for variables like age, diagnosis, alcohol intake, and smoking frequency.
3.	Data Visualization: Creating columns charts and comparative visuals in Excel to show trends by age group and diagnosis.
4.	Data Segmentation & Filtering: Using filters, pivot tables, and formulas to isolate subgroups (e.g., Altered (Diagnosis), Normal (Diagnosis), age ranges).
5.	Pattern Recognition & Trend Analysis: Interpreting the relationship between lifestyle factors and semen quality across age and diagnostic groups.
6.	Logical Reasoning & Insight Generation: Drawing evidence-based conclusions from observed patterns and linking them to possible reproductive health implications.
7.	Effective Communication of Findings: Summarizing results clearly for both technical and non-technical audiences, including stakeholders in healthcare or research.
