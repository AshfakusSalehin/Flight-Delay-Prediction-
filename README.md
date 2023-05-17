<!-- Predicting Flight Delays Using Spark Machine Learning (Spark MLlib)

Introduction:

Flight delays can be very frustrating to passengers and costly to airline companies. Flight delays are not easy to understand as they arise from multiple reasons like increase in air traffic at the origin or destination airport, weather etc. The on-time performance data of airline schedules could be useful to shed some light into causes of flight delays.

Dataset overview:
The U.S. Department of Transportation’s Bureau of Transportation Statistics (BTS) holds the record of all the domestic flights and their on-time, cancelled, delayed and diverted flight performances. The dataset has been collected from their Air Travel Report and contains 2015 flight summary. It can be downloaded here.

The dataset includes three csv files:

Flights.csv - It contains 31 columns describing each flight’s day, month, year, flight number, airline, scheduled arrival, origin airport, destination airport, scheduled departure, departure time, taxi out, taxi in, scheduled time, departure delay, elapsed time, weather delay, distance, wheels off, tail number, arrival time, arrival delay, diverted, cancelled, cancellation reason, air system delay, security delay, airline delay, late aircraft delay, air time.

Airlines.csv - It contains 2 columns of airlines names and their codes.

Airports.csv - It has 7 columns containing airport’s code and name, city, state, country, latitude and longitude. It contains 323 airport’s details with their codes.

Problem Statement:

The goal of this project is to construct a flight delay prediction model leveraging flight On-Time performance data and use the model for deriving insights about past flight delays. The on-time arrival data for non-stop domestic flights from US Department of Transportation (DoT) is used for this analysis.

Section: A (Exploratory Data Analysis)

To explore the dataset using the Spark SQL:                                                                                                        (50 Marks)

1.      Find out the Top 5 Longest departure delays

 2.     Find out the Average Departure Delay by Carrier

 3.     Find out the Count of Departure Delays by Carrier

 4.     Find out the Count of Departure Delays by Day of the Week

 5.     Find out the Count of Departure Delays by Hour of Day

 6.     Find out the Count of Departure Delays by Origin

 7.     Find out the Count of Departure Delays by Destination

 8.     Find out the Count of Departure Delays by Origin, Destination

 9.     Add Labels for Delayed Flights and count

 10.  Find out the Count of Departure Delays by Origin

                                                                                Section-B (Classification)

For this project, you will build different predictive models using traditional & popular machine learning algorithms like Logistic Regression, Decision trees & Random Forest to predict airline delays and use the following steps with PySpark.

Step-1: Basic operation                                                                                                                                                (50 Marks)

·         Reading a CSV file

·         Defining the Schema

Step-2: Data Exploration

·         Check the Data Dimensions

·         Describe the Data

·         Missing Values Count

·         Find Count of Unique Values in a Column

Step-3: Build a data processing pipeline

·      Transformers and Estimators

Step-4: Build the classifier

Step-5: Train and evaluate the model -->
