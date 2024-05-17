# Magic-Square-Puzzle

This Python project implements a solver for the "Moving Magic Square" puzzle using Genetic Algorithm principles. The objective of the puzzle is to rearrange numbers on a 3x3 table, including a movable number 9, such that each row, column, and diagonal sums up to 15.

## Puzzle Description
The "Moving Magic Square" puzzle consists of a 3x3 grid with numbers from 1 to 8 arranged initially. The number 9 is movable and can be placed in any empty cell. The goal is to rearrange the numbers along with the movable 9 so that the sum of each row, column, and diagonal equals 15.

## Genetic Algorithm Approach
The solver utilizes a Genetic Algorithm (GA) to search for the optimal solution. Here's how the GA is applied:

Initialization: Random initial population of solutions is generated.

Fitness Evaluation: The fitness of each solution is evaluated based on how close the sums of rows, columns, and diagonals are to 15.

Selection: Solutions are selected for reproduction based on their fitness, with fitter solutions having a higher chance of being selected.

Crossover: Selected solutions undergo crossover to produce offspring, combining the characteristics of their parents.

Mutation: Offspring may undergo mutation to introduce diversity into the population.

## Usage

To use the Moving Magic Square solver, follow these steps:

Clone the Repository: .git clone https://github.com/usmannazeer72/Magic-Square-Puzzle

Run this code on Google Colab.

## Configuration

You can adjust the parameters of the Genetic Algorithm, such as population size, mutation rate, and number of generations, by modifying the corresponding variables in the script or through command-line arguments.

## Contributing

Contributions to improve the solver or add new features are welcome. If you want to contribute, feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. You can find more details in the LICENSE file.


Replacement: The offspring replaces some solutions in the population, maintaining its size.
