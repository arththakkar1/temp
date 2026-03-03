# Active Conflicts = COUNTROWS(FILTER(war_economic_impact_dataset,war_economic_impact_dataset[Conflict_Name]="Active"))
# Avg Poverty Increase (%) = AVERAGEX(war_economic_impact_dataset,war_economic_impact_dataset[During_War_Poverty_Rate_%] - war_economic_impact_dataset[Pre_War_Unemployment_%])
