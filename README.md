# Weather-Forecasting-Analysis

This Power BI weather forecast dashboard provides a comprehensive visualization of weather, air quality, and atmospheric conditions for multiple Indian cities, including Ajmer, Kochi, Hyderabad, Bangalore, Mumbai, and Chennai. The dashboard presents real-time metrics and 7-day forecasts, utilizing clear data representation and user-centric design to enhance interpretability.

Dashboard Features:

► Current Weather Overview: The main card prominently displays the current temperature (30.9°C) and weather conditions for Ajmer, with easy toggling between cities.

► Forecasted Weather Trends: A combination of daily forecast cards and a trend line graph shows temperature variations over the upcoming week, enabling users to quickly grasp upcoming weather patterns.

Detailed Atmospheric Data:

► Visibility, humidity, pressure, wind speed, precipitation, and UV index are provided in dedicated visual elements for granular insight.

► Sunrise and Sunset Timings: Visual icons provide clear sunrise (05:55 AM) and sunset (07:18 PM) times, aiding in daily planning.

► Rain Probability: A horizontal bar chart depicts the chance of rainfall for each day, quickly indicating periods of high precipitation risk.

Air Quality Index (AQI):

► Centralized gauge visual outlines the AQI score (122 - Unhealthy for Sensitive Groups), with granular breakdowns for Ozone (O3), Particulate Matter (PM10, PM2.5), SO2, CO, and NO2.

► Color coding and advisory text emphasize public health considerations.

Data Cleaning and Preparation Techniques:

Power Query:

► Imported and consolidated weather datasets for all selected cities.

► Implemented data type transformations (e.g., date/time, numeric fields), handled nulls, and enforced consistent units of measurement (e.g., Celsius, kph).

► Performed text normalization and removed duplicates to ensure data integrity.

► Utilized query steps for dynamic filtering and reshaping of time-series weather data, optimizing it for visual analysis.

DAX (Data Analysis Expressions):

► Created calculated columns and measures for custom metrics, such as daily temperature averages, AQI banding, and chance-of-rain percentage computations.

► Employed time intelligence functions to generate rolling averages and week-over-week trend aggregations for temperature and AQI.

► Built slicers and city filter logic, allowing dynamic dashboard interaction across Ajmer, Kochi, Hyderabad, Bangalore, Mumbai, and Chennai.

Additional Data Practices:

► Applied error handling routines to manage incomplete or inconsistent weather records.

► Aligned data from multiple APIs and sources into a unified format, ensuring comparability across cities.

Visualization Techniques:

► Used card visuals, line graphs, bar charts, and gauge charts to represent key measures.

► Applied conditional formatting for AQI and rain probabilities to highlight critical values.

► Integrated iconography for a more intuitive, user-friendly layout.

This dashboard leverages Power BI’s robust data modeling (via Power Query and DAX) and advanced visualization capabilities to deliver actionable, up-to-date weather intelligence for diverse locations, making it a valuable reference for both everyday users and decision-makers.


preview : ![Dashboard Preview](https://github.com/sadik4li/Weather-Forecasting-Analysis/blob/main/Screenshot%202025-07-31%20100724.png)
