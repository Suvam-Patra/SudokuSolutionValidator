# Sudoku Solution Validator

/**
 
 * This program defines a sudoku puzzle solution and then determines whether 
 * the puzzle solution is valid using 27 threads. 9 for each 3x3 subsection, 9
 * for the 9 columns, and 9 for the 9 rows. Each thread updates their index in 
 * a global array to 1 indicating that the corresponding region in the puzzle
 * they were responsible for is valid. The program then waits for all threads
 * to complete their execution and checks if all entries in the valid array have
 * been set to 1. If yes, the solution is valid. If not, solution is invalid.
 */
