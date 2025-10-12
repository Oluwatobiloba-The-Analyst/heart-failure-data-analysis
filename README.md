# 🫀 Heart Failure Data Analysis using SQL and Power BI

A data-driven exploration into the demographics, medical history, and mortality patterns of heart failure patients.  
This project uses **SQL** for data modification, sorting, and filtering, as well as **Power BI** to visualize trends and uncover actionable insights that can aid early interventions and improve survival outcomes.

---

## 📝 Project Overview
Heart failure is a life-threatening condition that requires close monitoring and proactive care.  
This project analyzes medical data of **299 patients** with the aim of identifying factors contributing to heart failure outcomes, patient demographics, significant predictors, and patterns related to mortality, comorbidities, and biomarkers.  

Using **SQL** for data manipulation and **Power BI** for visualization, I aim to derive actionable insights and identify patterns that can support better clinical decision-making and targeted interventions.

---

## 🎯 Objectives
- Understand mortality rate and survival factors among heart failure patients.  
- Identify how age affects outcomes.  
- Identify underlying conditions and the number of patients associated with each condition.  
- Determine the percentage of male and female patients.  
- Analyze average biomarker values across patient outcomes.  
- Use Power BI to deliver an intuitive and insightful visual report.

---

## 🛠️ Tools & Technologies
- **Power BI** – Data Modeling and Visualization  
- **SQL** – Data Manipulation, Filtering, and Sorting  
- **GitHub** – Project Hosting and Version Control  

---

## 📁 Dataset Description
- **Source:** [Heart Failure Clinical Records Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records) *(Used for educational purposes only)*  
- **Size:** 300 rows × 13 columns  
- **Total Patients:** 299  

**Key Variables:**  
Age, Anaemia, Creatinine Phosphokinase (mcg/L), Diabetes, Ejection Fraction (%), High Blood Pressure (Hypertension), Platelet Count (platelets/µL), Serum Creatinine (mg/dL), Serum Sodium (mEq/L), Sex, Smoking, Time (Follow-up Period), Death Event (Mortality).

---

## 📊 Key Analysis & Visualizations

### 1. Gender Distribution
- **Male:** 64.88% (194 patients)  
- **Female:** 35.12% (105 patients)

### 2. Underlying Medical Conditions
- **Anaemia:** 129 patients  
- **Diabetes:** 125 patients  
- **Hypertension:** 105 patients  
- **Smoking History:** 96 patients

### 3. Mortality Rate
- **Survived Patients:** 203 (67.89%)  
- **Deceased Patients:** 96 (32.11%)

### 4. Age Analysis
- **Average Age of Deceased:** 65 years  
- **Average Age of Survived:** 59 years  
- **Most Affected Age Group:** 60 years  

### 5. Average Ejection Fraction by Death Events
- **Survived:** 40%  
- **Deceased:** 33%

### 6. Biomarker Comparisons by Death Event
- **Average Creatinine Phosphokinase (CPK)**  
  - Survived: 540 mcg/L  
  - Deceased: 670 mcg/L  

- **Average Serum Creatinine**  
  - Survived: 1.2 mg/dL  
  - Deceased: 1.8 mg/dL  

- **Average Platelet Count**  
  - Survived: 266,658 platelets/µL  
  - Deceased: 256,381 platelets/µL  

- **Average Serum Sodium**  
  - Survived: 137 mEq/L  
  - Deceased: 135 mEq/L  

---

## 💡 Key Insights

### 1. Patient Demographics
- **Gender:** ~65% of patients were male, indicating a higher prevalence of heart failure in men.  
- **Age:** The most commonly affected age group was 60 years.  
  - Average age of deceased: 65 years  
  - Average age of survivors: 59 years  
 This suggest that younger patients (below 60) had better survival outcomes, making **age** a significant risk factor.

### 2. Mortality Rate
- 32% of patients died during the follow-up period, indicating a significant level of mortality rate, emphasizing the need for early detection, intervention and improved treatment strategies, to further reduce the mortality rate and increase the survival rate.

### 3. Underlying Conditions
- **Anaemia (129 patients)** and **Diabetes (125 patients)** were the most common comorbidities.  
- **Hypertension (105 patients)** and **Smoking (96 patients)** were also notable contributors.  
Suggesting that heart failure often coexists with other chronic diseases rather than occurring in isolation.


### 4. Ejection Fraction: A Critical Indicator
   - A lower average ejection fraction was observed in deceased patients (33%) compared to survivors (40%). Since ejection fraction reflects the percentage of blood the heart pumps out with each beat, this suggests that reduced cardiac pumping capacity is strongly associated with poorer outcomes in heart failure patients. Ejection Fraction is therefore a critical functional indicator of survival.

### 5. Biomarkers
- **Serum Creatinine:** Higher in deceased patients (1.8 mg/dL vs 1.2 mg/dL in survivors). Since serum creatinine is a marker of kidney function, elevated levels suggest impaired renal performance, which is known to worsen heart failure outcomes. This highlights that renal function is closely tied to survival in heart failure patients.  
- **Creatinine Phosphokinase (CPK):** Higher in deceased patients (670 mcg/L vs 540 mcg/L). Elevated CPK is often linked to muscle damage, including cardiac muscle injury, which may signal more severe disease progression or greater stress on the heart. This suggests that increased CPK could be an additional risk factor associated with poorer outcomes in heart failure patients.

- **Serum Sodium:** Slightly lower in deceased patients (135 vs 137 mEq/L). Low sodium (hyponatremia) is a common complication of heart failure, often reflecting fluid overload or advanced disease progression. Even small differences can indicate worsening prognosis, making serum sodium a useful biomarker for identifying at-risk patients. 
 
- **Platelets:** Slightly lower in deceased patients (256,381 vs 266,658 platelets/µL), though within normal range.  
These findings suggest that higher creatinine phosphokinase levels, higher serum creatinine levels and lower serum sodium levels are associated with worse outcomes. These biomarkers may serve as useful indicators for identifying at-risk patients.

---

## 📈 Recommendations

-**Early Detection & Monitoring:**  
Hospitals should prioritize the regular monitoring of key clinical indicators — including ejection fraction, creatinine phosphokinase, serum creatinine, serum sodium levels, and blood pressure, as these strongly correlate with mortality. Patients with abnormal values should be promptly identified and provided with timely, targeted, and optimized medical interventions to reduce the risk of adverse outcomes.

- **Targeted Interventions for Underlying Conditions:**  
  Patient-specific care plan should be developed for those with anaemia, diabetes, and hypertension to mitigate complication.

- **Lifestyle Modification:**  
  Smoking cessation programs should be intensify, given its link to heart failure risk. Also heart-healthy diet/exercise guidance should be encouraged.

- **Age-Focused Strategies:**  
  Preventive measures and more aggressive interventions for patients above 60 should be implemented, as age significantly impacts outcomes.

- **Addressing Gender Disparities:**  
  Develop outreach programs specifically for men, since they appear to have higher prevalence in this dataset. Focus on education about early symptoms (e.g., breathlessness, fatigue, swelling) and the importance of routine check-ups. Recommend regular cardiovascular screenings for men above 40–50 years, especially those with risk factors (hypertension, diabetes, smoking). While men may be more represented, ensure women are not overlooked.

- **Data-Driven Decision-Making:**  
  Interactive dashboards in clinical settings should be deployed to help healthcare professionals track critical metrics in real-time.

---

## 🚀 Future Improvements
- Integrate **predictive modeling (Machine Learning)** to identify high-risk patients.  
- Incorporate **recent or real-time hospital data** for continuous monitoring.  
- Deploy as a **web-based analytics dashboard** for clinical use.

---


## 📬 Contact
**👩‍💻 Oluwatobiloba Taiwo**  
📧 [taiwooluwatobiloba2904@gmail.com](mailto:taiwooluwatobiloba2904@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/oluwatobiloba-taiwo-dvm-b43b51366?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)  
🌐 *Portfolio Website:* *(available shortly)*
