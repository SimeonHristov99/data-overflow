# Playing around with pandas

Solve problems using pandas.

## Task 1

Input parameters

```text
dataframe: pandas.DataFrame object
col: target column
```

Your function must return a new `pandas.DataFrame` object with the same columns as the original input. However, targeted column has in some of its cells a list instead of one single element.You must transform each element of a list-like cell to a row.

Input DataFrame will never be empty. You must not modify the original input. The target column will always be one of the dataframe columns.

Examples

Input

```text
     A      B
0 [1, 2]    5
1 [a, b, c] 6
2    77     3      
```

col = "A"

Output

```text
   A  B
0  1  5
1  2  5
2  a  6
3  b  6
4  c  6
5  77 3
```
