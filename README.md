# AutoDrivingCarSimulation


Design:

It is a console application that simulates autonomous cars driving on a rectangular grid field. 
This will allow user to add cars, specify their initial positions, directions, and move commands.
Also, simulate their movement and detect possible collisions.The simulation stops when a car moves out of bounds or collides with another car.

This application consists of two classes Car, Simulation.
Car Class:
1) properties are name, position, direction,commands, collision occurs or not and collidewith if collision occurs.
2) Methods are Move(moves in the current direction by 1 unit), Rotate(Car's direction will be changed based on L or R command),NextPosition(calculates next position wrt current direction)

Simulation Class:
1) properties are width,height(read only) and List of cars.
2) Methods are AddCar(adds car into the list), DisplayListofCars(Displays cars list into console), Run(main logic for simulation calculation)


Assumptions:

1) Rectangular field and car’s initial position and direction must be specified.
2) Commands consist of L (left turn), R (right turn), and F (move forward).
3) The simulation runs until all commands are processed or out-of-bound moves or a collision occurs.
4) The program supports multiple cars on the field at the same time, detecting collisions and stopping affected cars.
5) Collisions are detected when two cars attempt to occupy the same grid space.

Requirements:

.NET SDK: Version 9
Operating System: Windows
IDE: Visual Studio 

How to Run:
1) Clone or Download the Code.
2) Download and install the .NET 9 SDK if not installed.
3) Build the application
4) Run the Application
5) Interact with the Application by providing inputs according to the prompts.
6) Run unit tests for Simaulation and Car.