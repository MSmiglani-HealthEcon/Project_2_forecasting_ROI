📊 Forecasting Diabetes Healthcare Costs & ROI Analysis (India)
Overview

This project applies health economics and data analytics methods to forecast diabetes-related healthcare costs in India and evaluate the return on investment (ROI) of a hypothetical preventive intervention. It demonstrates how cost forecasting and economic evaluation can support evidence-based health policy decision-making.

The analysis uses historical cost data, time-series smoothing, regression-based forecasting, and intervention modelling to produce policy-relevant economic insights.

Objectives

-Forecast national diabetes-related healthcare costs over a 10-year horizon
-Apply moving average techniques to smooth historical trends
-Model a preventive healthcare intervention
-Estimate annual cost savings and ROI
-Produce reproducible outputs suitable for health policy analysis and MSc-level evaluation

Project Structure
Health-Economics-P2_Forecasting-ROI/
│
├── data/
│   ├── diabetes_cost_timeseries.csv
│   ├── diabetes_cost_timeseries_cleaned.csv
│   └── diabetes_forecast_results.csv
│
├── notebooks/
│   └── P2_financial_forecasting_ROI.ipynb
│
├── plots/
│   ├── forecast_costs.png
│   ├── intervention_adjusted_costs.png
│   └── roi_savings_plot.png
│
├── report/
│   └── Project_2_Forecasting_Diabetes_ROI_Report.docx
│
└── README.md

Data Sources

Historical diabetes healthcare cost data (2010–2024)
National-level annual expenditure (INR, millions)
Intervention assumptions (hypothetical)

Cost per person

Target population size
Assumed percentage reduction in healthcare costs
Intervention parameters are illustrative and used for methodological demonstration.

Methodology
1. Data Preparation

Imported historical cost data using Python (pandas)
Checked for missing values and inconsistencies
Ensured consistent units and time continuity

2. Trend Smoothing

Applied a 3-year moving average (MA3) to stabilise short-term fluctuations
Enabled clearer interpretation of long-term expenditure trends

3. Forecasting

Used regression-based forecasting to project healthcare costs for the next 10 years
Forecasts provide a baseline scenario for economic evaluation

4. Intervention & ROI Modelling

Modelled a preventive intervention reducing projected costs
Calculated annual savings
Estimated ROI using:
ROI= Programme Cost Savings−Programme Cost
Negative ROI values reflect common short-term trade-offs in preventive health economics.

Key Outputs

-Cleaned and processed healthcare cost dataset
-Forecasted cost projections (10-year horizon)
-Intervention-adjusted cost estimates
-Annual savings and ROI calculations
-Policy-ready tables and visualisations
-Visualisations
-Historical vs Forecasted Diabetes Healthcare Costs
-Intervention-Adjusted Cost Trajectory
-Annual Savings and ROI Trends
-All figures are stored in the /plots directory.
-Policy Relevance

This project demonstrates how:

-Forecasting informs budget planning
-ROI analysis supports preventive health investment decisions
-Economic evidence bridges clinical outcomes and financial sustainability

Tools & Technologies

-Python: pandas, numpy, matplotlib
-Jupyter Notebook
-Excel (tabulation and exports)
-GitHub (version control and dissemination)

Limitations & Future Work

-Hypothetical intervention parameters
-National-level aggregation only
-No stratification by age, region, or disease severity
-Future extensions could include:
-Cost-effectiveness analysis (e.g. cost per QALY)
-Longer time horizons
-Demographic-specific modelling

Author
Mansimran Singh Miglani
MSc (Medical Biotechnology & Business Management)
Aspiring Health Economist / Policy Analyst
