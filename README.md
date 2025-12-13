# Wheat-Price-Prediction-1968-2022-Using-Random-Forest-Regressor-Optimized-Using-Genetic-Algorithm
this project consists of a newer approach to price prediction where we use genetic algorithm to optimize random forest regressor to predict price of commodity (wheat) which uses a non- linear approach as compared to traditional methods such as ARIMA.
## Introduction
<p align="justify"> Agriculture plays a critical role in ensuring food security, economic stability, and rural livelihood development. In India, wheat represents a key crop whose pricing directly affects national food supply chains and market stability. Traditional price forecasting approaches often fail to capture the nonlinear and multi-dimensional relationships among environmental, production, and market variables. To address this gap, this research proposes a hybrid machine learning model that integrates a Genetic Algorithm (GA) with a Random Forest Regressor (RFR) for the optimization of hyperparameters, thereby improving prediction accuracy. The goal is to provide the government, farmers, and agribusinesses with a reliable forecasting tool that supports informed decision-making under uncertainty.

## Dataset Description
<p align="justify">
This dataset, rich with 25 independent variables and the crucial dependent variable Harvesting Price, provides a comprehensive understanding of the multi-dimentional factors influencing wheat pricing in Punjab. It captures the temporal dimension through the Year variable, shedding light on market conditions, climate, and external factors shaping pricing. Furthermore, it offers invaluable geographical insights via variables like Division, District, and Tehsil, allowing us to explore soil types, microclimates, and localized market dynamic's impact on wheat pricing.

Several critical variables, including Harvest Date, Wheat Variety, and Seed Type, play pivotal roles in determining crop quality, quantity, and pricing dynamics. Seed-related factors such as Seed Quantity (kg) and Sowing Date are instrumental in forecasting yield potential, while the Sowing Method significantly influences crop development. Fertilization variables like Organic Manure (Cow Dung) (kg), Urea Fertilizer (kg), and DAP Fertilizer (kg) directly affect crop vitality and economic outcomes. Soil type and irrigation method are crucial in defining the growing medium and hydraulic conditions, impacting crop development and financial results. No. of Watering Times and Residual Weed Material (kg) emphasize the interplay between moisture and weed control, while Previous Crop carries the legacy of past crops, impacting nutrient levels and diseases. Additionally, Seed Treatment, Number of Pest Sprays, and Number of Weed Control Sprays safeguard crops against pests and diseases. Finally, the dataset quantifies the crop's value through Yield (40 Kg/Acre) and Residual Material after Harvest (40 Kg/Acre), underscoring the influence of watering on agricultural outcomes.

With a substantial sample size of 44,424, the dataset is thoughtfully partitioned into a training set (80%) for model development and a testing set (20%) for validation, ensuring its robustness and applicability. This dataset offers a unique opportunity to gain comprehensive insights into the intricate dynamics of wheat pricing in Punjab, making it an invaluable resource for researchers, analysts, and stakeholders in the agricultural sector.

Key variable categories include:
- Temporal and Geographic Variables: Year, Division, District, Tehsil
- Seed and Crop Attributes: Harvest Date, Wheat Variety, Seed Type, Seed Quantity (kg), Sowing Date
- Soil and Fertilization Variables: Soil Type, Organic Manure (kg), Urea Fertilizer (kg), DAP Fertilizer (kg)
- Crop Management Variables: No. of Pest Sprays, No. of Weed Control Sprays, Irrigation Method, No. of Watering Episodes
- Economic Indicators: Yield (40 Kg/Acre), Residual Material after Harvest (40 Kg/Acre)

  ### Table 1: Summary of Descriptive Statistics for Variables within the Dataset
Variables                       | Minimum  | Median   | Maximum 
---                             | ---      | ---      | ---
Harvest Date                    | 0        | 2        | 22 
Wheat Variety                   | 1        | 6        | 13 
Seed Quantity (kg)              | 0        | 3        | 60 
Sowing Date                     | 0        | 3        | 6  
Organic Manure (kg)             | 0        | 1        | 4  
Urea Fertilizer (kg)            | 0        | 100      | 775
DAP Fertilizer (kg)             | 0        | 50       | 200
Soil Type                       | 0        | 1        | 3  
No. of Pest Sprays              | 0        | 0        | 3  
No. of Weed Control Sprays      | 0        | 1        | 13 
Yield (40 Kg/ Acre)             | 0.01452  | 35.211   | 82.80938
Residual Material (40 Kg/ Acre) | 0.680625 | 102.0938 | 1592.051
No. of Watering Episodes        | 0        | 3        | 10 
No. of Watering Episodes        | 0.12     | 1400     | 2600

