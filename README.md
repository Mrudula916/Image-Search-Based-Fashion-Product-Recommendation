# Image-Search-Based-Fashion-Product-Recommendation

1. Introduction

Clothing is what describes a person’s first impression of the world. Having a statement piece of clothing is everyone’s dream. But how does one get that one favorite dress that can make them stand out in an event? What if one sees something they like is on the T.V and they want to get something similar by clicking a picture of it? This is where the idea of Image based fashion recommendation system comes into play. The motivation of this work is to develop and implement algorithms that can efficiently identify different clothing items in each query image and recommend related clothing items to the user. If the query image consists of multiple clothing items and/or accessories, the model is designed to identify the various items and recommend similar products for each item. This project is divided into 3 risk levels: Low risk, where simpler models are used to get the recommendations and the accuracy is not a main concern, medium risk, where accuracy is a primary concern and comparatively efficient algorithms are used and finally High risk, which combines the recommendations with object detection for multiple objects in each image. The following sections talk about the steps in detail.

2. Dataset Description
The dataset used for this task is the Fashion Product Images Dataset. This dataset is openly available on Kaggle. It consists of about 44k images of 143 unique and different classes. This dataset consists of csv files and Json files that contain meta data about each product such as their category, subcategory, article type, color, gender they can primarily worn by, the links for each image etc.

Fashion Product Images Dataset: https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset

