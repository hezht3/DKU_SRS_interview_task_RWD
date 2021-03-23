# DKU_SRS_interview_RWD

## Task: clean an air pollution dataset for Spring, 2018


Hi. I would like to again express my thanks for your interests in our group's projects and thanks for taking out time participating in the arranged interview. We are thinking about implicating this short task in the interview for you to know that what your work might be like in the SRS project and for us to better know you, so please take it easy.


## Setup

To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.


## Background

This task is to generate a dataset to analyze air pollution level in each city in China in Spring, 2018.


## Dataset

Air pollution dataset: The "air quality data_20180101-20180331" dataset you got is the data of 15 types of air pollutant in each monitor station in each hour of each date. The first 3 variables show you the date, hour, and type, while the rest variables are the id of each monitor station.

Station id dataset: The "station id" dataset you got is the information of the city and street of each monitor station. The date in the file name shows you that the information is as of that date.

City admin code dataset: The "city admin id" dataset you got is the information of the administrative code of each city in the year 2018.

For all datafiles containing Chinese characters, the encoding used is "UTF-8".


## Task

First, please condense the air pollution data of each hour of each date, to the mean value of the air pollution data of that date, for each air quality station.

Second, please condense the air pollution data of each date, to the mean value of the air pollution data of the whole season, for each air quality station. The dataset you generated in this step should use the types of air pollutant as variables, and the station id as observations.

Third, please merge the dataset you generated with the station id dataset. Then, please condense the air pollution data of the whole season for each air quality station, to the mean value of the air pollution data of the whole season for each city. The dataset you generated should use the types of air pollutant as variables, and city name as observations.

Finally, please merge the dataset you generated with the city admin code dataset.

For each step, please drop all observations with NA or NaN values.


## Notes

The time limit is 40 minutes. It is definately not easy to finish all these tasks in 40 minutes, but let's see how much you can finish in this designated time.

We strongly recommend you to use R in this task. Packages beyond R base are allowed.

Please send back your code script and outputed dataset (csv version) when the time is out.
