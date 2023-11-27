# Used Car Price Prediction Competition
## Description

The demand for used cars has surged, creating an expansive market with the need for accurate pricing strategies. In response to this challenge, we present the Used Car Price Prediction Competition. Participants are tasked with developing machine learning models to predict the prices of used cars based on provided features. By doing so, contributors can aid businesses in formulating effective pricing strategies and gaining a competitive advantage in the growing pre-owned car market.[Competition Link](https://www.kaggle.com/competitions/used-car-price-prediction-competition2)


## Practice Skills

- Creative feature engineering: analyzing and transforming the provided features to enhance the performance of the models.
- Advanced regression techniques to build predictive models like random forest and gradient boosting.

## Evaluation

### Goal

It is your job to predict the price for each car. For each id in the test set, you must predict the value of the Price (Target) variable.

### Metric

Submissions are evaluated on R-Squared (R²), a statistical measure in a regression model that determines the proportion of variance in the dependent variable that can be explained by the independent variable.

## Submission File Format

The submission file should contain a header and follow this format:

```plaintext
id	Target
1	581851
2	4552.2
3	548122
```
## Dataset Description

### Columns
* ID: A unique identifier assigned to each car listing in the dataset.
* Price: The asking price set by the seller for the used car.
* Year: The year of manufacture or production of the vehicle.
* Manufacturer: The brand or manufacturer of the car (e.g., Toyota, Honda, Ford).
* Model: The specific model or variant of the car (e.g., Camry, Civic, Mustang).
* Condition: Describes the condition of the car, ranging from new to salvage.
* Cylinders: The number of cylinders in the car's engine.
* Fuel: The type of fuel used by the car (gasoline, diesel, electric, hybrid, etc.).
* Odometer: The recorded mileage or distance traveled by the vehicle.
* Title Status: Refers to the status of the car's title or ownership documents.
* Transmission: Specifies the type of transmission system in the car.
* Drive: Indicates the drivetrain configuration of the vehicle.
* Size: Describes the size or class of the car.
* Type: Refers to the body type or style of the car.
* Paint Color: Specifies the exterior color of the car.
* State: Indicates the state or location where the car is listed for sale.
* Latitude (Lat) and Longitude (Long): Geographical coordinates of the listing location.
* Posting Date: The date and time when the car listing was posted.
These fields provide comprehensive information about used cars, enabling various analyses and insights into market dynamics, pricing trends, vehicle characteristics, and buyer preferences.

### Files
* train.csv: The training set.
* test.csv: The test set.
* sample_submission.csv: A sample submission file in the correct format.
