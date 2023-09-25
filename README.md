# rocket-stimulator
# Rocket Simulation

This is a Python program that simulates the launch and flight of a rocket through different stages. It allows you to control the rocket's actions and monitor its parameters.

## Getting Started

To run the rocket simulation, you need Python installed on your computer.

1. Clone or download this repository to your local machine.

2. Open a terminal or command prompt and navigate to the directory where the code is located.

3. Run the simulation by executing the following command:

python rocket_simulation.py

markdown
Copy code

4. Follow the on-screen instructions to interact with the simulation.

## Features

- Simulates a rocket's launch and flight through different stages.
- Allows you to fast forward through the simulation.
- Provides real-time updates on the rocket's parameters, including stage, fuel, altitude, and speed.
- Checks for stage separation and orbit achievement.

## Commands

- `start checks`: Check all systems and report if 'Go' for launch.
- `launch`: Start the mission and enter the simulation loop.
- `fast forward [seconds]`: Speed up the simulation by specifying the number of seconds to fast forward.
- `exit`: Exit the simulation.

## Simulation Details

- The rocket has two stages: "Stage 1" and "Stage 2".
- Each stage has specific parameters for fuel depletion rate, altitude increase rate, and speed increase rate.
- The simulation checks for stage separation and orbit achievement conditions.
- The mission can end in success (orbit achieved) or failure (insufficient fuel).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The code is a basic simulation for educational purposes and can be extended and modified for more complex scenarios.

Feel free to modify and improve this code for your own purposes or contribute to the project!

Happy rocket simulation!
