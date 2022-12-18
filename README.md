# Mission_to_Mars

## Objective: 
Utilize our new skills to scrape a provided website about mars news and a separate website about mars data. 

## Analysis: 
### Part 1: Please view "part_1_mars_news" / "part_1_mars_news_json"

* Extract HTML code using Beautiful Soup
* Titles and preview text of news articles were scraped and extracted
* Stored scraped information in Python data structure as a list of dictionaries

### Part 2: Please view "part_2_mars_weather" / "mars_data"
* Scrape HTML table ensuring correct headings and data types
* Data analyzed to answer following questions: 
  * How many months exist on Mars = 12.
  * How many Martian days worth of data is there = 1867.
  * Which month, on average, has lowest/ highest temperature? 3rd month/ 8th month.
  
![low_high_temp_bar](https://user-images.githubusercontent.com/111904266/208323180-19e8af39-a14e-47d0-80b1-7540279029da.png)
![avg_temp_bar](https://user-images.githubusercontent.com/111904266/208323313-bcf71fdc-6614-40a1-bf8e-81b666cbc8a1.png)
![avg_temp_line](https://user-images.githubusercontent.com/111904266/208323316-b948cbd4-f786-4162-81d9-025c4200c933.png)

  * Which month, on average, has lowest/ highest atmospheric pressure? 6th month/ 9th month.
  
![low_high_pressure_avg](https://user-images.githubusercontent.com/111904266/208323247-2f76f9dd-61b1-4c80-a8a0-7465c07c75f8.png)![avg_pressure_month_bar](https://user-images.githubusercontent.com/111904266/208323329-c601e530-46aa-4e83-91c7-73f6a63c9d6f.png)
![avg_pressure_month_line](https://user-images.githubusercontent.com/111904266/208323333-cb455461-19ec-41e9-bf98-81cdc607afd1.png)

 
  *How many terrestrial days exist in a Martian year = guesstimation of 675-687 days per Martian year. 
  
  ![earth_days_martian_year](https://user-images.githubusercontent.com/111904266/208323303-1a99797d-7754-472f-a18e-6231420d67cf.png)
  
  * export DataFrame into a csv file. "mars_data"

