
<div align="center">
  <a href="https://github.com/Joe-Raymond-Justione/Feature_engineering/assets/171755523/91a0bd35-95c5-4dca-942e-e2734634833f">
    <img src="https://github.com/Joe-Raymond-Justione/Feature_engineering/assets/171755523/91a0bd35-95c5-4dca-942e-e2734634833f" width="100%" style="margin-bottom: 20px;"/>
  </a>
</div>








`Feature engineering is the process of using domain knowledge to extract and create new features from raw data that can be used to improve the performance of machine learning models. This crucial step in the data preprocessing pipeline involves transforming and refining data to highlight the patterns and structures that machine learning algorithms can learn from more effectively.
`

[![Feature Engineering with NYC Airbnb Dataset using PySpark](https://img.shields.io/badge/Feature_Engineering_with_NYC_Airbnb_Dataset_using_PySpark-black?style=for-the-badge&labelColor=black&color=blue&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#description)

## Introduction :

Welcome to the Feature Engineering project using the New York City Airbnb Open Data dataset! This project aims to enhance the predictive performance of machine learning models by applying advanced feature engineering techniques. Specifically, we use PySpark with DataFrames to handle and process large datasets efficiently, demonstrating the power of big data tools in the realm of data science and machine learning.

In this project, we focus on creating five new data features to improve the performance of a supervised Linear Regression algorithm for predicting Airbnb home prices. By leveraging the capabilities of PySpark, we ensure that the feature engineering process is scalable and can handle the vast amounts of data typical in real-world scenarios.

## Description :

The objective is to create `Features` that improve the accuracy of a basic Machine Learning model. Using the New York City Airbnb Open Data dataset, we implement the following steps:

## Data Collection & Preprocessing :

Here we `Load and preprocess` the raw data using PySpark DataFrames to ensure it is clean and suitable for feature engineering.

## Feature Creation :

Generate `Five` new features from the existing dataset to enhance the model's predictive power. These features are crafted using domain knowledge and data exploration insights.

## Feature Transformation and Selection :

Transform and select the most relevant features to ensure the Linear Regression model performs optimally.

## Model Training and Evaluation :

Train the Linear Regression model using the engineered features and evaluate its performance to demonstrate the improvements achieved through `Feature Engineering`.

[![New Features Created](https://img.shields.io/badge/New_Features_Created-ff69b4?style=for-the-badge&color=lavender&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) <sup>:</sup>

[![Feature 1](https://img.shields.io/badge/Feature_1-ff69b4?style=plastic&color=lavender&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) <sup>:</sup> <sup>Location popularity</sup>

Determines the popularity of the neighbourhood based on the total number of listings in that neighborhood and the total number of listings for each host. More popular locations might command higher prices.

[![Feature 2](https://img.shields.io/badge/Feature_2-ff69b4?style=plastic&color=lavender&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) <sup>:</sup> <sup>Host popularity</sup>

Based on the availability of the host, I decided their popularity. If they are available for less than 30 days in a year then the host is considered very popular among clients.

[![Feature 3](https://img.shields.io/badge/Feature_3-ff69b4?style=plastic&color=lavender&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) <sup>:</sup> <sup>Host Experience</sup>

Calculating a metric that represents the experience of the host based on the number of listings they have and the number of reviews they receive. This can indicate the reliability or attractiveness of the host's properties. Based on this I categorize them.

[![Feature 4](https://img.shields.io/badge/Feature_4-ff69b4?style=plastic&color=lavender&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) <sup>:</sup> <sup>Booking density</sup>

Calculating the ratio of the number of reviews to the availability of the listing. Higher booking density might indicate high demand, influencing prices.

[![Feature 5](https://img.shields.io/badge/Feature_5-ff69b4?style=plastic&color=lavender&logoColor=white&labelWidth=200)](https://github.com/Joe-Raymond-Justione/Feature_engineering#data-collection-preprocessing) <sup>:</sup> <sup>Room Diversity</sup>

Measures the diversity of room types offered by hosts. Hosts offering a variety of room types might attract a wider range of guests and potentially charge higher prices.

`Tools and Technologies` :

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=black)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=yellow) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![GoogleColab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

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

