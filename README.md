##Starfield Animation
#Project Description
This project is a starfield animation created using the Pygame library.

##Key Features

#Star Creation:
- Stars are created with random coordinates within the screen boundaries.
- Each star has coordinates (x, y, z), where z represents the distance to the star.
- The star color is set to white (255, 255, 255).
#Star Movement:
- Stars move towards the viewer by decreasing their distance z.
- The x and y coordinates are updated based on perspective (x = x * 256 / z, y = y * 256 / z).
- If a star goes off the screen, it is replaced with a new one.
#Star Rendering:
- Stars are displayed on the screen as white circles.
- Star coordinates are converted from the custom coordinate system to the Pygame coordinate system.
#Game Loop:
-The game loop updates the positions of the stars and renders them on the screen.
-The loop continues until the user closes the window.
 
