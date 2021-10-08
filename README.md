# Historical Spaceships Exploratory Data Analysis (EDA).

![](https://github.com/The-carlos/historic_spaceships_exploratory_data_analysis/blob/main/launches_per_location.png)

A exploratory data analysis for all historic human spaceships including all the space missions since the beginning of Space Race (1957).

## What it is.

This is a EDA based in a dataSet  scraped from https://nextspaceflight.com/launches/past/?page=1 and includes all the space missions since the beginning of Space Race to august 2020. All the data cleaning was made on python using a jupyter notebook and then I used Power BI to create some cool slides to show relevant information. I did this project in collaboration with my team at @DereumLabs

There are some cool things to spot in this project that make me feel proud:
- The data set was desing directly from scrapping the web (I'll add the code to this repo later (If you are visiting this repo from the future maybe it's already here)).
- I used some pandas tricks to get the exact direction from every launch location and the used the Googles Maps APIs to get the exact coordinates so I can later use them to make a real interactive map in Power BI to desplay the launche.
- Although it's no that difficult to use the Google Maps API it is not free after certain number of requests, so I used only unique location values to make requests instead of iterate through the entire dataset (clever, isn't it?).
- The I used the reliable old pandas.merge() to make a "VLOOKUP" with my coordinates data through the launch location (PARKOUR!). At the end it results in the fancy, interactive, cute map above.

For now the Power BI Dashboard is not public, but feel free to download the .ipbx file a open it in your computer. Here are snaps of the dashboard:

![](https://github.com/The-carlos/historic_spaceships_exploratory_data_analysis/blob/main/founds_invested.png)
![](https://github.com/The-carlos/historic_spaceships_exploratory_data_analysis/blob/main/historical_launches.png)
![](https://github.com/The-carlos/historic_spaceships_exploratory_data_analysis/blob/main/launches_per_company.png)
