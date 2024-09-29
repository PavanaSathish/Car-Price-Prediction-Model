# Car-Price-Prediction-Model
This project uses Python and machine learning to predict the selling price of used cars based on various features like the car's make, year, mileage, engine size, and transmission.

Dataset
The dataset includes 8,148 car entries with 13 features, including:

Name: Car model
Year: Year of manufacture
Selling Price: Price sold (target variable)
KM Driven: Total kilometers driven
Fuel: Fuel type (Petrol, Diesel, Electric, etc.)
Seller Type: Seller category (Individual, Dealer, Trustmark Dealer)
Transmission: Gear type (Manual, Automatic)
Owner: Number of previous owners
Mileage: Fuel efficiency (km/l)
Engine: Engine size (cc)
Max Power: Power output (bhp)
Torque: Car torque
Seats: Number of seats
Key Steps:
Data Exploration & Visualization

Inspected missing values and data types.
Visualized car price distribution, sales trends by year, and fuel/seller type analysis.
Data Preprocessing

Encoded categorical variables (Fuel, Transmission, etc.) using Label Encoding.
Converted string values in Mileage, Engine, Max Power, and Torque to numeric values.
Model Building

Trained a Decision Tree Regressor to predict car prices.
Split data into 98% training and 2% testing using train_test_split.
Model Evaluation

Achieved an R² score of 0.965, indicating strong predictive accuracy.
Libraries Used:
pandas: Data manipulation
numpy: Numerical computations
matplotlib & seaborn: Visualizations
sklearn: Machine learning
This project showcases basic steps in machine learning, from data preprocessing to model evaluation.
