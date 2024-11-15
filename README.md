# ML-data_processing

This project focuses on data preprocessing for a machine learning pipeline aimed at enhancing food productivity through irrigation modernization in Rwanda. The notebook `ml_pipeline_Johnson_Noe_Tuyishime_data_preprocessing.ipynb` outlines the following key steps:

- **Data Sources and Aggregation**: Data is sourced from Google Datasets, Kaggle, and IoT sensors monitoring climate, soil, and crop health.

- **Data Format Transformation**: Data is cleaned, normalized, and transformed to ensure consistency and usability for analysis.

- **Data Exploration**: Exploratory Data Analysis (EDA) is performed to understand correlations, data distributions, and identify patterns or trends.

- **Handling Missing Data**: Techniques such as mean imputation, forward fill, and backward fill are used to handle missing values.

- **Feature Selection**: Important features are identified using methods like random forests and mutual information.

- **Data Splitting**: The dataset is split into training, validation, and testing sets.

- **Model Training**: Machine learning models, such as Random Forest Regressor, are trained and evaluated.

- **Data Transformation for Modeling**: Numerical data is normalized or standardized, and categorical data is encoded.

- **Data Storage**: Processed data is stored in a PostgreSQL database for structured storage.