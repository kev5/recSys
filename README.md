# recSys
*This repository will be improved over time.*

A Recommender System predicts the likelihood that a user would prefer an item. Based on previous user interaction with the data source that the system takes the information from (besides the data from other users, or historical trends), the system is capable of recommending an item to a user.

The [pilot.py](https://github.com/kev5/recSys/blob/master/pilot.py) makes use of a class of Recommender System algorithm called collaborative filtering. A collaborative filtering algorithm works by finding a set of people (assuming persons are the only client or user of a RS) with preferences or tastes similar to the target user. Using this smaller set of “similar” people, it constructs a ranked list of suggestions. 
