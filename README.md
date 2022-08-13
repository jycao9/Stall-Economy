# Data and Source Code for *Stall Economy: The Value of Mobility in Retail on Wheels*

## Overview
This repository contains data and source code for the paper *Stall Economy: The Value of Mobility in Retail on Wheels*.

## Folders

* code: Python files

  - Numerical_Analysis.ipynb:	Results and figures in Section 5.2 and 5.3;
  - Simulation_meeting_rules.ipynb: 
    - Simulation of the Magnet rule and some alternatives;  
    - Validation of the spatial queueing models in the context of Toronto;
    
* data: 

  - canada_population.csv: population of province or territory in Canada
  - toronto_travel_time.csv: travel time and distance in Toronto
  - toronto_areas.csv: population and area in different areas
  - zip_codes_toronto.csv: zipcode and location of different areas in Toronto
  - zipcode_pop_speed_toronto: biking speed, population, and area in different FSA


* numerical_results:  
 
  - solution_toronto.csv: solution of stall deployment
  - solution_toronto_less_willingness_to_wait.csv: solution of stall deployment when doubling the coefficient of the mean waiting time
  - solution_toronto_less_willingness_to_walk.csv: solution of stall deployment when doubling the coefficient of the service radius
  - solution_toronto_longer_shopping.csv: solution of stall deployment when doubling the shopping time
  - tor_scenarioX_binary_YlGn_2022: FSA-level service mode choice in different scenarios
 



