# Data-Driven-Analysis-of-EV-Charging-Infrastructure-for-a-Smart-City
This project conducts a meticulous data-driven analysis, concentrating on the unique challenges and opportunities presented by the charging infrastructure tailored for medium/heavy-duty vehicles within the dynamic context of a smart city.

## Data- Driven Analysis:
Implemented a data-driven analysis with advanced forecasting machine learning models:
- Prophet model for forecasting the vehicle count (EV market analysis)
- Stacking Ensemble Regressor model integrated with weighted fusion for predicting range
- Temporal Fusion Transformer model utilized for energy demand for each charging station
- PuLP linear programming optimization model with K-means clustering for optimal placement of charging stations

### Prophet model for forecasting the Electric vehicle count and charging stations demand
<img width="700" alt="Pic1" src="https://github.com/abdulmahejabeen/Data-Driven-Analysis-of-EV-Charging-Infrastructure-for-a-Smart-City/assets/56336879/29c02ffb-78bf-4f24-be12-b893fa1ba337">

### Stacking Ensemble Regressor model integrated with weighted fusion for predicting range
<img width="700" alt="Pic2" src="https://github.com/abdulmahejabeen/Data-Driven-Analysis-of-EV-Charging-Infrastructure-for-a-Smart-City/assets/56336879/f6cefef5-6dd3-4ae3-a295-9308d96ded42">

### Temporal Fusion Transformer Architecture for Energy Demand Prediction at each Station
<img width="700" alt="Pic3" src="https://github.com/abdulmahejabeen/Data-Driven-Analysis-of-EV-Charging-Infrastructure-for-a-Smart-City/assets/56336879/06a7683a-7870-4e58-990f-0a1a64d3f364">

### PuLP linear programming optimization model with K-means clustering for suggesting optimal placement of charging stations
<img width="700" alt="Pic4" src="https://github.com/abdulmahejabeen/Data-Driven-Analysis-of-EV-Charging-Infrastructure-for-a-Smart-City/assets/56336879/bbba0570-5fd9-41be-908d-7d3b2e8e2cc1">

<img width="696" alt="Screenshot 2024-03-06 at 12 34 29 AM" src="https://github.com/abdulmahejabeen/Data-Driven-Analysis-of-EV-Charging-Infrastructure-for-a-Smart-City/assets/56336879/1b29a8df-81c7-41df-aa51-4fc0eb92ae5b">

## System Architecture
<img width="829" alt="Screenshot 2024-03-06 at 12 38 15 AM" src="https://github.com/abdulmahejabeen/Data-Driven-Analysis-of-EV-Charging-Infrastructure-for-a-Smart-City/assets/56336879/16259a92-7d2d-43f0-944b-8f6b445b9507">

Users send a request on the website using Flask Architecture. Then the backend process begins where it comprises of collection of all datasets and to identify all the parameters required for the machine learning models and all these datasets are hosted and stored in Amazon S3 and then collecting real - time data which will send the parameters to predict the desired results to the machine learning models and predict the required output.
