# 📊 National-Family-Health-Survey (NFHS-5) (2019–21) Interactive Power BI Dashboard


## 🧩 Problem Statement

India’s states and communities show sharp contrasts in health, nutrition, fertility, education, and gender empowerment.  
The **National Family Health Survey (NFHS-5, 2019–21)** provides 400+ indicators on these topics — but its complexity often overwhelms policymakers, researchers, and NGOs.  

The core problem: **There’s no easy-to-use, dynamic tool to decode, compare, and interpret this rich data without deep technical skills.**

---

## 🎯 Project Objective

✅ Turn NFHS-5 data into a clear, interactive **Power BI Dashboard**  
✅ Let users filter by **state, area, gender, and indicator group**  
✅ Highlight **regional disparities, gender gaps, and high-risk areas**  
✅ Support **data-driven decisions** for targeted health and social policy

---

## 🗂️ Dashboard Pages & Chart Narrative

---

### 🔵 **Page 1 — State-wise Health Indicator Heatmap**

**Purpose:**  
Visualize the geographic spread of any selected indicator.

**Visuals:**  
- **Slicers:** State, Area (Urban/Rural), Indicator Group, Indicator Name  
- **Filled Map:** State-wise indicator distribution with color gradients  
- **Dynamic Title & Summary (DAX):** Shows applied filters and values

🖼️ Dashboard Snapshots:

![HEAT MAP](https://github.com/user-attachments/assets/89e32a7e-7ec3-411d-ac6f-16662efd4d0a)

---

### 🟡 **Page 2 — Demographics, Literacy & Vital Registration**

**Purpose:**  
Show population coverage, basic amenities, mortality, early marriage, and digital inclusion.

**Visuals:**  
- **KPI Cards:** Households surveyed, Men interviewed, Women interviewed  
- **Clustered Bar Chart:** Top 5 states for Sex Ratio at Birth  
- **Matrices:**  
  - **Basic Household Amenities** (electricity, sanitation, water, clean fuel, iodized salt)  
  - **Education Insights** (schooling years, gender gap, GPI)  
  - **Literacy Insights:** Overall, Male/Female, Urban/Rural, Gender & Urban-Rural Gaps (SWITCH logic)  
- **Clustered Bar Chart:** Under-Five Mortality (breakdown by neonatal, post-neonatal, child)  
- **Pie Chart:** Early Marriage (girls under 18, boys under 21)  
- **Gauges:**  
  - Registered Births (% of children under 5)  
  - Registered Deaths (% of deaths in last 3 years)  
  - Internet Usage (% of men & women 15–49)
  - 
🖼️ Dashboard Snapshots:

![DEMOGRAPHICS](https://github.com/user-attachments/assets/f82dead9-71ee-44d8-91a4-39da324890f1)

---

### 🟢 **Page 3 — Public Health, Nutrition & Service Access**

**Purpose:**  
Track body measurement stats, child nutrition, immunization, anaemia, family planning, and child health services.

**Visuals:**

1️⃣ **Matrix:**  
- Body Measurement (BMI underweight, overweight, waist-to-hip ratio) by gender (15–49)

2️⃣ **Matrix:**  
- Nutritional Status of Children Under 5 (stunted, wasted, severely wasted, underweight, overweight)

3️⃣ **Matrix:**  
- Child Immunization (BCG, Polio, Penta/DPT, Measles, Rotavirus, Hepatitis B)

4️⃣ **Matrix:**  
- Family Planning Methods Used by Married Women 15–49 (any method, modern method, female/male sterilization, IUD, pills, condoms, injectables)

5️⃣ **Clustered Bar:**  
- Anaemia Prevalence (children 6–59 months, women 15–49, pregnant women, adolescent girls, men 15–49, young men)

6️⃣ **Gauges:**  
- Health Facility Visits for Diarrhoea (under 5)  
- Card-Based Vaccination Coverage (12–23 months)  
- Health Facility Visits for Fever/ARI (under 5)

🖼️ Dashboard Snapshots:

![Public Health ](https://github.com/user-attachments/assets/10c11f02-e4c3-42fb-a9a7-91dcc1154a20)

---

### 🟣 **Page 4 — Women’s Empowerment & Health Services**

**Purpose:**  
Assess women’s access to services/resources, risk factors, chronic diseases, screening, and fertility trends.

**Visuals:**

- **Pie Charts:**  
  - Public vs Private Vaccination Coverage (12–23 months)  
  - Caesarean Deliveries (public vs private facilities)  
  - Alcohol Use (by gender)  
  - Tobacco Use (by gender)

- **Gauge Charts:**  
  - Women facing Spousal Violence (ever married, 18–49)  
  - Children 9–35 months with Vitamin A dose in last 6 months  
  - Institutional Births (last 5 years)  
  - Tetanus Protection (last birth, 5 years)  
  - Average Delivery Cost — Public Facility  
  - Teenage Mothers or Pregnant (15–19 years)  
  - MCP Card Coverage (last 5 years)  
  - Adolescent Fertility Rate (15–19 years)  
  - Total Fertility Rate

- **Matrix:**  
  - Women’s Empowerment & Access:  
    - Decision participation  
    - Paid work  
    - Property ownership  
    - Bank account usage  
    - Mobile phone access  
    - Hygienic menstrual protection (age 15–24) — area-wise (urban vs rural)

- **Matrix:**  
  - Hypertension Levels (mild, moderate/severe, elevated) by gender

- **Matrix:**  
  - Blood Sugar Levels (high, very high, combined/treated) by gender

- **Clustered Bar:**  
  - Cancer Screening (women 30–49: cervical, breast, oral; men 30–49: oral)

🖼️ Dashboard Snapshots:

![Empowerment and Health](https://github.com/user-attachments/assets/d05d8590-0f98-422b-98d6-53ac52740e9d)


---

## ⚙️ Technical Highlights

| Feature | Description |
| ------- | ----------- |
| **Dynamic Slicers** | Filter by State, Area, Indicator Group, Name |
| **SWITCH Measures** | Switch logic for literacy, mortality, BMI, hypertension, blood sugar |
| **Datatables** | Hierarchy tables for dynamic toggling |
| **Dynamic Titles** | Auto-update with selected filters |
| **Conditional Formatting** | Positive/negative trends color-coded |
| **Alt Text & Accessibility** | Each visual has descriptive alt text |
| **DAX Summary Cards** | Filter summaries for context |

---

## ✅ Final Outcome

This dashboard:
- Makes 130+ key NFHS-5 indicators **accessible** and **comparable**
- Helps policymakers, students, and NGOs **target interventions**
- Bridges gender, area, and state-wise gaps with visual clarity

---

## 📌 Data Source

**🔗 [National Family Health Survey (NFHS-5), 2019–21](https://www.data.gov.in/catalog/national-family-health-survey-nfhs-5)**  
_Government of India — Ministry of Health and Family Welfare_

---

## 📜 License

This project is open for **educational and policy research use**.  
Please credit **NFHS-5** data and the dashboard author when sharing.

---

## 👤 Author

**Developed by:** SAKSHI PATIL  
📧 sakshipandit0909@gmail.com

---

## ⭐ Star This File!

If you found this helpful, please **star ⭐ this File** and share with your network.  
Let’s make public health data easy for everyone!

---


