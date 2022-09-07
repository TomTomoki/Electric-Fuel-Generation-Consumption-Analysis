# Electric Fuel Generation and Consumption Analysis

This is a repository for my group project in the DAMG7290 Data Warehousing and Business Intelligence course.

Team Members: Tomoki Kyotani, Sai Bhavana Atluri, Jignasuben Rohitbhai Vekariya, Bhavya Maheshwari


In this project, I led the team meetings, managed my team members to complete each task on time, designed the Data Model and Data Flow, wrote the Python files for data generation and preprocessing, and built a complete ELT pipeline using SSIS which handles initial data load, data transformation, incremental data load, and Slowly Changing Dimensions (SCD).


## Introduction (quoted from our final report "FinalProject_Report.pdf")

> Nowadays the population is increasing day by day, use of energy sources and pollution is also increasing rapidly which affects weather as well. We decided to build a warehouse with respective fields for more effective analysis on how energy source generation and consumption is affected by population, pollution, and weather in the U.S.
> For our project, we selected four datasets named Electric power data, Population data, Pollution data, and Weather data from four different sources. The Electric Power dataset contains details of electricity production in the entire U.S. from every energy generation plant by month and having data up to 2021. The air pollution dataset contains data of different pollutants like Carbon Monoxide, Nitrogen Dioxide etc. being released in the air in the U.S. The population dataset contains the population estimates of the citizens and immigrants in the U.S. The weather dataset has the data about average, minimum and maximum temperature of everyday of 2015 for every state in the U.S.
> By aggregating and joining these 4 datasets by state and year variables, we’re trying to analyze how each of these factors affect the other.
