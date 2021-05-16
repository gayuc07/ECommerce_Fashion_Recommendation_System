# SnapFash
#### An image-based e-commerce fashion recommendation system

Repository for image-based fashion/garment recommendation engine created for the M.S. capstone course in Data Science at GWU.

Authors: Anamay Agnihotri and Gayathri Chandrasekharan

## Introduction

The last decade has brought about a large wave in online retail and shopping. From groceries to electronics, the internet and it’s ever changing e-commerce ecosystem has made everything available at the doorstep across the world. In the US, e-commerce sales jumped from 5.1% of total retail sales in 2007 to 21% in 2020. Worldwide, the retail e-commerce market has roughly quadrupled in the last six years. Moreover, with the current pandemic, brick and mortar businesses are becoming less feasible and 2020 has seen a huge marketplace shift towards selling products on e-commerce platforms.

However, e-commerce, especially in the fashion and apparel domain, invites a sense of hesitancy in consumers. Unlike buying a car or electronics, consumers generally do not always have technical specifications when shopping for clothes. Being a largely visual experience, online garment shopping faces an array of challenges. From being overwhelmed with the never-ending options to browse through, to being unsure about finding the right sizes, consumers generally have a harder time finding and shopping for clothes due to the inherently subjective nature of the domain. The objective of this capstone is to address one such hurdle in fashion e-commerce by bridging the gap between what the consumer is looking for and what the e-commerce platform delivers. 

### Problem Statement

E-commerce fashion recommendations are highly sensitive to user interpretation of the product on the search engine. Text-based input from customers can be vague, and lead to irrelevant suggestions. An image-based recommendation system can better identify customer wants, thereby boosting sales for e-commerce vendors.

## Dataset

The SnapFash architecture utilizes two primary datasets

- DeepFashion Dataset
- e-commerce data - Flipkart and Myntra 

### DeepFashion Dataset

The DeepFashion database, which is a large scale fashion/clothes database with over 800,000 diverse fashion images, is a publicly available dataset. DeepFashion contains 50 categories of clothing, with each clothing image containing information on the category (class) and bounding box coordinates which specify exactly where in the image the item of clothing is located, also known as the region of interest. This dataset is used for training the object detection model that recognizes the type and location of the garment in the input image.

Source: http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html

### Ecommerce Dataset

The e-commerce data from Flipkart and Myntra was obtained from Kaggle and contains information on a wide array of retail products on the platforms. Combined, there are over 70,000 total products in this e-commerce dataset with information like product type, product url, product’s image urls, as well as other metadata. This dataset is used as a static database and product recommendations for the user are drawn from here.

Source: Kaggle - https://www.kaggle.com/PromptCloudHQ/flipkart-products

## Methodology

### Workflow - Development

![Dev_Workflow](images/dev_workflow.png?raw=true)






