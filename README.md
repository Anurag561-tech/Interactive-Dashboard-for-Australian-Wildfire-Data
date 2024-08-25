# Australian Wildfire Activity Analysis and Dashboard

This project is divided into two main parts: 
1. **Analyzing the Wildfire Activities in Australia** 
2. **Creating a Dashboard to Visualize the Data**

The project leverages various Python libraries such as Matplotlib, Seaborn, Pandas, Folium, Dash, and Plotly to explore, analyze, and visualize wildfire data from Australia, and then build interactive dashboards.

## Project Overview

### Part 1: Analyzing the Wildfire Activities in Australia

The objective of this part is to analyze and visualize wildfire activities across different regions of Australia using the provided dataset. You will explore patterns, trends, and gain insights into the behavior of wildfires in these regions.

#### Data Description

The dataset includes the following variables:
- **Region:** The 7 regions in Australia.
- **Date:** UTC date providing data for the next 24 hours.
- **Estimated_fire_area:** Daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% for each region in km².
- **Mean_estimated_fire_brightness:** Daily mean (by flagged fire pixels) of estimated fire brightness for presumed vegetation fires with a confidence level > 75% in Kelvin.
- **Mean_estimated_fire_radiative_power:** Daily mean of estimated radiative power for presumed vegetation fires with a confidence level > 75% for a given region in megawatts.
- **Mean_confidence:** Daily mean of confidence for presumed vegetation fires with a confidence level > 75%.
- **Std_confidence:** Standard deviation of estimated fire radiative power in megawatts.
- **Var_confidence:** Variance of estimated fire radiative power in megawatts.
- **Count:** Daily number of pixels for presumed vegetation fires with a confidence level > 75% for a given region.
- **Replaced:** Indicates with a 'Y' whether the data has been replaced with standard quality data when available (usually with a 2-3 month lag).

#### Tasks

1. **TASK 1.1:** Plot the change in average estimated fire area over time using a line chart.
2. **TASK 1.2:** Plot the estimated fire area over different months.
3. **TASK 1.3:** Use Seaborn to develop a bar plot showing the distribution of mean estimated fire brightness across regions.
4. **TASK 1.4:** Create a pie chart to represent the portion of count of pixels for presumed vegetation fires across regions.
5. **TASK 1.5:** Customize the pie chart for better visual representation.
6. **TASK 1.6:** Use Matplotlib to develop a histogram of the mean estimated fire brightness.
7. **TASK 1.7:** Use Seaborn with region as the hue to understand the distribution of estimated fire brightness across regions.
8. **TASK 1.8:** Develop a scatter plot to find the correlation between mean estimated fire radiative power and mean confidence level.
9. **TASK 1.9:** Mark all seven regions affected by wildfires on the map of Australia using Folium.

### Part 2: Dashboard to Display Charts Based on Selected Region and Year

In this part, you will create interactive dashboards using Dash and Plotly, allowing users to select a region and a year to view the related wildfire data.

#### Tasks

1. **TASK 2.1:** Add a title to the dashboard.
2. **TASK 2.2:** Add radio items and a dropdown for selecting Region and Year.
3. **TASK 2.3:** Create two empty divisions for output inside the dashboard.
4. **TASK 2.4:** Add the output and input components inside the `app.callback` decorator.
5. **TASK 2.5:** Implement the callback function to update the dashboard based on user inputs.

## Project Structure

- **Part 1: Analysis Notebooks**
  - `wildfire_analysis.ipynb`: Contains all tasks related to data analysis and visualization.
  
- **Part 2: Dashboard Implementation**
  - `flight_delay.py`: Contains code for creating the interactive dashboard.

## Results 
The results include detailed visualizations of wildfire activity in Australia, and an interactive dashboard that provides insights into the distribution
and impact of wildfires across different regions and years.

## Conclusion
This project demonstrates the use of data analysis and visualization techniques to understand wildfire patterns in Australia. 
The interactive dashboard enhances the analysis by allowing users to explore the data dynamically
