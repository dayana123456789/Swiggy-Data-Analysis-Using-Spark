# Swiggy-Data-Analysis-Using-PySpark and MYSQL

Swiggy is an online food delivary platform. This project deals with the analysis of Swiggy dataset using PySpark and MYSQL.
**PySpark** is a python API for Apache Spark. It is used to perform real-time, large-scale data processing in a distributed environment using Python. It also provides a PySpark shell for interactively analyzing your data.

# Analysis Workflow
Here's a brief overview of the workflow for this analysis:
1. **Data Import**: The Swiggy dataset was initially obtained from Kaggle https://www.kaggle.com/datasets/abhijitdahatonde/swiggy-restuarant-dataset/data and later loaded into a MySQL database.
2. **MySQL Integration**: A Python connector for MySQL was used to establish a connection to the MySQL database. This allowed for seamless retrieval of the dataset for further analysis.
3. **PySpark Analysis**: PySpark, a Python API for Apache Spark, was employed to analyze the Swiggy dataset. PySpark provides the capability to perform distributed data processing tasks, making it an ideal choice for handling large-scale datasets.

# Price Distribution
![download (5)](https://github.com/dayana123456789/Swiggy-Data-Analysis-Using-Spark/assets/99783461/5dd5f3ac-beab-46fa-9509-7fbe9067d30e)

* The dataset shows a left-skewed distribution of food prices, with a mean price of 348.44 rupees.
* The standard deviation from the mean is 230.92 rupees, indicating significant price variability.
* Food items in the 200-500 rupees price range are the most frequently ordered, suggesting this price range is popular among customers.
* The most frequently occurring food price in the dataset is 300.0 rupees, indicating a preference for food within this price range.

# Popular Restaurant - Cafe Cocomo

* Cafe Cocomo emerges as the highest-rated restaurant among customers.
* Several factors may contribute to its popularity, including exceptional service, food quality, affordability, a large customer base, prior visibility on Swiggy, or its location in a 
  densely populated area.
* The restaurant's high total ratings distinguish it from others.

# Average Ratings

* The average ratings of all restaurants in the dataset are similar to those of Cafe Cocomo.
* This suggests a balanced mix of both positive and negative ratings across the dataset.

# Most Popular Food Types

* Hyderabad South Indian cuisine tops the list as the most popular food type among customers.
* Bangalore South Indian cuisine holds the 10th place in popularity among food types.
  
![__results___21_0](https://github.com/dayana123456789/Swiggy-Data-Analysis-Using-Spark/assets/99783461/7674e05a-a6ed-47da-a6d6-1887240114e7)

This project showcases the use of PySpark and MySQL for the analysis of the Swiggy restaurant dataset. It offers valuable insights into the restaurant landscape on Swiggy, including pricing, ratings, and food types. 

Feel free to explore the provided notebook for detailed analysis and insights.

For any questions or feedback, please don't hesitate to contact me.

# **Happy analyzing!**
