# robot-simulation
Simulate the movement of cleaning robot in rooms to optimize efficiency 


This project simulates robotic vacuum cleaners with different cleaning strategies in a grid-based room. The room is represented by a rectangular grid of tiles, 
each containing an amount of dust that decreases as the robots clean. There are three types of robots, each with its own cleaning strategy:

1. BasicRobot: Moves in a set direction, cleaning tiles it encounters. If it would move outside the room, it randomly picks a new direction.
2. FaultyRobot: Similar to the BasicRobot, but with a chance of accidentally dropping dust on tiles instead of cleaning them.
3. SmartRobot: Uses a sensing mechanism to scan the surrounding area and move toward the dirtiest tiles.

The project includes a function to simulate the robots' behavior over multiple trials and calculate the average time required for them to clean 
a specific portion of the room, like 80% of tiles. Plots are generated to visualize and compare the time taken to achieve cleanliness based on different factors, such as the number of robots or room shape.
