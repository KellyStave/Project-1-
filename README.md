# Analysis  of COVID in California

## Questions to answer

* What was the total case rate and death rate for the state of California?
* When did COVID peak in California within the timeframe?
* Which counties were most  affected by COVID?
* Which counties were least affected by COVID?
* Is there correlation between number of covid cases and population/area of the county?

## The Data Used

The data set has  cumulative data for each county in the United States.

Reference data set: https://www.kaggle.com/datasets/fireballbyedimyrnmom/us-counties-covid-19-dataset 

Shortened the dataset to focus on  California’s 58 counties from July 1st, 2020 through June 30, 2021.

## Most Affected Counties

Top 5 counties that are mostly affected in our timeframe are Los Angeles, San Bernardino, Riverside, San Diego and Orange. All of these counties are in Southern California.

![Most Affected](./images/top_counties_cases.png)

![Most Affected](./images/top_counties_deaths.png)

## Least Affected Counties

Bottom 5 counties that are least affected in our timeframe are Sierra, Alpine, Trinity, Mariposa and Modoc.

![Least Affected](./images/bottom_counties_cases.png)

![Least Affected](./images/bottom_counties_deaths.png)

## Correlation Analyses (County Covid Cases/Deaths versus County Population/Area(Sqr mil))

The correlation between covid cases and population is 0.98 while correlation between covid cases and area (sqr mil) is 0.25.

![Cases Population Plot](./images/plot_cases_population.png)

![Cases Area Plot](./images/plot_cases_area.png)

The correlation between covid deaths and population is 0.97 while correlation between covid deaths and area (sqr mil) is 0.22.

![Deaths Population Plot](./images/plot_deaths_population.png)

![Deaths Area Plot](./images/plot_deaths_area.png)

## Covid Timeline Analysis
Despite a lockdown renewed on December 3rd in California, the cases grew dramatically during the holiday season. This makes sense assuming people are shopping, traveling and coming in contact with more people during this time.

During the surge, the biggest dip in daily cases was on December 25th, 2020. We conclude that people did not check, themselves in  because of Christmas. This leads to the highest number of cases recorded the following day on December 26th, 2020. The day after Christmas day recorded 64,986 new covid cases.
![Holiday Daily Cases](./images/holiday_daily_cases.png)

The growth of Covid cases and low vaccine distributions results to an increase in deaths in the early months of 2021. The spike in deaths reaching 1,084 deaths on February 24th, 2022.

![Califonia Covid Deaths](./images/california_covid_deaths.png)

In early 2021 vaccines become more available and accoring to CBS news 20 million Californians are partially or fully vaccinated as of May 28th 2021. With more people getting vaccinated the timeline of Covid Cases shows cumilitive cases flattening in between February and March. 

![California Covid Cases](./images/california_covid_cases.png)


