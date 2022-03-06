# WA Public Sector Employee Perception Survey

***By Alex Lee***

### Description
<img align="right" src="/../main/Graphics/WA_Perth_Parliament.jpg" width="300" height="240"></img>

More and more global companies are embracing workplace gender diversity. Are the Australian public sectors the taking appropriate steps in reducing gender gaps? We know that female exmployees make up more than 50% of the total public service workforce at both state and federal levels. However, simply increasing women presence in the workplace is not enough: are women being paid the same to men doing the same amount of work? Are women treated fairly and respectfully in the workplace? Are women given the same career opportunities and development as men?

In this project, I analyzed the Public Sector Employee Perception Survey data conducted by the Western Australia Public Sector Commission in 2015, available in [this link](https://data.gov.au/data/organization/public-sector-commission-wa). Using the data, I examined if there are gender gaps in job satisfaction, salary and career opportunities within the WA public sector. This analysis could be useful for improving leadership, culture and diversity in the public sector, with the potential to boost productivity and promote ehtical decision making. You can see the exploratory data analysis in [SurveyData.ipynb](https://github.com/alex-cplee/WA-Public-Service-Perception-2015/blob/main/SurveyData.ipynb). 

The dashboard for the analysis can be found [here](https://github.com/alex-cplee/WA-Public-Service-Perception-2015/blob/main/PowerBI_dashborad.pbix?raw=true). You will need MS Power BI to open the file

### Analytical techniques
This project was generated using the Jupyter Notebook. Data was stored into a local MySQL server and relevant data was retrieved using SQL queries. Data cleaning was carried out using SQL queries and data visualisation and manipulation were carried out using Python and its libraries. 

Various methods were used, including ANOVA, Student's t-test, Pearson correlation analysis, hierarchical clustering and cronbach's alpha.

If you wish to rerun the notebook in your environment, make sure you have access to a local SQL server (or cloud SQL server, as long as you have connection to it) and the following libraries installed in Jupyter Notebook:

- ipython-sql
- pandas 
- numpy 
- matplotlib.pyplot
- seaborn as sns
- scipy 
- pingouin
