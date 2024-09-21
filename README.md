Welcome! This is a webpage where I highlight some of my personal projects. Most of my projects are not on GitHub (especially older ones), but I figured they should have a cozy home in case someone wants to know what I work on outside of work!



## Road Riddle

![Screenshot of Road Riddle]({{ BASE_PATH }}/sample3.jpg)

Road Riddle is a PC game that fits into the puzzle and simulation genres. The player creates the roads which complete a highway intersection, and cars try to navigate across the map. Completing a level involves building all necessary routes without using too much concrete or causing massive traffic jams. There are buildings and mountains to deal with too, but players will find the biggest obstacle is all the other cars on the road.

Cars avoid hitting each other and judge each others' speed to merge into busy lanes seamlessly. Lanes can be built, edited, and grouped, and they'll snap into place while respecting the boundaries of existing roads. I've challenged myself to make the entire game without any text, relying on icons, small animations, and an intuitive UI to create a UX which needs no localization. Except for right-hand drive, of course.




## Flatwater

![Screenshot of Flatwater]({{ BASE_PATH }}/flatwater-screenshot1.png)

Flatwater is admittedly a moonshot. It's an optimization for cellular fluid simulation that relies on certain properties of low-viscosity fluids, such as the fact that at a coarse scale, fluids are typically flat on the top.

If possible, this could make the fluids in games far more dynamic without stealing the entire CPU or GPU. It sounds too good to be true, and honestly it very well might be, but I'm still giving it a chance. The screenshot above is a bit of terrain stored in an octree that I'm writing for the sim.




## Bermuda

![Screenshot of Bermuda]({{ BASE_PATH }}/bermuda-demo1.png)

Bermuda is a board game, not a video game, but there's also a companion app/website that you'll use to play the game. This project has been my most structured attempt at game design to date, requiring extensive economy, pace, and randomness balancing. But it has also been an outlet for my artistic side, letting me design tiles, cards, and documentation which meet my personal standards of attractiveness and functionality.




## Gravity

![Screenshot of Gravity]({{ BASE_PATH }}/gravity-screenshot.jpg)

Gravity is a Kerbal Space Program clone that I built with a fellow KSP fan. It likely won't get any more attention and goodness knows the graphics could use it, but it did provide me an opportunity to tackle problems most games don't have to worry about: predictable orbital physics and time warping. That's a problem that KSP has always had to compromise on and I had to try my hand at solving it. No spoilers on whether I was successful.




## MovieMap

![Screenshot of MovieMap]({{ BASE_PATH }}/moviemap_screenshot2.png)

Have you ever browsed Netflix aimlessly, hoping to find a movie you might like to watch? Have you ever googled 'best action movie list' in hopes of discovering a hidden gem of Hollywood? MovieMap predicts which movies you might like based on your similarity to other users. It's as if someone with the exact same taste as yourself ranked every movie out there and handed you the list.

MovieMap is under development. The UI is nearing MVP (minimum viable product), and it is connected to a third party API to retrieve the movie data. It's a web app using ASP.NET Razor pages with HTML 5 Canvas (JavaScript) for the UI.




## RiteNote

![Screenshot of RiteNote]({{ BASE_PATH }}/ritenote_screenshot_2.png)

Available for PC download on [SourceForge](https://sourceforge.net/projects/ritenote/).

I created the first version of RiteNote several years ago as a solution for taking notes in class, after finding that none of the existing applications had the clean, minimalistic, easy-to-use feel that I wanted. The interface is designed to be navigated from the keyboard, and the feature set focuses on efficiency. There are still a few important features missing, but I (and hopefully a few other people) still use it for taking class notes.

It was created using Livecode, which is a business-app creator that isn't very github-friendly. The project can be downloaded at sourceforge, but you'd need Livecode installed to look at it.




## TicTacToe AI

![Screenshot of TicTacToe AI]({{ BASE_PATH }}/tictactoe_screenshot_1.png)

This was a young and naive attempt to make an AI that could teach itself simple board games. It learns quite well if a human takes the time to play against him, but it's still pretty shoddy if it only plays against itself.

I made this before I took any AI courses, so I'll probably try again at some point. It was written in Java.




## Justice

![Screenshot of Justice]({{ BASE_PATH }}/justice_screenshot_5.png)

This is a very old personal project of mine, the favorite of my many abandoned game projects from before university. It had a user interface and level menu complete with soundtrack and logo animation, a first level with win conditions, and that classic Unity grass texture.

The player drives a police cruiser, tasked with pursuing a getaway car around a beautiful mountainous landscape. The AI car has a sequence of waypoints which it follows, while the player must catch up and either wreck the getaway car without totalling the cruiser, set up a roadblock, or shoot out the car's tires.

Like all my old 3D projects, Justice was created in Unity and written in JavaScript. Before the project was abandoned, I did get it working on an Android phone, using tilt steering and UI controls.
