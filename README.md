# 🚗 India EV vs Petrol Market Share Shift Analysis (2022–2025)

## 📌 Project Overview
This project analyses the shift in vehicle fuel-type registrations across 35 Indian states from 2022 to 2025, using data from the Vahan government dashboard. The core question explored is — **are EVs replacing petrol vehicles, or are they simply absorbing new buyers?**

---

## 🛠️ Tools Used
- **Python (Pandas)** — Data cleaning and merging 35 state-wise Excel files
- **MySQL** — Data storage and analysis using window functions and CTEs
- **Excel** — Interactive dashboard with pivot tables, charts and slicers

---

## 📊 Analyses Performed
### 1. Market Share % per Fuel Type per Year
Calculated each fuel type's share of total registrations nationally, filtered to fuel types with >0.5% share.

### 2. Year-on-Year Market Share Change
Identified which fuel types gained or lost market share each year using a self-join CTE.

### 3. Petrol Decline vs EV Rise
Compared absolute registration volumes and share % of Petrol, EV and CNG side by side across years.

### 4. EV Growth % in Top States
Ranked top 20 states by EV volume and compared their growth rate from 2022 to 2025.

### 5. State-wise EV Penetration %
Calculated EV registrations as a % of each state's total registrations in 2025.

---

## 🔍 Key Insights
- **EVs are not replacing petrol — they are absorbing new buyers.** Petrol volume grew from 17.8M to 22M between 2022 and 2025 while EV volume more than doubled.
- **EV share nearly doubled** from 4.71% in 2022 to 8.05% in 2025 with consistent year-on-year growth.
- **West Bengal is the fastest growing EV market** among high-volume states — growing 805% from 11K to 1 lakh EVs, largely driven by e-rickshaw adoption.
- **Only 5 of 35 states have crossed 10% EV penetration** — Tripura leads at 18.3%, followed by Assam, Delhi, Kerala and Karnataka.
- **The Gujarat paradox** — home to major EV manufacturers yet recorded the lowest EV adoption growth at just 9.8% among top states.
- **Non-metro states are outpacing metros** — Bihar, Assam and Odisha all grew faster than Delhi and Maharashtra.

---

## 📁 Data Source
[Vahan Dashboard — Ministry of Road Transport & Highways, Government of India](https://vahan.parivahan.gov.in/vahan4dashboard)

---

## 👤 Author
**Harshal Ahuja**
[LinkedIn](https://www.linkedin.com/in/harshalahuja-nsut/) 
