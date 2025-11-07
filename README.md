# sepsis-prediction-analysis


### **Title**

**"Early Prediction of Sepsis Using Machine Learning on Clinical Data"**

---

### **Introduction**

Sepsis is a life-threatening condition caused by the body’s extreme response to infection, leading to organ dysfunction and potentially death if not treated promptly. Early detection and intervention are crucial in improving patient outcomes. Traditional methods of sepsis diagnosis rely on clinical judgment and laboratory findings, which may delay treatment. Machine learning offers a promising approach to identify sepsis risk factors and predict its onset using patient health records.
This project aims to develop a predictive model for early detection of sepsis based on a synthetic clinical dataset. By leveraging patient demographics, vital signs, and laboratory measurements, the model can provide valuable insights for healthcare providers to initiate timely interventions and reduce mortality.

### **Dataset Description**

The dataset is a synthetic clinical dataset consisting of **10,000 patient records and 14 attributes**. Each record corresponds to an individual patient’s clinical measurements and outcomes. The dataset includes demographic details, vital signs, laboratory values, comorbidities, and patient outcomes such as sepsis diagnosis, hospital readmission, and mortality.

---

### **Data Attributes**

1. **patient_id** – Unique identifier for each patient.
2. **age** – Age of the patient (in years).
3. **sex** – Gender of the patient (Male/Female).
4. **bmi** – Body Mass Index (kg/m²), a measure of body fat based on weight and height.
5. **systolic_bp** – Systolic blood pressure (mmHg).
6. **diastolic_bp** – Diastolic blood pressure (mmHg).
7. **glucose** – Blood glucose level (mg/dL).
8. **cholesterol** – Blood cholesterol level (mg/dL).
9. **creatinine** – Serum creatinine level (mg/dL), an indicator of kidney function.
10. **diabetes** – Presence of diabetes (0 = No, 1 = Yes).
11. **hypertension** – Presence of hypertension (0 = No, 1 = Yes).
12. **diagnosis** – Primary clinical diagnosis (e.g., Sepsis, Heart Failure, Normal).
13. **readmission_30d** – Hospital readmission within 30 days (0 = No, 1 = Yes).
14. **mortality** – Patient mortality outcome (0 = Survived, 1 = Died).

