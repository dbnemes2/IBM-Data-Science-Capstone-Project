# IBM Data Science Capstone Project

Contained within this repository is the final project for the IBM Applied Data Science Capstone. The full presentation of the work can be found in the pdf presentation.
This readme serves as a concise summary of the steps taken during this work.

## Data Collection

The data was collected in primarily two ways. First was using spacex API calls, which can be found in:<br>
[2_spacex_data_collecton_webscraping.ipynb](2_spacex_data_collecton_webscraping.ipynb)
<br><br>
Second was using web scraping, as can be seein in:<br>
[2_spacex_data_collecton_webscraping.ipynb](2_spacex_data_collecton_webscraping.ipynb)
<br><br>


## Exploratory Data Analysis (EDA)

In this section of work, the data was explored using PANDAS, SQL queries, and initial data visualizations using matplotlib and seaborn
- [3_data_wrangling.ipynb](3_data_wrangling.ipynb)
- [4_EDA_visualization.ipynb](4_EDA_visualization.ipynb)
- [5_EDA_SQL.ipynb](5_EDA_SQL.ipynb)

Multiple informative plots from this EDA were made to gain a quick understanding of the data. One such example is launch site vs flight number, with the points colored based on success rate. Here you can see as time goes on more successful launches are made.<br><br>
![EDA_1](https://github.com/dbnemes2/IBM-Data-Science-Capstone-Project/assets/154485507/cc594b8c-04ea-4d7e-8453-453a6a0c4467)
<br><br>

## Advanced Visualization of Data

Following EDA, more advanced methods of reporting data was explored using interactive maps and creating an interactive dashboard.
- [6_FOLIUM_interactive_map.ipynb](6_FOLIUM_interactive_map.ipynb)
- [7_dashboard.py](7_dashboard.py)
<br>

One such example is a folium map showing the number of successful and failed launches for a single site, as can be seen below.<br><br>
![Folium2](https://github.com/dbnemes2/IBM-Data-Science-Capstone-Project/assets/154485507/6bf16825-1842-4a34-86d5-91c9a30a0b38)
<br><br>

## Machine Learning and Predictive Modeling

Finally, using the data provided four machine learning models were investigated to see how well we can model and predict the success of a launch based on the available features. <br>
[8_predictive_models.ipynb](8_predictive_models.ipynb)

The results of each model were compared against each other. Here below is one example, the confusion matrix for a simple logistic regression model.<br><br>
![Confusion_Matrix](https://github.com/dbnemes2/IBM-Data-Science-Capstone-Project/assets/154485507/1209192c-9702-4caf-a47c-2544abc37774)

