# Toronto Restaurants

### Jupyter Notebooks: 
1. restaurants_data_scraper.ipynb: 

Selenium web scraper. Outputs "raw_restaurant_data.csv"

2. restaurants_clean_data.ipynb: 

Wrangles "raw_restaurant_data.csv" (clean's formatting, typecasts vars to appropriate type, removes duplicate rows, one-hot encodes categorical variables). Gets geo-coordinates from Google API. Outputs "clean_restaurants_data.csv"

3. restaurants_analysis_and_modelling.ipynb: 

Exploratory data analysis, data viz, clustering on "clean_restaurants_data.csv"

4. restaurants_map.ipynb:  

[Interactive Map](https://nbviewer.jupyter.org/github/monavvari/Toronto_Restaurants/blob/master/restaurants_map.ipynb?fbclid=IwAR1KC3VK0KkS9XUbdjeHaQjtzvyyz8h3ZluM7C-fneYJ5UO3KHt6ubFFjWM)
