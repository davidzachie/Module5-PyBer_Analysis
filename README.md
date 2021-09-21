# **Module5 Challenge - PyBer_Analysis**
## **Module 5 PyBer_Analysis Creating Charts using Python Script, Pandas Library, and Matplotlib in Jupyter Lab**

## **Overview of the Project**

#### The purpose of this analysis is to provide decision-makers at PyBer with summarized ride sharing information about number of rides, number of drivers, total fares, average fare per ride and average fare per driver by city types, i.e. Urban, Suburban and Rural.  This information provides comparison data about how PyBer ride sharing business performs in different types of cities and could help PyBer's decision-makers to optimize their business strategy and further the growth of PyBer's ride sharing business.

## **Analysis and Results**

#### The first step is summarizing the total number of rides, total number of drivers, total amount of fares, as well as average fare per ride and average fare per driver and grouping them by Urban, Suburban, and Rural city types.  This summarization is accomplished by using groupby function to obtain Total Rides, Total Drivers, and Total Fares grouped by City Types (Urban, Suburban, and Rural).  Next, Average Ride per Fare and Average Driver Fare for all City Types are calculated.  Finally, a PyBer Summary Data Frame is created to display all the data in a tabular format to provide clear and concise information.

#### **The PyBer Summary Data Frame**

#### [PyBer Summary Data Frame](https://github.com/davidzachie/Module5-PyBer_Analysis/blob/main/analysis/Pyber_Summary_DF.png)

![Pyber_Summary_DF](analysis/Pyber_Summary_DF.png)



#### The second step is creating a multiple-line chart of the total weekly fares for each city type.  The chart is created by first grouping fare data by city type and date.  Then a pivot table is created showing date as index, city type as columns, and fare as values.  Finally, resample function is used to create a data frame showing the sum of fares for each week by city type and to create a multiple line graph that shows the total fares for each week by city type for the period of January 1, 2019 to April 28, 2019.

#### **Total Fare by City Type Chart**

#### [Total Fare by City Type Chart](https://github.com/davidzachie/Module5-PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

![Pyber_fare_summary](analysis/Pyber_fare_summary.png)

#### PyBer Challenge codes can be seen: [Pyber Challenge](https://github.com/davidzachie/Module5-PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)





The purpose of our analysis is to create a summary dataframe that will show ride sharing data by city type(Rural,Urban & Suburban). Once we find our data we are going to create a multiple line graph that shows total weekly fares by each city type. How we first pulled our data is by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019.

Results by city type:

#Quick facts by city type, seen in the image below our facts

Rural cities has the least amount of drivers, rides and total fares.
Urban cities have the most amount of drivers, rides and total fares.
Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
Although Rural cities see the least amount of drivers,rides & fares the have the highest average of fare per ride and fare per driver.
Although the Urban cities command the most drivers, rides and fares they have the lowest average of fare per ride and fare per driver.

