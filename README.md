# A Tableau analysis of dota 2
#### Tableau visuations project created by Mikki Seidenschnur
##### Data obtained from [Kaggle](https://www.kaggle.com/devinanzelmo/dota-2-matches)
Ironhack data bootcamp in Berlin 27-06-2020

This repository contains:
* .gitignore
* README.md
* links to tableau project

#### 1. What is DOTA 2?
The best person to answer that question is the famous "get started" youtuber Purge. See [this](https://www.youtube.com/watch?v=9Szj-CloJiI) short video to become enlightened.

#### 2. Where do we find those amazing visualisations that we've been promised?
The tableau project is available

#### 3. Which is what, and what does it show?
1. How often does each team win
    * The map that the teams play on is NOT mirrored fully. In fact, some objectives only exist in one part of the map (Such as ROSHAN, let's hope you being paying attention to the terminology in the videos). Therefore, this visualisation shows that actually, the Radiant team has a winning advantage of 51.9% of all the 50000 games. Though this might make think as a DOTA 2 player: "Then I'll always chose the radiant side", it doesn't really matter, as teams placed by a pseudo random algorithm after they have been matched up with player of same level by the [ELO rating system](https://en.wikipedia.org/wiki/Elo_rating_system).
2. Which heroes are picked the most?
    * Heroes choices are widely recognized in the dota 2 community as one of the biggest impact factors of dota two. With each patch (hero update) usually the prefered and most picked heroes changes, since the dev-ops (Valve) has chosen to balance certain hero skills and abilities.
    During the patch analysed the 3 most picked heroes were [Windranger](https://www.youtube.com/watch?v=Lnk-SkHSB5M), [Shadow Fiend](https://www.youtube.com/watch?v=U9nKwvGtnaY), [Invoker](https://www.youtube.com/watch?v=oCcsA4P3dUM). 
    While Windranger and Invoker was chosen alot, the graph shows that it was relatively equally distribued throughout the matches analysed. However, it also shows that Shadow Fiend is chosen around 1000 times more by the Radiant team. This phenomenon can be confirmed by the following [guide](https://www.dotafire.com/dota-2/guide/updating-shadow-fiend-guide-nevermore-the-soultrain-stealer-221) that talks about this advantage in the given patch.
3. What is the average duration of a DOTA 2 match?
    * When getting into DOTA 2, you need to know what kind of a time-machine it is! One moment you start a new game, and sometimes it will take up to 1 1/2 hours, if not more to finish the game. Even if you get an average game, that would mean that you have to stay for at least 40-45 minutes. 
    This is confirmed by the community [bloggers](https://www.gamespot.com/forums/pc-mac-linux-society-1000004/average-game-length-in-dota-2-vs-lol-29113042/) that on average estimate 40-50 minutes without data. The data shows to be normally distributed, if the 1 outlier of 16000 seconds is omitted from the data set, as it is just below the world record of the longest ever played games (usually these games are a result of player prolonging the game unecessarily)
4. 


Write the following in your terminal:
``` markdown
git clone https://github.com/MikkiSeidenschnur/data_ber_ms_tic_tac_toe.git
```
#### 3. Navigate to the repository folder
If the repository has been cloned, navigate to the path of that repository in your command line.

#### 4. Activate python (Optional: If conda is installed, activate the conda environment)

Run the python script:
``` python
python tictactoe.py
```

#### 5. Enjoy the game by making your bash terminal full-screen ;)
![introduction screen](img/TicTacToe_IntroductionScreen.png "introduction screen")