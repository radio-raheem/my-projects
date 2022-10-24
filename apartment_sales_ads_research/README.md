# Apartment sales ads research

Can we determine the market value of objects, having real estate ads for several previous years?  
Great news: yes we can!  
  
We have the data of the service for placing real estate ads — an archive of ads for the sale of apartments in a large Russian city and its suburbs for several years.  
We need to learn how to determine the market value of real estate and set key parameters. This will allow to build an automated system: it will track anomalies and fraudulent activity.  

Two types of data are available for each apartment. The first one is entered by the user, the second one is obtained automatically based on cartographic data. For example, the distance to the center, the airport, the nearest park and pond.

Let's describe our data.

* airports_nearest - distance to the nearest airport in meters (m)
* balcony - number of balconies
* ceiling_height - ceiling height (m)
* cityCenters_nearest - distance to city center (m)
* days_of_exposure - how many days the ad has been placed (from publication to removal)
* first_day_of_exposure - date of publication
* floor - floor number
* floors_total - total number of floors in the building
* is_apartment - apartment (Boolean type)
* kitchen_area_room - kitchen area in sq.m.
* last_price - price at the moment of removal from publication
* living_area - living space in square meters (m²)
* locality_name - name of the locality
* open_plan - free layout (Boolean type)
* parks_around3000 - number of parks within a radius of 3 km
* parks_nearest - distance to the nearest park (m)
* ponds_nearest3000 - number of ponds within a radius of 3 km
* ponds_nearest - distance to the nearest pond (m)
* rooms - number of rooms
* studio - one-room apartment (Boolean type)
* total_area - area of the apartment in square meters (m²)
* total_images - number of pictures of the apartment in the ad

The main steps of our project will be:
* Examining the provided data
* Data preprocessing
* Calculations and adding results to the table
* Exploratory data analysis
* General conclusion

The project is made in **Jupyter Notebook**, Notebook server version: 6.1.4. **Python** 3.7.8.
The project uses the **Pandas**, **MatPlotLib** libraries and the **IPython** module.
