# UCB-Module-11-Assignment

**Link to [notebook](https://github.com/thechiangsta/UCB-Module-11-Assignment/blob/main/car_price_analysis.ipynb)**

## Overview
This repo contains data analysis on a Kaggle dataset about used car pricing. The goal of this analysis is to identify the key predictors for used car prices. And aims to provide a model for businesses to leverage in stocking vehicles and how to price them.

## Dataset
*   **Source:** Kaggle
*   **Description:**  The dataset contains information about used car prices, namely, categorical features of the car (make, model, year, etc.)
*   **Key Variables:**
    *   `region`: General region of the car's location (e.g. Prescott, Florida Keys)
    *   `price`: Price of the car
    *   `year`: Year of production of the car
    *   `manufacturer`: Car manufacturer (e.g. Toyota, Ford)
    *   `model`: Car model (e.g. Prius, Camry)
    *   `condition`: Condition (e.g. Excellent, Fair)
    *   `cylinders`: Number of engine cylinders (e.g. 6 cylinders, 8 cylinders)
    *   `fuel`: Fuel type (e.g. gas, diesel)
    *   `odometer`: Odometer reading (e.g. 12000)
    *   `title_status`: Car title (e.g. clean, salvage)
    *   `transmission`: Transmission type (e.g. automatic, manual)
    *   `VIN`: VIN of the car
    *   `drive`: Drive type (e.g. 4WD, AWD)
    *   `size`: Car size (e.g. sedan, truck)
    *   `type`: Vehicle type (e.g. car, truck)
    *   `paint_color`: Color of the car.
    *   `state`: State the car is located (e.g. California, Nevada).

## Findings
- **Age is the most important factor**: The age of the car has by far the biggest impact on its price.
- **Odometer reading is the second most important**: The distance a car has been driven is also very influential.
- **Drivetrain type matters**: The type of drive (e.g. 2WD, 4WD) is a significant factor.
- **Manufacturer plays a role**: The car's manufacturer has notable importance.
- **Engine and Vehicle Characteristics are Important**: Features like the number of cylinders, model, fuel type, and condition also contribute substantially to price.
- **Other Factors**: Transmission type, condition, title status, and paint color have moderate importance.

# Actionable Items
### Pricing Strategy:

- **Refine Age/Mileage Models**: Non-linear depreciation, mileage bands, regional adjustments.
- **Drive Type Pricing**: Premium/discount based on local demand (2WD vs AWD/4WD).
- **Manufacturer Adjustments**: Value differences based on brand reputation.
- **Dynamic Pricing**: Real-time adjustments using market data.

### Inventory Acquisition:

- **Prioritize Lower Mileage**: If cost-effective, target vehicles with lower odometer readings.
- **Stock Popular Brands**: Focus on manufacturers with strong resale value.
- **Strategic Condition Sourcing**: Balance high-end (excellent) with reconditionable vehicles.

### Marketing & Sales:

- **Highlight Age/Mileage**: 
Emphasize low mileage, newer age vehicles.
- **Targeted Ads**: Segment by vehicle characteristics (AWD SUVs, etc.).

### Ongoing Data & Analytics:
- **Model Refinement**: Regularly update pricing with new data.
- **Competitor Analysis**: Track similar vehicle prices.
- **Demand Forecasting**: Predict demand based on seasonality/economy.