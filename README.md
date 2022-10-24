# Project 2

![](images/graph1/../chess.jpeg)


### Goals
Goals for this project is analyze a database and do webscraping to create new data frame and prove the hypotesis through visualization graphics

### Hypothesis

My hypothesis for this analysis is that the statistics are usually taken from high ranking players like(mean of turns, expected win percentage, expected winner(white or black), most usesd openings, more difference in elo less resign games,and castle is a move that occurs in most of the games), and statistics of a normal player(arround 1000-1600 elo) will be a little different.

Also want to prove in online chess the most common victory status is resign for a normal chess player.

### Cleansing and Web Scraping

Cleaning and Scraping proces is contained in the juppiter notebooks.

I started cleansing the databe, this databe base was really clean then i only remove some columns or made new one with standarized values.

Also scrapped chess info in internet some tables to complement my csv with win % and more information

At the end i merged everythin in 1 data frame then later can work better with the visualization process.

### Analysis
In order to prove my inicial hypothesis at the beginning of the document we use graphics to help us to make some conclusions

#### win % based on elo difference
![](images/graph1/../graph2.jpeg)

to clarify all percentages below 50% chance of winning means white has more elo than black and more than 50% means black has more elo than white.
As expected 40%-50% are the biggest values due to chess online pages try to match players with similiar elo or a bit higer or lower

#### expected winner vs real winner
![](images/graph1/../graph3.jpeg)

It is assumed that a player with a higher ranking would usually have to beat a lower ranked player, and in the graph you can see who was expected to win and who won

#### victory status compared with elo difference
![](images/graph1/../graph7.jpeg)

we can see the victory status that is more frequent as we said in the hypothesis is the resign thats because in chess you can resing the game since the turn 1, also observe that as the difference in rating between the players is greater, the number of resigns decreases.

#### Most used openings 
![](images/graph1/../graph5.jpeg)

Looking at the openig graph several conclusions can be drawn,sicilian defense is the most used opening in this database because e4 is the most used first move as white and the best counter for this movement as black is moving c5 and thats the start of the sicilian defence or any variation, or othe conclusion can be is opening most people like.

![](images/graph1/../graph4.jpeg)

#### Average turns by victory status

![](images/graph1/../graph9.jpeg)

The graph shows how draw games and games out of time tend to have a higher average number of moves due to their longer duration



### Conclusion

 First of all, some people who make web pages should sign up for the Ironhack bootcamp.
Regarding my initial hypotheses we can say that resign is the win status with more occurrences, and the stats from this player are a little different from the general ones, which as we said usually take into account high elo players.

![](images/graph1/../chess2.jpeg)


















