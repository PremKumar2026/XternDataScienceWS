<h1>Food Truck Route Planner</h1>

This project contains a notebook and associated data files that create an optimal route to visit food trucks in Indianapolis over a weekend. The primary objective is to help someone new to the city plan their meals over the weekend, covering breakfast, lunch, dinner, and late-night snacks, using food trucks.

**Tasks Covered:**

**Data Gathering:** Used Google Maps API to find food trucks in Indianapolis.   
**Data Cleaning and Processing:** Organized the obtained data into structured form, and cleaned up any inconsistencies or missing values.   
**Selection:** Filtered out the best food trucks based on user preferences (e.g., opening hours) and chose 4 for each day of the weekend.   
**Routing:** Once the food trucks were selected for each day, determined the best route to visit them using Routes and Directions API and then visualized this route using Folium.   

**Methods Used:**   
Google Maps API: For collecting data about the food trucks.   
Routes and Directions API: Used for extracting latitude and longitude details for route planning.    
Folium: A Python library used for visualizing the routes on a map.    
Pandas: For data manipulation and analysis.      

**Results:**   
The results include a schedule (saved as ex_#_day.csv) and a visual map (day#_map.html) for both Saturday and Sunday. To get a view of the route, you can download the HTML map files and open them in any web browser.

**How to Use:**     
Clone or download this repository to your local machine.
Navigate to the folder containing the notebook.
Run the Jupyter Notebook to see the complete code, data processing steps, and results.
If you want a detailed visual representation, open the day#_map.html files in your browser.   
**Note:** Make sure you have all the required libraries installed to run the notebook.

**Tags:**   
-Route Planning   
-Food Truck   
-Indianapolis  
-Google Maps API  
-OpenRouteService API
-Folium  
-Data Visualization  
-Routes and Directions API   
-Weekend Planner   

**I hit the mark by crafting a comprehensive dataset of nearby food trucks and plotting a two-day culinary journey. These visuals provided clarity on the food landscape, aiding in shaping the itinerary and ensuring a delightful experience for the Xterns!**
