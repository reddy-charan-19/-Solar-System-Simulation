# -Solar-System-Simulation
This Python-based project simulates the movement of planets around the Sun using Tkinter for the graphical user interface (GUI) and math for orbital calculations. It provides an interactive, real-time visualization of the solar system, allowing users to explore planetary motions and view detailed planet information.
Code Overview:
Initialization:
The program initializes a window using Tkinter and sets up a black canvas to simulate space.
A yellow circle is drawn to represent the Sun at the center of the canvas.
A list of planets is created with their names, colors, distances from the Sun, sizes, and orbital speeds.
Planets and Orbits:
For each planet, an orbit is drawn as a white circle around the Sun, and a small circle representing the planet is created.
Planets are placed on their respective orbits and continuously move around the Sun based on their speed

Real-Time Updates:
The update_planets() function is called repeatedly to update the position of each planet using sin() and cos() for orbital motion, ensuring smooth movement in real time.
The canvas is updated every 50 milliseconds to give the effect of continuous motion.

User Interaction:
Clicking on a planet triggers a popup window using tkinter.messagebox.showinfo() that displays the planet's name, distance from the Sun, and orbital speed.
User Controls:
The program provides buttons to slow down, speed up, or pause the simulation, allowing users to control the pace of the planet's movements.
Stars:
A background of randomly placed stars is generated to enhance the space-like appearance.

Functions:
add_stars(): Generates a random distribution of stars on the canvas.
update_planets(): Updates the positions of planets based on their orbital speed and distance from the Sun.
show_planet_info(event): Displays detailed information about a planet when clicked.
slow_down(): Reduces the speed of the simulation.
speed_up(): Increases the speed of the simulation.
pause(): Pauses the simulation by setting the speed to zero.
