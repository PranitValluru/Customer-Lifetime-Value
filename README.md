# Customer-Lifetime-Value
Customer lifetime value analysis using [lifetimes] (https://lifetimes.readthedocs.io/en/latest/#) package in python. 
Using Beta Geometric Negative Binomial Distribution and Gamma-Gamma methods to predict repeat purchases and lifetime value

Lifetimes can be used to analyze your users based on a few assumption:

1. Users interact with you when they are "alive".
2. Users under study may "die" after some period of time.

I've quoted "alive" and "die" as these are the most abstract terms: feel free to use your own definition of "alive" and "die" (they are used similarly to "birth" and "death" in survival analysis). Whenever we have individuals repeating occurrences, we can use Lifetimes to help understand user behaviour.

Applications:
1. Predicting how often a visitor will return to your website. (Alive = visiting. Die = decided the website wasn't for them)
2. Understanding how frequently a patient may return to a hospital. (Alive = visiting. Die = maybe the patient moved to a new city, or became deceased.)
3. Predicting individuals who have churned from an app using only their usage history. (Alive = logins. Die = removed the app)
4. Predicting repeat purchases from a customer. (Alive = actively purchasing. Die = became disinterested with your product)
5. Predicting the lifetime value of your customers
