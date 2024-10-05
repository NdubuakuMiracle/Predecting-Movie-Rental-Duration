# DVD Rental Prediction Model  

## Overview  

I recently undertook a project with a DVD rental company that sought my expertise in predicting how many days a customer would rent a DVD based on various features. The goal was to develop regression models that could meet their requirement of achieving a Mean Squared Error (MSE) of 3 or less on a test set. The model I built will ultimately help the company enhance its inventory planning and improve overall efficiency.  

## Data Source  

The company provided a dataset in the `rental_info.csv` file, which contains several features relevant to the rental process:  

- **rental_date**: The date and time the customer rents the DVD.  
- **return_date**: The date and time the customer returns the DVD.  
- **amount**: The amount paid by the customer for renting the DVD.  
- **amount_2**: The square of the "amount."  
- **rental_rate**: The rate at which the DVD is rented.  
- **rental_rate_2**: The square of the "rental_rate."  
- **release_year**: The year the movie being rented was released.  
- **length**: The length of the movie being rented, in minutes.  
- **length_2**: The square of the "length."  
- **replacement_cost**: The cost to replace the DVD.  
- **special_features**: Any special features, such as trailers or deleted scenes, that the DVD may have.  
- **Rating columns**: Dummy variables for movie ratings (NC-17, PG, PG-13, R). Each column takes the value 1 if the movie is rated with that label and 0 otherwise. The reference dummy variable has already been dropped for convenience.  

## Methodology  

In developing the prediction model, I employed the following steps:  

1. **Data Exploration**: I first explored the dataset to understand its structure and the distribution of various features.  
2. **Feature Engineering**: I utilized the provided features, including the dummy variables, to construct a robust feature set for training the models.  
3. **Model Selection**: I tried out several regression models, assessing their performance based on the MSE metric.  
4. **Model Evaluation**: For each model, I split the data into training and test sets, trained the models, and evaluated their MSE on the test set to ensure it met the requirement of 3 or less.  
5. **Result Analysis**: After identifying the best-performing model, I analyzed the results to draw conclusions on the effectiveness of the predictors and their relationships to rental duration.  

## Conclusion  

By developing a reliable regression model, I was able to assist the DVD rental company in accurately predicting rental durations for customers, thereby enhancing their inventory planning and operational efficiency. I look forward to sharing these insights and helping the company implement the model successfully.
