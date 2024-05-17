# Flight Ticket Price Prediction

## Problem Statement
# Flight Fare Prediction

Predicting flight ticket prices accurately is challenging due to their dynamic nature. Prices can fluctuate frequently, making it difficult for both airlines and travelers to anticipate costs. In this project, we aim to leverage machine learning to predict flight ticket prices, providing airlines with valuable insights for pricing strategies.

## Dataset Overview
The dataset contains the following columns:

1. **Airline**: Name of the airline operating the flight.
2. **Date_of_journey**: Date of the flight journey.
3. **Source**: Departure location.
4. **Destination**: Arrival location.
5. **Route**: Flight route.
6. **Arrival_Time**: Arrival time of the flight.
7. **Duration**: Duration of the flight in hours and minutes.
8. **Total_Stops**: Total number of stops in the flight.
9. **Additional_info**: Additional information about the flight booking, such as food options, baggage policies, etc.
10. **Price**: Price of the flight for the complete journey.

## Approach and Results
We employed a machine learning approach to predict flight ticket prices. After data preprocessing, including label encoding, one-hot encoding, and standard scaling, we experimented with various algorithms. Hyperparameter tuning was performed to optimize model performance.

### Challenges Faced
- Dynamic nature of flight ticket prices
- Ensuring accurate feature encoding and scaling
- Optimizing model performance through hyperparameter tuning

### Best Results
The best results were achieved using label encoded + one-hot encoded standard scaled data in the Gradient Boosting algorithm, significantly increasing accuracy.

## Conclusion
By leveraging machine learning techniques, we were able to predict flight ticket prices with improved accuracy. This predictive capability can assist airlines in making informed decisions about pricing strategies, ultimately benefiting both airlines and travelers.
