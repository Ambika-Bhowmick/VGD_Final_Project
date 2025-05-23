# VGD_Final_Project
Title and description of the game: The title of my game is "Stuck in Space!", it's a game where there is a mysterious person that has to go back to their home planet. The red cloaked person is stuck at a mysterious planet and by getting to the portal at the end of the first level, the player escapes the planet. Then, in the second level they have to reach the flag at the end of the level on Earth and then they will win the game.

Controls and how to play: The player has to avoid obstacles that are the spikes, if they touch them they will automatically lose. At the end of level one, there is a portal that will transport them to the second level. After that, there is a flag at the end of level 2 and that is when the player will win. The player will move left and right when pressing the arrows and jump when the space bar is pressed.

A list of script changes and why you made them: 
  Movement: This is the script that makes the player move when you press the left arrow, right arrow and space button. The speed and jump speed have be changed in this script.
  Cam1: This is the script that make the camera follow the player and I made it so I could have longer levels.
  Lvl_Loader: This is the script that changes the level when you touch the portal at the end of level 1.
  Lose: This is the script that changes the screen to the "Lose Screen" when the player touches a spike.
  Winner: This is the script that changes the screen to the "Win Screen" when the player touches the flag at the end of level 2.

What you’re most proud of in your game: I'm most proud of the abilty for my game to switch levels, as I didn't know how to do it at all. It makes my game more enjoyable for people as it creates a different scenery making the game harder. It took a lot of time to figure it out, so I'm really proud of it! Also, the fact that my game is able to show the win screen and lose screen makes me really proud too. It makes my game functionable and harder for the player to win.

Any challenges you encountered and how you solved them: I faced a challenge with the level loader, as it had a lot of errors when I first made the script. I'm more used to python coding, so I formatted the C# code wrong causing a lot of errors in my game. After following a tutorial to help me, I got it kind of figured out. I had attached it to the wrong sprite, and when I attached it to the right sprite after that(The Portal) but it still wasn't working. Through trial and error, I figured out that I forgot to put the "Is Trigger" as on for the collider. After that, it finally worked.
