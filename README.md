# BigMart Product Sales Prediction Project
<img align="center" alt="Coding" width="600" src="https://img.freepik.com/premium-photo/rear-view-young-woman-red-cap-standing-supermarket-reading-book-woman-with-shopping-store-shelf-ai-generated_538213-8058.jpg">

### Business Understanding
This project aims to analyze and predict the factors that most significantly influence product sales at BigMart. The dataset provides detailed information on 1,559 products across 10 stores, covering various attributes such as product weight, visibility, and store characteristics.

### Project Overview
By leveraging data from BigMart’s stores and products, we aim to identify the optimal store setup that maximizes product sales. This involves analyzing key product attributes and store features to determine which factors most affect sales performance.

### Dataset
The dataset contains the following key features:
- **Item_Weight**: Product weight in kilograms.
- **Item_Fat_Content**: Fat content of the product.
- **Item_Visibility**: Product visibility in stores.
- **Item_Type**: Type or category of the product.
- **Item_MRP**: Maximum retail price of the product.
- **Outlet_Establishment_Year**: Year the outlet was established.
- **Outlet_Size**: Size of the outlet.
- **Outlet_Location_Type**: Type of outlet location (urban, rural, etc.).
- **Outlet_Type**: Type of store (grocery or supermarket).
- **Item_Outlet_Sales**: Sales of the product in the outlet (target variable).

### Project Objective
The objective is to use machine learning models to predict which factors have the biggest influence on product sales. This insight will help in optimizing store setups and marketing strategies to drive higher sales.

### Model and Conclusion
After a comprehensive analysis, the **CatBoost Regressor** was identified as the best-performing model for predicting product sales. This model outperformed others based on key performance metrics, proving its reliability in handling the complexities of the dataset. This finding provides BigMart with actionable insights on store management and product marketing to optimize sales outcomes.
