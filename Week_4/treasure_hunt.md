# Treasure Hunt

### Problem: 
You're exploring a grid of size **`N x M`** (treasure map). 
Cells are either open (.) or blocked (#).
Start at (0,0), goal is (N-1, M-1). You can only move right or down.

Find the **maximum gold** you can collect on any valid path. Gold values are given in a second grid (0 if
no gold).

If no path exists, output -1.


### Input:
- First line: N M
- Next N lines: the map grid
- Next N lines: the gold values (integers 0-100)


### Constraints: 
$$2 ≤ N,M ≤ 30 $$


### Sample Input:
```
3 3
...
.#.
...
1 3 1
0 10 4
2 1 5
```

### Sample Output: 
```
13
```


### Points:
You will get 100 points for this task.