# Capstone2

**Abstract:**
Capstone 2 - Supervised Learning: Predicting Used Car Listing Prices
Robert L Harris
4/14/21
The dataset of interest was found on Kaggle.com. It is composed of vehicles for sale on Craigslist.com compiled by Austin Reese. The dataset has approximately 500k listings throughout the USA. My computer was unable to download the entire csv file(267MB) do to hardware limitations. Therefore, the file was split into 46 separate files having 10K listings apiece. A looping algorithm was used to load in multiple files for investigation purposes. The dataset was then filtered to only look at California listings. Those listings were stored on 5 of the 46 files (vehicles_2.csv - vehicles_6.csv). While California was the state of interest, the code could be easily adjusted to accommodate any state of interest. One could even adjust it per generalized region (NW, W, SW, etc...).

**Task:**
Write a Supervised Learning model to predict the appropriate asking price of an automobile for sale on Craigslist.com. Our investigation will use California as the testing ground, but the model could be easily adjusted to look at any other state or region as stated earlier.

Capstone 2 - Supervised Learning: Predicting Used Car Listing Prices
Robert L Harris
4/14/21
The dataset of interest was found on Kaggle.com. It is composed of vehicles for sale on Craigslist.com compiled by Austin Reese. The dataset has approximately 500k listings throughout the USA. My computer was unable to download the entire csv file(267MB) do to hardware limitations. Therefore, the file was split into 46 separate files having 10K listings apiece. A looping algorithm was used to load in multiple files for investigation purposes. The dataset was then filtered to only look at California listings. Those listings were stored on 5 of the 46 files (vehicles_2.csv - vehicles_6.csv). While California was the state of interest, the code could be easily adjusted to accommodate any state of interest. One could even adjust it per generalized region (NW, W, SW, etc...).

**Task:**
Write a Supervised Learning model to predict the appropriate asking price of an automobile for sale on Craigslist.com. Our investigation will use California as the testing ground, but the model could be easily adjusted to look at any other state or region as stated earlier.

**Linear Regression:**
A linear regression approach will be pursued as the target listing price, a continuous variable, should increase on average over time. Multiple models will be implemented once the dataset is cleaned and feature engineering is completed on all the categories of interest.

**Stakeholders:**
Anyone interested in listing their vehicle on Craigslist.com should have an idea of an appropriate listing price depending on particular parameters (i.e. make, model, miles, year, etc...). If the best model gives an adequate result, then the individual would have a good idea of what to ask as a listing price for their vehicle.

**Limitations:**
Unfortunately, the sale price is not of record. Knowing the sale price would allow much more flexibility in the direction to pursue my analysis. Predicting sale price is much more informative in my opinion that predicting the listing price. Likewise, knowing the sales price along with listing price would allow for some basic inference regarding "if listing price with these features, then expect a possible sale price in this range as determined by some margin of error". One would also be able to pursue the concept of maximizing sale price depending on differing factors.

