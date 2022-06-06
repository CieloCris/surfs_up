# Surfs Up Analysis

## Overview

In this Project, We performed an analysis of weather conditions in Oahu, Hawaii, in order to know if We can invest and open a Surf and Ice Cream Shop with the support of an investor called W. Avy. In other words, We wanted to identify if the weather data were in favorable conditions to open the business all year.

To accomplish our purpose, the challenge was specifically to study the temperature trends in June and December, using an SQLite data file and other resources, such as SQLAlchemy, Pandas, Numpy, Matplotlib, Jupyther Notebook as well as Python, and Anaconda.

Our final task was to present summary statistics of temperature data for the chosen months. That information helps us to define if the Surf and Ice Cream Shop Business can be successful and sustainable all the year. We also perform an additional analysis about precipitation. 

## Resources

-Data source: hawaii.sqlite
-Programming Tools, Languages and Software: SQLite, SQLAlchemy, Python, Jupyter Notebook, Anaconda, Pandas, Matplotlib, and NumPy

## Results

To achieve our goal, our task was to retrieve data from the hawaii.sqlite file to perform our analysis with SQLAlchemy, Python, NumPy, Matplotplib, and some Panda functions and methods. Once the temperatures of June and December were obtained by using queries, we converted the data into lists and DataFrames. The final step was to print statistics summaries.

The following DataFrame shows the temperature statistics for June.

![Alt text](/Resources/june_tem.png "imagen1")

As we can see, the average temperature in June is almost 75 ℉; while the minimum is 64 ℉ and the maximum is 85℉; the deviation standard is 3.2574. In addition, we added a histogram that is presented below:

![Alt text](/Resources/june_his.png "imagen2")

The following DataFrame shows the temperature statistics for December.

![Alt text](/Resources/dec_tem.png "imagen3")

In December, the average temperature is 71.0415 ℉. Also, the minimum and maximum temperatures are 56 ℉ and 83 ℉, respectively. The deviation standard is 3.7459. In the image below, we display a histogram with the December Temperatures:

![Alt text](/Resources/dec_his.png "imagen4")

### Key Differences:

The next results indicate some key differences in weather patterns between June and December.

- The average temperature in June is 74.9441 ℉ and in December is 71.0415. This means that the temperature is 3.9026 degrees lower in December.

- Temperatures in December have more variations than in June due to the winter season. In other words, while the minimum and maximum temperatures in December are 56 ℉ and 83 ℉, respectively; in June the minimum is 64 ℉ and the maximum is 85 ℉.
Even though the lowest temperatures between June and December have 8-degrees differences, the highest temperature have only 2-degrees apart.

- Histograms demonstrate that the frequency temperatures in June have a more normal curve of distribution compared to December.

- There are more counts capturing temperatures in June than in December (1700 versus 1517).

In addition to our objective, we also conducted an analysis of June and December Precipitations, because too much rain can reduce our business sales. The following DataFrame shows June and December’s precipitations.

#### June Precipitation DataFrame
![Alt text](/Resources/june_pre.png "imagen5")

#### December Precipitation DataFrame
![Alt text](/Resources/dec_pre.png "imagen6")

As we can see, the average precipitation in June is .14 mm and in December is 0.21 mm, the difference shows little variance.

## Summary

According to the _gohawaii website_, Hawaii has semi-tropical weather temperatures that usually range from 75 to 90 degrees during the daytime, and 70 to 80 degrees at night.

So, although there is some variation between the temperatures of December and June, our data shows that the difference is only 4-degrees. In addition, the lower temperatures occur in December at night, not during the daytime.

Also, according to the_Suffertoday website_, there are two seasons to go surfing in Hawaii: The summer season is from May to October and the winter season is from November to April.

After analyzing the temperatures and precipitations for June and December, we can conclude that it may be feasible and viable to open the Surf and Ice Cream Shop Business all year. In the summer season, we can sell more ice cream and during wintertime, we may be able to sell more special surfing suits.

Although we have appropriate weather conditions for opening our shop according to our analysis, it’s recommended to extend the research to study other factors, such as the local competition, the water temperature, the winds variations, and the impact of the hurricane season.
