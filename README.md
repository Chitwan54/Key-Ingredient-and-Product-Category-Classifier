# Key-Ingredient-and-Product-Category-Classifier

**Problem Statement:**
1) Scraping Mamaearth’s Beauty category:
https://mamaearth.in/product-category/beauty 
Scarpe the website for the following basic data points:
● Product Name
● Product Link
● Rating
● Reviews
● MRP
● Pack Size
● Discount/Offers running on the product

2) Build a classification model which can fetch the key ingredient
used in the product and also classify the product based on its category. So, taking
Mamaearth Onion Hair Oil as an example, the key ingredient here is Onion and the
category is Hair Oil.

**Solution Description:**
1) **Selenium Web Driver** is used to scrape the website.
2) **Bag of words** pipeline is used for Data Preprocessing.
3) Classfiers such as **Logistic Regression, NaiveBayes, Decision Tree, Random Forest and XGBoost** are used for the classifcation tasks.

The Repository includes the following:
1) Jupyter Notebook containing the solution to the problem statement.
2) Scraped Dataset
3) README.md file
