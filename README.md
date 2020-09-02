# AB-testing-with-cookie-cats-mobile-game
Analyze an A/B test from the popular puzzle game, Cookie Cats
**View my project at [this link](https://nbviewer.jupyter.org/github/katiethaoha/Mobile-games-A-B-testing-with-cookie-cats/blob/master/AB-testing-notebook.ipynb)**

Cookie Cats is a hugely popular puzzle game developed by Tactile Entertainment.  It's a classic "connect three" style puzzle game where player must connect tiles of the same color in order to clear the board and win the level. It also features singing cats. Check out this short demo:
https://youtu.be/GaP5f0jVTWE

As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non trivial amount of time or make an in-app purchase to progress. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to 40. In particular, we will analyze the impact on player retention. 

The project is implemented using pandas DataFrames and pandas plot method. Also, it is necessary to have some understanding of hypothesis testing and boostrap analysis.
