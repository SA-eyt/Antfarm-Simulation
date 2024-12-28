
# Antfarm Simulation Project

## Description
This project simulates an ant farm, where various species of ants are spawned, interact, and perform tasks like gathering resources and fighting each other. The project uses object-oriented programming principles in C++ to simulate the behavior of different species in the colony.

## How the Code Works
- The program uses classes to represent `Colony`, `ColonyFactory`, and `AntFarm`.
- The `Colony` class defines the properties of a colony (species, resources, warriors, workers, etc.) and includes methods to give resources, fight other colonies, and print the colony's status.
- The `ColonyFactory` class is used to create new colonies.
- The `AntFarm` class acts as a singleton that manages all colonies, spawning new colonies, giving resources, and handling fights between colonies.
- Commands such as spawning colonies, listing colonies, giving resources, and initiating fights are executed using the `Command` design pattern.

## Outputs
The console output of the simulation has been attached for convenience.

## How to Run
1. Clone the repository: `git clone https://github.com/your-username/ant-simulation.git`
2. Open the project in a C++ IDE or text editor(I have used CodeBlock).
3. Compile and run the `main.cpp` file.
4. Follow the on-screen prompts to interact with the ant colonies.

