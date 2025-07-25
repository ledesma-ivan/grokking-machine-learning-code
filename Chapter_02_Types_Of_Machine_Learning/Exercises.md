# Exercise 2.1

For each of the following scenarios, state if it is an example of **supervised** or **unsupervised** learning. Explain your answers. In cases of ambiguity, pick one, and explain why you picked it.

## a. 
A recommendation system on a social network that recommends potential friends to a user  
**Type:** unsupervised 
**Explanation:**  Because it analyzes for similar patterns and groups them and does not require predefined tags.

## b. 
A system in a news site that divides the news into topics  
**Type:** supervised
**Explanation:**  A model is created with training data and predefined tags. If it meets certain criteria, it is selected with the corresponding category.

## c. 
The Google autocomplete feature for sentences  
**Type:** supervised
**Explanation:** Regression is used to predict the following letter

## d. 
A recommendation system on an online retailer that recommends to users what to buy based on their past purchasing history  
**Type:** Content-based filtering
**Explanation:** It is neither category.

## e. 
A system in a credit card company that captures fraudulent transactions  
**Type:** supervised
**Explanation:**  It is supervised because it is trained with data with predefined tags and usually with a tag that defines whether it is fraud or not.


# Exercise 2.2

For each of the following applications of machine learning, would you use **regression** or **classification** to solve it? Explain your answers. In cases of ambiguity, pick one, and explain why you picked it.

## a. 
An online store predicting how much money a user will spend on their site  
**Type:** Regression   
**Explanation:** In this case we are determining a finite number.

## b. 
A voice assistant decoding voice and turning it into text  
**Type:** Classification  
**Explanation:** Because the system assigns audio segments to categories for conversion to text. 

## c. 
Selling or buying stock from a particular company  
**Type:** Regression  
**Explanation:** Since we would use the variables in the dataset to predict the behavior of the stock and take an action to either sell or buy a stock.

## d. 
YouTube recommending a video to a user  
**Type:** Classification  7
**Explanation:** As it seeks to classify the individual with a group of people who have similar patterns


# 📘 Exercise 2.3

Your task is to build a self-driving car. Give at least **three examples** of machine learning problems that you would have to solve to build it. In each example, explain:

- if you are using **supervised** or **unsupervised** learning,
- and, if supervised, whether you are using **regression** or **classification**.
- If you are using **other types** of machine learning, explain which ones and why.

## Example 1  
**Problem:**  Classifying traffic light colors (red, yellow, green)
**Learning Type:** Supervised
**Regression/Classification/Other:**   Classification
**Explanation:** The system learns from labeled images of traffic lights to predict which color is on at that moment and make a decision whether to move forward or not.

## Example 2  
**Problem:** Predicting the speed of nearby vehicles
**Learning Type:**  Unsupervised
**Regression/Classification/Other:**  Regression
**Explanation:** The goal is to predict a continuous value (the speed) based on sensor input (e.g., radar, camera). Since the output is a numeric value, it is a regression problem. 

## Example 3  
**Problem:**  Detecting pedestrians or animals on the road
**Learning Type:**  Supervised
**Regression/Classification/Other:**  Classification
**Explanation:**  The car uses images or video to determine whether an object is a pedestrian, animal, or something else. This is a classification problem because it assigns labels to detected objects, helping avoid collisions.
