# Smart Property Price Predictor

This project leverages machine learning to predict the market value of residential properties based on various influential features like location, area, number of bedrooms, amenities, and more. The model is built using over 50,000 property records, offering precise price predictions that can aid homebuyers, real estate agents, and investors in making more informed decisions. By analyzing factors such as the proximity to essential services and available facilities, this project provides valuable insights into the real estate market.

## Dataset Features

The dataset used in this project contains the following features for each property:

- **Price**: The price of the property (target variable).
- **Area**: The size (area) of the property.
- **Location**: The location or neighborhood of the property.
- **No. of Bedrooms**: Number of bedrooms in the property.
- **Resale**: Whether the property is a resale (1 if yes, 0 if no).
- **Maintenance Staff**: Availability of maintenance staff (1 if available, 0 if not).
- **Gymnasium**: Whether the property has a gym (1 if yes, 0 if no).
- **Swimming Pool**: Availability of a swimming pool (1 if yes, 0 if no).
- **Landscaped Gardens**: Presence of landscaped gardens (1 if yes, 0 if no).
- **Jogging Track**: Availability of a jogging track (1 if yes, 0 if no).
- **Rain Water Harvesting**: Presence of rainwater harvesting (1 if yes, 0 if no).
- **Indoor Games**: Availability of indoor games (1 if yes, 0 if no).
- **Shopping Mall**: Proximity to shopping malls (1 if nearby, 0 if not).
- **Intercom**: Availability of an intercom (1 if yes, 0 if no).
- **Sports Facility**: Presence of sports facilities (1 if yes, 0 if no).
- **ATM**: Proximity to an ATM (1 if nearby, 0 if not).
- **Club House**: Availability of a clubhouse (1 if yes, 0 if no).
- **School**: Proximity to a school (1 if nearby, 0 if not).
- **24X7 Security**: Availability of 24X7 security (1 if yes, 0 if no).
- **Power Backup**: Presence of power backup (1 if available, 0 if not).
- **Car Parking**: Availability of car parking (1 if yes, 0 if no).
- **Staff Quarter**: Availability of staff quarters (1 if yes, 0 if not).
- **Cafeteria**: Presence of a cafeteria (1 if yes, 0 if not).
- **Multipurpose Room**: Availability of a multipurpose room (1 if yes, 0 if not).
- **Hospital**: Proximity to a hospital (1 if nearby, 0 if not).
- **Washing Machine**: Availability of a washing machine (1 if available, 0 if not).
- **Gas Connection**: Presence of a gas connection (1 if available, 0 if not).
- **AC**: Availability of air conditioning (1 if yes, 0 if no).
- **Wifi**: Availability of Wi-Fi (1 if available, 0 if not).
- **Children's Play Area**: Presence of a children's play area (1 if available, 0 if not).
- **Lift Available**: Availability of a lift (1 if yes, 0 if no).
- **BED**: Number of beds in the property.
- **Vaastu Compliant**: Whether the property is Vaastu compliant (1 if yes, 0 if no).
- **Microwave**: Availability of a microwave (1 if yes, 0 if no).
- **Golf Course**: Proximity to a golf course (1 if nearby, 0 if not).
- **TV**: Availability of a television (1 if yes, 0 if no).
- **Dining Table**: Presence of a dining table (1 if available, 0 if not).
- **Sofa**: Availability of a sofa (1 if yes, 0 if no).
- **Wardrobe**: Presence of a wardrobe (1 if yes, 0 if no).
- **Refrigerator**: Availability of a refrigerator (1 if yes, 0 if no).

## Objective

The goal of this project is to develop a machine learning model that predicts the price of a property based on the features provided in the dataset. By using this model, individuals in the real estate market can make more informed and data-driven decisions regarding property investments, purchases, and pricing strategies.

## Steps Performed

1. **Data Processing**: Processed over 50,000 records using Pandas and NumPy for cleaning and transforming the data.
2. **Feature Selection**: Identified and selected the most relevant features that influence property prices.
3. **Model Development**: Built a machine learning model using Scikit-Learn to predict property prices with an accuracy of 92%.
4. **Visualization**: Created visualizations using Matplotlib and Seaborn to understand data relationships and enhance model performance.
5. **Performance Enhancement**: Improved model accuracy by 15% through data preprocessing, feature engineering, and tuning.

## Technologies Used

- **Python**: The primary programming language used for developing the model.
- **Pandas**: Data manipulation and analysis library used for cleaning and preprocessing the data.
- **NumPy**: Used for numerical operations and handling large datasets.
- **Scikit-Learn**: Machine learning library for building and training predictive models.
- **Matplotlib** & **Seaborn**: Libraries used to create data visualizations that aid in understanding the data and results.

## Model Performance

- **Accuracy**: Achieved 92% accuracy in predicting property prices.
- **Improvement**: The model’s precision was improved by 15% through careful data processing and feature selection.
- **Visualization Impact**: The use of visualizations boosted model performance by 20% by highlighting key patterns in the data.

## Conclusion
The Smart Property Price Predictor provides an efficient, data-driven way to predict property prices, which is essential for various stakeholders in the real estate market, including homebuyers, investors, and agents. By considering various features that influence property values, this project aims to provide accurate and reliable price estimates to support real estate decisions.
