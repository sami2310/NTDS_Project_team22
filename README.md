# Important note:
#### We are using Folium to display the maps and they don't show on the notebook on github.
#### Please run the code locally.


# Title

Small Components' Analysis and Flight Delay Prediction.

A Network Tour of Data Science project

##### Team 22:
  - Sami Ben Hassen.
  - Nourchene Ben Romdhane.
  - Firas Kanoun.
  - Ali Fessi.

# Abstract

In a more and more connected world, flight routes give us a great framework in order to see countries/cities that are socially isolated from the rest of the world. An access to the flight delays dataset gives us a great opportunity to try and predict if a given flight would have a delay.

# Datasets:

  - We will use the Openflights routes database from their websoite.
This OpenFlights/Airline Route Mapper Route Database contains 67,663 routes (EDGES) between 3,321 airports (NODES) on 548 airlines spanning the globe.

  - We will also use a subset of the 2015 flight delays and cancellations dataset .


# Project Description:
We split the project into 4 main parts:

  - ## Data Analysis:
    In the previous assignments,  we didn’t get the chance to visualise the data since we only explored it as agraph.  This project is a great opportunity to explore and analyze it using maps so that we can exactly seehow everything is connected.

 - ##  Smaller components analysis:
    The question we kept asking ourselves while working on the homework is ”How about the small components?”For this part, we located the components that are not part of the giant components we have deeply explored during the semester.

 - ##   North Korea:
    As a result of its isolation, North Korea is sometimes known as the "hermit kingdom", a term that originally referred to the isolationism in the latter part of the Joseon Dynasty. Initially, North Korea had diplomatic ties with only other communist countries. Here we explore its connections to other parts of the world.

 - ##   Predicting flight delays:
    In this section, we will explain the different steps we took in order to predict whether the delay corresponding to a flight departure time is negligible or not. We consider a delay negligible if the flight is only delayed by 30 minutes, less or not delayed at all. Otherwise, it is important. Many models/classifiers have been tried in order to come to the best result.
    ### The results:
    | Algorithm  |    Hyper-Parameter value|    Accuracy|
    | ------------- | ------------- | ------------- |
    | Gradient Boosted Trees     |17  |    87.021 |
    |Random Forest Classifier  |    100  |    86.02  |
    |K Nearest Neighbors |    29  |   86.97  |
    |Logistic Regression  |    0 |    87.02  |
