This repository contains my solutions for the Round 2 Coding Puzzle Challenge.

---

Problem 1 – Grid Transform

I used the given grid and the row directions.  
Each row is rotated either left or right by one step.  
After rotating all rows, I selected the middle row (index 2).  
I added the ASCII values of all characters in that row.  
This total became **Clue 1**.

---

Problem 2 – String Process

Input string: `soscchallenge`

Steps followed exactly:

1. Reversed the string.
2. Removed every 3rd character.
3. Shifted all characters by +2 in ASCII.
4. Counted the vowels in the final string.

The vowel count became **Clue 2**.

---

Problem 3 – State Simulation

Numbers move through states based on rules:

- Even numbers advance normally.
- Prime numbers use a direct transition.
- Odd composites do not advance.

I counted how many reach the final state.  
This became **Clue 3**.

---

Final Key

I converted Clue 1 into hexadecimal.  
Then I repeated Clue 2 exactly Clue 3 times.
