 # EXAMINATION OF VEHICLE EMISSIONS AND IMPACT ON CLIMATE (Project 2)

This repository, developed to share documentation and code related to UNCC/UNC Chapel Hill AI Bootcamp Project 2 (Group 4), contains the source data, approach, algorithms and key findings related to an examination of the climate impact of individual and market adoption of light-weight electric vehicles.

## PROJECT OBJECTIVE
To examine the climate impact of individual and market adoption of light-weight electric vehicles through exploration of vehicle lifecycle emissions, light-duty vehicle sale trends, vehicle stock and EV adoption outlook, projected vehicle efficiency changes, key climate policies and current climate science. 


## APPROACH

![Approach grahic](/Images/UNC-UNCCH_Project_2_Group_4_Approach.png)

Modeling for this project was conducted in three parts:
1) Vehicle Lifecyle Emissions
2) Climate Change Impacts
3) 100% EV Adoption Scenario


### 1 - Vehicle Lifecyle Emissions 
* **Datasets** examined and explored in our modeling and analysis are compiled in the _Resources_ folder and read in to the _project_datasets.ipynb_ file along with additional data read in from html. Dataset descriptions, including links to documentation and data transformation notes, are available within the _project_datasets_ notebook. 

* **Analytical and machine learning models** used to determine emissions from individual vehicles by type and vehicle sales and stock projections by vehicle class over time  may be found in the _vehicle_and_emissions_analysis.ipynb_ file.

* **Instructions:** To run these models simply run the _vehicle_and_emissions_analysis.ipynb_ file. Running this notebook will also automatically run the _project_datasets.ipynb_ notebook to pull in the needed variables and dataframes used. 
 

### 2 - Climate Change Impacts 
* **Datasets** used to conduct modeling for the climate change impacts analysis are compiled in the _Resources_ folder and read in to the _elliots_filename_. 

* **Analytical and machine learning models** used to show the correlation between global carbon concentration and global temperature deviations from the mean global temperature, the contributions of individual vehicles by type to those deviations, and the estimated ICEV to BEV transition required are available in _elliots_filename_. This notebook uses the ICEV, PHEV and BEV lifecycle emission values from the _vehicle_and_emissions_analysis_.

* **Instructions:** To run these models simply the _elliotsfilename_ file. Running this notebook will also automatically run the _vehicle_and_emissions_analysis.ipynb_ notebook to pull in the need variables and dataframes used. 


 ### 3 - 100% EV Adoption Scenario
* **Datasets** used to conduct modeling for the 100% EV adoption analysis are compiled in the _Resources_ folder and read in to the **_jasons_filename__**. 

* **Analytical and machine learning models** used to determine the CO2 emissions saved by 100% EV adoption in the US may be found in the _jasons_filename_ file.

* **Instructions:** To run this models run the _jasons_filename_ file.  
 


## SUMMERY FINDINGS
Analyses and modeling revealed that the lifecycle carbon emissions, using 2023 data, for ICE, PHEV and BEV were 46.1, 42.2 and 27.2 million metric tons of CO2, respectively, and every BEV that displaces an ICEV to a BEV avoids 1.41 x 10^-12 °C of deviation from the global temperature mean -- temperature changes that fuel climage change impacts. We also noted that 100% EV adoption from 2025 to 2050 would avoid 733,200,000 metric tons of CO2 annual (approximately 73% of the emissions from burning coal in the US in 2023 or only 9% of the coal emissions from world's the largest coal consumming country, i.e., China.) 

See the associated _UNC_AI_Bootcamp_Project_2_Presentation.pdf_ file for addional context.

## ADDITIONAL REFERENCE CONTENT
### Python Libraries
Libaries used to conduct these analysis include 
* numpy
* pandas
* matplotlib
* sklearn
* statsmodels
* requests
* json
* os
* datetime

### Project Contributors
* Jamie Bond | [GitHub @JBondAI](https://github.com/jbondAI/) 
* Jason Campbell | [GitHub @JCamp-12](https://github.com/jcamp-12/)
* Elliot Sancrant | [GitHub @ElliottSancrant](https://github.com/ElliottSancrant/)

## Other Acknowledgments
* Project instruction and requirements provided by [The Artificial Intelligence Boot Camp at UNC Charlotte](https://bootcamp.charlotte.edu/artificial-intelligence/)

