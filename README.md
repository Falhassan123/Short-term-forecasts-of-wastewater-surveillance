# Short-term-forecasts-of-wastewater-surveillance
This GitHub repository contains weekly real-time forecasts of SARS-COV-2 in the United States. We use an n-sub-epidemic modeling framework to produce forecasts each week.


# Model Specification and Forecasting
We conduct a 2-week forecast based on a 16-week calibration period. The Nonlinear Least Squares estimation method is utilized, with a Normal distribution applied for error modeling.

#Additional Information
The data presented on the dashboard and used for all forecasts is collected every Saturday from the Centers for Disease Control and Prevention (CDC) [2]. 


# References
1. Chowell G, Dahal S, Bleichrodt A, Tariq A, Hyman JM, Luo R. SubEpiPredict: A tutorial-based primer and toolbox for fitting and forecasting growth trajectories using the ensemble n-sub-epidemic modeling framework. Infect Dis Model. 2024 Feb 9;9(2):411-436. doi: 10.1016/j.idm.2024.02.001. PMID: 38385022; PMCID: PMC10879680.
2. Centers for Disease Control and Prevention. National Wastewater Surveillance System, Weekly COVID-19 Wastewater National and Regional Trends. Atlanta, GA. Office of Public Health Data, Surveillance, and Technology. Available at:
   https://www.cdc.gov/nwss/rv/COVID19-nationaltrend.html
