# Rooted-Tree
You are given a rooted tree with N nodes and the root of the tree, R, is also given. Each node of the tree contains a value, that is initially empty. You have to mantain the tree under two operations:

Update Operation
Report Operation
Update Operation
Each Update Operation begins with the character U. Character U is followed by 3 integers T, V and K. For every node which is the descendent of the node T, update it's value by adding V + d*K, where V and K are the parameters of the query and d is the distance of the node from T. Note that V is added to node T.

Report Operation
Each Report Operation begins with the character Q. Character Q is followed by 2 integers, A and B. Output the sum of values of nodes in the path from A to B modulo (109 + 7)

Input Format
The first Line consists of 3 space separated integers, N E R, where N is the number of nodes present, E is the total number of queries (update + report), and R is root of the tree.

Each of the next N-1 lines contains 2 space separated integers, X and Y (X and Y are connected by an edge).

Thereafter, E lines follows: each line can represent either the Update Operation or the Report Operation.

Update Operation is of the form : U T V K.
Report Operation is of the form : Q A B.
Output Format
Output the answer for every given report operation.

Constraints

1 ≤ N, E ≤ 105
1 ≤ E ≤ 105
1 ≤ R, X, Y, T, A, B ≤ N
1 ≤ V, K ≤ 109
X ≠ Y
