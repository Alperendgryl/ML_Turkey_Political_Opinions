# Political-Opinions-Of-Turkish-Citizens-Machine-Learning-w-Python-

In this machine learning project, 
Turkish citizens were asked about their 
- age
- gender
- region 
- education level
- which party they voted for or would vote for.
- and 10 different questions 

The questions are:
- 1- Do You Think Our Economic Status is Good?
- 2- Do You Think Education Should be Reformed?
- 3- Do You Think Privatization is Wrong?
- 4- Do You Support the Death Penalty For Certain Crimes?
- 5- Do You Find Our Journalists Objective Enough?
- 6- Do You Support the Prohibition of Alcohol After 10 PM?
- 7- Do You Want to Live in a More Secular State?
- 8- Do You Support the Abortion Ban?
- 9- Do You Think That the Extraordinary State (OHAL) Restricts Freedoms?
- 10- Do You Support a New Party in the Parliament?

Metrics, scores and graphs: 

- There are several plot graphs about distribution for the samples (Sex, age, education level, party distribution by age, party distribution by education level etc.)

- Also a heatmap created to see the correlation between attributes

- By using Party label as predictor and target, 4 classification methods (Decision Tree, Random Forest, SVC, KNeighbors) created to find the best classifier to predict
the party of any citizen supports. (Generaly Random Forest method gives the best result min = 50, max = 85)

- According to the answer of the questions and other attributes that are answered by the voters, 
the machine shows the metrics score (accuracy, precision, recall and f1 score).

- To see the results more detailed, classification report is also created and shown with plots to visualize the results.

- There is a survey at the end of the project. This survey takes the answers of "user" and the other attributes as an input and shows which party the "user"
is more inclined.

