Final Project Proposal
================
Jingchen Chai, Wenjia Zhu, Ruihan Zhang, Yifei Zhao, Chenyao Ni

``` r
library(tidyverse)
```

    ## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.2 ──
    ## ✔ ggplot2 3.3.6      ✔ purrr   0.3.5 
    ## ✔ tibble  3.1.8      ✔ dplyr   1.0.10
    ## ✔ tidyr   1.2.0      ✔ stringr 1.4.1 
    ## ✔ readr   2.1.2      ✔ forcats 0.5.2 
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()

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

## Intended final project

A report analyzing the prevalence of insufficient sleep in relation to
socioeconomic and physiological factors, and an interactive panel to
predict the risk of insufficient sleep for individuals.

## Anticipated Data Resources

We plan to utilize data from the
[CDC](https://www.cdc.gov/sleep/data-and-statistics/adults.html)
website. The data are based on the Behavioral Risk Factor Surveillance
System (BRFSS) survey. The data we are using are the age-adjusted
prevalence of adults aged greater than 18 who reported short sleep
duration varied by state in 2020. We plan to focus on the states, and
create a map according to the distributions of the age-adjusted
prevalence among different states.

The second data set we will use is a [questionnaire sleeping
data](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/SLQ_J.htm) and also the
date related with their
[demographic](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/DEMO_J.htm)
information, both comes from the
[NHANES](https://www.cdc.gov/nchs/nhanes/index.htm) website. We plan to
merge the two data sets, and include variables:

The third data set is \[PLACES: Census Tract Data\]
(<https://catalog.data.gov/dataset/places-census-tract-data-gis-friendly-format-2020-release-fb1ec>).

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
