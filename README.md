# Assignment_5
Assignment 5 for IMG 420

In this assignment I created 3 systems within Godot using C#.

For the Shader portion of the systems, I used C# to create a flexible modifier for the inserted sprite.
-It uses a wave distortion effect to distort the image, warping the particle created over time.
-It also uses a vertical gradient to blend the color of the particles.
The script also creates a 'wave_intensity' factor in the Inspector, to alter the distortion.

For the Physics segment:
-The script instantiates several 'clones' of the created segment
-Connects all the clones with a PinJoint2D (stable, rigid) or DampenedSpringJoint2D (stretchy, bouncy).
-The script also has a bunch of editable factors to alter the strength/rigidness of the connected chains.
-It contains a form of interactivity, using the ApplyForceToSegment() process.

The raycasting portion uses a script to:
-Create a ray protruding from the Node2D
-Alter the ray color and shape when the CharacterBody2D node touches/enters the ray's line of sight
-Print the message 'ALARM! Player detected!'

I am turning in this assignment late, and willing to take whatever penalty is assigned.
