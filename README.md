# 2401PTDS_Regression_Project

![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

<div id="main image" align="center">
  <img src="https://github.com/marcmarais/2401FTDS_Regression_Project/blob/main/agri_image.png" width="450" height="300" alt=""/>
</div>

# Table of contents
* [1. Introduction and Objectives](#project-description)
* [2. Dataset](#dataset)
* [3. Creating the Coding Enviroment](#packages)
* [4. Notebook Structure](#environment)
* [5. Team Members](#team-members)

## 1. Introduction <a class="anchor" id="project-description"></a>

Our dedicated team of environmental consultants and data scientists has been commissioned by a coalition of agricultural stakeholders to assess and forecast the impact of CO2 emissions from the agri-food sector on climate change. This coalition comprises policymakers, agricultural enterprises, and environmental organizations. Our initiative is focused on comprehensively understanding how agricultural practices contribute to climate change and formulating strategies for sustainable development. By leveraging an extensive dataset sourced from the Food and Agriculture Organization (FAO) and the Intergovernmental Panel on Climate Change (IPCC), we investigate various sources of emissions, conduct regression analyses to anticipate temperature fluctuations, and provide practical recommendations for our stakeholders.

##### Objectives
+ To apply exploratory data analysis.
+ To implement feature engineering techniques to extract meaningful information.
+ To model and assess various supervised machine learning algorithms for the prediction ....
  
## 2. Dataset <a class="anchor" id="dataset"></a>

Emissions from the agri-food sector play a crucial role in climate change, as they represent a significant share of global annual emissions. The dataset highlights the substantial contribution of the various sources of emissions. Therefore, it is essential to understand and address the environmental impact of the agri-food industry to mitigate climate change and promote sustainable practices within this sector.

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

## 3. Creating the Coding Enviroment <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
  
  ##### Creating the coding environment  
##### Step 1: Install Anaconda
This will install Python, Jupyter Notebook, and other useful packages.

##### Step 2: Create a New Environment
Open Anaconda Navigator: Launch Anaconda Navigator from your applications menu.
Create a New Environment:
Click on the “Environments” tab on the left.
Click the “Create” button.
Name your environment (e.g., Regression) and select the Python version you want to use.
Click “Create” to set up the environment.

##### Step 3: Activate the Environment
Activate via Anaconda Navigator:
In the “Environments” tab, select your new environment.
Click the “Play” button and choose “Open Terminal”.
Activate via Command Line:
Open your terminal (or Anaconda Prompt on Windows).
Type conda activate Avocado and press Enter.

##### Step 4: Install Jupyter Notebook
Install Jupyter Notebook:
In the terminal, type conda install jupyter and press Enter.
This will install Jupyter Notebook in your environment.

##### Step 5: Launch Jupyter Notebook
Launch via Anaconda Navigator:
Go to the “Home” tab.
Select your environment from the dropdown menu.
Click “Launch” under Jupyter Notebook.
Launch via Command Line:
In the terminal, type jupyter notebook and press Enter.
This will open Jupyter Notebook in your default web browser.

##### Step 6: Create a New Notebook
Create a New Notebook:
In the Jupyter Notebook interface, click “New” and select “Python 3” (or the version you installed).
This will open a new notebook where you can start coding.

##### Step 7: Install Additional Packages (Optional)
Install Packages:
In a code cell in Jupyter Notebook, you can install additional packages using !pip install package_name or !conda install package_name.

### This is how you activate the virtual environment in a terminal and install the project dependencies
```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```

## 4. Notebook Structure <a class="anchor" id="environment"></a>

##### Notebook Structure
 ##### Project Overview: 
Provides the introdution, problem statement, and objectives for the project. 

 ##### Importing packages:
Import packages for data visualization and analysis, data visualisation, regression and machine learning, and statistics. 

 ##### Loading data: 
The data used for this project was located in the 2401PTDS_REGRESSION_PROJECT folder on github. To better manipulate and analyse the co2_emissions_from_agri.csv file, it was loaded into a Pandas Data Frame using the Pandas function, `.read_csv()`. We defined the dataset using the df function and will be used throughout the notebook.

 ##### Cleaning data: 
Data cleaning is a crucial step in the data analysis process, involving the correction or removal of incorrect, corrupted, duplicate, or incomplete data within a dataset. Through various techniques such as filling missing values, removing outliers, and standardizing data formats, it ensures the accuracy and reliability of subsequent analyses and decision-making.

 ##### Exploratory Data Analysis (EDA):
To give a better understanding of the variables and the relationships between them, we set out to do an **Exploratory Data Analysis (EDA)** of our dataset. The main tasks includes investigating and summarizing the dataframe's main characteristics by data visualization methods and statistical analyses. Furthermore, investigating the dataset’s key features, summarizing its central characteristics, and employing both data visualisation techniques and statistical analyses to draw meaningful insights that can guide further research and data-driven decision making.

 ##### Feature Engineering

 ##### Modelling 
 We are preprocessing the data to later understand the relationship between various variables related to CO2 emissions in the agri-food sector and the increase 
 in temperatures, which will be our target for the Machine learning part of the project.

 ##### Conclusion 
 This section focuses on the insights and conclusion drawn from the Exploratory Data Analysis.

## 5. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| [Maphuthi Matsape                                                                           | maphuthimatsape@gmail.com 
| [Nomathemba Maphike                                                                         | namaphike@gmail.com
| [Jeanet Ramoshaba                                                                           | jeanetramoshaba@gmail.com
| [Mikateko Chauke                                                                            | mikaprudence@gmail.com
