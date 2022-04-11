# Explainable expected goals models for football analytics

[Mustafa Cavus](https://www.researchgate.net/profile/Mustafa-Cavus-2)

## Abstract

Football is inherently a low-scoring game. Usually matches result in no or few goals. A team that has many goal attempts in a match dominates the game, but may lose the match with only one goal conceded by its opponent which has a few goal attempts. Because of such situations, the score does not represent the game. The expected goals is proposed by [Green (2012)](https://www.statsperform.com/resource/assessing-the-performance-of-premier-league-goalscorers/) to quantify the probability of a shot resulting in a score as an alternative to score. Thus, while the performance of a team and a player can be measured independently of the score, this metric is also used in the prediction of the match result ([Eggels et al., 2016](http://ceur-ws.org/Vol-1842/paper_07.pdf)). The metric is calculated as an outcome of a machine learning model with the attributes are distance to goal, angle to goal, game setting, last action and etc on football event data. In this respect, it is a kind of binary classification problem and there are many problems such as imbalancedness, quality of validation data and explainability of the model, encountered in machine learning. In this project, it is aimed that an explainable expected goals model for predicting the xG metric with high accuracy is proposed to eliminate the problems are seen in the literature.


### Why is the project important?

The xG models proposed in the literature still have the potential to be improved in terms of accuracy. Moreover, the explainability of these models is limited only by the variable importance. This project will also focus on the instance-based explanations for extracting the player and team based informations. To the best of our knowledge, this project will be the first in the literature in terms of providing comprehensive explainability frame in such models.


### What shall be completed by the end of the project?

* An explainable expected goals model for predicting the xG metric with high accuracy is proposed.
* The behavior of the model is investigated in terms of the research questions related with data quality used in training of the model as in [Robberechts and Davis (2020)](https://doi.org/10.1007/978-3-030-64912-8_2).
* Investigating the problems of the xG model related data drift.


### What will the intern(s) learn during the summer project?

* Visualizing the football event data. 
* Training tree-based ML models by using AutoML tools.
* Discovering the ML models' behaviors by using XAI methods.


## Follow-up

* Collaborating on writing a research paper / a conference proceeding.
* The topic can be used for the diploma thesis.
