# Airbnb - Seattle - Insights to Move-in

Airbnb, Inc. is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based in San Francisco, California, the platform is accessible via website and mobile app.

Github Repo: https://github.com/anands-code/DataScienceBlog.git

**Files Contained in this Repo**

* *WriteDataScienceBlog.ipynb - Jupyter Notebook*

* *Readme.md - Readme* 

### File Description

There is one exploratory notebook available here to showcase my work in detailed analysis along with resolving three questions supported with statistical results. 
Markdown cells were used throughout to explain the process taken.

### Installations:

* *NumPy*

* *Pandas*

* *Seaborn*

* *Matplotlib*

* *sklearn*

* *math*

No additional installations beyond the Anaconda distribution of Python and Jupyter notebooks.

### Project Motivation

Motivated to analysing insights on Airbnb Seattle open data from popular data platform - Kaggle for customer booking, pricing and popularity of listings.
Further seek to find relation of amenities/facilities with the people's interest therein. Eventually the goal is to draw conclusions from the data and try to tackle some of the questions/hypothesis:
1. What are the most common amenities ?
2. What are the prominent features contributing to highly rented properties ?
3. How much price differs with the distance from city center / downtown ? 

We resolve above posed questions by relying on principles of Cross-Industry Standard Process of Data Mining (CRISP-DM):

* Business Understanding
The business objective is to seek for most successful listings and features they provide which entices people to book them repeatedly. Property prices in the city of Seattle may vary in direct consequence to an amenity available or not.
For this data mining task, I can foresee the cost-benefit and users perspective success metrics as:
  * *Service Provider: Airbnb/Property Owners* would be enhanced revenues generated by recommending amenities most likened for any listing by their prospective customers.
  * *Sevice Consumer: Vacationers/travellers* will also benefit from our analysis and findings on the relations and insights on various factors to help them make informed decisions.
This project makes use of Python, Pandas and relevant visualization tools/libraries.

* Data Understanding
We download the kaggle dataset for Seattle Airbnb listings and load in pandas dataframe to perform analysis. On examining listings data we notice there are invalid / missing with null values. Additionally the price, advance payment, surcharge, tax are represented in string format most often prepended with currency denominations. In all about 3.8k Seattle listing of Airbnb records are taken in account for our deep dive and visualizations and related to their calendar bookings data. Post stay review data is also provided giving us insights on user experience. Charts have been plotted at different levels to perform univariate and bivariate analysis between the variables in the dataset.

* Prepare Data
Data is extracted for getting unique amenities available among Seattle listings. We slice only the relevant dataset needed from this huge columns of data provided. The dataset is further refined to change string-represented numerical data to float to enable model calculations staged further ahead under CRISP-DM methodology steps.

* Data Modeling
Added a separate jupyter notebook for the modeling section, wherein we find most attractive amenities, besides we'll attempt feature engineering and implement Linear Regression on the dataset and estimate the pricing impact over distance from Seattle downtown. Further used ML to train and test the dataset to derive linear coefficients.

* Evaluate the Results
Inference drawn shows that the washer/dryer is most seeked out amenity at the listings. Also using regression, we come to know that the listing price inversly impacts with its distance from Seattle downtown.
  
### Medium Blog Post

The main findings of the code can be found at the Medium blog post available here [Medium](https://medium.com/@anand-blog/data-science-blog-1ead4fd41e5) explaining the technical details of my project.

### Licensing, Authors, Acknowledgements, etc.
Being an author for this project, I'd like to acknowledge Udacity for the project idea.
