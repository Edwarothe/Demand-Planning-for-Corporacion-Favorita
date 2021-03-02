# favorita
Demand Forecasting with Machine Learning


In October 2017, the large Ecuadorian-based grocery retailer, Corporacion Favorita, posted its data here on Kaggle for analytics and ML enthusiasts to predict the sales of various items for August 2017. The reason I chose this dataset was the fact that it was as close a real world dataset, as one could get. It has a realistic relational data model and one can derive patterns from different perspectives depending on the angle of focus. I chose to focus on the demand planning aspect of the data; how can we get the right products to match the demand at a particular time. I also forecasted the unit sales for specific items at the end of the notebook.

At the moment of writing this article, I'm using a windows machine, 7 cores with 8 GB RAM. Why is this information important? As you'll see the entire dataset takes around 5 GB in csv format which is too much for my machine to handle. My solution was to bucketize the train dataset into years (2013-2017). This method worked out especially well compared to several others I considered. I even have a short medium article comparing the different solutions I tried, results and compromises for each, and my choice, which is really important in case you come across a similar problem. Using SQL via Postgresql was an option but since the data is small enough to load as an iterable, I chose pandas which is more versatile and powerful as compared to SQL. The reader will be keen to note, however, I have used SQL-like statements especially pandas' merge, value counts among other functions, given the relational nature of the data.

This is definitely an initial dive into the data and any different way to analyze the data, improvements or suggestions are much welcome. Suggestions especially dealing with optimizing code and resources, so that a local machine without a big RAM can analyze this kind of data, would be helpful.

This project is maintained by Ed Warothe.
