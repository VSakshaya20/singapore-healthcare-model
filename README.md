# Singapore Public Healthcare Sustainability (2026–2035)

This spreadsheet modelling project was developed for IS602: Spreadsheet Modelling for Decision Making as part of the Master of IT in Business programme at Singapore Management University.

It evaluates whether Singapore’s public healthcare system can remain sustainable through 2035 under rapid population ageing, rising hospital demand, medical inflation, and subsidy trade-offs.

## Overview

Singapore is projected to become a super-aged society, with healthcare demand rising as the elderly population grows. This project builds an integrated spreadsheet model to assess long-term sustainability across four linked dimensions:

- Demographic change
- Hospital demand and bed occupancy
- Government healthcare costs
- Financing and household out-of-pocket burden

The model is built in Excel and combines forecasting, sensitivity analysis, scenario modelling, and trade-off analysis.

## Problem Statement

As Singapore’s population ages, healthcare demand is expected to increase significantly.

The key question addressed in this project is:

**Can Singapore’s public healthcare system remain operationally and financially sustainable through 2035, and which policy levers matter most?**

## Model Structure

The workbook is organised into four modules:

### Module 1: Demographic Projection
Projects Singapore’s resident population from 2026 to 2035 using historical fertility and mortality trends, with elderly age bands segmented in more detail to reflect healthcare demand intensity.

### Module 2: Hospital Demand and Admission Forecasting
Forecasts hospital admissions, bed-day demand, and Bed Occupancy Rate (BOR) using projected population, age-specific admission rates, average length of stay, and bed expansion assumptions.

### Module 3: Government Healthcare Costs Projection
Estimates future government-funded healthcare costs using projected operating expenditure, bed demand, healthcare CPI, and medical inflation assumptions.

### Module 4: Financing and Subsidy Sustainability
Assesses whether projected government budgets can support future healthcare costs, and estimates household out-of-pocket burden under different subsidy and fiscal scenarios.

## Key Features

- Four-module integrated spreadsheet model.
- Influence diagram and blackbox model structure.
- Scenario analysis (low, base, high).
- One-way and two-way sensitivity analysis.
- Trade-off analysis for:
  - bed expansion rate vs BOR.
  - subsidy rate vs fiscal sustainability.
- Interactive ward-level out-of-pocket burden calculator.
- Clear workbook navigation and summary dashboard.

## Key Findings

Under the base-case model:

- Elderly dependency ratio is projected to reach **41% by 2035**.
- Bed Occupancy Rate is projected at **74% by 2035**, remaining below the 85% threshold.
- Projected government healthcare cost reaches **SGD 14.1 billion by 2035**.
- Financing deficit emerges in the later years of the projection horizon.
- Household out-of-pocket burden remains relatively affordable as a share of median household income under the base scenario.

The model also finds that:

- Bed expansion rate is one of the most important drivers of hospital capacity pressure.
- Medical inflation and elderly cost multipliers strongly affect long-term cost sustainability.
- There is a policy trade-off between higher subsidies and fiscal sustainability.

## Tools Used

- Microsoft Excel
- Forecasting functions and spreadsheet modelling logic
- Sensitivity analysis
- Trade-off analysis
- Interactive spreadsheet design

## Data Sources

The model uses publicly available data from sources including:

- Singapore Department of Statistics
- data.gov.sg
- Ministry of Health (MOH)
- World Health Organization (WHO)
- Central Provident Fund (CPF)

## Limitations

Some assumptions were required due to data availability constraints. These include:

- Using historical trends to project future healthcare budgets and inflation.
- Limited age-granularity in hospital admission data.
- Using inpatient cost proxies for broader affordability analysis.
- Assuming a fixed share of government operating expenditure attributable to hospital admissions.

## Why This Project Matters

This project demonstrates the use of spreadsheet modelling for public policy and resource planning. Beyond Excel proficiency, it highlights the ability to:

- Structure a complex decision model.
- Connect demographic and financial drivers across modules.
- Evaluate uncertainty with sensitivity analysis.
- Translate quantitative outputs into policy insights.

## Team Members and Roles

- Akshaya Vijayakumar Sivakami — Demographic projections.
- Xiong Yu — Hospital demand and admission forecasting.
- Cher In Teo — Government healthcare costs projection.
- Carina Faith Peh Xin Yi — Financing and subsidy sustainability.
- Serene Cheng — Financing and subsidy sustainability.
