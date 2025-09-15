# Medical Insurance Claims Dashboard

## 📌 Project Overview

This project analyzes **medical insurance claims** data to uncover insights about how demographic and lifestyle factors (age, gender, BMI, smoking habits, children, region) influence **insurance charges**.

The cleaned dataset was processed in **Google Colab** and visualized in **Tableau** with interactive dashboards.

---

## 📂 Dataset

**Name:** `medical_insurance_claims.csv`

**Columns:**

* `age` → Age of the insured person
* `sex` → Gender (male/female)
* `bmi` → Body Mass Index (indicator of body fat)
* `children` → Number of children/dependents
* `smoker` → Smoking status (yes/no)
* `region` → Residential region (northeast, northwest, southeast, southwest)
* `charges` → Insurance charges billed

---

## ⚙️ Tools & Technologies

* **Python (Google Colab):** Data cleaning & preprocessing
* **Tableau:** Dashboard creation & visualization
* **GitHub:** Project documentation

---

## 📊 Dashboard Features

### 1. **KPI Cards**

* **Average Charges** 💰
* **Total Customers** 👥
* **Smoker vs Non-Smoker Ratio**
* **Hugh Cost %** 🚬

---

### 2. **Visualizations**

1. **Bar Chart — Average Charges by Region**

   * Compare healthcare costs across regions.

2. **Scatter Plot — BMI vs Charges (Risk View)**

   * **X-axis:** BMI
   * **Y-axis:** Charges
   * **Color:** Smoker status
   * **Trend Line:** Linear → shows risk correlation between BMI and charges.

3. **Box Plot — Charges by Smoker**

   * Shows how smoking drastically increases insurance charges.

4. **Histogram — Age Distribution**

   * Highlights which age groups file more claims.

---

### 3. **Filters**

* By **Region**
* By **Smoker status**
* By **Gender**

---

## 📈 Insights

* **Smokers** pay significantly higher charges compared to non-smokers.
* Higher **BMI** is positively correlated with increased charges.
* The **southeast region** tends to have higher insurance costs.
* Most policyholders are between **20–40 years old**.

---

## 🚀 How to Run This Project

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/medical-insurance-dashboard.git
   ```
2. Open `medical_insurance_claims.csv` in **Tableau**.
3. Load the prebuilt Tableau workbook (`.twb` or `.twbx`).
4. Explore the interactive dashboard.

---

## 📷 Dashboard Preview

*https://public.tableau.com/views/MedicalClaims_17578448970090/MedicalClaimsDashBoard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link*
*<img width="1640" height="716" alt="Medical Claims DashBoard" src="https://github.com/user-attachments/assets/a9549517-4179-454b-a1c8-d9eecfef0435" />
*

---

## 📝 Conclusion

This dashboard provides a **risk and cost analysis view** for insurance companies, helping them:

* Identify high-risk groups (smokers, high BMI individuals).
* Adjust premium strategies.
* Better understand demographic cost drivers.
