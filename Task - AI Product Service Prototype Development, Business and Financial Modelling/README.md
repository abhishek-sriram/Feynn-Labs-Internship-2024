# CropSenseAI - Revolutionizing Small-Scale Farming with Data-Driven Solutions

## Project Overview
**CropSense AI** is an intelligent, data-driven crop management system designed to empower small-scale farmers with real-time insights and recommendations. The system uses advanced AI models to predict crop yields, suggest optimal planting times, and alert farmers to potential pest threats. With CropSense AI, we aim to bridge the gap between traditional farming practices and modern AI-driven solutions, offering a sustainable, efficient farming experience.

## Features
- **Crop Yield Prediction**: Provides accurate predictions to help farmers optimize their harvest times.
- **Pest and Disease Alerts**: Early detection of conditions favorable to pests and diseases, enabling preventive actions.
- **Planting Schedule Optimization**: Recommends the best planting times based on localized weather and soil data.
- **Resource Efficiency**: Offers insights into the best use of water and fertilizers, reducing wastage and input costs.

## Technologies Used
- **Python**: Core programming language for data processing and model building.
- **Pandas, NumPy, Scikit-learn**: For data cleaning, preprocessing, and implementing machine learning models.
- **Matplotlib, Seaborn**: For data visualization.
- **Linear Regression and Random Forest Regressor**: Used for crop yield prediction.

## Data Collection and Preprocessing
- Data was collected from sources like Kaggle, including weather conditions, soil properties, and crop yields across different regions.
- **Missing values** were handled using statistical methods like mean and median imputation.
- **Outlier detection** was performed using the IQR method and boxplots.

## Data Visualization
Key visualizations were generated, such as:
- **Distribution plots** to examine the spread of features like temperature and humidity.
- **Scatter plots** to visualize relationships between environmental factors and crop yield.
- **Correlation heatmaps** to identify strongly correlated variables.

## Machine Learning Models
- **Linear Regression**: Used as the baseline model for crop yield prediction.
- **Random Forest Regressor**: The final model selected for its superior performance in handling complex relationships, resulting in higher accuracy.
