# CitiBike NYC Crime Neighborhood Prediction Tools
Title of our paper under review for publication: Applying Predictive Analytics to Open Data: Rodent Complaints, Citi Bike Stations have Predictive Power of Crime in NYC


This is a refactored set of tools/functions we used to extract, cleanse or prepare our data while building out dataset.
Original python code spanned over 10+ scripts as we played with different data or features while exploring.  Those scripts while used, was not incorporated during our final revision of our paper.

This notebook only contains some of the relevant functions as the heterogenous data cannot be easily created with a single python script. If you attempt to run all the functions, it may take more than 50+ hours. This is limited by the the Arcgis. We added a small sleep function to prevent the script from spamming Arcgis with large volumns of api calls.
