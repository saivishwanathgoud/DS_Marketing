# DS_Marketing

Predicting Super Customers Using Feature Labs and Pycaret

Propensity modelling is a process of assigning propbabilities to commit a certain action (e.g. to buy, to churn, etc.) to each individual in your customer base using statistical models. Hence, we can think of it as a classification problem which can be solved using a multitude of ML models. When could these models be used? Propensity scores allow marketing managers to tailor their communications and offers on the individual level. Knowing if a customer is going to buy in the next month can help us formulate the type of communications that he/she is going to receive. For example, if we know that this high propensity customer enjoys a particular category of products, we can send tailored recommendations to this customer’s email which is going to imporve the customer’s experience with our brand. On the other hand, if we know that a customer is likely to churn, we can offer a special discount to encourage the customer to stay.

Bottom line: propensity models form a crucial pillar in marketing analytics and are extremely valuable to the business. Let’s see now how can we make the process of propensity modelling in Python as easy as possible.

Kaggle: https://www.kaggle.com/vasudeva009/predicting-coupon-redemption

# Objective: 

What kind of propensity are we going to predict? Well, if you look at the EDA section in the notebook, you can see that customers make pruchases quite freuqently, so propnesity to buy in the next month or week would not be very useful for this business. Hence, instead of predicting if a person is going to make pruchase, we are going to predict if the number of transactions is going to be larger than average. We’re also going to do it on the weekly level as it gives more detailed insights and can still be actionable for marketing managers. The only thing that we need to specify is the threhsold above which we’lll classify the customer as super customer for the next week. 

