Car Price Prediction Project
Overview
This project uses a dataset of cars to build a machine learning model that predicts car prices. The dataset contains information about car brands, models, manufacturing years, mileage, engine power, fuel type, and more. A multivariate linear regression model is used for the price prediction task, along with various preprocessing techniques and visualizations.

Dataset
The dataset includes information on various car features such as:
Brand
Model
Year
Kilometers Driven
Fuel Type
Transmission
Owner Type
Mileage
Engine Capacity
Power
Seats
Price
The dataset is sourced from this CSV file.

Libraries Used
Pandas
Numpy
Matplotlib
Seaborn
Scikit-learn
Workflow
Data Preprocessing:

Handling missing values using SimpleImputer.
Encoding categorical features using OneHotEncoder.
Standardizing numerical features with StandardScaler.
Splitting the data into training and test sets using train_test_split.
Model Training:

A LinearRegression model is trained on the preprocessed data using a Pipeline to combine preprocessing and modeling steps.
Evaluation:

The model is evaluated using the root mean squared error (RMSE) and R² variance score.
Visualization:

2D and 3D scatter plots were created to explore the relationship between the year, kilometers driven, and price.
Model Metrics
Root Mean Squared Error (RMSE): 0.164
R² Variance: 0.932
How to Run
Clone the repository or download the project files.


git clone <repository_url>
Install the required Python libraries:

pip install -r requirements.txt
Run the Python script:


python car_price_prediction.py
Results
The regression model performed well, achieving an R² variance score of 0.932, meaning that the model explains about 93% of the variance in car prices based on the available features.

License
This project is licensed under the MIT License.
