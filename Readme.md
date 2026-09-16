#  Titanic Survival Analysis – Power BI Dashboard

Interactive Power BI dashboard analyzing passenger survival patterns from the Titanic disaster using DAX measures and data visualizations.

---

## Project Overview

This project explores the famous Titanic dataset to uncover insights about survival rates based on key factors such as:

- Passenger Class
- Gender
- Age Group
- Fare Category
- Port of Embarkation
- Whether the passenger was traveling alone
- Demographic group (`who` – man / woman / child)

The dashboard includes **KPI cards**, interactive charts, slicers, and a detailed passenger table.

---

##  Key Metrics (KPI Cards)

| Metric              | Description                          |
|---------------------|--------------------------------------|
| Total Passengers    | Overall number of passengers         |
| Total Survivors     | Number of passengers who survived    |
| Total Deaths        | Number of passengers who did not survive |
| Survivor Rate       | Overall survival percentage          |
| Average Age         | Mean age of passengers               |
| Average Fare        | Mean ticket fare                     |
| Highest Fare        | Maximum fare paid                    |
| Total Fare          | Sum of all fares                     |

---

##  Visualizations

| Visual Type       | Title                          | Purpose |
|-------------------|--------------------------------|--------|
| Donut Chart       | Survival Distribution          | Overall Survived vs Not Survived |
| Column Chart      | Passenger Class vs Survivors   | Survival by Class (1st / 2nd / 3rd) |
| Bar Chart         | Gender vs Survivors            | Survival comparison by Sex |
| Bar Chart         | Who vs Survivors               | Survival by demographic group (man/woman/child) |
| Line Chart        | Age Group vs Survival Rate     | How survival rate changes across age groups |
| Treemap           | Embarked Distribution          | Passenger count by port of embarkation |
| Scatter Chart     | Age vs Fare                    | Relationship between age and ticket price |
| Table             | Passengers Details             | Detailed view with Class, Age Group, Fare Category & Survival |

---

##  Interactive Slicers

Users can filter the entire dashboard using:

- Survival Status
- Gender
- Passenger Class
- Age Group
- Fare Category
- Embarked Port
- Is Alone (Yes/No)

---

##  Calculated Fields & Measures Used

**Measures:**
- `total_passengers`
- `total_survivers`
- `total_death`
- `surviver_rate`
- `Avg_age`
- `Avg_fare`
- `highest_fare`
- `total_fare`

**Calculated Columns / Groups:**
- `Age Group`
- `Fare Category`
- `Passenger Class`
- `is_alone`
- `who`
- `survival_distribution`

---

##  Tools Used

- **Power BI Desktop**
- **Power Query** (data cleaning & transformation)
- **DAX** (measures and calculated columns)

---

## How to Use

1. Download the `New Titanic Dax.pbix` file
2. Open it with **Power BI Desktop**
3. Interact with the slicers and visuals

---

##  Dataset

Classic Titanic passenger dataset (commonly available on Kaggle).

---

##  Author

**Your Name**  
Samyak Narwade (www.linkedin.com/in/samyaknarwade) | [GitHub](samyaktnarwade09-dotcom)

---

 If you found this project useful, feel free to star the repository!
