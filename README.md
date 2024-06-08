# Stock_Flow_Dynamic
#Description of the model:

The model runs for 550 timesteps, with each step representing one month, starting from 2003. All necessary data to run the model are defined within it, eliminating the need to import data from external files.

To run, different variables representing pathways and scenarios are defined:

1.	GDP_Difference: This variable represents the range of scenarios for GDP growth, with inputs including [GDPSSP11, GDPSSP12, GDPSSP21, GDPSSP22, GDPSSP31, GDPSSP32, GDPSSP41, GDPSSP42, GDPSSP51, GDPSSP52].

2.	OC_Growth: It represents the range of scenarios for ownership cost growth, with inputs including [SSP1_INP1, SSP1_INP2, SSP2_INP1, SSP2_INP1, SSP3_INP1, SSP3_INP1, SSP4_INP1, SSP4_INP2, SSP5_INP1, SSP5_INP2].

3.	Population: This variable represents the range of scenarios for population growth, with inputs including [SSP1_Pop1, SSP1_Pop2, SSP2_Pop1, SSP2_Pop2, SSP3_Pop1, SSP3_Pop2, SSP4_Pop1, SSP4_Pop2, SSP5_Pop1, SSP5_Pop2].

4.	IncomeTrend: It represents the range of scenarios for income growth, with inputs including [SSP1_Income1, SSP1_Income2, SSP2_Income1, SSP2_Income2, SSP3_Income1, SSP3_Income2, SSP4_Income1, SSP4_Income2, SSP5_Income1, SSP5_Income2].

5.	STD: It represents the range of scenarios for affordability standard deviation, with inputs including [SSP1_GINI, SSP2_GINI, SSP3_GINI, SSP4_GINI, SSP5_GINI].

6.	Productivity: This variable represents the range of scenarios for productivity growth, with inputs including [PSSP1, PSSP2, PSSP3, PSSP4, PSSP5].

7.	CL: It represents the range of scenarios for covered land area growth, with inputs including [CL1, CL2, CL3, CL4, CL5].

8.	PUncertainty: This variable considers the uncertainty of productivity growth, with 3 scenarios including [Productivity_Uncertainty_1, Productivity_Uncertainty_2, Productivity_Uncertainty_3].

9.	CC: This variable considers the uncertainty of construction cost growth, with 3 scenarios including [Construction_Cost_1, Construction_Cost_2, Construction_Cost_3].

10.	OCgrowth1: This variable explores the impact of an increase in insurance premiums on the market dynamics. To see the impact of these scenarios, the "OwnershipCost" variable should be rewritten by replacing OCgrowth with OCgrowth1. There are 10 predefined scenarios with different increase rates including [Insurance_Premium_1, Insurance_Premium_2, Insurance_Premium_3, Insurance_Premium_4, Insurance_Premium_5, Insurance_Premium_6, Insurance_Premium_7, Insurance_Premium_8, Insurance_Premium_9, Insurance_Premium_10], but they can be customized for different growth rates.

#Outputs:

When the model is run, the outputs are exported to an Excel file named "output550". This file contains two sheets:

1.	DirectModelOutptut: This sheet contains raw outputs.
2.	Output: This sheet presents the data with titles for easier understanding.

