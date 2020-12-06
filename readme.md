# PES Dataset Exploration

This is a complete set of Player Data from eFootball PES 2020 video game ,
 the latest of the football franchise by KONAMI. 
the data available at
https://www.kaggle.com/homerkommrad/efootball-pes-2020-all-players-csv

## the structure of my dataset
The data contains 15035 players with 18 features

12 variables are numeric (height , weight , age , offensive , defensive , ball_control , dribbling , heading , speed , acceleration , overall_rating)
5 variables are categorical (name , team_name , league , nationality , foot , position)

## Summary of Findings
The rating distribution has one peak from 65 to 70 and most of the players are between 60 and 75 rating.
The finishing accuracy has one peak on 60 and most of the players have accuracy between 55 and 70.
The minimum finishing accuracy is 40, and very low number of players are above 90.
The maximun age found is 43 years old, less than 10 players are 15 years old, and the most repeated age is 22 years old.
Brazil have the highest number of players in the dataset with 1600 players,then Spain,France and Argentina with around 1000 players for each of them
The overall rating is partly correlated with each numerical variable except height and weight.
As expected:
* height and weight are highly correlated.
* speed and acceleration are highly correlated.
* ball_control,dribbling and finishing are highly correlated with each other.
* offensive is correlated with all skills.
* defensive is not correlated at all with any of other skills.
* age is not correlated with anything.
France and Netharlands have the least median of age.
Brazil and Argentina have the highest range of ages.
75% of all players are less than 30 years old.
50% of all players between 20 and 30 years old.
Left footed players almost the same percentage of all countries.
High rated players in Brazil more than any other country.
players from Europe,Brazil and Argentina have big chance to get high rate.
GK,CB and CF are much higher than other positions.

Left positions are higher rated than right positions.
GK is the least position rating in most of countries.
The second division leagues players are low rated.
The English league has the best quality of players.
All players in free Agent are around 30 years.

