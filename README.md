# POE_techniques [v0.1 BETA]
_Post-occupancy evaluation (POE) techniques_

This project is further detailed in the following scientific article: 

  **reference**


## Overview
This project involves a set of data-based fault detection and diagnosis techniques to deeply understand real building operation and identify potential building faults.
The techniques are divided into three action areas, related to building characteristics (A), energy systems (B), and occupants’ behaviour (C).



## Versions

	-_v0.1 BETA - First version of the project_ 	- 23/07/2023
	-_v0.2 comming soon..._				- 

## Requirements to use POE_techniques

### Python version
 - Python 3.8+

### Installing development requirements
------------

    pip install -r requirements.txt


## How to use **POE_techniques**?

The approach is divided into different Jypyter Notebooks to guide the workflow.


**A.Building characteristics**
- **Notebook a1_Ventilation_diagnosis** - CO2 concentration above 1000ppm.
- **Notebook a2_Airtightness_diagnosis** - CO2-based decay method.

**B.Energy systems**
- **Notebook b1_Unsupervised_load_disaggregation** - Load disaggregation through non-intrusive load monitoring (NILM). 
- **Notebook b2_Thermostat_Control_Diagnosis** - Evaluation of the heating system working at full-load and partial-load operation.

**C.Occupants’ behaviour**
- **Notebook c1_Lighting_system_diagnosis** - Percentage of time in which lighting is on in unoccupied spaces.
- **Notebook c2_Discrepancies_occupancy_operation** - Percentage of time in which fixed building/HVAC operating schedules don’t match with occupancy.


## The directory structure
------------

The directory structure of POE_techniques project looks like this: 

```
POE_techniques/
│ 
├── LICENSE 				<- MIT license
├── README.md
├── requirements.txt   			<- The requirements file for reproducing the analysis environment
│          		
├── notebooks				<- Jupyter notebooks to guide the workflow 	
│   ├─ a1_Ventilation_diagnosis.ipynb        		
│   ├─ a2_Airtightness_diagnosis.ipynb 
│   ├─ b1_Unsupervised_load_disaggregation.ipynb 
│   ├─ b2_Thermostat_Control_Diagnosis.ipynb 
│   ├─ c1_Lighting_system_diagnosis.ipynb  
│   ├─ c2_Discrepancies_occupancy_operation.ipynb    		
│             		
├── data/				<- Monitoring data of a university building in the UK (Oxford)
│   ├─ *.csv files
│       
└──
```
