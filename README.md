

# Designing mobile application messages to impact route choice: a survey and simulation study

This repository contains the code and result data for the article 'Designing mobile application messages to impact route choice: a survey and simulation study'.
Our study comprises two parts 

1. Survey. Please find the minimal data set for the survey in the sub-repository [survey-route-choice](https://github.com/pedestrian-dynamics-HM/survey-route-choice).
2. Simulation study. Please find the minimal data set for the survey in the sub-repository [crownet](https://github.com/roVer-HM/crownet/tree/route_choice_survey).

The data minimal data set of each part is stored in a seperate repository. The following table gives an overview how manuscript and repositories are organized:


| Sub-repository      | Objective                                                    | Corresponding section in the manuscript | Comments                                                                  |
|---------------------|--------------------------------------------------------------|-----------------------------------------|---------------------------------------------------------------------------|
| [survey-route-choice](https://github.com/pedestrian-dynamics-HM/survey-route-choice) | Investigate effect of message design on route choice         | II. Survey                              | requires R installed                                                      |
|                     | Compute route choice proportions for the traffic simulation  | III. Traffic assignment model           | requires R installed                                                      |
| [crownet](https://github.com/roVer-HM/crownet/tree/route_choice_survey)             | Investigate effect of message design on congestion situation | IV. Traffic simulation                  | Several requirements (docker, Python, ...)  See README of the repository  |


We recommend to clone the complete repository including all sub-repositories using
```console
git clone --recurse-submodules https://github.com/pedestrian-dynamics-HM/message-design-and-route-choice.git
```
If you want to clone the `route-choice-survey` repository only:
```console
git clone -b master https://github.com/pedestrian-dynamics-HM/survey-route-choice.git
```

If you want to clonce `crownet` repository only:
```console
git clone -b route_choice_survey https://github.com/roVer-HM/crownet.git
```
