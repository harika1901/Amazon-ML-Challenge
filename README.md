# PRODUCT LENGTH PREDICTION
### Amazon-ML-Challenge

**Purpose**
The purpose of this hackathon is to create a machine learning model that can predict a product's length dimension. The length of a product is an important quality that customers use to assess the product size before purchasing, and it is also important for packaging and storing things efficiently in the warehouse.

### Dataset
The dataset provided consists of two files, train.csv and test.csv, containing 2.2 million and 734,736 product records, respectively. The data contains the following columns:

PRODUCT_ID: Represents a unique identification of a product
TITLE: Represents the title of the product
DESCRIPTION: Represents the description of the product
BULLET_POINTS: Represents the bullet points about the product
PRODUCT_TYPE_ID: Represents the product type
PRODUCT_LENGTH: Represents the length of the product

### Task
It is required for participants to develop a machine learning model that, using the provided metadata, can forecast a product's length. The mean absolute percentage error (MAPE) is the assessment measure used for this hackathon, and the following formula is used to determine the score:
_**score = max(0, 100*(1 - metrics.mean_absolute_percentage_error(actual, predicted)))**_
