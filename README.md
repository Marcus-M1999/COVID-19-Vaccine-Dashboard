COVID-19 Vaccine Dashboard
======


Summary
-------


Everything changed when COVID-19 Pandemic began. After spending billions of dollars over a year we were finally able to develop and test COVID-19 Vaccines, we were finally able to release them in mass to the public. This was only the beginning, however, as now we have to distribute the vaccines to millions of people. This prompted us to ask the following questions: How do we know if the Vaccine is being distributed equitably? How can we improve the efficiency of the vaccine supply chains? How can policymakers, vaccine distributors, and others without a technical background discover this information?


To answer these questions we created our COVID-19 Vaccine dashboard. Through analyzing data from various sources including the California COVID-19 tracker, Carnegie Mellon, and numerous county-level resources we were able to uncover several interesting patterns in the data and visualize them in an easy-to-understand Tableau dashboard. Since we conducted our analysis through python and Tableau all of our materials are open source and publicly available to use and improve upon. We hope that our dashboard will prove useful to professionals and amateurs alike in informing them on the inequities in vaccine distribution and inspire solutions to be created.


Project Components
-------


##### 1.) Data collection
We began to collect data at various levels, however after discussing and reinventing our dashboard we decided to collect county-level data for the following reasons: it was available, it was at a low enough level to show trends while being statistically significant and without normalizing the data and losing the trends. Once we decided on the level of data to collect we had to decide on the kind of visualizations to make. We planned on having multiple heatmaps to show the vaccination rates in comparison to other factors such as race, gender, and education.


We collected our data from a variety of sources including California state, county, and city-level databases, as well as non-profit organizations such as studies from Carnegie Mellon University. We collected data from all counties in California, and despite encountering setbacks with differences in reporting depending on the region we were able to collect enough data to sufficiently analyze the vaccine distribution.


##### 2.) Exploratory data analysis
Once we had the data we began the EDA process which included data cleaning and making some initial observations. We began to merge the data frames and compile all of the relevant data for race, education, gender, age, and income into one dataset that we could use to analyze the vaccine distribution. For each variable, we attained the relevant geospatial data to create a heatmap. After the initial visualizations were made we began to compile everything into a Tableau dashboard and refine them.


##### 3.) Tableau
We used Tableau as the main tool to show our analysis because it allowed us to show our visualizations in a visually appealing and simple way. We used the data collected from the previous step to create the visualizations and gradually refined them after discussing them with our group members and our mentors. As we were redesigning the visualizations we decided to create a correlation matrix to better visualize how the variables affect each other and the vaccination rate.


##### 4.) Blogging
As we were nearing the end of our project we decided to create a blog to document our experiences in the class and any surprising discoveries. We hope that the blog will inspire future students and users of the dashboard to make improvements by blogging their discoveries.


How our Solution works
-------
##### 1.) Download or view our workbook
You can download our Tableau workbook from our Tableau public link [here](https://public.tableau.com/profile/stanford.anwar?fbclid=IwAR0JHYLfXN40Y7VxUU4FyNybsEStLSTzJkAd-_l7VAkidHWNvy25Jz3dRB8#!/vizhome/COVID-19DashboardFinal/StatewideGeneralCaseStatistics). If you do not wish to download the workbook you can look at it through the Tableau public website instead.


##### 2.) Clone our Github Repository
Clone our repository found [here](https://github.com/Marcus-M1999/COVID-19-Vaccine-Dashboard.git). This will give you access to all of the datasets we used in creating this dashboard, and allow you to edit the dashboard.


##### 3.) Download Tableau (optional)
If you want to use tableau in the workbook then you need to have it installed. Once Tableau is downloaded make sure to connect the data source to all of the CSV files in the Final Dashboard folder in Github. If you’re new to Tableau you may want to consider checking out [this](https://help.tableau.com/current/guides/get-started-tutorial/en-us/get-started-tutorial-home.htm) tutorial. Skip this step if you just want to look at our dashboard through Tableau public.
##### 4.) Making changes
You can make changes to any of the sheets in the Tableau workbook by clicking on the sheets at the bottom of the Tableau window and editing the visualizations. In addition, you can connect additional data sources if there is other data you wish to analyze. We encourage you to play around with the workbook and publish your results with a summary of any interesting information you found in the process.


File Hierarchy
-------
Our file structure is broken down below:
Collab Workbook
This folder contains our Google Collab notebooks in the form of a jupyter notebook file. The following files are included in this folder:

    - Data Cleaning(Delphi).ipynb
    - Data Cleaning (Race).ipynb
    - Data Cleaning + EDA.ipynb


Final Dashboard
This folder contains all of the necessary files to download and run our Collab notebook, including the CSV files and Tableau workbook files.

    - COVID-19 Dashboard Final.twb
    - VEM.csv
    - Age_time_cleaned.csv
    - Norm.csv
    - Race_timeseries.twb
    - Timeseries_cleaned.csv


##### Data
The data folder contains our data files in the following sub folders:

##### Alameda
This folder contains the following files:
    
    - Alameda_County.csv
##### Santa Clara County
This folder contains the following files:

    - Deaths_with_COVID-19_by_race_ethnicity.csv
    - Deaths_with_COVID-19_by_gender.csv
    - Deaths_with_COVID-19_by_age_group.csv
    - COVID-19_vaccinations_among_county_residents_by_gender.csv
    - COVID-19_testing_by_date.csv
    - COVID-19_cases_by_method_of_transmission.csv
    - COVID-19_cases_by_gender.csv
    - COVID-19_cases_by_city_of_residence.csv
    - COVID-19_cases__tests_and_positivity_rate_over_time_by_zip_code.csv
    - Count_of_deaths_with_COVID-19_by_date.csv
##### Statewide
This folder contains the following files:

    - Ab5df872-5a84-4839-9199-f0174239e4e6.csv
    - c341576f-90d2-41ec-bdb1-a4e69f40e6a3 (2).csv
    - Cases_by_age_group.csv
    - Cases_by_race_ethnicity__all_age_groups.csv
    - Cases_by_sex__all_age_groups.csv
    - Covid19_vaccinations_in_long_term_care_facilities.csv
    - Covid19_vaccinations_in_the_united_states.csv
    - COVID-19_Vaccine_Distribution_Allocations_by_Jurisdiction_-_Moderna.csv
    - COVID-19_Vaccine_Distribution_Allocations_by_Jurisdiction_-_Pfizer.csv
    - Covid19vaccinesbycountybydemographic.csv
    - Deaths_by_age_group.csv
    - Deaths_by_race_ethnicity__all_age_groups.csv
    - Deaths_by_sex__all_age_groups.csv
    - Gender_data.csv
    - odp_hcp_flu_vaccination_by_county_2018-19_season_final (1).csv
    - Road Condition.csv





