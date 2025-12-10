# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
Most Important:
1. Square Footage   
2. Bathrooms
3. Bedrooms
4. Age 
Least Important:

**Explanation:**
Square footage is the most important for developing the house price model because the bigger houses had a higher price, a decent amount houses with more bathrooms had a bigger price, some houses with more bedrooms costed more, and the age of the house wasn't as consistent with the pricing of the houses.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each additional square foot increases the price by about $120

**Feature 2:**
Each additional bathroom increases the price by about $25,000

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My R2 score was around 0.9 which means that it predicted the homes prices pretty well. Yes, there's room for improvement I think if additional important information is added like the home's neighborhoods, could help make it more accurate. 



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:** 
Location

**Why it would help:**
The price of the house could depend on where the house is located since in safer areas or areas where there are good schools, house are typically more expensive.

**Feature 2:**
House conditions

**Why it would help:**
The condition of the house can affect the value of the house since houses that have recently been renovated sell for higher than houses that are older and worn down.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
No I would not trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old because the model has never seen a house like this in its training data. This means that it would guess outside the range it was trained on, leading to a less accurate guess.

