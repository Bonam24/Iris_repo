# Iris_repo
Author Bonam Osene
Professor: Lawrence Nderu
About the Repo:
The Repo for comparing  the accuracy score of using different number of hidden layers of different models and their analysis.
My analysis suggests that increasing the number of hidden layers of the model decreases the accuracy.
This is because for relatively simpler problems like this one putting a lot of hidden layers leads to overfitting. Adding more hidden layers will only increase the accuracy for complex problems but will reduce the accuracy for simpler problems because of overfitting.
My accuracy score was 100 for c(50,3),  100% for  c(20,16,10,5) and 96.66% for  c(30,24,20,18,16,14,12,8,6,3).

Results
Tabular Report
Number of Hidden Layers	Accuracy (%)
6	100
10	100
2	96.67
Results:

Each model's accuracy is evaluated and compared. Plots of the neural network architecture and performance metrics are included.

Files Included
R Markdown Document (.Rmd): Contains the code for data preparation, model training, and evaluation. Output Document (.pdf): Compiled PDF report with results and plots. Installation and Usage To run the code, make sure to install the necessary R packages:

Requirements
R (version 4.0.0 or later)
R packages:
neuralnet
keras
tensorflow
tidyverse
Installation
Install R: If you don't have R installed, download and install it from CRAN.

Install Required Packages: Open R and run the following command to install the necessary packages:


