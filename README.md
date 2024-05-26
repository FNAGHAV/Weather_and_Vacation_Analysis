# Weather and Vacation Analysis

Project Overview
This repository contained two main Python projects: WeatherPy and VacationPy. These projects leveraged data science techniques and APIs to analyze weather patterns and help plan ideal vacation destinations.

WeatherPy
The WeatherPy project visualized the weather of over 500 cities at varying distances from the equator. It used the OpenWeatherMap API, the citipy library, and Python for data analysis and visualization.

Key Objectives:

Prepared the Data: Merged mouse metadata and study results into a single DataFrame and removed any duplicate entries to ensure data accuracy.
Generated Summary Statistics: Calculated mean, median, variance, standard deviation, and standard error of the mean for tumor volumes across different drug regimens.
Created Bar Charts and Pie Charts: Visualized the distribution of timepoints and gender among the mice using both Pandas and Matplotlib.
Calculated Quartiles, Found Outliers, and Created Box Plots: Examined the distribution of tumor volumes for promising drug regimens, identified outliers, and visualized the data using box plots.
Conducted Individual Mouse Analysis: Analyzed tumor volume over time for a specific mouse treated with Capomulin and explored the correlation between mouse weight and average observed tumor volume.

VacationPy
The VacationPy project could help plan future vacations based on weather conditions. It used the weather data from WeatherPy and additional APIs to find ideal vacation spots and nearby hotels.

Key Objectives:

Created a Map: Displayed points for every city in the DataFrame with point size representing humidity.
Filtered Ideal Weather Conditions: Narrowed down cities based on specific weather criteria.
Found Nearby Hotels: Used the Geoapify API to locate the first hotel within 10,000 meters of each city’s coordinates and displayed it on the map.

Added a .gitignore File:
For this assignment, I needed to add a .gitignore file to the repo. Doing so prevented the api_keys.py file that contained my API key from being shared with the public.

Conclusion
The WeatherPy and VacationPy projects showcased the power of Python and data science in analyzing weather patterns and planning vacations. By leveraging APIs and data visualization techniques, these projects provided valuable insights for both scientific research and practical decision-making.
