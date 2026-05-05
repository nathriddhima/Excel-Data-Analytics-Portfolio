#  Bike Sales Dashboard — Excel Data Analytics Project

### Interactive Dashboard built using Microsoft Excel | Pivot Tables | Slicers | Charts

---

##  About Me
**Riddhima Nath** | B.Com Student, Allahabad University | McKinsey Forward Scholar
Aspiring Business & Data Analyst | [LinkedIn](https://www.linkedin.com/in/riddhima-nath/)

---

##  Objective
To analyze bike purchase patterns across 1000 customers using Microsoft Excel, identifying key demographic and behavioral factors that influence bike buying decisions — delivering actionable insights through an interactive dashboard.

---

##  Dataset
- **Records:** 1,000 customers
- **Columns:** ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Purchased Bike

---

##  Tools & Features Used
| Tool/Feature | Purpose |
|---|---|
| Microsoft Excel | Core platform |
| Pivot Tables | Data summarization and analysis |
| Pivot Charts | Visual representation of insights |
| Slicers | Interactive dashboard filtering |
| Data Cleaning | Removing duplicates, standardizing values |
| VLOOKUP / IF formulas | Data transformation in working table |

---

##  Project Workflow

### Step 1 — Data Cleaning (Working Table)
- Removed duplicate records
- Standardized Marital Status values (M → Married, S → Single)
- Standardized Gender values (M → Male, F → Female)
- Created Age Brackets using nested IF formula:
  - Young Adults (< 31)
  - Middle Aged (31–54)
  - Old (55+)

### Step 2 — Pivot Tables (3 Created)
- **Average Income by Gender** — split by Purchased Bike (Yes/No)
- **Age Bracket vs Bike Purchase** — count of customers per age group
- **Commute Distance vs Bike Purchase** — purchase patterns by distance

### Step 3 — Interactive Dashboard
- Built 3 pivot charts linked to pivot tables
- Added 4 slicers for dynamic filtering:
  - Marital Status
  - Education
  - Region
  - Gender
- Designed clean layout with professional formatting

---

##  Key Findings & Business Insights

### 1️. Income Drives Bike Purchases
- Male customers who purchased bikes earned an average of **$60,124** vs **$56,208** for non-buyers
- Higher income correlates strongly with bike purchase likelihood
- **Business Insight:** Marketing campaigns should target mid-to-high income segments

### 2️. Middle Aged Customers Dominate
- Middle Aged customers (31–54) account for **151 bike purchases** — highest of any age group
- Young Adults surprisingly show lower purchase rates despite fitness trends
- **Business Insight:** Product messaging should resonate with 31–54 age demographic

### 3️. Short Commuters Buy More Bikes
- Customers with **0-1 mile commute** are the highest bike buyers (93 purchases)
- Purchase likelihood **decreases** as commute distance increases
- Customers commuting **10+ miles** show the lowest purchase rates
- **Business Insight:** Target marketing towards short-distance urban commuters

### 4️. Regional Patterns
- Use Region slicer to compare Europe vs North America vs Pacific purchase behavior
- Interactive filtering reveals distinct regional preferences

---

##  Business Recommendations
1. **Target middle-aged, mid-income urban professionals** — highest conversion likelihood
2. **Focus campaigns on short-distance commuters** — most likely to see bikes as practical transport
3. **Differentiate regional marketing** — Pacific vs Europe vs North America show different patterns
4. **Male-focused campaigns** can leverage the income-purchase correlation insight

---

##  Repository Structure
```
├── Excel_DA_Project.xlsx    # Complete workbook with all sheets
│   ├── bike_buyers          # Raw dataset
│   ├── working table        # Cleaned and transformed data
│   ├── Pivot table          # Three pivot tables
│   └── Dashboard            # Interactive dashboard with slicers
└── README.md                # Project documentation
```

---

## How to Use
1. Download `Excel_DA_Project.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Go to the **Dashboard** tab
4. Use the **slicers** on the left to filter by Marital Status, Education, Region, or Gender
5. All three charts update simultaneously

---

## Other Projects in My Portfolio
-  [Tableau — Hollywood Films Genre Analysis](https://public.tableau.com/app/profile/riddhima.nath)
-  [SQL — Data Cleaning + EDA Portfolio](https://github.com/nathriddhima/SQL-Data-Analytics-Portfolio)
-  [Python — Indian IPO EDA (2010–2025)](https://github.com/nathriddhima/Indian-IPO-EDA)

---

## Connect With Me
-  [LinkedIn](https://www.linkedin.com/in/riddhima-nath/)
-  [Tableau Public](https://public.tableau.com/app/profile/riddhima.nath)
-  [GitHub](https://github.com/nathriddhima)

---
*This project was created as part of my Data Analytics portfolio.*
