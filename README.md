# InstaCart Market Basket Analysis
CMPE-255 Main Project Team-8
This repository is for the project-Instacart Market Basket Analysis. It consists of data cleaning, exploratory data analysis,data visualization and machine learning algorithms developed for the project.


# Project Team Members:
Akhila Kumari Puppala - akhila.puppala@sjsu.edu

Ashwin Kumar - ashwin.kumar01@sjsu.edu

Divya Mittal - divya.mittal@sjsu.edu


# Steps to run the project:

Clone the repository into your local directory

Open Google Colab or Jupyter Noetbooks

Upload the .ipynb file

Download the dataset and upload in the google colab local directory

Execute the code

# Data Sources:
Instacart open-sourced 3 Million of their Instacart Orders. This data is also available on Kaggle: https://www.kaggle.com/c/instacart-market-basket-analysis/data

This anonymized dataset contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, Instacart provide between 4 and 100 of their orders, with the sequence of products purchased in each order. Data also provide the week and hour of day the order was placed, and a relative measure of time between orders.


# Objective :
This project aims to help Instacart to analyze and utilize the customer transaction data while defining the customer behavior and the types of items that are purchased in combinations and the number of units of each purchased item in order to facilitate reorder and maintain adequate product stock. Furthermore, to identify segments and sub-groups of customers that possess similar purchasing behavior, as well as visualize the data to develop recommendations that aim to improve the company's revenues and customer experiences through segmentation and prediction models.


The project is divided into 3 parts which includes creating segmentation of users, then the relationship is calculated between different products which is fed to the model to recommend products to new as well as existing users based on their buying pattern.

# file-1 : Exploratory_Data_Analysis.ipynb
With the information collected we must have a way to paint a picture of that data so we can interpret it. Data visualization gives us a clear idea of what the information means by giving it visual context through maps or graphs. Provided data is explored using graphs and word clouds.

# file-2 : CustomerSegmentation.ipynb
Here, we identified the users based on their habits and preferences. The users average is calculated based on their rate of ordering from different aisles. The data is sent to different algorithms to segment the customers. Algorithms used for this process are Kmeans, Agglomerative and MinibatchKMeans. The data is then converted into a csv. Output of this file can be found in #clusters Folder

# file-3: Association Rules For clusters.ipynb
The generated csv file from file-1 is processed by Apriori algorithm and association rules algorithm and generated csv file containing rules.Output of this file can be found in #Association Rules Folder

# file-4: Recommendation_System.ipynb
Here, the Apriori data is used in making a recommendation system by using Natural language Processing algorithms and Classification Models.
