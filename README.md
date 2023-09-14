# <ins>Python Projects</ins>

The following are all the python projects in this repository along with the process that was used to analyze their respective datasets using Jupyter Notebooks

## <ins>Screen Time Analysys</ins>

Screen time analysis lets you know how much time you spend on what kind of applications and websites using your device and the analysis gives a visual report of the same. For the task of screen time analysis, an ideal dataset (https://github.com/kodjoP/Python_Projects/blob/main/Screentime-App-Details.csv) that cotains the data below was used:

1. Date
2. Usage of Applications
3. Number of Notifications from Applications
4. Number of times apps opened

### <ins>Analysis</ins>

Jupyter Notebook (https://github.com/kodjoP/Python_Projects/blob/main/Screen%20Time%20Analysis.ipynb)
1. import all necessary python libraries (i.e. pandas, numpy, plotly.express, plotly.graph_objects)
2. read dataset into Jupyter Notebook
3. Look through the dataset for any null values and the descriptive statistics of the data (i.e. count, mean, std, min, ...)
4. Start analyzing the screen time of the user by looking at the amount of usage of the apps between Whatsapp and Instagram
5. Next, we'll look at the number of notifications from the apps and the number of times the apps opened.
6. Lastly, we look at the relationship between the number of notifications and the amount of usage because generally, we use our smartphones when we get notified by any app.

## <ins>Supply Chain Analysis</ins>

To analyze a company's supply chain, we need data on the different stages of the supply chain, like data about sourcing, manufacturing, transportation, inventory management, sales and cutomer demographics. The dataset used includes data about the supply chain of a Fashion and Beauty startup (https://github.com/kodjoP/Python_Projects/blob/main/supply_chain_data.csv)

### <ins>Analysis</ins>

Jupyter Notebook (https://github.com/kodjoP/Python_Projects/blob/main/Supply%20Chain%20Analysis.ipynb)
1. import the necessary python libraries (pandas, plotly.express, plotly.io, plotly.graph_objects)
2. read dataset into the Jupyter Notebook to reveal information such as price, availability, number of products sold, revenue generated and many more
3. Print descriptive statistics of the dataset
4. For the analysis, we start by looking at the relationship between the price of the products (haircare, skincare, and cosmetics) and the revenue generated by them using a scatterplot and a trendline for the different product types. *From the visualization, the company derives more from skincare products, and the higher the price of skincare products, the more revenue they generate*
6. Visualizations were generated to show the relationship between the sales of the product types and the total revenue by shipping carrier
7. Further analysis was done to determine stock levels of the products and revenue generated using the SKU
8. Cost Analysis visualizations were generated to compare shipping costs by carrier and compare cost distribution by transportation mode (road, rail, air, sea)
9. Finally, the defect rate of the products were analyzed by looking at the products that have something wrong or are found broken after shipping, and slo the transportation mode that causes the most defects in the products.

## <ins>Area and Population</ins>

In this project we use the size of points to indicate the area and populations of California cities, a legend that specifies the scale of the sizes of the points, and we accomplish this by plotting some labeled data with no entries.

Dataset(https://github.com/kodjoP/Python_Projects/blob/main/california_cities.csv)

### <ins>Analysis</ins>

Jupyter Notebook (https://github.com/kodjoP/Python_Projects/blob/main/Area%20and%20Population.ipynb)
1. import pandas, numpy, matplotlib.pyplot, seaborn library and the above dataset into the Jupyter Notebook
2. Extract data we are interested in (latitude, longitude, population, area)
3. We plot the points using size and color to differentiate the size of the area and population respectively

## <ins>Netflix Data Analysis</ins>

Netflix is one of the largest providers of online streaming services. It collects a huge amount of data because it has a very large subscriber base. We can analyze a lot of data and models from Netflix because this platform has consistently focused on changing business needs by shifting its business model from on-demand DVD movie rental and now focusing on production of their original shows. We will look at some very important models of Netflix data to understand what's best for thei business. Some of the tasks we can analyze from the Netflix data are:

1. understand what content is available
2. understand the similarities between the content
3. understand the network between the content
4. what exactly Netflix is focusing on
5. Sentiment analysis of content available on Netflix

Dataset(https://github.com/kodjoP/Python_Projects/blob/main/netflix_titles.csv)

### <ins>Analysis</ins>

Jupyter Notebook()
1. import pandas for data preparation, numpy for linear algebra, plotly.express for data visualization and textblob for sentiment analysis
2. To begin analysis, we'll look at the distribution of content ratings on Netflix (TV-MA, TV-14, TV-PG, R, PG-13, etc.) using a piechart
3. Next, we'll look at the top 5 directors and actors on the platform by the total number of content they have uiing horizontal bar chart
4. The next thing to analyze from the data is the trend of production over the years on Netflix and finally sentiment analysis
5. Using vertical stacked bar chart, we analyze the sentiment of content on Netflix to find that, overall, the positive content is always greater than the neutral and negative content combined.


## <ins>A/B Testing</ins>
