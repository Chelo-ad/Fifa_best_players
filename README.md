# Fifa_best_players: : Project Overview

This is a exploratory and descriptive project to undestand what physical features have in common the best soccer players.

-Explore and clean the data frame

-Compare the physical aspects with the overall ranking: **Height**, **Main foot**, **Age**, **Weight**

-Analize how those physical features affect the overall ranking.


 # Code and Resources Used
 
Python Version: 3.10

**Packages**: pandas, numpy, matplotlib, seaborn


# Explore and clean data

Data used from the Oficcial Fifa data 2020: male preofessional players

I created a new data frame with the columns I'm going to use. In the original data set we have a bunch of columns, but I'm going to look only at how physical aspects can affect the over all ranking of players. We have the following physical aspects: Height, Weight, Age and Foot (there are other physical aspects that are more subjective and because of that they are not going to be analyzed on this work).

I review the data frew looking for duplicates and null spaces, but it was clean.


# Analisys

![fifa1](https://user-images.githubusercontent.com/74560416/158886990-b43e1401-0874-483e-a7e9-69cd26c8cfa1.png)


I looked at the distributions of the data and relations bettwen variables. The main point of the analisys is  how phisycal features can affect the overall ranking. In the process it was necesary to create 7 new data frames to simplify the analysis and even more columns, it was necesary to create cathegories to make an easier classification, the cathegories were not arbotrary, but based on the distributions.
 
Those are some of the result of the analisys:

### Main foot
![fifa2](https://user-images.githubusercontent.com/74560416/158887056-48ee222f-eae7-48e1-92ca-b33bf7bd26e7.png)
![fifa2-1](https://user-images.githubusercontent.com/74560416/158887063-b589fd6d-2d32-4442-9b63-5eadb81bfff0.png)

### Weight
![fifa3](https://user-images.githubusercontent.com/74560416/158887167-bb027ac1-2add-4726-97d6-fd2cc5c63fa8.png)
![fifa3-2](https://user-images.githubusercontent.com/74560416/158887176-e37c7a85-1ddb-42ca-b766-0374988ce870.png)

### Height
![fifa4](https://user-images.githubusercontent.com/74560416/158887212-83b963ae-efdd-4ae6-af9c-cb61dae7c8ab.png)
![fifa4-2](https://user-images.githubusercontent.com/74560416/158887214-8415c910-293d-4a99-bbf8-80a386a7fdfe.png)

### Age
![fifa5](https://user-images.githubusercontent.com/74560416/158887252-5ea967be-860e-4870-b97b-ed9d1d970219.png)
![fifa5-2](https://user-images.githubusercontent.com/74560416/158887256-e11ca46c-b769-4eb0-bf8f-ee64c43ca61f.png)

### Correlation between age and weight
![fifa6](https://user-images.githubusercontent.com/74560416/158887365-6420978b-1a8b-4342-8d68-6a5937e2d1c9.png)



