# Documentation Group 6 - Dike model
Alexander Berck				4494652
Karo Oude Groote Beverborg	4584333
Jeroen ter Haar				4454383 
Joost Oortwijn				4593472 
Job Onkenhout				4595769 
Pieter van Spaendonck		4476697

This README file is created to give structure to the documentation. The documentation consists of the following important files:
**problem_formulation_group6.py** : Contains a new 7-objective problem formulation under the problem_formulation_id == 2. This problem formulation is used in all notebook files.

**EPA1361_group_6_Main.ipynb**:
**Step1** : Step 1 - Problem formulation of the report is executed
This step generates the results of the base case scenario and these results are stored as file: step1_basecase_outcomes_experiments.csv 

**Step2** : Step 2 - Generating alternatives of the report is executed
This step runs the directed search. All generated pareto solutions are stored in: all_pareto_solutions.csv
The 11 policies that fit the constraints are stored in: generated_policies.csv

**Step3** : Step 3 - Uncertainty analysis of the report is executed
In this step the 11 generated policies are ran for 1.000 scenarios. These are stored in: scenarios.csv

**Step4** : Step 4 - Scenario discovery of the report is executed

**Contributions**:
The code are the work of Ciullo et al. (2019) and their paper can be found at https://www.mdpi.com/2073-4441/11/12/2530 and are provided by Jan Kwakkel. The ema_workbench module are the work of Jan Kwakkel. See his GitHub repositories at https://github.com/quaquel/epa1361_open and https://github.com/quaquel/EMAworkbench for full documentation on both the model and the EMA workbench. 




