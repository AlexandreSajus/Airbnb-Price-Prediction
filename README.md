# **Course Project: Airbnb Berlin Price Prediction**

The project aims to predict the price of a night's accommodation offered on the short-term rental website Airbnb in the city of Berlin. This project is derived from a data challenge proposed by dphi.tech. Details of the data challenge is available available in this link.

## **To obtain the data:**
Simply download the training and testing files train_airbnb_berlin and test_airbnb_berlin.

## **Pandas for handling the data:**
The files you obtained are in CSV format. We strongly suggest using Python Pandas package to load and visualize the data. Here is a basic tutorial on how to handle data in CSV file using Pandas.

## **Data**

If you open the train_airbnb_berlin.csv or the test_airbnb_berlin.csv files using Pandas, you will find that it contains following columns:

- Listing ID - unique id of the listing
- Listing Name - this is the name of the listing, this is anonymized in the dataset and you can feel free to drop this variable from the data
- Host ID - unique ID of the listing host
- Host Name - name of the host who manages/owns the listing
- Host Since - date since they have been hosting on Airbnb
- Host Response Time - Avg time taken by the host to respond to any query they get
- Host Response Rate - Avg response rate to the queries that the host receives for their listing
- Is Superhost - this field says whether the host is superhost or not. Superhost implies the best-rated host badge given by Airbnb based on the overall listing experience
neighbourhood - provides information about neighbourhood of the listing
- Neighborhood Group - provides information about neighbourhood group of the listing
- City
- Postal Code
- Country Code
- Country
- Latitude
- Longitude
- Is Exact Location
- Property Type
- Room Type
- Accomodates
- Bathrooms
- Bedrooms
- Beds
- Square Feet
- Guests Included
- Min Nights
- Reviews
- First Review
- Last Review
- Overall Rating
- Accuracy Rating
- Cleanliness Rating
- Checkin Rating
- Communication Rating
- Location Rating
- Value Rating
- Instant Bookable
- Business Travel Ready
- **Price, Price is the target variable.**

## **Data preprocessing tasks before starting the project :**

- Download the training and test data. 
- Load the data using pandas.
- Apply adequate pre-processing (use what we learned during courses and lab sessions, and more you learned by yourself).


## **Task for the project**

The project guidelines are:

- Apply all approaches taught in the course and practiced in lab sessions (Decision Trees, Bagging, Random forests, Boosting, Gradient Boosted Trees, AdaBoost, etc.) on this data set. The goal is to predict the target variable (price). You can try more advanced approaches if you think that they are adequate. If you do that, please justify the adequation.
- Compare the performances of all these models (in terms of the adequate accuracy metrics you can output). 
- Conclude the most appropriate approach to this data set for the predictive task. 
- Write a report and send it in .pdf format that addresses all these guidelines with a maximum page number of 5 (including figures, tables, and references). We will consider the quality of the writing and presentation of the report.
