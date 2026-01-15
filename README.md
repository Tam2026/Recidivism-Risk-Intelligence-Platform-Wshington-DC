## 🔍 Project Motivation

This self‑motivated pilot project reflects my personal interest in justice‑system analytics and my commitment to understanding how data can improve public safety outcomes. I created this project to explore how modern data engineering, predictive modeling, and visualization techniques can support evidence‑based decision‑making in justice agencies .

To simulate a realistic cross‑agency environment, I generated a fully synthetic, non‑realistic dataset ecosystem. These datasets are entirely fictional and randomly generated, designed only to mimic the structure of typical justice‑system administrative data.

---

## Synthetic Datasets Used (All Random & Fictional)

The project uses a suite of synthetic datasets stored in the `data_raw/` directory:

- **Arrest Records (`arrests.csv`)**  
  Randomized arrest events including:  
  `person_id`, `case_id`, `arrest_date`, `charge_type`, `gun_involved`, `zip_code`, `ward`

- **Court Outcomes (`court_outcomes.csv`)**  
  Fictional court processing data:  
  `person_id`, `case_id`, `court_date`, `disposition`, `sentence_type`

- **Community Supervision Logs (`supervision.csv`)**  
  Simulated supervision activity:  
  `person_id`, `case_id`, `supervision_start`, `supervision_end`, `violation_flag`

- **Demographic Profiles (`demographics.csv`)**  
  Random demographic attributes:  
  `person_id`, `age`, `gender`, `race_ethnicity`, `ward`, `zip_code`

- **Recidivism Labels (`recidivism_labels.csv`)** *(optional)*  
  Randomly assigned 12‑month recidivism outcomes:  
  `person_id`, `case_id`, `recidivism_12m`

All datasets are **synthetic**, **randomly generated**, and contain **no real individuals or real justice‑system information**.

---

## Project Overview

Using these fictional datasets, I built an end‑to‑end **Recidivism Risk Intelligence Platform** that demonstrates:

- **ETL pipelines** for cleaning, standardizing, and integrating multi‑source justice data  
- **Data Lake architecture** with raw, clean, and analytics‑ready layers  
- **Predictive modeling** (logistic regression, random forest) to estimate 12‑month recidivism risk  
- **Geospatial analysis** to identify neighborhood‑level patterns  
- **Interactive dashboards** (Power BI + Shiny) for policy‑oriented data storytelling  

This project is intentionally  to support **data‑driven public safety**, reduce recidivism, and strengthen community well‑being.

---

## Why I Built This

I am deeply interested in how data can be used to:

- Improve justice‑system transparency  
- Identify high‑risk individuals early  
- Support community‑based interventions  
- Reduce disparities across neighborhoods  
- Strengthen cross‑agency collaboration  

This project allowed me to combine my background in **public health**, **behavioral health**, and **data analytics** with my growing interest in **justice‑system data integration and recidivism modeling**.

---

## Technical Stack

- **R** — ETL, data cleaning, feature engineering, predictive modeling  
- **SQL** — schema design, data lake integration  
- **Power BI** — interactive dashboards for decision‑makers  
- **Shiny** — optional web app for real‑time risk exploration  
- **Geospatial Tools** — mapping and neighborhood‑level analysis  
- **GitHub + Netlify** — portfolio deployment and documentation  

---

## Disclaimer

All datasets in this project are **synthetic**, **randomly generated**, and **do not represent real individuals, events, or justice‑system records**.  
This project is for **educational and portfolio purposes only**.
