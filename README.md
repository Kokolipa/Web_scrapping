# Web Scrapping
### Project description:
This project outlines two scrapping methods:
1. Scrapping a web page (identifying HTML elements and extracting the content) to extract all the articles headers and teasers from [mars news](https://static.bc-edx.com/data/web/mars_news/index.html). 
    * Creating a jsonified representation of the data to ease information sharing with others (**title_preview.txt**). 
2. Scrapping a web page table for analysis purposes [mars data](https://static.bc-edx.com/data/web/mars_facts/temperature.html)
    * Extracting the table info from the URL address above and using Pandas and Matplotlib to summarise the analysis results and answer the following questions:
        * How many months exist on Mars?
        * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        * What are the coldest and the warmest months on Mars (at the location of Curiosity)?
        * Which months have the lowest and the highest atmospheric pressure on Mars?
        * About how many terrestrial (Earth) days exist in a Martian year?

### Libraries used: 
1. Splinter
2. BeautifulSoup
3. Pandas
4. NumPy
5. Matplotlib


### Analysis Images
##### Average temperature by month
![avg_temp](https://github.com/Kokolipa/Web_scrapping/blob/mars_main/Images/Fig_1.png)

##### Identify the coldest and hottest months in Curiosity's location
![avg_temp](https://github.com/Kokolipa/Web_scrapping/blob/mars_main/Images/Fig_2.png)

##### Average pressure by month
![avg_temp](https://github.com/Kokolipa/Web_scrapping/blob/mars_main/Images/Fig_3.png)

##### Terrestrial (earth) days in Martian year? - Visual Representation
![avg_temp](https://github.com/Kokolipa/Web_scrapping/blob/mars_main/Images/Fig_4.png)


#### Folder structure
``` yml
.
├── SurfsUp
│   ├── Images    
│   |   ├── Fig_1.png
│   |   ├── Fig_2.png
│   |   ├── Fig_3.png               
│   |   ├── Fig_4.png               
│   ├── mars_scrapping
│   |   ├── part_1_mars_news.ipynb               
│   |   ├── part_2_mars_weather.ipynb              
│   ├── output
│   |   ├── df.csv             
│   |   ├── title_preview.txt              
|___.gitignore               
|___README.md
``` 


