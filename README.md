# Amazon-ML-2023
Amazon Machine Learning 2023 Hackathon

Product length prediction

In this hackathon, the goal is to develop a machine learning model that can predict the length dimension of a product. Product length is crucial for packaging and storing products efficiently in the warehouse. Moreover, in many cases, it is an important attribute that customers use to assess the product size before purchasing. However, measuring the length of a product manually can be time-consuming and error-prone, especially for large catalogs with millions of products.

You will have access to the product title, description, bullet points, product type ID, and product length for 2.2 million products to train and test your submissions. Note that there is some noise in the data.

Task: You are required to build a machine learning model that can predict product length from catalog metadata.

Dataset description:

train.csv: 2249698 x 6
test.csv: 734736 x 5
sample_submission.csv: 734736 x 2
The columns provided in the dataset are as follows:
![233914439-fa021fd2-b41a-4111-9e21-1f37ab49a12e](https://user-images.githubusercontent.com/109471459/234355862-3920bd87-d03c-41c2-aa1f-57aa9e54b74f.png)


The dataset folder contains the following files: 

Evaluation metric: score = max( 0 , 100*(1-metrics.mean_absolute_percentage_error(actual,predicted)))

Complete Dataset Google Drive Link: https://drive.google.com/file/d/1JTziUTO3EeCuq-oWM4e0HLaOR52utfAC/view?usp=share_link

Result submission guidelines

The index is "PRODUCT_ID" and the target is the "PRODUCT_LENGTH" column.
The submission file must be submitted in .csv format only.
The size of this submission file must be 734736 x 2.
Note: Ensure that your submission file contains the following:

Correct index values as per the test file
Correct names of columns as provided in the sample_submission.csv file
