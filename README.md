# POE_techniques [v0.1 BETA]
_Post-occupancy evaluation (POE) techniques_

This project is further detailed in the following scientific article: 

  **reference**


## Overview
This project involves a set of data-based fault detection and diagnosis techniques to deeply understand real building operation and identify potential building faults.
The techniques are divided into three action areas, related to building characteristics, energy systems, and occupants’ behaviour



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

- **Notebook a_Ventilation_diagnosis** - CO2 concentration above 1000ppm.
- **Notebook b_Airtightness_diagnosis** - CO2-based decay method.
- **Notebook c_Unsupervised_load_disaggregation** - Load disaggregation through non-intrusive load monitoring (NILM). 
- **Notebook d_Thermostat_Control_Diagnosis** - Evaluation of the heating system working at full-load and partial-load operation.
- **Notebook e_Lighting_system_diagnosis** - Percentage of time in which lighting is on in unoccupied spaces.
- **Notebook f_Discrepancies_occupancy_operation** - Percentage of time in which fixed building/HVAC operating schedules don’t match with occupancy.


## The directory structure
------------

The directory structure of POE_techniques project looks like this: 

```
POE_techniques/
│ 
├── LICENSE 				<- MIT licence
├── README.md
├── requirements.txt   			<- The requirements file for reproducing the analysis environment
│          		
├── notebooks				<- Jupyter notebooks to guide the workflow 	
│   ├─ a_DataExtraction_Netatmo.ipynb        		
│   ├─ b_DataPre-processing.ipynb 
│   ├─ c_DataAnalytics_Preparatory.ipynb 
│   ├─ 04_DataAnalytics_HourlyDiagnosis.ipynb 
│   ├─ 05_DataAnalytics_AnnualDiagnosis.ipynb     		
│             		
├── data/				<- Monitoring data of a university building in the UK (Oxford)
│   ├─ *.csv files
│       
└──
```
