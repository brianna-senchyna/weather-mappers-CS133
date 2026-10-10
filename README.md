## Weather Mappers: Exploring U.S. Weather with NOAA GHCN-Daily Data

Authors: 
Brianna Senchyna, Jennie Le

### Description:
Weather conditions such as temperature, precipitation, and humidity vary across location and time. In this project, we will perform exploratory data analysis (EDA) on data collected from the 
NCEI NOAA, a federal agency that manages environmental data. We will compare California data across 3 stations and track the conditions in 3 randomly selected 2-year intervals. Graphs, tables, and other statistical analysis will be used to explore the relationships between weather variables in relation to season, location, and year. This will provide key information about changes in CA weather trends and potential insight on future patterns. 

### Interface Plan: 
- We will create a Jupyter notebook and a dashboard. 
- The notebook will walk through our data cleaning and analysis step by step. 
- The dashboard will let viewers explore our findings.

### Data Collection and Storage Plan:
Our weather data comes from NOAA’s GHCN-Daily dataset. We download the yearly files directly from the NOAA website in Python using urllib, read them into pandas and keep only the measurements we need such as temperature and precipitation. We then merge in the station metadata (which includes name, location and elevation) on station ID. Each yearly file is downloaded to a temporary file that is deleted after loading, so no raw data is stored. We plan to clean and reshape the data and store it as a CSV file. Depending on the size, we will either upload it to the Github repo under data/, or we will add data/ to our .gitignore, along with instructions on how to download the data locally.

### Data Analysis and Visualization Plan:
- Identify weather condition features (ex: max temperature, precipitation) that are most relevant across the stations and years and minimize missing data
- Apply statistical concepts such as calculating mean, median, standard deviation of conditions. Performing hypothesis testing to determine significant weather of different years and stations for seasonal months.
- Creating graphs (histograms, boxplots, line plots, etc.) to identify distributions and possible relationships between condition variables
- Combine key analysis and visualization to create a dashboard that summarizes the bigger picture for weather conditions

