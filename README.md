# Data-Visualization

# Purpose of Project
The project's main purpose is to help the client to make improvement in game using these graphs. The client conduct this game using Artificial Intelligence. By getting information from visuals he will be able to make changes in game to get higher or predicated results.

# General Information About Starcraft Game
In this Starcraft game there are 13 bots which plays with each other in 10 different maps and 10 rounds. So, each bot play 1200 games per tournment, 100 games against the each bot. In this bots runs through AI.

# Problem Domain
The problem domain for these notebook is to produce some visual figures which helps to increase performance of bots in future or make any changes with algorithm on which bots are playing in game. There are some specific requirements from the clent.
-> Try to find count of games which crash on particular I/P addresses
-> Plot a useful figure which cover more than 2 atrributes and provide as much as information possible
-> Plot Game Id which have (W-L)/Max value is negative or nearest to zero
-> Performance of bot over the rounds in tournment

# Dataset Field Explanation
-> Game id- Unique id of each game
-> Winner Bot- Name of winner robot from that particular game
-> Loser Bot - Name of loser bot from that particular game
-> Game Type - Basic type of game is normal, but few games crash in between or some of them were not recorded from the start because of some technical or other isuue
-> Round- Information about the round in the particular tournment
-> Map- Name of Map in which game was played between two bots
-> Winning Score- Score of winning bot
-> Losing score - Score of Loser bot
-> W-L/max - Score of winning bot minus score losing bot divided by value which is greater from that two value
-> Winning I/Ps - I/P of winner bot
-> Lossing I/Ps - I/P of loser bot
-> Start time- Time and date stamp value when game was started
-> End time - Time and Date stamp value when game was ended

# How to run this project
To run this project start local python in your local machine to avoid CORS error in browser.
