>## [enhanced COVID-19 project](https://github.com/victorlifan/projects_review/tree/master/COVID-19%20project)

## Project Title
COVID_19 Data Analyzation and Prediction

## by Fan Li

## Date created
Project is created on March 16th 2020.


## Description
With 168,019 confirmed cases and 6,610 deaths, 148 countries were affected (by March 17th) by the Coronavirus disease. The outbreak has gone way beyond what we expected. This pandemic caused WHO (World Health Organization) to raise the health emergency to its highest level along with many more countries' top emergency warnings. This project is targeted to briefly analyze the COVID-19 outbreak in the United States with some comparison against China (worst hit area) along with a rough prediction of the spreading trend.

Workflow:
+ Data Gathering
+ Data Cleaning
+ Univariate Exploration
+ Bivariate Exploration
+ Multivariate Exploration
+ Prediction


## Dataset

[`csse_covid_19_data`](https://github.com/victorlifan/COVID_19-data-analyze-and-prediction/tree/master/csse_covid_19_data)

 Data set is operated by the Johns Hopkins University Center for Systems Science and Engineering ([`JHU CSSE`](https://github.com/CSSEGISandData/COVID-19)). Also, Supported by ESRI Living Atlas Team and the Johns Hopkins University Applied Physics Lab (JHU APL). I extracted 2,989 records in total, 1,715 records in China and 1,274 records in the U.S. Information is recorded from 2020 Jan 22nd until 2020 Mar 16th.

 ## Summary of Findings

 > Univariate Exploration
 + The plot shows the virus on record is between (-160, -65) in longitude and between(20,65) in latitude. More specifically, there are two humps in the Longitude distribution plot, they reflect more cases on both coasts. On the other hand, there is significantly high volume in the latitude plot which occurs around 40 to 45 latitude. This points to WA, Northern CA, OR and Northern east coast states around NY.

 > Bivariate Exploration
 + Northeastern and Northwestern states have the most cases reported. Top four significant states are WA, NY, CA and MA. WA has the most dead cases while KS has the highest fatality rate on average. CA has the most recovered cases so far while AZ has the top recovery rate on average.

 > Multivariate Exploration
 + Giving the same frame of time the virus is spreading faster in the U.S. than in China at this moment. Scatter plot show a relationship between total Recovered and total Deaths within two countries. The steeper slope is the more people recovered than died. Fortunately both countries showing a higher average recovery rate than average fatality rate.


 ## Key Insights for Presentation

 > Infected numbers prediction (15 days frame)
 + Max confirmed cases would likely be around 37,774, and 15 days from Mar 16th which is Mar 31st, confirmed cases might reach over 30,000.

 ## About
###### Cleaned data :
+ [`df.csv`](https://github.com/victorlifan/COVID_19-data-analyze-and-prediction/blob/master/csse_covid_19_data/df.csv): Wrangling result, ready to analyze data in csv file.

###### Action codes:
 + [`COVID_19 data analyzation and prediction exploration.ipynb`](https://github.com/victorlifan/COVID_19-data-analyze-and-prediction/blob/master/COVID_19%20data%20analyzation%20and%20prediction%20exploration.ipynb):
 Codes for gathering, assessing, cleaning, analyzing, and visualizing data.
 + [`COVID_19 data analyzation and prediction presentation.ipynb`](https://github.com/victorlifan/COVID_19-data-analyze-and-prediction/blob/master/COVID_19%20data%20analyzation%20and%20prediction%20presentation.ipynb):
 Codes for converting ipynb file to slides shows.

###### Report: [`presentation`](https://github.com/victorlifan/COVID_19-data-analyze-and-prediction/tree/master/presentation)
 + Action ipynb codes in HTML format.


## Software used
+ Jupyter Notebook
+ Python 3.7
> + Pandas
> + Numpy
> + Matplotlib
> + Seaborn
> + scipy

+ WPS 2019


## Credits
+ Data provided by:
    + [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
+ Instruction and assist: [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
+ [COVID-19 in US and Canada](https://coronavirus.1point3acres.com/en)
+ [2020年冠状病毒肺炎 - 武汉加油 使用Logistic增长模型预测确诊病人数目](https://blog.csdn.net/qq_26822029/article/details/104213781)
+ [Exponential & logistic growth](https://www.khanacademy.org/science/biology/ecology/population-growth-and-regulation/a/exponential-logistic-growth)
+ [Novel Coronavirus (COVID-19) Situation](https://experience.arcgis.com/experience/685d0ace521648f8a5beeeee1b9125cd)
