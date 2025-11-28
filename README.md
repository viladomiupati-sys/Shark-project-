# Shark-project-

# Sharkboy & Lavagirl Surf Camp – Shark Attack Analysis

## Hypothesis & Camp Strategy

**Problem:**  
Many young surfers—especially beginners and teenagers—enter the ocean without sufficient knowledge about marine ecosystems, shark behavior, or safe surfing practices.

**Hypothesis:**

- _Teenagers (12–20) may underestimate the risks of coastal sports, including surfing, making them vulnerable to shark attacks._
- _A structured surf camp with safety education can reduce risk and promote safe practices._

**Camp Strategy:**

**High-Risk Coastal Focus:** Prioritize U.S. coastal areas—such as Florida—where shark incidents among young surfers are historically higher, ensuring that interventions target the zones of greatest need.

**Relevant Age Group (12–20):** Center the program on teenagers, the group identified as both highly active in surfing and often lacking knowledge of marine ecosystems and shark behavior.

**Structured, Supervised Surf Activities:** Offer guided surfing lessons supported by trained instructors, integrating low-risk skill-building sessions for beginners to reduce unsafe independent entry into the water.

**Shark & Ocean Safety Education:** Incorporate comprehensive training on shark behavior, ocean conditions, risk-reduction strategies, and emergency responses to address the knowledge gaps identified in the problem statement.

Data-Informed Seasonal Scheduling:Operate the camp during high-risk periods—particularly summer months in Florida—to proactively intervene when teenagers are most likely to encounter sharks during surfing.

**Expected Outcome:**

- Teens learn surfing in a **safe and controlled environment**.
- Exposure to risk is minimized using **data-informed decisions**.
- The camp positions itself as **professional, safe, and teen-focused**, supporting both safety and business growth.

---

## Day 1 — Data Tasks

- Loaded dataset, inspected columns, missing values, and duplicates.
- **Issues & fixes:**

| Column   | Issue                | Action Taken                 |
| -------- | -------------------- | ---------------------------- |
| Age      | Missing/inconsistent | Cleaned, converted to int    |
| Activity | Inconsistent strings | Categorized into groups      |
| Date     | Stored as string     | Converted to datetime        |
| Sex      | Inconsistent values  | Standardized, filled Unknown |
| Location | Missing values       | Filled 'Unknown'             |

---

## Day 2 — Data Cleaning

- Standardized column names, cleaned categorical values, removed duplicates.
- Filled missing values (median/mode/‘Unknown’).
- Created additional columns: `age_group`, `Activity_Category`, `Season`.

---

## Day 3 — Aggregation & Analysis

- Filtered data: **U.S. teens 12–20, from 1950 onward**.
- Aggregated:
  - Top states and activities for shark attacks.
  - Age patterns within the target group.
  - Pivot tables: State × Activity.
- Key outcomes: fatal vs non-fatal attacks.

---

## Day 4 — Insights & Recommendations

- **Safe Locations:** Coastal U.S. states with historically low attacks → ideal camp sites.
- **High-Risk Activities:** Surfing is higher risk → implement supervised sessions; other activities are lower risk.
- **Target Age:** Teens 12–20 → focus safety campaigns and training here.
- **Fatality:** Most attacks are non-fatal, but emergency preparedness is recommended.
- **Combined View:** Heatmap of State × Activity guides **location, activity planning, and supervision strategies**.

**✅ Outcome:**  
Enables a **data-driven, safe, and profitable teen surf school** with targeted lessons, optimal locations, informed safety protocols, and structured risk management.
