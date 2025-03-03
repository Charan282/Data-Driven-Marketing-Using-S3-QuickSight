# Data-Driven-Marketing-Using-S3-QuickSight
📌 Overview
This project focuses on analyzing e-commerce product listings to extract valuable insights about product availability, pricing trends, brand popularity, and seller performance. By leveraging data processing and visualization techniques, we aim to uncover patterns that can help optimize inventory management, pricing strategies, and customer targeting.
# Features
product_id	title	availability	brand	categories	price (USD)	seller_id	seller_name	url
# Technologies Used
AWS S3, AWS QuickSight
# Usage
Dataset is from Brightdata. The dataset is only the subset dataset. 
# Process
Open S3 and Create a bucket with a name and upload both the dataset and also the json file but before uploading json file, open it and change the name of bucket as your bucket name and save and upload the new json file. Open amazon quicksight and sign in to it.  Give a name to quicksight account and email address. Make sure to select the S3 bucket we created under S3 service which can be seen. Go to amazon QuickSight and click on New datasets, S3 and then copy the URL of json file which was uploaded in S3 before and paste it in the upload a manifest.file place and give a data source name and then Visualize. By clicking create, We can visualize columns and name the sheet, Most popular brands. Drag brands to window and click on brand and sort options and do descending by count. And we can also insert various visual types and use them. We can create additional visualizations too.
