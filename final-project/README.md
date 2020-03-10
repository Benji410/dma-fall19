# DS144 Final Project - NBA Injury Predictions

This project is trying to tackle the problem of frequent NBA Injuries and we want to see if a Machine Learning Solution is possible. 
The aim is to create a binary classifier which will indicate whether or not a player should sit out or not based off player stats per game and previous injury records. 

## Data
* Scraped data of professional player stats per game from two NBA seasons (16-17 and 17-18). 
* Scraped data of injury records from those two seasons for all players. 
* Joined stats with injury records
* Created score based off of injury records
* Whether or not a player sat out for a game was our binary target variable

## Classifier
We fit and tested multiple classifiers with hyperparameter adjustments to see which classifier could obtain the best recall and precision. 
Our choices of classifiers were chosen based on their ability to predict binary outcomes. 
We finally decided to use a Decision Tree Classifier as our final classifier with over 70% recall, precision and f1_score. 

## Final Thoughts
This project was mostly experimental and there is lots of room for improvement and adjustments, such as joining other datasets relating to player exhaustion and injuries, more player seasons, etc. 
I had a lot of fun experimenting ML solutions and problem solving data techniques. Big thanks to Milan Butani, Alvin Yu, and Alex Yip. They were partners in this project and I had a lot of fun working with them. 
