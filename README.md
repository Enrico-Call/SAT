# SAT
The following repository contains a SAT Solver developed for the purposes of the course Knowledge Representation (2020) at the Vrije Universiteit Amsterdam.
The code was co-created with Caya de Haas, Jaspreet Singh, and Nicole	van de Weijer.

### Run the program with inputfile containing sudoku rules and a sudoku puzzle in DIMACS format:
$ python SAT.py -Sn inputfile

### Run the program with rules and sudoku containing the rules and sudoku in DIMACS format.
$ python SAT.py -Sn rules sudoku

### Run the script with sudoku containing a sudoku to convert it into a sudoku in DIMACS format:
$ python SAT.py -Sn sudoku

### The output in DIMACS format is written to an outfile called inputfile.out.txt, where inputfile is the first file that is given as an argument.
