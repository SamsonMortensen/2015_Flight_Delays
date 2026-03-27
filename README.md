# US Flight Delays & Cancellations Analysis (2015) #

## Project Overview ##

The goal of this project is to analyze the operational efficiency and punctuality of the US aviation network using 2015 domestic flight data. By evaluating millions of flight records, this analysis identifies specific regional airports that experience the longest average wait times and compares the performance of individual airlines. The insights generated are designed to assist airline operations managers in pinpointing logistical bottlenecks and help travelers avoid historically troublesome hubs.

**Data Sources**

This analysis utilizes the 2015 Flight Delays and Cancellations dataset from Kaggle (US Department of Transportation). The project integrates three primary CSV files to map flight routes and airline performance:

flights.csv

airlines.csv

airports.csv

**Tools and Technologies Used**

* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Wrangling), Matplotlib, Seaborn (Data Visualization)
* **Environment:** Jupyter Notebook
* **Tableau** (Data Visualization, Interactive Dashboarding, Geospatial Mapping)

## The Problem ##


Maintaining a continuous-flow environment in aviation requires strict adherence to schedules and safety regulations. When delays occur, they strand physical assets (aircraft) and disrupt the broader supply chain network. The objective of this analysis is to:
1. Clean and standardize a massive dataset of domestic flights.
2. Isolate the primary drivers of delays (e.g., carrier-caused, routing, or weather).
3. Identify geographic and temporal clusters where ground-level bottlenecks are most severe.

## How to Run the Analysis ##

1. Clone this repository.
2. Ensure Python and the required libraries (Pandas, NumPy, Matplotlib, Seaborn) are installed.
3. Open the Jupyter Notebook file and execute the cells sequentially to view the data wrangling process and visual insights.

## Data Analysis & Wrangling ##

**Key Visualizations & Insights**

1. Geographic Distribution of Flight Departure Delays

Methodology: Developed a geographic map to illustrate the average departure delay (in minutes) for domestic flights across US airports. Applied an accessible orange-blue diverging color palette to clearly differentiate between early arrivals (negative values) and delayed departures (positive values).

Insight: The spatial mapping effectively highlights regional clusters of poor performance that would otherwise remain hidden in standard tabular data, immediately directing attention to hubs requiring urgent logistical enhancements.

***Live View***: https://public.tableau.com/views/Anatomy_of_2015_US_Flight_Delays_story/Anatomy_of_Delays?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

2. Airline Operational Scale vs. Punctuality

Methodology: Designed an interactive dashboard utilizing side-by-side bar charts to compare categorical variables (airlines) against quantitative measures (flight volume and average delay minutes). Incorporated a sequential, colorblind-accessible palette and interactive filters allowing users to isolate individual carriers.

Insight: The visualization reveals the relationship between operational scale and punctuality, highlighting whether high-volume carriers experience longer delays or if delay severity is more pronounced among lower-volume airlines.

***Live View***: https://public.tableau.com/views/Average_Delay_Time_vs_Flight_Volume/Dashboard_FlightDelay_Volume?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
