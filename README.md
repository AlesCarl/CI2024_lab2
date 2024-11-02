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
| **Method**  | **COST** | **Iteractions**| 
|---|---|---| 
| Greedy | 4436.03 km | 2070 | 
| Greedy with mutation | 4425.72 km |16805|
| Simulated Annealing | 4705.76.60 km | 699999* | 
| Simulated Annealing with swapping | 4298.83 km | 699999* | 
|||
--- 

### 2. Russia: 

| **Method**  | **COST** | **Iteractions**| 
|---|---|---| 
| Greedy | 40051.59 km | 27722 |
| Greedy with mutation | 39120.17 km | 24909|
| Simulated Annealing | 42940.37 km | 699999* |
| Simulated Annealing with swapping | 44748.28 km | 699999*| 
|||

---




### 3. USA:

| **Method**  | **COST** | **Iteractions**| 
|---|---|---| 
| Greedy  | 46244.33 km | 105950 | 
| Greedy with mutation | 45627.90 km |42453| 
| Simulated Annealing  | 64249.30 km | 611705* |
| Simulated Annealing with swapping  | 62994.33 km | 699999* |
|||

--- 
### 4. China:

| **Method**  | **COST** | **Iteractions**| 
|---|---|---| 
| Greedy  |  62116.04 km | 52635 | 
| Greedy with mutation |  61859.22 km |  91674  | 
| Simulated Annealing   | 102381.43 km | 999999** | 
| Simulated Annealing with swapping  | 105670.63 km | 999999**  | 
|||

--------

_*iteractions are limited to 700.000_ 

_**iteractions are limited to 1.000.000_ 



The exercise was carried out in collaboration with Lorenzo di Rosa  (329169)



