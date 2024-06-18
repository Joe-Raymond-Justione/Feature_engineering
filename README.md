
<div align="center">
  <a href="https://github.com/Joe-Raymond-Justione/Feature_engineering/assets/171755523/91a0bd35-95c5-4dca-942e-e2734634833f">
    <img src="https://github.com/Joe-Raymond-Justione/Feature_engineering/assets/171755523/91a0bd35-95c5-4dca-942e-e2734634833f" width="100%"/>
  </a>
</div>







_Feature engineering is the process of using domain knowledge to extract and create new features from raw data that can be used to improve the performance of machine learning models. This crucial step in the data preprocessing pipeline involves transforming and refining data to highlight the patterns and structures that machine learning algorithms can learn from more effectively._


Feature Engineering with NYC Airbnb Open Data using PySpark
##Introduction
Welcome to the Feature Engineering project using the New York City Airbnb Open Data dataset! This project aims to enhance the predictive performance of machine learning models by applying advanced feature engineering techniques. Specifically, we use PySpark with DataFrames to handle and process large datasets efficiently, demonstrating the power of big data tools in the realm of data science and machine learning.

In this project, we focus on creating five new data features to improve the performance of a supervised Linear Regression algorithm for predicting Airbnb home prices. By leveraging the capabilities of PySpark, we ensure that the feature engineering process is scalable and can handle the vast amounts of data typical in real-world scenarios.

[![Description](https://img.shields.io/badge/Description-black?style=for-the-badge&labelColor=black&color=lightyellow&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#description)

The objective of this project is to showcase the practical application of feature engineering techniques to improve the accuracy of machine learning models. Using the New York City Airbnb Open Data dataset, we implement the following steps:

[![Data Collection & Preprocessing](https://img.shields.io/badge/Data_Collection_&_Preprocessing-ff69b4?style=for-the-badge&color=tomato&labelWidth=700)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing)



Load and preprocess the raw data using PySpark DataFrames to ensure it is clean and suitable for feature engineering.

[![Feature Creation](https://img.shields.io/badge/Feature_Creation-ff69b4?style=for-the-badge&color=tomato&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing)

Generate five new features from the existing dataset to enhance the model's predictive power. These features are crafted using domain knowledge and data exploration insights.

[![Feature Transformation and Selection](https://img.shields.io/badge/Feature_Transformation_and_Selection-ff69b4?style=for-the-badge&color=tomato&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing)

Transform and select the most relevant features to ensure the Linear Regression model performs optimally.

[![Model Training and Evaluation](https://img.shields.io/badge/Model_Training_and_Evaluation-ff69b4?style=for-the-badge&color=tomato&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) 

Train the Linear Regression model using the engineered features and evaluate its performance to demonstrate the improvements achieved through feature engineering.

[![New Features Created](https://img.shields.io/badge/New_Features_Created-ff69b4?style=for-the-badge&color=tomato&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) 

Price per Square Foot: Calculated by dividing the price by the square footage of the listing.
Booking Rate: Derived from the number of bookings per month, indicating the popularity and demand for the listing.
Host Experience: Number of years the host has been active on Airbnb, providing insight into the host's experience level.
Review Score: Average review score of the listing, reflecting guest satisfaction and listing quality.
Seasonality Factor: Adjustment based on the time of year, accounting for seasonal variations in pricing.
Tools and Technologies
PySpark: For distributed data processing and efficient handling of large datasets using DataFrames.
Pandas: For initial data exploration and manipulation.
Scikit-learn: For implementing and evaluating the Linear Regression model.
Matplotlib and Seaborn: For data visualization and exploratory data analysis.
Project Structure
data/: Contains the raw and processed datasets.
notebooks/: Jupyter notebooks detailing the feature engineering process and model training steps.
scripts/: Python scripts for data preprocessing, feature creation, and transformation.
results/: Output files and evaluation results of the Linear Regression model.
README.md: Project overview and instructions.
Getting Started
To get started with this project, follow these steps:

Clone the repository:
sh
Copy code
git clone https://github.com/Joe-Raymond-Justione/Feature_engineering.git
Install the required dependencies:
sh
Copy code
pip install -r requirements.txt
Run the Jupyter notebooks or scripts to explore the feature engineering techniques.
Contributing
Contributions are welcome! If you have any suggestions, improvements, or additional feature engineering techniques to share, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

