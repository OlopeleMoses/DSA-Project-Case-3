# DSA-Project-Case-3: Palmoria HR Gender & Salary Analysis (Power BI Project)
This project investigates gender-related issues in the Palmoria Group's HR data, including gender distribution, salary analysis, pay gaps, and bonus allocation, using PowerBi
This project is part of a Data Analysis training program by **Digital Skill Africa (DSA)**. The goal is to uncover gender-related insights, salary structures, and bonus distribution to support equitable decision-making.

## 🎓 Project Context
The Palmoria Group case was provided as a capstone project to assess proficiency in:
- Data cleaning and transformation
- DAX and calculated columns
- Power BI dashboard creation

## 📦 Dataset Summary
- **Total records**: 1,000+ employee rows
- **Fields included**:
  - Employee Name
  - Gender (with some missing)
  - Region
  - Department (with NULLs removed)
  - Salary (with blanks filtered out)
  - Rating (used for bonus allocation)
  - Bonus Rule Table (separate)

## 🧹 Data Cleaning Highlights
- Replaced missing gender with `"Male"`
- Filtered out employees with:
  - No salary
  - NULL department
- Created DAX-calculated fields:
  - `Salary Band` (grouped in $10,000 ranges)
  - `Bonus Amount` based on rating
  - `Total Compensation` (Salary + Bonus)

## 🎯 Key Questions Answered
1. What is the gender distribution across Palmoria Group?
2. How does gender distribution vary by region and department?
3. What is the rating distribution by gender?
4. Is there a gender pay gap in the company?
5. Which regions or departments show pay inequality?
6. Does Palmoria meet the $90,000 minimum salary regulation?
7. What is the distribution of employees by salary band?
8. How much bonus is paid per region and company-wide?
9. What is the total compensation per employee?

## 📊 Tools & Techniques Used
- **Power BI Desktop**
- **Power Query** (for data cleaning)
- **DAX** (for calculations & measures)
- **Interactive Visuals** (cards, clustered bars, pie charts, matrix tables)

## 📈 Dashboard Overview
The interactive dashboard contains:
- Gender distribution charts
- Salary band distribution by region
- Compliance checks (e.g., minimum salary)
- Performance vs bonus payouts
- Drill-down visuals per department/region


## 📌 Conclusions from the Palmoria HR Gender & Salary Analysis
### 1. Gender Distribution Reveals Imbalance
The organization is male-dominated overall.
Certain regions and departments have little to no female representation.

### 2. Evidence of a Gender Pay Gap
Average salaries for female employees are consistently lower than those for male employees across multiple departments and regions.

#### 🔍 Recommendation: Conduct a formal audit to review promotion and salary decision criteria. A gender pay equity framework should be introduced.

### 3. Salary Regulation Compliance is Incomplete
A significant percentage of employees earn less than $90,000, which is below the new minimum salary regulation.

#### 🔍 Recommendation: Urgently review compensation policies and adjust all sub-minimum salaries to meet the legal threshold.

### 4. Skewed Salary Band Distribution
-Most employees fall within the $40,000 – $80,000 salary band.
-Very few employees earn over $120,000, indicating a flat salary structure.
-The salary distribution shows clustering in lower bands, particularly among female employees.

#### 🔍 Recommendation: Consider re-evaluating role valuation and pay scale progression. Transparent salary banding could also improve fairness.

### 5. Bonus Allocation Favors Higher Ratings, But Gender Plays a Role
-Bonuses are distributed based on performance ratings.
-Male employees tend to receive higher ratings more frequently, and thus, higher bonuses.

#### 🔍 Recommendation: Standardize performance review processes and consider blind reviews to minimize unconscious bias.

### ✅ Overall Summary
##### Palmoria Group faces key HR challenges:
##### Gender representation is uneven.
##### Gender pay disparities are evident.
##### Many employees fall below salary compliance thresholds.
##### Performance and bonus processes may require fairness reviews.
##### With the Power BI dashboard in place, management now has the data-driven insights needed to take corrective action.

![image](https://github.com/user-attachments/assets/94434c48-523c-4fab-a893-64ec558af0bb)


