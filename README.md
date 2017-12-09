# SnakeGame 
Snake GamePlay :
  When the program starts its default state is pause, user must press an arrow key to start game.
  While playing user can use mouse to hover over buttons and click to either pause, quit, or start new Game. 
  Score functionality still missing but every time snake eats food this score increases by 10 points.
Program:
    There are eight classes for this program.
    Wall - Creates a wall object with x and y coordinates.
    Food - Creates a Food object with x and y coordinates.
    Empty - Creates an empty object with x and y coordinates. Mainly used to generate random available positions.
    Snake - creates snake object with x and y coordinates.
    GameManager - manages the logic of the game, creates board, checks collisions, generates walls, food, snake, and empty objects.
    BoardPanel - manages the panel where gameboard is drawn, the actual playing area.
    GameGUI - the main class that launches the frame. Defines map by default or by specified argument txt configuration.
  The most notable aspect of this game is that the logic implemented is based on the position of the objects which is y
      having x and y coordinate is essential for collision detection, etc. 
      
Issues:
  -There are a bunch of issues with my program which i didnt realize at first. My level Configuration is very different, it allows 
    for only horizontal and vertical walls, with (yCoor, XCoor) to (yCoor,XCoor) indicating initial starting point to end.
    I should also add myPaint component draws other configurations weirdly, i could not figure out, printing board to string prints correct
    board but frame paint configuration was wrong. 
  -As mentioned score functionality not available yet, it was a bit hard to get game to respond to changing snake size.
  -The DefaultMap configuration is the only one that works for now I believe. it should be present in jar file.
    Its present whithin the jar file, i couldn't get the jar file to execute it, don't know how to? however exctracting it
    into the desired directory side by side with the jar should make the jar executable. 
  -well there are lots of things that i wanted to include like custom made maps, and any drawings of my own, i would really 
    like to implement my own digital designs into future projects. 
  -There are so many things that I wanted to do do but couldn't! Need more knowledge! Thank you!
