# Flight ticket price predictor
**Objective:** Build a model to predict the price of a flight ticket, given the journey related information like 
- date and time of journey
- source and destination
- other services 

## Steps to build a robust model
- Split data into train, validate and test sets
- Clean the data 
    - missing value treatment
    - outlier treatment
    - bucket if catg column has lots of values
- Create good features out of the data 
    - Catg columns --> OHE, etc.
- Build simple **model** to start with 
    - Perform hyper parameter tuning on validation data 
    - Evaluate model performance on test data
- Build **pipeline**
- Reiterate with more complex models
    - compare model performance
- Select best model