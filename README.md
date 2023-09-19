### Project goals

- To predict the quality of wine while incorporating unsupervised learning techniques. 


### Project description

- I've been tasked to find drivers of wine quality for the California Wine Institute. 

### The Plan 

### Initial hypotheses

- Amount of Alcohol present determines the quality
- 
- 

### Acquire: 
- Acquire the data from Data.World as CSVs
- You will need to use the winequality-red.csv and winequality-white.csv
- Combines into a Total csv called wine.csv and should save in current folder

### Prepare


### Explore: 

- QUESTIONS OF THE DATA
- 
- 
- What are the features that have the highest effect on the Quality of wine?
    - 1: Alcohol
    - 2: Free Sulfur Dioxide
    - 3: Total Sulfur Dioxide
- What are the features that have the least effect?
    - 1: Fixed Acididty
    - 2: Volatile Acidity
    - 3: Citric Acid
    - 4: Residual Sugar
    - 5: Chlorides
    - 6: Density
    - 7: pH
    - 8: Sulphates
- How do these features stand up to the Mann-Whitney TTest?

|feature_vs_quality	| test_statistic | p_value |
|------------|---------------|------------|
| fixed_acidity | 2359532.0 | 0.000000e+00 |
| volatile_acidity | 15186609.0 | 0.000000e+00 |
| citric_acid | 15186609.0 | 0.000000e+00 |
| residual_sugar | 9558465.5 | 1.477977e-88 |
| chlorides | 15186609.0 | 0.000000e+00 |
| free_sulfur_dioxide | 702421.5 | 0.000000e+00 |
| total_sulfur_dioxide | 2034.0 | 0.000000e+00 |
| density | 15186609.0 | 0.000000e+00 |
| ph | 15118202.0 | 0.000000e+00 |
| sulphates | 15186609.0 | 0.000000e+00 |
| alcohol | 921.0 | 0.000000e+00 |
| quality | 7593304.5 | 1.000000e+00 |
| is_red | 15186609.0 | 0.000000e+00 |

### Modeling: 
- Use drivers in explore to build predictive models of different types
- Evaluate models on train and validate data
- Select the best model based on accuracy
- Evaluate the test data


### Data dictionary:

| Feature | Definition |
|--------|-----------|
|Fixed Acidity| These acids play a crucial role in balancing the wine's taste and imparting freshness.|
|Volatile Acidity| Volatile acidity represents the portion of acidity in wine that can be detected through its aroma, in contrast to those acids that are perceptible through taste. High volatile acidity, often referred to as wine sourness, is a common wine defect.|
|Citric Acid| Citric acid is an allowable additive in winemaking. It serves three main purposes: adjusting wine acidity, wine fining, and filter cleaning to prevent fungal and mold contamination.|
|Residual Sugar| Residual sugar refers to the grape sugar that remains unfermented and retains its sweetness in the wine.|
|Chlorides| The mineral content in wine, including chlorides, sulfates, sulfites, and metal cations (e.g., potassium, sodium, magnesium), significantly influences its taste profile, including salinity or "sapidità." These constituents are influenced by factors like climate, oenological practices, storage, and aging conditions.|
|Free Sulfur Dioxide| Sulfur dioxide, commonly referred to as SO2, is employed as a preservative in wine due to its antioxidant and antimicrobial properties. Molecular SO2 acts as a crucial antimicrobial agent, preventing spoilage caused by microorganisms, including wild yeast.|
|Total Sulfur Dioxide| Sulfur dioxide, commonly referred to as SO2, is employed as a preservative in wine due to its antioxidant and antimicrobial properties. Molecular SO2 acts as a crucial antimicrobial agent, preventing spoilage caused by microorganisms, including wild yeast.|
|Density| Wine's density can either exceed or fall below that of water. It primarily depends on the concentration of alcohol and sugar. Generally, white, rosé, and red wines have lower densities at 20°C than 998.3 kg/m³.|
|pH| pH is a measure of wine's acidity level, with the ideal range falling between 2.9 and 4.2. Lower pH values indicate higher acidity, while higher pH values signify lower acidity.|
|Sulphates| Sulfates are naturally produced during yeast fermentation of wine sugars into alcohol, and the presence of sulfites in wine is negligible.|
|Alcohol| The alcohol content in wine varies based on factors such as grape variety, sugar content in the grapes, production techniques, and growing conditions. Wine alcohol content can range from 4.5% to 22%, depending on the wine category.|
|Quality| Quality is a target variable in the dataset, indicating the overall quality or rating of the wine.|
|Color Type| red or white|

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