The task is to develop an algorithm for predicting the carbon content and temperature of cast iron.

There are two subtasks in this task:

1. Implement an algorithm that predicts the carbon content and temperature of cast iron at the end of metal melting
2. The task from the real world is to figure out how to generalize the algorithm from point 1 to the situation of real production. In real time, we do not know when the end of the purge will come, but we must determine it ourselves based on the predicted parameters of cast iron. What should I add? How do I move from a model problem to a real-world problem? How to develop the algorithm so that it is as useful to the business as possible?

<img src='https://eventcaddy.s3.amazonaws.com/uploads/sponsor/image/12564/42cf50a8-e165-4cf6-89b5-ddd106d22fe2.png'>

In our submission we use a single CATBOOST tuned by GridSearchCV from Scikit-learn.

<img src='https://miro.medium.com/max/1200/1*iEO6b3roCesXxI0vkx9IPg.png'>

On private LeaderBoard we finished on #14th place#.
<img src='https://github.com/NN-team-01/evraz-hack/blob/main/data_processing/EVRAZ_NN_TEAM_14th.png?raw=true'>
