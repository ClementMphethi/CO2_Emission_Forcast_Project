![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

<div id="main image" align="center">
  <img src="https://github.com/marcmarais/2401FTDS_Regression_Project/blob/main/agri_image.png" width="450" height="300" alt=""/>
</div>

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>
Introduction:
Our team, consisting of environmental consultants and data scientists, has been commissioned by a coalition of stakeholders within the agricultural sector. These stakeholders include policymakers, agricultural businesses, and environmental organizations.

Objective:
Our primary goal is to conduct an in-depth analysis and prediction of CO2 emissions originating from the agri-food sector. This analysis is crucial for understanding the correlation between agricultural activities and climate change. Additionally, we aim to develop sustainable strategies to mitigate the environmental impact of these activities.

Dataset:
We are utilizing a comprehensive dataset obtained from two key entities: the Food and Agriculture Organization (FAO) and the Intergovernmental Panel on Climate Change (IPCC). This dataset serves as the basis for exploring various emission sources, conducting regression analysis to forecast temperature variations, and deriving actionable insights for stakeholders.

Deliverables:
Upon completion of the project, we expect to achieve the following outcomes:

Gain a thorough understanding of the relationship between agricultural activities and CO2 emissions.
Develop sustainable practices to alleviate adverse environmental effects.
Present actionable insights and recommendations tailored to policymakers, agricultural businesses, and environmental organizations.
Impact:
The insights and recommendations generated from this project are anticipated to make significant contributions to ongoing efforts aimed at promoting sustainability within the agri-food sector. By offering valuable insights into the environmental consequences of agricultural practices, our project aims to empower stakeholders to make informed decisions and catalyze positive change towards a more sustainable future.

## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset utilized in this project focuses on emissions from the agri-food sector, which play a pivotal role in climate change due to their significant contribution to global annual emissions. Understanding and addressing the environmental impact of the agri-food industry is essential for mitigating climate change and fostering sustainable practices within this sector.

Importance of the Dataset
Emissions from the agri-food sector represent a substantial share of global annual emissions. This dataset sheds light on the significant contribution of various sources of emissions within this sector, highlighting the urgency of understanding and addressing their environmental impact.

Data Sources
The data for this analysis is sourced from two reputable organizations:

Food and Agriculture Organization (FAO): Provides comprehensive data on agricultural activities and emissions.
Intergovernmental Panel on Climate Change (IPCC): Offers authoritative information on climate change and its impacts.
Coverage
The dataset covers CO2 emissions from a wide range of agricultural activities, providing a comprehensive view of the environmental footprint of the agri-food sector.

Purpose
The primary purpose of utilizing this dataset is to:

Analyze the emissions from various agricultural activities.
Understand the environmental impact of the agri-food industry.
Inform decision-making and policy development aimed at promoting sustainability within this sector.
Conclusion
By leveraging data from reputable sources such as the FAO and IPCC, this dataset serves as a valuable resource for gaining insights into the environmental implications of agricultural practices. Understanding these emissions is crucial for implementing effective strategies to mitigate climate change and foster sustainable practices within the agri-food sector.

**Dataset Features:**
- Savanna fires: Emissions from fires in savanna ecosystems.
- Forest fires: Emissions from fires in forested areas.
- Crop Residues: Emissions from burning or decomposing leftover plant material after crop harvesting.
- Rice Cultivation: Emissions from methane released during rice cultivation.
- Drained organic soils (CO2): Emissions from carbon dioxide released when draining organic soils.
- Pesticides Manufacturing: Emissions from the production of pesticides.
- Food Transport: Emissions from transporting food products.
- Forestland: Land covered by forests.
- Net Forest conversion: Change in forest area due to deforestation and afforestation.
- Food Household Consumption: Emissions from food consumption at the household level.
- Food Retail: Emissions from the operation of retail establishments selling food.
- On-farm Electricity Use: Electricity consumption on farms.
- Food Packaging: Emissions from the production and disposal of food packaging materials.
- Agrifood Systems Waste Disposal: Emissions from waste disposal in the agrifood system.
- Food Processing: Emissions from processing food products.
- Fertilizers Manufacturing: Emissions from the production of fertilizers.
- IPPU: Emissions from industrial processes and product use.
- Manure applied to Soils: Emissions from applying animal manure to agricultural soils.
- Manure left on Pasture: Emissions from animal manure on pasture or grazing land.
- Manure Management: Emissions from managing and treating animal manure.
- Fires in organic soils: Emissions from fires in organic soils.
- Fires in humid tropical forests: Emissions from fires in humid tropical forests.
- On-farm energy use: Energy consumption on farms.
- Rural population: Number of people living in rural areas.
- Urban population: Number of people living in urban areas.
- Total Population - Male: Total number of male individuals in the population.
- Total Population - Female: Total number of female individuals in the population.
- total_emission: Total greenhouse gas emissions from various sources.
- Average Temperature °C: The average increasing of temperature (by year) in degrees Celsius,
 

CO2 is recorded in kilotonnes (kt): 1 kt represents 1000 kg of CO2.

The feature "Average Temperature C°", represents the average yearly temperature increase. For example, if it is 0.12, it means that the temperature in that specific location increased by 0.12 degrees Celsius.

Forestland is the only feature that exhibits negative emissions due to its role as a carbon sink. Through photosynthesis, forests absorb and store carbon dioxide, effectively removing it from the atmosphere. Sustainable forest management, along with afforestation and reforestation efforts, further contribute to negative emissions by increasing carbon sequestration capacity.

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ 'Pandas': '2.0.3'
+ 'NumPy': '1.25.2'
+ 'Seaborn': '0.13.1'
+ 'Matplotlib': '3.7.1'  
+ 'Scikit-Learn': '1.2.2'
+ 'StandardScaler': '1.2.2'
+ 'MinMaxScaler': '1.2.2'
+ 'DecisionTreeRegressor': '1.2.2'
+ 'RandomForestRegressor': '1.2.2'
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```

### 5. For more details, visit our [official documentation](https://www.canva.com/design/DAGHMUbHnZA/M5yVzz4u19-BW0DakU7kKA/edit?utm_content=DAGHMUbHnZA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## 6. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| [Keneilwe Madihlaba](https://github.com/Madihlabakeneilwe)                                  |keneilwemadihlaba@gmail.com
| [Clement Mphethi](https://github.com/HoOdpHarMxcisT)                                        |clementmphethi@gmail.com
| [Carroll Tshabane](https://github.com/carrolltshabane)                                      |ctshabane@gmail.com
| [Charlotte Dimpho Lebea](https://github.com/DimphoLebea28)                                  |dimpholebea28@gmail.com
| [Lebogang Malata](https://github.com/LebogangMalata)                                        |Mich.malata@gmail.com
| [Thobile Mvuni](https://github.com/ThobMvuni)                                               |thoyomvuni@gmail.com
