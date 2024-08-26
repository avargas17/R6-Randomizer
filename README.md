# R6-Randomizer
R6 Operator Randomizer
R6 Operator Randomizer is a Python application designed to help users randomly select operators and weapons from the game Rainbow Six Siege. The app categorizes operators into Attackers and Defenders, and allows users to randomize selections based on roles or weapon types. This tool can be particularly useful for players looking to explore different operators and weapons or simply add a bit of randomness to their gameplay.

Features:
- Random Operator Selection: Choose between Attackers and Defenders to randomly select an operator.
- Position-Based Randomization: Randomly select operators based on their roles, such as Support, Intel, and more.
- Weapon-Based Randomization: Filter and randomize weapons based on type, such as Assault Rifles, Shotguns, SMGs, etc.
- Interactive Menu: A simple command-line interface guides the user through options for randomization.

Project Structure:
- data.py: Handles reading operator data from a JSON file.
- operator_selection.py: Contains functionality for random operator selection.
- position_randomization.py: Manages randomization based on operator roles.
- weapon_randomization.py: Facilitates randomization based on weapon types.
- main.py: The entry point of the application, coordinating between different modules.
