# Coupon Classifier
This dataset was taken from a reserach paper, cited in reference, and made avaiable on UCI's data respository.  

## 1. Summary 

##### Problem Statement
Build a classifier to predict if a person will accept a 20% discount coupon. 

##### Technical Overview
The dataset is comprised of all categorical variables and some missing values. I tested several ensamble 

## 2. Results

- fill

  
## 3. Data Description

##### Notes
All coupons provide a 20% discount. The survey was given to Amazon Mechnical Turk.

- destination: No Urgent Place, Home, Work
- passanger: Alone, Friend(s), Kid(s), Partner (who are the passengers in the car)
- weather: Sunny, Rainy, Snowy
- temperature:55, 80, 30
- time: 2PM, 10AM, 6PM, 7AM, 10PM
- coupon: type of coupon give -- Restaurant(<$20), Coffee House, Carry out & Take away, Bar, Restaurant($20-$50)
- expiration: 1d, 2h (the coupon expires in 1 day or in 2 hours)
- gender: Female, Male
- age: 21, 46, 26, 31, 41, 50plus, 36, below21
- maritalStatus: Unmarried partner, Single, Married partner, Divorced, Widowed
- has_Children:1, 0
- education: Some college - no degree, Bachelors degree, Associates degree, High School Graduate, Graduate degree (Masters or Doctorate), Some High School
- occupation: Unemployed, Architecture & Engineering, Student, etc..
- income: (feature meaning: how many times do you go to a bar every month?)
- CoffeeHouse: (feature meaning: how many times do you go to a coffeehouse every month?)
- CarryAway: (feature meaning: how many times do you get take-away food every month?)
- RestaurantLessThan20: (feature meaning: how many times do you go to a restaurant with an average expense per person of less than $20 every month?)
- Restaurant20To50:  (feature meaning: how many times do you go to a restaurant with average expense per person of $20 - $50 every month?)
- toCoupon_GEQ15min: 0,1 (feature meaning: driving distance to the restaurant/bar for using the coupon is greater than 15 minutes)
- toCoupon_GEQ25min: 0, 1 (feature meaning: driving distance to the restaurant/bar for using the coupon is greater than 25 minutes)
- direction_same: 0, 1 (feature meaning: whether the restaurant/bar is in the same direction as your current destination)
- direction_opp: 1, 0 (feature meaning: whether the restaurant/bar is in the same direction as your current destination)

*Target Variable*
- Y:1, 0 (whether the coupon is accepted)

  
## 4. Libraries
-sklearn
-pandas
-numpy
-xgboost
-catboost
-lightgbm

## 5. References
Wang, Tong, Cynthia Rudin, Finale Doshi-Velez, Yimin Liu, Erica Klampfl, and Perry MacNeille. 'A bayesian framework for learning rule sets for interpretable classification.' The Journal of Machine Learning Research 18, no. 1 (2017): 2357-2393.

https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation
