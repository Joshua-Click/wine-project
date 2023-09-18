### Project goals

- To predict the quality of wine while incorporating unsupervised learning techniques. 


### Project description

- I've been tasked to find drivers of wine quality for the California Wine Institute. 

### The Plan 

### Initial hypotheses

- Amount of Alcohol present determines the quality?
- 
- 

### Acquire: 
- Acquire the data from Data.World as CSVs
- You will need to use the winequality-red.csv and winequality-white.csv

### Explore: 

- QUESTIONS OF THE DATA
- 
- 
- 
- 

### Modeling: 
- Use drivers in explore to build predictive models of different types
- Evaluate models on train and validate data
- Select the best model based on accuracy
- Evaluate the test data


### Data dictionary:

| Feature | Definition |
|--------|-----------|
|Fixed Acidity| Number of Bedrooms|
|Volatile Acidity| Number of Bathrooms|
|Citric Acid| Usable Square Footage of Home|
|Residual Sugar| Price of Home|
|Chlorides| Year house was built|
|Free Sulfur Dioxide| Square Footage of the entire property lot|
|Total Sulfur Dioxide| County location of home|
|Density| Number of Cars that Fit in Garage|
|pH| Square Footage of the Garage|
|Sulphates| Last time the house was sold in 2017|
|Alcohol| Number of Cars that Fit in Garage|
|Quality| Square Footage of the Garage|
|Color Type| Last time the house was sold in 2017|

### How to Reproduce
- Clone this repo
- Acquire data https://data.world/food/wine-quality
- Run Notebook

### Key findings 
- 
- 

### Takeaways and Conclusions
- After running scaled data through the model
- Test data ran on Model 4
    - 39.7% accuracy overall
- Still quite low and only within 338k of the correct home value price which is alot of error.
### Recommendations
- Recommend splitting data into counties and adding more features to the data collected in order to potentially predict Home Values in the future.
- Simply having just bedrooms, bathrooms, and finished area are not enough to predict home values.