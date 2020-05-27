# Mapping of COVID-19 (coronavirus) data in USA, Statistical Analysis and Parametric Curve Fitting

Throughout this project, some notebooks were developed in order to study, through different parameters, the epidemiological situation of the coronavirus in The United States, one of the most affected countries by the virus.

## Dataset

The dataset used is part of a project called "COVID19 Tracking"(https://github.com/COVID19Tracking).


To facilitate data access and analysis, these datasets have been changed. The datasets used are in [Dataset](https://github.com/claudiarmabreu/Epidemologia/tree/master/Projeto%20Covid-19/Dataset).

## Notebooks

In this project, different Jupyter notebooks were developed:

🗂️ [Mapping Covid-19 number of cases, deaths and recovered in USA (.ipynb)](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Notebooks/COVID19-US-Maps.ipynb)

🗂️ [Statistics and Parametric Curve Fitting of Covid-19 in USA (.ipynb)](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Notebooks/COVID19-US-Stats.ipynb)



## Mapping


### Number of cases in Italy

This mao shows the distribution of the number of cases on each state of the USA.
Here it is possible to consult this map. [image](hhttps://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/number_cases.png)

![case map](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/number_cases.png)


## Statistical analysis

This notebook presents several statistical analysis regarding Covid19 in USA [notebook](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Notebooks/COVID19-US-Stats.ipynb)

In this notebook, it is possible to find many top 5 and bottom 5 plots of number of cases, number of deaths, number of recovered and many others.

The TOP 5 Cases are presented on this [figure]  (https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/Top5_cases.png)

The Bottom 5 Cases are presented on this [figure]  (https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/Bottom5_cases.png)

### NY vs NJ

This next plot presents a comparison between the two most affected states, NY and NJ.

![nynj](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/NY_NJ.png)



### Currently ventilated Cases

This pie chart shows the percentage of cases currently ventilated on each state: [Currently ventilated Cases](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/Ventilated.png).


### Evolution of number of cases in NY

This [plot] (https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/cases_NY.png) shows the evolution of the number of positive cases in the state of New York, the most affected state, over the days, since the beginnig of this pandemic.


### Evolution of number of recovered in NY

This [plot] (https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/Recovered_NY.png) shows the evolution of the number of recovered cases in NY.



## Parametric Curve Fitting

When using a forecasting model, it is possible, through a curve adjustment, to find the ideal combination of parameters, capable of minimizing errors.
Throughout the development of this Jupyter notebook, numerous [forecasting models](https://github.com/kika-nogueira97/Epidemologia/blob/master/Projeto_Italy/Notebooks/Italy_prevision.ipynb) have been developed.
In the figure below it is possible to see the number of deaths in Molise (black dots) and the three models (blue - logistic, light blue - exponential and dark blue-linear) that try to fit the Molise curve. With the observation of the model it is possible to verify that the exponential model is the most adequate.

![curve](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/PCF.png) 

Accordingly, it was also possible to find the ideal parameters for the four models.

![prediction](https://github.com/claudiarmabreu/Epidemologia/blob/master/Projeto%20Covid-19/Images/PCF2.png)


## Work made by

Ana Cláudia Abreu A80276 

Biomedical Engineering student in the Master of Medical Informatics
University of Minho


## Date

27/05/2020