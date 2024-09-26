# LaptopPricePredict
In this project, various methods were employed to predict laptop prices using machine learning techniques. Here’s a detailed overview of the methods used:

Data Preprocessing: Initially, the dataset underwent preprocessing to remove unnecessary columns and convert data types to appropriate formats. For instance, variables like RAM, weight, and screen resolution were transformed into usable formats.

Feature Engineering: New features were created to enhance the dataset. For example, features such as touch screen and IPS were engineered, and the pixel density (PPI) of the screen was calculated. Additionally, storage types and capacities were processed to derive meaningful insights.

Train-Test Split: The dataset was divided into training and testing sets to allow for a robust evaluation of the model's performance. This step is crucial for ensuring that the model can generalize well to unseen data.

Model Building: Various regression algorithms were utilized to construct prediction models. The methods included:

Linear Regression: A foundational model that predicts a dependent variable based on one or more independent variables.
Ridge Regression: A regularized version of linear regression that helps prevent overfitting by adding a penalty for large coefficients.
Lasso Regression: Similar to Ridge but uses L1 regularization, which can shrink some coefficients to zero, effectively performing feature selection.
K-Nearest Neighbors (KNN): A non-parametric method that predicts prices based on the average price of the 'k' nearest neighbors in the feature space.
Support Vector Regression (SVR): A regression technique that uses support vector machines to predict continuous outcomes.
Random Forest Regression: An ensemble method that builds multiple decision trees and averages their predictions to improve accuracy and control overfitting.
Model Evaluation: The performance of each model was assessed using various metrics, including R² score and Mean Absolute Error (MAE). These metrics provided insights into how well each model was able to predict laptop prices.

Result Visualization: The results obtained from the different models were visualized using graphs and charts, allowing for an easier comparison of their performance.
