### Project Title
Airline Passenger Satisfaction - Predicting The Factors that Matter 

**Author**
Ben Harosh

#### Executive summary

#### Rationale
In the competitive landscape of the airline industry, airlines are often struggling with customer satisfaction and identifying features that can contribute to increasing customer satisfaction, can be crucial to airlines in terms of keeping existing customers, expanding customer base and increasing revenue as a consequence.

#### Research Question
Find the factors that contribute to airline customer satisfaction and tailor their services accordingly to enhance the overall customer experience.

#### Data Sources
Kaggle data Source “Airline Customer Satisfaction”:
https://www.kaggle.com/datasets/raminhuseyn/airline-customer-satisfaction/data

#### Methodology
Classification ML techniques to classify airline passenger satisfaction based on input features as flight delay times, flight distance and passenger type, combined with survey data collected from the airline passengers regarding their satisfactions (regarding food, seat comfort, etc.).

#### Results

The following result present the scores and train time of the model tested.

|Model              |score   |train_time|train_accuracy|test_accuracy|train_f1|test_f1   |  
|:------------------|:-------|:---------|:-------------|:------------|:-------|:---------|                
|Logistic Regression|0.828293|5.540851  |0.829049      |0.828293     |0.829048|  0.828276|
|SVM                |0.607522|113.460496|0.608063      |0.607522     |0.608587|  0.608001|
|KNN                |0.704606|0.017247  |0.810891      |0.704606     |0.810663|  0.704113|  
|Decision Tree      |0.932557|0.580034  |1.000000      |0.932557     |1.000000|  0.932544|
|Random Forest      |0.956346|2.166682  |0.999979      |0.956346     |0.999979|  0.956389| 
|Ada Boost          |0.932937|0.650584  |1.000000      |0.932937     |1.000000|  0.932928|  
|Gradient Boost     |0.920821|13.277025 |0.920577      |0.920821     |0.920601|  0.920839|

From the above initial results we can see that Random Forest Classifier showed the best test set score results with 0.956. I'm planning to improve the above by running GridSearchCV on the leading models - Random Forest, Decision Tree, Ada Boost, and Gradient Boost.                                   

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [Link to capstone notebook](https://github.com/benharosh/berkeley_capstone/blob/master/capstone-final.ipynb)
- [Link to capstone notebook on GitHub Dev](https://github.dev/benharosh/berkeley_capstone/blob/master/capstone-final.ipynb)

##### Contact and Further Information