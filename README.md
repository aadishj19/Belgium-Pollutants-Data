# Belgium Air Pollution Data Analysis

To render the interactive maps, [click here to run the ipynb](https://nbviewer.org/github/aadishj19/Belgium-Pollutants-Data/blob/main/Belgium_Air_Pollutants.ipynb#).

This Jupyter Notebook showcases an analysis of air pollution data in Belgium. It utilizes the `folium` library to create interactive maps, visualizing the distribution of pollutants across different cities in Belgium.

## Project Overview

The main goals of this project are:
- Analyze air pollution data in Belgium
- Visualize the average values of pollutants (PM10 and SO2) by city
- Create interactive maps to display the spatial distribution of pollutants using `folium` 

## Data

The air pollution data is sourced from Kaggle.

- `City`: The name of the city
- `Location`: The specific location within the city
- `Coordinates`: Latitude and Longitude coordinates of the location
- `Pollutant`: Type of pollutant (PM10 or SO2)
- `Value`: Pollutant value (in μg/m³)
- `Last Updated`: Date of the last update

## Analysis and Visualization

The notebook performs the following steps:

1. Data preprocessing:
   - Removes unnecessary columns
   - Extracts latitude and longitude values from the 'Coordinates' column
   - Converts latitude and longitude columns to float
   - Converts 'Last Updated' column to a datetime object and extracts the year
   
2. Data analysis and visualization:
   - Calculates the average PM10 and SO2 pollutant values by city
   - Plots bar charts to visualize the average pollutant values by city using Matplotlib
   
3. Interactive map creation:
   - Defines functions to plot maps using `folium` and `CircleMarker`
   - Creates interactive maps to showcase the spatial distribution of PM10 and SO2 pollutants

4. For interactive maps, note that they might not be fully rendered on GitHub. Please use `nbviewer` link above to view the notebook with interactive maps.

## Plots
![image](https://github.com/aadishj19/Belgium-Pollutants-Data/assets/84670503/92d2c086-a1b1-49d3-a214-f41ea4bd2334)
![image](https://github.com/aadishj19/Belgium-Pollutants-Data/assets/84670503/3f2b2bda-3a38-42f7-8aab-814394b1032d)


## Conclusion

This project demonstrates how to analyze air pollution data and visualize it using `folium` in Python. Feel free to explore the notebook and interact with the maps to gain a better understanding of the air pollution scenario in different cities.
