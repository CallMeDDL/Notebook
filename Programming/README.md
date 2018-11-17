# Programming

## Data Structure
0. Linear 
* Binary search

1. String
* Pattern searching: KMP, Rabin-Karp


2. Tree
* DFS(Stack) and BFS(Queue), Iterative and recursive
* Segment tree

3. Graph
* Union find, Disjoint set
* Topological sort : Map<Integer, List<Integer>> graph, int[] visited

4. Dictionary
* Binary search
* Trie: great for word validation problem
	Class node{
		HashMap<Char, Node> children;
		Boolean isCompleteWord;
	}

5. TreeMap


## Underlying Algorithm

0. Divide and Conquer
* Mergesort algorithm

1. Dynamic Programming
* Simplify a decision by breaking it down into a sequence of decision steps over time
* Usually used to improve DFS and solve special NP problem in polynomial time
* DFS with memorization is equal to DP algorithm

2. Greedy

3. Backtrack
* DFS

4. Branch and Bound
*  Discrete programming

5. Math
* GCD(Greatest Common Divisor): Euclidean algorithm: gcd(a,b) = gcd(b,a % b)
* LCM(Least Common Multiple): lcm(a,b) = a * b / gcd(a,b)
* Exclusive or: A ^ B ^ B = A

## Heuristic Algorithm
0. Minimax Algorithm:
* When dealing with gains, it is referred to as "maximin"—to maximize the minimum gain.
* Improvement: alpha-beta pruning and Monte Carlo tree search

1. A* Algortihm
* Alpha–beta pruning
