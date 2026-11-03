## Weather Mappers: Exploring Global Weather with NOAA GHCN-Daily Data

Authors:
Brianna Senchyna, Jennie Le

### Description:
Weather conditions such as temperature, precipitation, and snowfall vary across location and time. In this project, we will perform exploratory data analysis (EDA) on data collected from the NCEI NOAA, a federal agency that manages environmental data. We will compare data across 3 stations (Dublin, Toronto, and San Jose) and track the conditions from 2013 to 2025. Graphs, tables, and other statistical analysis will be used to explore the relationships between weather variables in relation to season, location, and year. This will provide key information about changes in weather trends and potential insight on future patterns.

### Interface Plan:
- We will create a Jupyter notebook and a dashboard.
- The notebook will walk through our data cleaning and analysis step by step.
- The dashboard will let viewers explore our findings.

### Data Collection and Storage Plan:
Our weather data comes from NOAA's GHCN-Daily dataset. We read the yearly files directly from the NOAA website into pandas and keep only the measurements we need such as temperature and precipitation. We also keep the station metadata (which includes name, location and elevation) for our 3 stations in a separate small file. Each yearly file is loaded straight into memory, so no raw data is stored. We plan to clean and reshape the data and store it as a CSV file in the Github repo under data/.

### Data Analysis and Visualization Plan:
- Identify weather condition features (ex: max temperature, precipitation) that are most relevant across the stations and years and minimize missing data
- Apply statistical concepts such as calculating mean, median, standard deviation of conditions. Performing hypothesis testing to determine significant weather of different years and stations for seasonal months.
- Creating graphs (histograms, boxplots, line plots, etc.) to identify distributions and possible relationships between condition variables
- Combine key analysis and visualization to create a dashboard that summarizes the bigger picture for weather conditions

