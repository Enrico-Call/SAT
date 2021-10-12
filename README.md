# SAT
The following repository contains a SAT Solver developed for the purposes of the (2020) course Knowledge Representation at Vrije Universiteit Amsterdam. The algorithm is based on the popular DPLL approach and contains one-sided Jeroslow-Wang (JW) and Maximum Occurrences in clauses of Minimal size (MOM) heuristics.

- SAT.py, file containing the SAT Solver with JW and MOM Heuristics implemented
- KRVU2020_paper_29.pdf, final report containing a draft research for the SAT Solver

#### Run the program with inputfile containing sudoku rules and a sudoku puzzle in DIMACS format:
$ python SAT.py -Sn inputfile

#### Run the program with rules and sudoku containing the rules and sudoku in DIMACS format.
$ python SAT.py -Sn rules sudoku

#### Run the script with sudoku containing a sudoku to convert it into a sudoku in DIMACS format:
$ python SAT.py -Sn sudoku

#### The output in DIMACS format is written to an outfile called inputfile.out.txt, where inputfile is the first file that is given as an argument.


Code written by: Enrico Calleris, Caya de Haas, Jaspreet Singh, and Nicole	van de Weijer.

Reproduced parts of the code have been properly cited.
