# CO2 and pollutant emissions from vehicles sold in France
This README provides an overview of the data analysis conducted on the Car Labelling dataset from ADEME France. The analysis focuses on understanding vehicle characteristics, cleaning and preprocessing the dataset, performing exploratory data analysis (EDA), identifying patterns through clustering, and building predictive models for CO2 emissions. The study highlights how fuel type, vehicle mass, engine power, gearbox, and body type relate to fuel consumption and environmental impact.

# Dataset Description

The dataset was loaded from the file:

cl_JUIN_2013-complet3.csv

It contains 44,850 vehicle records and includes information on a wide range of vehicle specifications and environmental indicators. After renaming the original French columns into English, the main variables used in the analysis included:

* Brand: Manufacturer of the vehicle
* Folder Model: Vehicle model grouping
* Fuel: Fuel or energy type
* Hybrid: Indicates whether the vehicle is hybrid
* Administrative Power: Fiscal horsepower
* Maximum Power (kW): Engine power in kilowatts
* Gearbox: Transmission type
* Urban / Extra Urban / Combined Consumption (l/100km): Fuel consumption measures
* CO2 (g/km): Carbon dioxide emissions
* CO type 1 (g/km), HC (g/km), NOX (g/km), HC+NOX (g/km), Particles (g/km): Pollutant emissions
* Empty Mass Euro Min / Max (kg): Minimum and maximum empty mass
* Body: Vehicle body type
* Range: Vehicle segment

A new feature, Empty Mass Euro Avg (kg), was created by averaging the minimum and maximum empty mass values.

# Technology Stack

The analysis was conducted in Python using the following tools and libraries:

**Python:** Core language for analysis
**Pandas:** Data loading, cleaning, transformation, and summarization
**NumPy:** Numerical operations
**Matplotlib and Seaborn:** Data visualization
**Scikit-learn:** Clustering and predictive modeling
**Google Colab:** Execution environment with Google Drive integration

# Exploratory Data Analysis (EDA)

-Examination of how different energy types are represented across vehicles.  
-Analysis of the distribution of vehicle manufacturers in the dataset.  
-Investigation of engine power–related variables.  
-Evaluation of CO₂ emission levels and their patterns.  
-Exploration of the relationships between vehicle weight, engine power, fuel consumption, and emissions.  
-Application of clustering methods to detect potential groupings based on vehicle weight and fuel consumption.   

# Key Findings
Some key findings from the analysis include:  

The distribution of energy types showed a significant presence of diesel and gasoline vehicles.  
Certain vehicle brands were more prevalent in the dataset.  
Power-related variables exhibited various distributions and relationships.  
CO2 emissions varied across different vehicle brands and energy types.  
One noteworthy observation is the strong correlation between weight and both consumption and CO2 emissions. Heavier vehicles tend to have higher consumption and emissions, emphasizing the importance of vehicle weight in environmental impact assessments.
