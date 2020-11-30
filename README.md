# Tableau - Citi Bike Analytics

[Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

1. Downloaded data for the last 6 months from the webpage above. Saved in "data" folder.

2. In order to merge the data, we needed to create a index or a unique ID for each spread sheet. This one done in the "data_cleanup" folder using Jupyter Notebook. CSV files were created from this cleanup (05_2020, 06_2020, 07_2020, 08_2020, 09_2020, 10_2020).

3. Usage (both by total duration and total users) was graphed for data from the last 6 months. There we saw a decreasing trend of usage. Furthermore, we used table calculations to determine duration per user. Not only were we able to see a decrease in users, we noticed the average duration of usage per user is decreasing as well. 

4. Location of start and end stations were mapped with a layer of population of age median by zip code. We saw most utilized stations were all within population with 2.4 - 35.8 years as median age. 

5. Lastly we determined which bikes may need maintenance based on usage (trip duration and number of users).