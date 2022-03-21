# Fifa_best_players: : Project Overview

This is a exploratory and descriptive project to undestand what physical features have in common the best soccer players.

-Explore and clean the data frame

-Compare the physical aspects with the overall ranking: **Height**, **Main foot**, **Age**, **Weight**

-Analize how those physical features affect the overall ranking.


 # Code and Resources Used
 
Python Version: 3.10

**Packages**: pandas, numpy, matplotlib, seaborn


# Explore and clean data

Data used from the Oficcial Fifa data 2020: male preofessional players [(https://www.kaggle.com/datasets/ekrembayar/fifa-21-complete-player-dataset)]

I created a new data frame with the columns I'm going to use. In the original data set we have a bunch of columns, but I'm going to look only at how physical aspects can affect the over all ranking of players. We have the following physical aspects: Height, Weight, Age and Foot (there are other physical aspects that are more subjective and because of that they are not going to be analyzed on this work).

I review the data frew looking for duplicates and null spaces, but it was clean.


# Analisys

![fifa1](https://user-images.githubusercontent.com/74560416/158886990-b43e1401-0874-483e-a7e9-69cd26c8cfa1.png)


I looked at the distributions of the data and relations bettwen variables. The main point of the analisys is  how phisycal features can affect the overall ranking. In the process it was necesary to create 7 new data frames to simplify the analysis and even more columns, it was necesary to create cathegories to make an easier classification, the cathegories were not arbotrary, but based on the distributions.
 
Those are some of the result of the analisys:

### Main foot
![fifa2](https://user-images.githubusercontent.com/74560416/158887056-48ee222f-eae7-48e1-92ca-b33bf7bd26e7.png)
![fifa2-1](https://user-images.githubusercontent.com/74560416/158887063-b589fd6d-2d32-4442-9b63-5eadb81bfff0.png)

The data shows that the main foot of the player doesn't have correlation with how good a player is.

### Weight
![fifa3](https://user-images.githubusercontent.com/74560416/158887167-bb027ac1-2add-4726-97d6-fd2cc5c63fa8.png)
![fifa3-2](https://user-images.githubusercontent.com/74560416/158887176-e37c7a85-1ddb-42ca-b766-0374988ce870.png)

We can see a clear correlation between Weight and a good score, the heavier the player, the best  he can be, there is a difference of 8.94% between the mean score of heavy players and the mean score of light players. That result is contra intuitive because you don't expect heavy players to be better at soccer, but the thing is heavy doesn't mean necessarily  big but tall too. We can explore it in the next physical aspect.

### Height
![fifa4](https://user-images.githubusercontent.com/74560416/158887212-83b963ae-efdd-4ae6-af9c-cb61dae7c8ab.png)
![fifa4-2](https://user-images.githubusercontent.com/74560416/158887214-8415c910-293d-4a99-bbf8-80a386a7fdfe.png)

Contrary to what i thought, Height is not relevant on how well a player is ranked, so the reason why heavier players are better raked should be in another factor.

### Age
![fifa5](https://user-images.githubusercontent.com/74560416/158887252-5ea967be-860e-4870-b97b-ed9d1d970219.png)
![fifa5-2](https://user-images.githubusercontent.com/74560416/158887256-e11ca46c-b769-4eb0-bf8f-ee64c43ca61f.png)

Age affects how well players perform, the older the player, the more chances to be a good player.

### Correlation between age and weight
![fifa6](https://user-images.githubusercontent.com/74560416/158887365-6420978b-1a8b-4342-8d68-6a5937e2d1c9.png)

There are correlation between heavier player and older players, but it doesn't mean that heavier players are paid more because they are older, it's a possibility, but correlation doesn't imply causation. To understand that it's necessary a deeper analysis, but it's out of the scope of this exploratory project.


# Results

After analyzing the data base, we understand that  main foot and Height doesn't have a good correlation of how good a player is. In the other hand, Weight and Age, have a clear correlation, but the results are contra intuitive, the heavier the player, the  better ranked he is (and its not because of the Height), and the older the player, the better ranked he is. This second correlation in even more clear than the first. There is correlation too between heavier and older player, it can be the reason why heavier players are paid more, but the information i have it's not conclusive and deeper analysis would be necessary to determine that.

You can see the code in: https://github.com/Chelo-ad/Fifa_best_players/blob/main/best_players.ipynb



