Food Truck Code

This Python script utilizes the Google Maps API to search for food trucks within a 5000-meter radius of the center of Indianapolis, IN. Afterward, the script collects pertinent information about these food trucks, including their names, addresses, ratings, user rating totals, websites, opening hours, cuisine types, and geographic coordinates, and stores them in lists. The data is organized into a Pandas DataFrame and saved as a CSV file named "food_trucks_data.csv." This code is a practical example of accessing and processing location-based data using the Google Maps API and storing it in a structured format for future analysis or applications.

The data of nearby food trucks, along with their details, will be stored in the CSV file named "food_trucks_data.csv"

Plan Code

This Python script, designed for creating a "foodie plan," loads food truck data from the CSV file "food_trucks_data.csv." The code first filters food trucks with user ratings or reviews above 50. Afterward, of the food trucks with reviews above 50, the script picks the top 6 food trucks. It then optimizes a foodie route by generating a schedule with day and time assignments and leveraging the Google Maps API to calculate a path with the least travel distances. The resulting plan is stored in a Pandas DataFrame and saved as the CSV file "foodie_plan.csv." This tool is ideal for those exploring the local food scene while maximizing their culinary experience based on ratings and proximity. To personalize the experience, users must replace the API key and tailor the code to their location and preferences.

The output of Plan Code will be stored in the CSV file named "foodie_plan.csv"

The mapping of the foodie plan route will be in Google Maps.png
