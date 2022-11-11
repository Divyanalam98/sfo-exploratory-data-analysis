# PLACES TO AVOID ON YOUR FIRST DATE IN SAN FRANCISCO

**_Pre Requisites:_** _Python, Basic Python Libraries_

**_Packages and Libraries used:_** _NumPy, Pandas, Matplotlib,Ipyleaflet_

In San Francisco, you can find more interesting dates than the typical coffee dates or happy
hour beverages. San Francisco is a beautiful city well-known for its landscape and
restaurants, and it’s a city filled with young people.

First dates are important, you do not want to end up in an embarrassing situation.

![Image](https://github.com/Divyanalam98/sfo-exploratory-data-analysis/blob/main/images/image2.png)

In this project, we would be finding restaurants to avoid going to based on risk category,
inspection score and other parameters. Good news, we would be finding some safe places as
well!

The dataset is downloaded from Kaggle
(https://www.kaggle.com/datasets/datasf/sf-restaurant-inspection-scores).Here’s some more
description of the dataset:

The SF Health Department has developed an inspection report and scoring system. After
conducting an inspection of the facility, the Health Inspector calculates a score based on the
violations observed. Violations can fall into:high risk category: records specific violations
that directly relate to the transmission of food borne illnesses, the adulteration of food
products and the contamination of food-contact surfaces.moderate risk category: records
specific violations that are of a moderate risk to the public health and safety.low risk
category: records violations that are low risk or have no immediate risk to the public health
and safety.The score card that will be issued by the inspector is maintained at the food
establishment and is available to the public in this dataset.


San Francisco's LIVES restaurant inspection data leverages the LIVES Flattened Schema
(https://goo.gl/c3nNvr), which is based on LIVES version 2.0, cited on Yelp's website
(http://www.yelp.com/healthscores).

In this project, we would be looking at :
● Top 20 High Risk Restaurants
● Top 20 Violations observed in the restaurants
● Zipcodes with most high risk restaurant count
● Checking if one inspection score would help in determining the restaurant safety.
● Map with locations of safe restaurants marked.

The results obtained are mentioned below. Respective graphs and descriptions are provided
as well.

![Image](https://github.com/Divyanalam98/sfo-exploratory-data-analysis/blob/main/images/image5.png)

_Figure 1: head and tail of dataframe_

![Image](https://github.com/Divyanalam98/sfo-exploratory-data-analysis/blob/main/images/image1.png)

_Figure 2: Top 20 High Risk Restaurants in San Francisco ( based on risk category)_

![Image](https://github.com/Divyanalam98/sfo-exploratory-data-analysis/blob/main/images/image6.png)

_Figure 3: Top 20 violations found in the restaurants_

![Image](https://github.com/Divyanalam98/sfo-exploratory-data-analysis/blob/main/images/image4.png)

_Figure 4: Zipcodes with the most high risk restaurants_

![Image](https://github.com/Divyanalam98/sfo-exploratory-data-analysis/blob/main/images/image7.png)

_Figure 5: Safe Restaurants in San Francisco ( low risk category and inspection score =100)_

![Image](https://github.com/Divyanalam98/sfo-exploratory-data-analysis/blob/main/images/image3.png)

_Figure 6: Safe Restaurants plotted/marked on San Francisco map_
