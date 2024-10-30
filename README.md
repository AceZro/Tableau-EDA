Project Overview
In this project, an Exploratory Data Analysis (EDA) was conducted on the Global Terrorism dataset in Python before dashboard creation in Tableau. The goal of the project is to deliver data-driven insights and patterns about terrorism incidents worldwide, offering a clear, interactive, and informative interface for users.

The challenge focuses on:

Data Visualization: Creating intuitive and informative visuals
Dashboard Design: Clear layout, color consistency, and a well-organized structure
User Interactivity: Interactive filters and navigation for better user experience
Data Cleaning and Transformation: Pre-processing data to ensure accuracy and clarity
Dataset Description
The Global Terrorism Database (GTD) is an open-source database that provides detailed information on global terrorism incidents from 1970 onward. It includes data points such as incident type, location, year, attack type, target, weapon used, and the number of casualties.

Dataset source: Global Terrorism Database (GTD)

Key Attributes Used:

Incident Date: Year and month of each incident
Location: Country and city where the incident took place
Attack Type: Type of attack (e.g., bombing, armed assault)
Target Type: The primary target category (e.g., civilians, government)
Weapon Type: Weapon used in the incident
Casualties: Number of fatalities and injuries

Project Workflow
Data Preparation and Cleaning: The dataset was cleaned in Python to address missing values, remove inconsistencies, and transform data for improved dashboard accuracy.
Exploratory Data Analysis (EDA): EDA was performed to gain insights into the dataset’s structure, identify patterns, and determine areas of focus.
Dashboard Design and Visualization: Based on EDA results, key insights were visualized in an interactive dashboard in Tableau.
Interactivity and User Experience: Filters and tooltips were added to enhance user interactivity, allowing users to explore specific countries, years, or attack types.

Dashboard Highlights
The Tableau Dashboard covers the following insights:

Global Trends: Overview of global terrorism trends over the years
Country-Specific Analysis: Incidents, targets, and attack types by country
Incident Distribution: Heatmap of incidents by region and country
Casualty Analysis: Total fatalities and injuries over time and by attack type
Most Affected Regions and Attack Types: Highlighted areas most impacted by terrorism
Features and Visualizations
Time Series Analysis: Visualizing incident trends over time to identify peak periods of terrorist activities.
Heat Maps and Geographic Representation: Displaying incidents by location for regional analysis.
Bar Charts and Stacked Visualizations: Showing attack types and target distributions for comparative insights.
Filters and Interactive Tooltips: Enabling users to drill down by year, location, and attack type for deeper insights.

Setup and Usage
Prerequisites:

Tableau Desktop or Tableau Public for dashboard interaction (if modifying)
Python environment with libraries for data processing (Pandas, NumPy)

Data Preparation:

Clean and process the dataset in Python (scripts provided in data_processing.py).

Dashboard File:

Open the Tableau file (Global_Terrorism_Dashboard.twb or Global_Terrorism_Dashboard.twbx) in Tableau to interact with the visualizations.

View the Dashboard:

Link to Tableau Public (if published online)
Or, download and open the file in Tableau for offline access
