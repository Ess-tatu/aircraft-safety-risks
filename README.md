# ✈️ Aircraft Safety Risks Analysis

This project provides data-driven insights into aircraft safety risks to guide a company seeking to expand into aviation. Using historical accident and incident data from the National Transportation Safety Board (NTSB), this project analyzes accident trends, identifies high-risk aircraft types, and provides actionable recommendations to support safe fleet acquisition and operation.

## 📊 Project Overview

A company planning to enter the aviation sector is evaluating potential aircraft for purchase. This project answers the key question:  
**"Which aircraft types present the lowest safety risks for initial acquisition and operation?"**

The CRISP-DM methodology is applied to explore patterns in historical aviation accidents, uncovering risk factors tied to aircraft type, flight phase, weather, and more.

## 📁 Dataset

- **Source**: [NTSB Aviation Accident and Incident Data](https://www.ntsb.gov)
- **Time Period**: 1962 – 2023
- **Rows**: 88,889 entries  
- **Columns**: 31 features including injury severity, aircraft make/model, engine type, phase of flight, and weather conditions.

## 🧠 Methodology

The analysis follows the CRISP-DM framework:

1. **Business Understanding** – Define project objectives aligned with fleet acquisition.
2. **Data Understanding** – Inspect, clean, and preprocess the NTSB dataset.
3. **Data Analysis** – Use statistical summaries and visualizations to uncover trends.
4. **Conclusions** – Summarize key findings on aircraft safety.
5. **Recommendations** – Provide actionable steps to minimize operational risk.

## 🔍 Key Insights

### 1. **Aircraft Risk Profiles**
- **Cessna** aircraft show the **highest accident frequency** (due to widespread general aviation use).
- **Mooney** aircraft show the **lowest recorded accident frequency**.
- **Boeing** models display **lower accident rates**, aligned with commercial operation standards.

  ![download 4](https://github.com/user-attachments/assets/a8253d63-396d-424b-9e86-2caf0fc1c68f)

  ![download 2](https://github.com/user-attachments/assets/5736640e-89ed-45d2-bab3-336323a1147a)
  
  ![download 1](https://github.com/user-attachments/assets/f812f335-6327-4a0e-ab39-f54b306339db)
  
### 2. **Contributing Factors**
- Accidents are **most frequent during landing**, indicating a critical risk phase.
- **VMC (Visual Meteorological Conditions)** had more accidents than IMC, suggesting issues with weather-related judgment or pilot experience.
- **Three-engine reciprocating aircraft** showed the highest fatal injury averages.

  ![download 6](https://github.com/user-attachments/assets/99102b7e-49eb-4595-bfac-ea6c558e6a40)
  
  ![download 5](https://github.com/user-attachments/assets/2492a31a-e05a-4b0f-bd88-1d1176ac9d79)

  ![download 3](https://github.com/user-attachments/assets/66fb9f14-6a5f-46bc-a1b5-98d85af40526)

### 3. **Temporal Patterns**
- Peak accident rates occur in **July**, suggesting risks tied to high-traffic summer months.
- A spike in fatal injuries occurred between **1990–2000**, likely linked to aging fleets and general aviation growth.
- **Pilot** or privately - operated flights contributed to most of the accidents.
- Most accidents occurred between **1980-2020**

  ![download 8](https://github.com/user-attachments/assets/369d1bac-43c0-45b2-a997-7632365d13f5)
  
  ![download 9](https://github.com/user-attachments/assets/e22fa495-f61e-47dc-a8e7-b91166d29d41)

  ![download 10](https://github.com/user-attachments/assets/05085833-fcae-4c6b-b84f-91912871d4c2)

  ![download 7](https://github.com/user-attachments/assets/885f1fc2-951b-4983-bdeb-0c8dda87dcfa)

## ✅ Recommendations

1. **Aircraft Selection**
   - Prioritize modern, commercial-grade aircraft (e.g., Boeing).
   - Avoid aging or less reliable general aviation models.

2. **Pilot Training**
   - Emphasize simulator-based training for landing and adverse weather conditions.

3. **Operational Scheduling**
   - Increase inspections and risk controls during July and other high-traffic months.

4. **Technology Adoption**
   - Equip aircraft with real-time safety monitoring systems.
   - Continuously update operational manuals based on recent data trends.

## 📈 Interactive Dashboard

Explore the interactive version of this analysis on **Tableau Public**:  
👉 [Aircraft Safety Risks and Management Strategy Dashboard](https://public.tableau.com/views/AircraftSafetyRisksandManagementStrategy/Story2?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This dashboard presents dynamic visualizations and insights to support executive decision-making.
