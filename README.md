## Matrix Multiplication Using MapReduce over HDFS

In the following example we will learn to multiply two matrices which are stored over HDFS in the given structure.

```
A,0,0,63
A,0,1,45
A,0,2,93
A,0,3,32
A,0,4,49
A,1,0,33
A,1,3,26
A,1,4,95
A,2,0,25
A,2,1,11
A,2,3,60
A,2,4,89
A,3,0,24
A,3,1,79
A,3,2,24
A,3,3,47
A,3,4,18
A,4,0,7
A,4,1,98
A,4,2,96
A,4,3,27
B,0,0,63
B,0,1,18
B,0,2,89
B,0,3,28
B,0,4,39
B,1,0,59
B,1,1,76
B,1,2,34
B,1,3,12
B,1,4,6
B,2,0,30
B,2,1,52
B,2,2,49
B,2,3,3
B,2,4,95
B,3,0,77
B,3,1,75
B,3,2,85
B,4,1,46
B,4,2,33
B,4,3,69
B,4,4,88
```
Where each row in trhe dataset represents
<Matrix_Name>, &lt;Row&gt;, &lt;Column&gt;

1. Data is stored in the file input.txt (given above for download) or simply do.
```
$ touch input.txt
$ vi input.txt
```
![]()
