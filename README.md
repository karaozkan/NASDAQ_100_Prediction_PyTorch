# NASDAQ 100 Prediction (Deep Learning Model: PyTorch)

## Ozkan Kara & Sertan Avdan

Published: 2023.02.09

Goal: Predicting the price of the Nasdaq 100 index 55 days later

3 datasets will be used for this project
- Nasdaq 100 (NDX) (2015.01.01 - 2023.01.27) 
- U.S. Consumer Price Index (CPI) YoY (2014.12.17 - 2023.01.27)
- Fed Interest Rate Decision (2014.12.17 - 2023.01.27)


# Project Roadmap
1. Acquire the dataset
    - Source of dataset
    - Brief information about data
2. Explore the data
    - Understand the distribution of the data
3. Prepare the data
    - Remove unnecessary columns or rename columns
    - Merge datasets by date
    - Filling missing values
    - Relationships between different attributes
4. Feature engineering
    - Create new features or modify existing features
    - Adding technic analysis features
    - Visualization of new features
    - Shifting features
5. Split the data
    - Divide the data into train and test sets
6. Develop the model
    - PyTorch Models
7. Conclusion
    - The best model

## Results
![download22](https://user-images.githubusercontent.com/113067787/217866887-2568260e-b1bc-4928-81b7-8350e950792f.png)
![download2313](https://user-images.githubusercontent.com/113067787/217866898-bcb4c10b-61a1-4e63-b8db-bd9ec0f0476a.png)
![download33](https://user-images.githubusercontent.com/113067787/217866934-764a452f-af5d-4482-ac73-c994aba9cb21.png)
![download1](https://user-images.githubusercontent.com/113067787/217866947-f8e9a794-16df-4c47-90b4-10b2044e3608.png)



## Conclusion
**Model 4** was deemed the best due to its utilization of a high number of neurons. The inclusion of a buffer zone effectively eliminated any potential data leaks, which often result in models that are overly optimistic and therefore useless for practical applications and production use.

We attempted to forecast 55 days in advance. The 55-day interval was selected to surpass the maximum limit of 50 days of the technical analysis indicators we utilized.
