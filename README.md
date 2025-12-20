# Aircraft with lowest Risk Analysis for Business Expansion ✈️

## Overview
This project analyzes historical aviation accident data to identify the **lowest-risk aircraft models** for a company planning to expand into commercial and private aviation operations.  

Using data cleaning, aggregation, risk scoring, and visualization techniques, the project delivers **data-driven recommendations** to support safe and strategic aircraft purchasing decisions.

---

## Business Understanding
### Stakeholder
Head of the Aviation Division

### Business Problem
The company intends to enter the aviation industry but lacks insight into the **relative safety risks of different aircraft models**. Poor aircraft selection could lead to financial loss, reputational damage, and safety concerns.

### Key Business Questions
1. Which aircraft models present the **lowest operational risk**?
2. How do accident history and fatality records compare across aircraft?
3. Which aircraft should be prioritized for initial investment?

---

## Data Understanding & Preparation
### Data Source
- National Transportation Safety Board (NTSB) Aviation Accident Dataset  
- Coverage: 1962–2023  
- Source: Kaggle

### Data Cleaning Steps
- Removed duplicate and irrelevant records
- Standardized aircraft make and model names
- Handled missing values appropriately (retained nulls where data was genuinely unavailable, e.g., latitude)
- Aggregated accident data at the **aircraft make–model level**
- Created engineered features including:
  - Total accidents
  - Fatal accidents
  - Total fatalities
  - Fatal accident flag
  - Composite **Risk Score**

The final cleaned dataset was exported and used for **Tableau dashboard development**.

---

## Data Analysis & Visualizations
The analysis focused on comparing aircraft safety using:
- Accident frequency
- Fatal accident history
- Total fatalities
- Risk score ranking

### Top 3 Safest Aircraft Models (Final Recommendation)
| Rank | Make | Model | Risk Level |
|-----|------|-------|------------|
| 1 | Hawker | Sea Fury TMK 20 | Very Low |
| 2 | Kolb | Twin Star Mark III | Very Low |
| 3 | Koleno | Titan T-51 | Very Low |

These aircraft demonstrate **minimal accident involvement and no fatal accident history**, making them suitable for low-risk entry into aviation operations.

---

## Interactive Tableau Dashboard 

**[[INSERT YOUR TABLEAU PUBLIC DASHBOARD LINK HERE](https://public.tableau.com/views/Book4_17661000027750/finalDB?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]**

The interactive dashboard allows stakeholders to:
- Compare aircraft risk scores
- Filter by fatal accident history
- Explore accident and fatality distributions
- Identify low-risk aircraft visually and intuitively

---

## Conclusions & Recommendations
### Key Findings
1. Aircraft with **no fatal accident history** consistently show the lowest risk scores.
2. A small number of aircraft models dominate the **low-risk category**, making selection clearer.
3. Risk scoring simplifies complex safety data into **actionable insights**.

### Business Recommendations
- Prioritize acquisition of **HawKER Sea Fury TMK 20**, **Kolb Twin Star Mark III**, and **Koleno Titan T-51**
- Avoid aircraft models with recurring fatal accident patterns
- Use risk scoring as a **standard evaluation tool** for future fleet expansion

---

## Next Steps
- Incorporate operational cost and maintenance data
- Update dashboard periodically with new accident records
- Expand analysis to include regional and environmental risk factors

---

## Repository Structure
├── data/
│ └── cleaned_aviation_data.csv
├── notebooks/
│ └── aviation_risk_analysis.ipynb
├── presentation/
│ └── aviation_risk_presentation.pdf
├── README.md
└── .gitignore


---

## Author
**Abel Aleu Chol Garang**  
Data Scientist | Aviation Risk Analysis  
🔗 LinkedIn: [*(add your LinkedIn link here)*](https://www.linkedin.com/in/abel-aleu-941799247?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BByYx6s9aQ7WQv%2FXWyVZvOA%3D%3D)


---

## Acknowledgements
- National Transportation Safety Board (NTSB)
- Kaggle
- Tableau Public
