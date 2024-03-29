This readme file was generated on 2024-03-28 by Jing Jiang

This is a repository of temporal iterpolation of weather station data. The first test was done on a random weather station's hourly data (measured ~ every 3 hours), for the period of 1961-1980. 

# Author Information

Name: Jing Jiang

ORCID: 0000-0002-8068-4451

Email: jiangjing.gingercrystal@gmail.com




# Data used
Title of Dataset: Central weather beaureu of Taiwan, beaureu-wide stations (rather than automatic stations).

Date of data collection: Spring 2022


# METHODOLOGICAL INFORMATION

1. Hourly data for 1961-2017 was appended from .xlsx files. Hourly data for 2017-2018 period was recognized from txt files and appended. Appended data was stored in a .csv file.

2. Hourly air temperature was interpolated using spline.

