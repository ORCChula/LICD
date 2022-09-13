# LICD
Simulation Models for the LICD (both the current and the new LICD layouts), together with its container traffics in Oct 2018 - Sep 2019.

Evaluating the long-term operational performance of a large-scale inland terminal: A discrete event simulation-based modeling approach

About the project
This project evaluates the long-term operational performance of a large-scale inland terminal by using a Discrete Event Simulation (DES) modeling framework.

Data
The data in this study were provided by the State Railway of Thailand (SRT) and the Eastern Sea Laem Chabang Terminal Co., Ltd (ESCO), including the numbers of import and export containers at the LadKrabang Inland Container Depot (LICD), Thailand, during October 1, 2018 - September 30, 2019. 

1.	LICD settings and the five scenarios
There are two main LICD settings and five scenarios in this study, namely (i) a setting for the current layout, with the current operation (scenario S1) and with the new transportation policy (scenario S2), and (ii) a setting for the new LICD layout at three different stages of development, referred to as scenarios S3, S4, and S5. The detailed information for each of these scenarios is summarized as follows.
a)	Scenario 1: the current LICD layout and operation, in which the transportation ratio between rail and road is set at 20:80.
b)	Scenario 2: the current LICD layout and operation with the new transportation policy, in which the transportation ratio between rail and road has been changed to 50:50.
c)	Scenario 3: the initial phase of LICD’s development plan. In this scenario, the new LICD layout follows the Port Authority of Thailand (PAT) with the least fleet size, while the transportation ratio between rail and road has been set at 50:50.
d)	Scenario 4: the second phase of LICD’s development plan, in which a rubber tyred gantry crane (RTG) is introduced into the rail zone for the improvement of rail transportation efficiency, along with the increased numbers of container handling equipment (CHE).
e)	Scenario 5: the third phase of LICD’s development plan, with the full fleets of CHE.
	In addition to the above five scenarios, Scenario 6 (S6-1, S6-2, S6-3) is also simulated, where container demands are incrementally increased by 10% until they reach the level of 140% of the current container demand.

2.	Files
a)	The data concerning import and export containers arriving and departing the LICD between October 2018 and September 2019 are summarized in the file entitled “Container traffics at the LICD in Oct 2018 - Sep 2019”. These data contain the monthly numbers of loads (both import and export containers) handled by gate operators at the LICD. 
b)	According to data in (a), as well as those provided by the ESCO, we could then determine the model parameters, summarized in Table 1. These model parameters have been later passed down and embedded into the simulation model representing each scenario. Due to the sizes of models, in this repository, only two simulation models will be provided in the folder named “Model”: one representing the current LICD layout and operation (scenario S1) and another representing the initial phase of LICD’s development plan (scenario S3). With SIMIO simulation program, interested readers may download the abovementioned simulation models, run or modify them, for their specific purposes.   
