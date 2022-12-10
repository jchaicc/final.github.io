Final Project Proposal
================
Jingchen Chai(jc5929), Wenjia Zhu(wz2631), Ruihan Zhang(rz2614), Yifei
Zhao(yz4433), Chenyao Ni(cn2604)

## **Factors Influencing Sleeping Duration**

## Motivation of our project

Adults should sleep 7 or more hours per night on a regular basis to
promote optimal health. However, more than one-third of the US
population gets less than the recommended amount of sleep. Sleep is a
necessary physiological process for individuals, interacting with
several economic, social and physical factors, influencing risks of
multiple health problems. Therefore, based on NHANES dataset, we focus
on sleep-related public health issues to carry out our research, hoping
to popularize the significance of adequate and healthy sleep, arousing
the public’s health awareness of improving sleep quality and obtaining
adequate sleep duration. We also want to visualize and discuss the
biological, economic and social factors interacting with sleep,
informing the public and healthcare providers on the importance of
advocating public policy to promoting the nowadays sleep situation and
overall public health.

## Intended Final Project

A report analyzing the prevalence of insufficient sleep in relation to
socioeconomic and physiological factors, and an interactive panel to
predict the risk of insufficient sleep for individuals.

## Anticipated Data Resources

We plan to utilize data from the
[CDC](https://www.cdc.gov/sleep/data-and-statistics/adults.html)
website. The data are based on the Behavioral Risk Factor Surveillance
System (BRFSS) survey. The data we are using are the age-adjusted
prevalence of adults aged greater than 18 who reported short sleep
duration varied by state from 2016 to 2020. We plan to focus on the
states, and create maps of the age-adjusted prevalence among different
states for each year.

The second data set we will use is a [questionnaire sleeping
data](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/SLQ_J.htm) and also the
date related with their
[demographic](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/DEMO_J.htm)
information, both comes from the
[NHANES](https://www.cdc.gov/nchs/nhanes/index.htm) website. Our final
dataset that we will be using will be based on the above datasets by
joining them together.

The third data set is [PLACES: Census Tract
Data](https://catalog.data.gov/dataset/places-census-tract-data-gis-friendly-format-2020-release-fb1ec).

## The planned analyses / visualizations / coding challenges

We plan to start from a map GIF image, which illustrates prevalence of
short sleep duration among US adults by state from 2016 to 2020.

For NHANES datasets, firstly, We can simply build a linear model between
sleep disorder factors and length of sleep, and from this model we could
briefly obtain the sleep length with sleep behavioral factors. Secondly,
we classify the people into two groups by length of sleep, people with
sufficient sleep and people with insufficient sleep. We plan to use
scatterplot and barplot to show the basic features of sleep conditions
of the data. Thirdly, after joint with other datasets, we could discover
the correlation among sleep conditions and social economic factors using
bubble charts and heatmap.

As for PLACES: Census Tract Data, we focus on the key variables like
countyname, (disease name)\_crudeprev, sleep_crudeprev, sleep_crude95ci,
geolocation and totalpopulation. Visulization method will include
Leaflet for mapping with sleepcrude values and populationcount,
correlation plots among sleep figures and other disease values, and
linear model for such factors.

The coding challenges are mainly from tidying data and do further
manipulation like aggregating and creating linear models, since some
values are missing, undefined or ourliers, and the models maybe
irrational if it is simply based on subjective factors.

## Timeline

| Date      | Task                                             | Due                |
|:----------|:-------------------------------------------------|:-------------------|
| Nov.4     | Brainstorm                                       | NA                 |
| Nov.11    | Finish draft proposal                            | NA                 |
| Nov.12    | Submit formal proposal                           | Nov 12 by 1:00 pm  |
| Nov.15    | Assign tasks                                     | NA                 |
| Nov 15-18 | Project review meeting                           | Nov 15-18          |
| Nov.30    | Finish coding part                               | NA                 |
| Dec.6     | Construct website                                | NA                 |
| Dec.9     | Report & Webpage and screencast & Peer asessment | Dec 10 by 11:59 pm |
| Dec.13    | Presentation practice                            | NA                 |
| Dec.15    | In class discussion                              | Dec 15 by 11:59 pm |
