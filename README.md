# Sales Analysis [![Awesome](https://awesome.re/badge.svg)](https://github.com/kfrawee/SalesAnalysis)

Using Python, Pandas &amp; Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

**Check:** 
- [SalesAnalysis notebook](https://github.com/kfrawee/SalesAnalysis/blob/master/SalesAnalysis.ipynb)
- [`/data/`](https://github.com/kfrawee/SalesAnalysis/tree/master/data) for row sales data.
- [`/img/`](https://github.com/kfrawee/SalesAnalysis/tree/master/img) exported images.
- [`/output/`](https://github.com/kfrawee/SalesAnalysis/tree/master/output) exported cleand data (csv).

---
**First we start by assessing our data for:**
- Quality: issues with content. Low quality data is also known as dirty data.
- Tidiness: issues with structure that prevent easy analysis. Untidy data is also known as messy data.

**Then cleaning our data:**
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the datatypes (to_datetime, astype)
- Extact data from values 
- Merge all datasets into one dataset

**Once we have cleaned up our data a bit, we move the data exploration section.**

**In this section we explore 5 high level business questions related to our data:**
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

**To answer these questions we walk through many different pandas & matplotlib methods. They include:**
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

---
**Author**

This project was completed by Muhammad Elkfrawy.<br>
*Following [Keith Galli](https://github.com/KeithGalli/)'s [video](https://www.youtube.com/watch?v=eMOA1pPVUc4)*
