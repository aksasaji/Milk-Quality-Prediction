# Milk-Quality-Prediction

Milk Quality Prediction
Life cycle of Machine Learning Project

-Understanding the problem statement

-Data Collection

-Exploratory Data Analysis

-Data Cleaning

-Data Pre-Processing

-Model Training

-Feature Imoortance Using Random Forest Classifier

-PCA of Features

-Artificial Neural Network

Description of Dataset:
This dataset is manually collected from observations. It helps us to build machine learning models to predict the quality of milk. This dataset consists of 7 independent variables ie pH, Temperature, Taste, Odor, Fat, Turbidity, and Color.

pH: This feature defines pH of the milk, which is in the range of 3 to 9.5. temperature: This feature defines the temperature of the milk, and its range is from 34'C to 90'C.

taste: This feature defines the taste of the milk and takes the possibles values: 1 (good) or 0 (bad).

odor: This feature defines the odor of the milk and takes the possibles values: 1 (good) or 0 (bad).

fat: This feature defines fat of the milk and takes the possibles values: 1 (good) or 0 (bad).

turbidity: This feature defines the turbidity of the milk and takes the possibles values: 1 (good) or 0 (bad).

colour: This feature defines the color of the milk, which is in the range of 240 to 255.

grade: This is the target and takes the values: low_quality, medium_quality, or high_quality.

We have to perform data processing, and data augumentation to build statistical and predictive models to predict the quality of the milk.

Conclusion:
-It can seen that,all the model accuracy is more than 70%. The highest accuracy is 100% of the Extreme Gradient Boost and Random Forest.
-The dataset pH and Temperature seem to be the most valuable features influencing the Grade of the Milk.
-Observed that temperature and color have over 95% composition to PC-1 and PC-2. For milk factory to ensure the quality of their product, these two parameters are the first priority
