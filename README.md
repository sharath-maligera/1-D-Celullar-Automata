# 1-D Cellular Automata
- The code implements a 1-dimensional cellular automaton with the k = 2 states {0, 1}, 
with a neighborhood radius of r = 1 or r = 2, and 84 cells.
- The boundary cells j = 0, j = 1, j = 82, j = 83 are fixed to the content aj = 0. 
- The programm will depict in every line the complete state of all 84 cells as text console ASCII output.
- Two possible starting conditions for the CA:
  - S: a seed (all cells are empty but cell no 42, ai=42 = 1), and
  - R: random starting condition, each cell is set with a probability of p = 0.5.
- the user enters at runtime: the neighborhood radius r, the rule for the CA (Wolfram Notation), 
and the starting condition (S or R).
