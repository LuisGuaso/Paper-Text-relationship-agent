# Paper-Text-relationship-agent
The agent uses a Logistic Regression algorithm to get the probability of a paper being related to a certain topic. The model needs to be train using analyse texts. Marking papers with a 1 (positive) if they are related to the searched topic and 0 (negative) if they are not related.
The training is done by a Grid Search. It is self train by choosing the most optimal combination of parameters using ROC AUC and F1 Macro to test the performance. 
![image](https://user-images.githubusercontent.com/111091383/184256135-0f0c86b2-45c1-4c3c-ae69-7a2b5fddab41.png)
