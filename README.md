# Flipkart Air Conditioner Web Scraping & Analysis 📊❄️
## Project Overview

This project focuses on web scraping, data analysis, and visualization of Air Conditioner products listed on Flipkart.
The goal is to analyze pricing, features, ratings, reviews, energy efficiency, and brand positioning to help customers identify the best value-for-money air conditioners.

## The project includes:

* A Python web scraping notebook
* A Power BI interactive dashboard
* A presentation (PPT) explaining the end-to-end analysis
## Business Problem

Flipkart offers a large number of air conditioner models with varying:

* Prices

* Features

* Energy ratings

* Customer reviews and ratings

This variety makes it difficult for customers to choose the right AC.
This analysis aims to identify:

* Key factors influencing price

* Relationship between price, features, and customer satisfaction

* Best-performing brands in terms of value for money

## Objectives

* Analyze and compare Flipkart air conditioner models

* Identify factors affecting pricing and customer satisfaction

* Provide insights for informed purchasing decisions

* Understand brand positioning (budget, mid-range, premium)

## Tools & Technologies Used

* Python

* Requests

* BeautifulSoup

* Pandas

* NumPy

* Matplotlib / Seaborn

* Power BI

* Jupyter Notebook

## Dataset Information

* Source: Flipkart (Web Scraped)

* Rows: 2,288

* Columns: 18

* Includes:

         * Brand

             * Price (Original & Discounted)
             * Ratings & Reviews
             * Energy Rating
             * Power Usage
             * Capacity (Tonnage)
             * Model Year

# Data Collection (Web Scraping)

* Identified relevant HTML elements using browser developer tools

* Scraped product data such as:

                     * Price
                     * Ratings
                     * Reviews
                     * Features

* Used Requests and BeautifulSoup to fetch and parse web pages

* Stored raw data for cleaning and analysis

# Data Cleaning & Preprocessing

* Removed unwanted characters (₹, commas, text labels)

* Converted price, ratings, reviews, and discounts to numeric format

* Extracted and standardized:

                    * Brand names

                    * Tonnage

                    * Energy ratings

                    * Annual power usage

                    * Room size

* Handled missing values and corrected data types

* Renamed columns for better readability

* Treated outliers to improve analysis reliability

## Exploratory Data Analysis (EDA)
### Univariate Analysis

* Majority of ACs are 2025 models, showing focus on newer products

* Blue Star has the highest product share

* Several brands have limited market presence

### Bivariate Analysis

* Premium brands (LG, IFB, Daikin) have higher prices

* Budget brands (MarQ, Lloyd) focus on affordability

* Mid-range price segment shows highest customer engagement

* No strong linear relationship between price and reviews

* Slight decline in average ratings from 2024 to 2025

### Multivariate Analysis

* Strong correlation between original price and discount price

* Power usage moderately affects price

* Ratings and reviews have weak influence on pricing

* Some budget brands offer high ratings at lower prices

* Limited availability of 5-star energy-efficient models


# Power BI Dashboard

The Power BI dashboard provides:

* Brand-wise price comparison

* Rating and review distribution

* Energy rating analysis

* Price vs customer engagement insights

* Interactive filters for better exploration

## Power BI DashBoard 1
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/6e4163bf-4be0-42f4-a2b3-0be5126f8c71" />


## Power BI DashBoard 2
<img width="1920" height="1020" alt="Screenshot 2025-12-18 113321" src="https://github.com/user-attachments/assets/da95eb65-85c8-4e2b-9e0c-5745c535c77b" />

## Presentation

* A detailed PPT explaining:

* Business problem

* Objectives

* Web scraping process

* Data cleaning steps

* Key insights and visualizations

* Conclusion and challenges faced
## Conclusion

* Flipkart primarily lists newer AC models

* Premium pricing does not always guarantee better ratings

* Mid-range and budget brands often provide better value

* Energy efficiency should be prioritized alongside price

* Discounts play a major role in influencing purchase decisions

## Challenges Faced

* Website structure changes during scraping

* Inconsistent and unstructured raw data

* Handling mixed text and numeric values

* Outlier treatment without losing meaningful insights

* Ratings and reviews not always aligning with pricing
