# Data Analysis Portfolio
Portfolio of data analysis related projects by Ryan Carroll.
* [Main Github Page](https://github.com/ryanjcarroll)
* [LinkedIn](https://www.linkedin.com/in/ryan770)

# Project 1: [MLB Free Agent Contract Analysis](https://github.com/ryanjcarroll/MLB-Free-Agents-Data-Analysis)
* Web scraped all MLB free agent contract signings (2006-2019) from tables on ESPN.com, using BeautifulSoup and JSON.
* Used Pandas to clean the scraped data, ignoring certain types of low-value data such as minor league signings and retirements. Also converted several scraped values from formatted strings to integers and corrected bad values.
* Generated visualizations of how contract sizes vary by player age and the year they were signed, using Seaborn and Matplotlib.
* Also web scraped the primary and secondary colors for each MLB team to format team-breakdown graphs.

![Bar chart showing MLB contract values by player age](https://i.imgur.com/4VR4Svb.png)
![Bar chart showing largest MLB contract values by team](https://i.imgur.com/p1ZD6hL.png)

# Project 2: [Recipe Analysis from Allrecipes](https://github.com/ryanjcarroll/Recipes-Data-Analysis)
* Web scraped ~4,000 recipes from Allrecipes.com using Python's BeautifulSoup and JSON libraries.
* Using Pandas, cleaned the data. This included extracting ingredient names, converting various cook time formats to consistent numerical values, and locating HTML elements across multiple webpage layouts.
* Generated charts of the most common ingredients, title keywords, and instructions using Matplotlib.
* Analyzed distribution of recommended serving sizes and cook times, and generated visualizations using Matplotlib.

![Bar chart showing most common ingredients in Allrecipes posts](https://i.imgur.com/3ei8CEC.png)
