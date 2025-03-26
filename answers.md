# CMPS 2200 Reciation 5
## Answers

**Name:**_________________________


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
|      n |   qsort-fixed-pivot |   qsort-random-pivot |   tim-sort |
|--------|---------------------|----------------------|------------|
|    100 |               0.000 |                1.001 |      0.000 |
|    200 |               0.000 |                1.000 |      0.000 |
|    500 |               2.000 |                1.000 |      0.000 |
|   1000 |               3.000 |                3.001 |      0.000 |
|   2000 |               6.000 |                7.001 |      0.000 |
|   5000 |              15.003 |               19.005 |      0.000 |
|  10000 |              31.008 |               39.008 |      2.001 |
|  20000 |              81.018 |               81.018 |      3.000 |
|  50000 |             177.901 |              232.668 |     16.003 |
| 100000 |             391.087 |              461.103 |     34.008 |

Both the fixed pivot and random pivot run similarly, with the random pivot matching the expected O(n log n) time.


- **1c.**
As seen above, tim-sort is by far the fastest, running over 10x faster than quicksort with both a fixed and random pivot.