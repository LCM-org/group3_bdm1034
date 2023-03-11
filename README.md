# CabSurgeArea
 
Subject: 2023W-T2 BDM 1034 - Application Design for Big Data 01
Group Number: Group 3
Group Members:
    Javier Melo Diagama
    Jenny Jitendra Joshi
    Lucia Martinez Torres
    Olivia Deguit
    Rochan Mehta

Project Name: Cab Surge Area
Overview and Objective:
    This group project is the implementation of what we have learned about data science, machine learning using Python. The main objective of the project is to determine the Cab Surge per Area. Our dataset includes 693071 records with 57 columns.
    Out of the 57 columns we are utilizing the 'datetime' and 'source' to identify the area and the cab surge based on day of the week and time. 'source' field is a categorical type of data and we converted this to numerical values using mapping. For the distribution of data set, we are using 90% to train and 10% to test the dataset. We are utilizing MongoDB as our DB to store reference data and preditcion data. For the map generator we generally used folium library in Python. Matrixes and other graphical representation to show the model is targeted to be covered in the project as well.
    
Dataset Filename: rideshare_kaggle.csv