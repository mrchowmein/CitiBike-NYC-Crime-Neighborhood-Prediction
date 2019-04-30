# CitiBike NYC Crime Neighborhood Prediction Tools
Title of our paper under review for publication: Applying Predictive Analytics to Open Data: Rodent Complaints, Citi Bike Stations have Predictive Power of Crime in NYC

Overview: We created a classification dataset to predict crime in NYC. Each row represented a zipcode with the following features CitiBike docks, rat complaints, dog licenses, poverty, and bachelor degree information.  

This is a refactored set of tools/functions we used to extract, cleanse or prepare our data while building out dataset.
Original python code spanned over 10+ scripts as we played with different data or features while exploring.  Those scripts while used, was not incorporated during our final version of our paper.  The scripts were used to primarily extract the raw data. Later phases of our project, we used Excel/Google Sheets to easily create different trial datasets to feed into the different machine learning platforms used.

This notebook only contains some of the relevant functions as the heterogenous data cannot be easily created with a single python script. If you attempt to run all the functions, it may take more than 50+ hours. This is limited by the the Arcgis. We added a small sleep function to prevent the script from spamming Arcgis with large volumns of api calls.
