# CI2024-lab2 

This project aims to solve the TSP problem for various cities in Italy, Russia, China and Usa using two different algorithms: 
- Greedy 
- Simulated Annealing. 

The goal is to find the shortest possible route that visits each city exactly once and returns to the starting point.

## Mutation Processes

This project utilizes two mutation strategies to optimize solutions: 

1. **Insert Mutation** :
Randomly selects two cities in the path and repositions one, introducing variations that help explore shorter routes.

2. **Insert Mutation with Swapping** :
Performs multiple swaps in a single mutation, allowing for a broader search of the solution space by repositioning several cities based on a dynamic number of swaps.



## RESULT: 


### 1. Italy: 
| **Method**  | **COST** |
|:---|:---|  
| Greedy | 4436.03 km |
| Greedy with mutation | 4425.72 km |
| Simulated Annealing | 4888.60 km |
| Simulated Annealing with swapping | 4659.95 km |
|||
--- 

### 2. Russia: 

| **Method**  | **COST** |
|---|---|
| Greedy | 40051.59 km |
| Greedy with mutation | 39120.17 km |
| Simulated Annealing | 42940.37 km |
| Simulated Annealing with swapping | 44748.28 km |
|||

---




### 3. USA:

| **Method**  | **COST** |
| --- | --- |
| Greedy  | 46244.33 km |
| Greedy with mutation | 45627.90 km |
| Simulated Annealing  | 64249.30 km |
| Simulated Annealing with swapping  | 62994.33 km |
|||

--- 
### 4. China:

| **Method**  | **COST** |
| --- | --- |
| Greedy  |  62116.04 km |
| Greedy with mutation |  61859.22 km |
| Simulated Annealing   | 102381.43 km |
| Simulated Annealing with swapping  | 105670.63 km |
|||

--------




The exercise was carried out in collaboration with Lorenzo di Rosa  (329169)
