# Clash of Clans Inspired Tower Defense Game

For the final project for SoftDes, our group decided to create a tower defense game in the theme of Clash of Clans. In our game, you can place towers such as the archer tower, the wizard tower, and the inferno tower to defeat enemies like barbarians, goblins and giants. Our goal was to create a game had strategy involved and challenged the user to strategically place towers. A screenshot of the gameplay can be seen below:

![Game image local](/gameplay.png)

## In-Game Strategy

When we created our tower defense game, we wanted to add some elements of strategy so it would be more entertaining to play. At the start of the game, the user is given 200 in currency to spend on placing towers on the map. Towers like the wizard tower, and the inferno tower have special abilities like multi-target and exponential damage, but they also cost more currency, so the user has to be strategic regarding which towers to place each round. Each time the user kills an enemy, they are rewarded with some currency that can be used to buy more towers. The game ends when the user either wins by clearing all 5 waves or loses by lets too many enemies reach the end of the path.

### Game Functions and Design

Our game includes 4 distinct screens: the start screen, the gameplay screen, the game over screen, and the win screen.

![Game start screen](/start_screen.png)

Once the user presses start, gameplay begins! The enemies start spawning immediately and users can use their in-game money to buy towers to defeat enemies before they reach the end of the map. Defeating enemies gain more currency that can be used to buy or upgrade towers. These functions can be seen on the right-side menu of the game screen. Place towers by clicking the buy tower buttons and then clicking on an open stump to place it on. Upgrade towers by clicking the upgrade button and clicking on an existing tower on the map. Upgrading costs 100 currency. Towers can also be sold for full price.

![Gameplay start](/gameplay_start.png)

If you let 10 enemies reach the end of the map, the game ends and you lose.

![game over](/game_over.png)

Pass all five waves and you win!

![you win](/you_win.png)

## Video Presentation

For a full video presentation of our game please click [here](https://www.youtube.com/watch?v=XKhHMn6yVh0)

## Installation

To play our game, please follow the following steps:
* clone our repository into your local device (the repository can be found here)
* install pygame as per the instructions in our repository (a detailed guide can be found [here](https://github.com/olincollege/tower-defense-game)
* run the main.py file

## Credits

Hope you enjoyed learning more about our game! The game was created by [Jefferson Wu](https://github.com/JeffersonWu25) , [Sam Wisnoski](https://github.com/swisnoski), and [Minu Rajasinghe](https://github.com/minurajasinghe).

Much of the inspiration for our game and the graphic elements of the towers and enemies can be attributed to SUPERCELL, the creators of Clash of Clans. For more information on their game, please visit [supercell.com](https://supercell.com/en/).

All images were retrieved from the [Clash of Clans wiki](https://clashofclans.fandom.com/wiki/Clash_of_Clans_Wiki)
