MAT 215 Written Problems
===


## Written Homework 3: Set Theory
**Instructions** Pick a selection of five of the following for Written Homework 3. You may select your own "written" proof problems, but they must be related to Set theory from chapter 2, sections 2.1 - 2.5.

1. Let $A$, $B$, and $C$ be sets, show that $A\cup(B\cap C)=(A\cup B)\cap(A\cup C)$.
2. Let $A$, $B$, and $C$ be sets, show that $A\cap(B\cup C)=(A\cap B)\cup(A\cap C)$.
3. Either prove that for all sets $A$, $B$, and $C$, $A\oplus(B\oplus C)=(A\oplus B)\oplus C$ or provide an example showing that this associativity fails. 
4. Show that is $A$, $B$, and $C$ are sets, then $|A\cup B\cup C|=|A|+|B|+|C|-|A\cap B|-|A\cap C|-|B\cap C|+|A\cap B\cap C|$.
5. Show that $A\oplus(B\oplus C)=(A\cup B\cup C)-\bigl((A\cap B)\cup(A\cap C)\cup(B\cap C)\bigr)$. Explain why this shows that $A\oplus B\oplus C$ makes sense and generalize to $A_1\oplus A_2\oplus\cdots\oplus A_n$. 
6. Let $A$ and $B$ be finite sets. Show that $f:A\to B$ is onto iff it is one-to one.
7. For $A$ a set define $f_A(x)=\begin{cases}1&x\in A\\0&x\not\in A\end{cases}$ be the characteristic function of $A$. For $A$ and $B$ sets find simple algebraic expressions for $f_{A\cup B}$, $f_{A\cap B}$, $f_{\bar{A}}$, and $f_{A\oplus B}$. Show that the expressions you come up with are correct.
8. Show that $A$ is infinite iff there is $B\subsetneq A$ so that $|A|=|B|$. 
9. Show that for any set $A$, $|{\cal P}(A)|>|A|$. Hint: $f:A\to {\cal P}(A)$ is onto, so that $|{\cal P}(A)|\le |A|$, consider $B=\{a\in A\mid a\notin f(a)\}$.
10. Explain why $|2^A|=|{\cal P}(A)|$ where $2^A=\bigl\{f\mid f:A\to \{0,1\}\bigr\}$.

## Written Homework 4A: Induction 
**Instructions** Pick a selection of three of the following for Written Homework 4. You may select your own "written" proof problems, but they must be related to Induction from sections 5.1 and 5.2, at least one should involve stong induction or structural. There is a separate benchmark on recursion fro this week, that is the reason for three instead of the usual 5 here.

**Note** These all come directly from the text.

1. Use induction to show that if $n$ lines that are not parallel and no three of which contain a common point separate the plane into $(n^2+n+2)/2$ many regions. 

   As a variant, you might consider going up a dimension and consider slicing space by $n$ non-parallel planes, that do not intersect on a line. Also going down a dimension and consider slicing the real line by $n$ points. It is interesting to make a guess based on the first few cases of each. ([See this.](https://youtu.be/h0gbw-Ur_do))
2. Use induction to show that the ***arithmetic mean*** $(a_1+\cdots+a_n)/n$ is always $\ge$ the ***geometric mean*** $(a_1\cdot a_2\cdots a_n)^{1/n}$ for positive real numbers $a_i$ with equality only when $a_i=1$ for all $i$.

   **Hint** First show that it suffices to consider the case where $a_1\cdot a_2\cdots a_n=1$ so that what is really proved by induction is for $a_i>0$
   $$
 a_1\cdot a_2\cdots a_n=1\implies     a_1+\cdots+a_n\ge n.\tag{$P(n)$}
   $$
  with equality only when $a_i=1$ for all $i$.

   **More Hint** (This is a spoiler so don't give it at first.) $P(n)$ is clearly true if $a_i=1$ for all $i$ so assume some $a_i>1$. Without any loss of generality, assume $i=n$. So we have by induction 
$$
a_1/a_n+\cdots +a_{n-1}/a_n+a_n/a_n\ge n+1
$$
so 
$$
a_1+\cdots a_{n-1}+a_n\ge (n+1)a_n>n+1.
$$
3. Use mathematical induction to show that given a set of $n + 1$ positive integers, none exceeding $2n$, there is at least one integer in this set that divides another integer in the set.
4. Prove that $n^2-1$ is divisible by $8$ whenever $n$ is an odd positive integer.
5. Show that $21$ divides $4^{n+1}+5^{2n-1}$ whenever $n$ is a positive integer.
6. Show that if $h>-1$, then $1+nh\le (1+h)^n$ for all $n$. 
7. Prove that for any positive integer $n$,
   $$
   1+\frac{1}{\sqrt{2}}+\frac{1}{\sqrt{3}}+\cdots+\frac{1}{\sqrt{n}}>2\bigl(\sqrt{n+1}-1\bigr)
   $$
8. Prove that $H_1+H_2+\cdots H_n=(n+1)H_n-n$ where $H_i=1+\frac{1}{2}+\frac{1}{3}+\cdots+\frac{1}{i}$.
9. **Pick’s theorem** says that the area of a simple polygon P in the plane with vertices that are all lattice points (that is, points with integer coordinates) equals $I (P ) +B(P )/2 − 1$, where $I (P )$ and $B(P )$ are the number of lattice points in the interior of $P$ and on the boundary of $P$, respectively. Use strong induction on the number of vertices of $P$ to prove Pick’s theorem. 
   **Hint** For the basis step, first prove the theorem for rectangles, then for right triangles, and finally for all triangles by noting that the area of a triangle is the area of a larger rectangle containing it with the areas of at most three triangles subtracted
10. Let $P (n)$ be the statement that when nonintersecting diagonals are drawn inside a convex polygon with $n$ sides, at least two vertices of the polygon are not endpoints of any of these diagonals. (
    
    (a) Show that when we attempt to prove $P (n)$ for all integers with $n \ge 3$ using strong induction, the inductive step does not go through. 
    
    (b) Show that we can prove that $P (n)$ is true for all integers $n$ with $n \ge 3$ by proving by strong induction the stronger assertion $Q(n)$, for $n \ge 4$, where $Q(n)$ states that whenever nonintersecting diagonals are drawn inside a convex polygon with $n$ sides, at least two nonadjacent vertices are not endpoints of any of these diagonals


## Written Homework 4B: Recursion
**Instructions** Two problems should be chosen on recursion to meet one of the benchmarks. Again, these are taken from the text section 5.3.

1. a) Give a recursive definition of the function ones(s), which counts the number of ones in a bit string s. 
   
   b) Use structural induction to prove that $\rm{ones}(st) = \rm{ones}(s) + \rm{ones}(t)$. 
   
2. a) Give a recursive definition of the function $\rm{m}(s)$, which equals the smallest digit in a nonempty string of decimal digits. 
   b) Use structural induction to prove that $\rm{m}(st) = \min(\rm{m}(s), \rm{m}(t))$.

3. A **partition** of a positive integer *n* is a way to write n as a sum of positive integers where the order of terms in the sum does not matter. For instance, $7 = 3 + 2 + 1 + 1$ is a partition of 7. Let $P_m$ equal the number of different partitions of $m$, and let $P_{m,n}$ be the number of different ways to express $m$ as the sum of positive integers not exceeding $n$.
 
   a) Show that $P_{m,m} = P_m$. 

   b) Show that the following recursive definition for $P_{m,n}$ is correct: 
   $$
   Pm,n = \begin{cases}
   1 &\text{if } m = 1\\
   1 & \text{ if }n = 1\\
   P_{m,m} & \text{if }m <n\\
   1+P_{m,m-1}&\text{if }m=n>1\\
   P_{m,n−1} + P_{m−n,n} & \text{if }m>n> 1
   \end{cases}
   $$
   
   c) Find the number of partitions of 5 and 6 using the preceding recursive definition.

4. Use structural induction to show that $l(T )$, the number of leaves of a full binary tree $T$ , is 1 more than $i(T )$, the number of internal vertices of $T$.

The reversal of a string is the string consisting of the symbols of the string in reverse order. The reversal of the string $w$ is denoted by $w^R$.

5. Use structural induction to prove $(w_1w_2)^R=w_2^Rw_1^R$.
6. Give a recursive definition of the set of bit strings that are palindromes.


## Written Homework 7: Counting
**Instructions** Pick a selection of five of the following for Written Homework 7. You may select your own "written" problems, but they must be related to counting as presented in chapter 6. 

1. Use truth tables to show that there are $2^{2^n}$ *distict propositions*. Here a proposition $\phi$ and $\psi$ are ***equivalent*** if the truth tables of $\phi$ and $\psi$ are the same. 
2. Use tree diagrams to show count how many ways the numbers 2, 3, 6, 10 can be used to form a sum of 12 where repetition is allowed. So for example, $10+2$ and $2+2+2+2+2+2$ is another way, but the order of the terms do not matter, so $2+10$ and $10+2$ are considered the same. 
3. Prove that at a party where there are at least two people, there are two people who know the same number of other people there.
4. Let $n$ be a positive integer, and $x$ be an irrational number. Show that for some positive integer $j$ not exceeding the positive integer $n$, the absolute value of the difference between $jx$ and the nearest integer to $jx$ is less than $1/n$.
5. Prove Pascal’s identity, using the formula for ${n\choose r}$.
6. Prove the hockeystick identity 
   $$
   \sum_{k=0}^r{n+k\choose k}={n+r+1 \choose r}
   $$
   whenever $n$ and $r$ are positive integers,    
   a) using a combinatorial argument. 
   b) using Pascal’s identity.
7. Give a combinatorial proof that $\sum_{k=1}^n k{n\choose k}  = n2^{n−1}$. 
   **Hint**: Count in two ways the number of ways to select a committee and to then select a leader of the committee.
8. Give a combinatorial proof that $\sum_{k=1}^n k{n\choose k}^2  = n{2n-1\choose n-1}$
   **Hint**: Count in two ways the number of ways to select a committee, with n members from a group of n mathematics professors and n computer science professors, such that the chairperson of the committee is a mathematics professor.
9. How many solutions are there to the inequality $x_1 + x_2 + x_3 ≤ 11$, where $x_1$, $x_2$, and $x_3$ are nonnegative integers? 
   **Hint**: Introduce an auxiliary variable $x_4$ such that $x_1 + x_2 + x_3 + x_4 = 11$.
10. How many ways are there to travel in $xyzw$-space from the origin $(0, 0, 0, 0)$ to the point $(4, 3, 5, 4)$ by taking steps one unit in the positive $x$, positive $y$, positive $z$, or positive $w$ direction? (Explain your reasoning and calculation, the answer alone will not suffice.)

## Written Homework 8: Counting
**Instructions** Pick a selection of five of the following for Written Homework 8. You may select your own "written" problems, but they must be related to counting as presented in chapter 8.

1. a) Find a recurrence relation for the number of ternary strings of length $n$ that do not contain consecutive symbols that are the same. 
   b) What are the initial conditions? 
   c) How many ternary strings of length six do not contain consecutive symbols that are the same? 
2. a) Find a recurrence relation for the number of ternary strings of length $n$ that contain two consecutive symbols that are the same. 
   b) What are the initial conditions? 
   c) How many ternary strings of length six contain consecutive symbols that are the same?
3. Let $S(n,m)$ be the number of onto functions from a set of $m$ elements to a set of $n$ elements. Show that
    $$
    S(m,n)=n^m-\sum_{k=1}^{n-1}C(n,k)S(m,k)
    $$
   for $m\ge n>1$ and initial condition   $S(m,1)=1$.
4. Find the solution to $a_n = 2a_{n−1} + 5a_{n−2} − 6a_{n−3} with $a_0 = 7$, $a_1 = −4$, and $a_2 = 8$.
5. Find all solutions of the recurrence relation $a_n = 5a_{n−1} − 6a_{n−2} + 2^n + 3n$. 
   **Hint**: Look for a particular solution of the form $qn2^n+ p_1n + p_2$, where $q$, $p_1$, and $p_2$ are constants.
6. (Generating Functions) Use generating functions to solve the recurrence relation $a_k = 4a_{k−1} − 4a_{k−2} + k^2$ with initial conditions $a_0 = 2$ and $a_1 = 5$. 
7. (Generating Functions) Use generating functions to solve the recurrence relation $a_k = 2a_{k−1} + 3a_{k−2} + 4k + 6$ with initial conditions $a_0 = 20$, and $a_1 = 60$.
8. (Generating Functions) Use generating functions to prove Pascal’s identity: $C(n, r) = C(n − 1,r) + C(n − 1, r − 1)$ when $n$ and $r$ are positive integers with $r<n$.
   **Hint**: Use the identity, $(1+x)^n=(1+x)^{n-1}+x(1+x)^{n-1}$.
9. (Generating Functions) Use generating functions to prove Vandermonde’s identity: $C(m + n, r) = \sum_{k=0}^r C(m, r − k)C(n, k)$, whenever $m$, $n$, and $r$ are nonnegative integers with $r$ not exceeding either $m$ or $n$. 
   **Hint**: Look at the coefficient of $x^r$ in both sides of $(1 + x)^{m+n} = (1 + x)^m(1 + x)^n$.
10. (Inclusion-Exclusion) How many permutations of the 26 letters of the English alphabet do not contain any of the strings *fish*, *rat*, or *bird*?

## Written Homework 11A: Graph Models
**Instructions** Pick a selection of two of the following for Written Homework 11A. You may select your own "written" problems, but they must be related to counting as presented in section 10.1 .

1. In a round-robin tournament the Tigers beat the Blue Jays, the Tigers beat the Cardinals, the Tigers beat the Orioles, the Blue Jays beat the Cardinals, the Blue Jays beat the Orioles, and the Cardinals beat the Orioles. Model this outcome with a directed graph.
2. Describe a graph model that represents whether each person at a party knows the name of each other person at the party. Should the edges be directed or undirected? Should multiple edges be allowed? Should loops be allowed? 
3. Describe a graph model that represents a subway system in a large city. Should edges be directed or undirected? Should multiple edges be allowed? Should loops be allowed? 
4. For each course at a university, there may be one or more other courses that are its prerequisites. How can a graph be used to model these courses and which courses are prerequisites for which courses? Should edges be directed or undirected? Looking at the graph model, how can we find courses that do not have any prerequisites and how can we find courses that are not the prerequisite for any other courses? 
5. Describe a discrete structure based on a graph that can be used to model relationships between pairs of individuals in a group, where each individual may either like, dislike, or be neutral about another individual, and the reverse relationship may be different. 
   **Hint**: Add structure to a directed graph. Treat separately the edges in opposite directions between vertices representing two individuals.
6. Suppose that you have a three-gallon jug and a five-gallon jug. You may fill either jug with water, you may empty either jug, and you may transfer water from either jug into the other jug. Use a path in a directed graph to show that you can end up with a jug containing exactly one gallon.
   **Hint**: Use an ordered pair $(a, b)$ to indicate how much water is in each jug. Represent these ordered pairs by vertices. Add an edge for each allowable operation with the jugs.

## Written Homeworrk 11B: Graphs
**Instructions** Pick a selection of four of the following for Written Homework 11B. You may select your own "written" problems, but they must be related to counting as presented in chapter 10, sections 10.2, 10.4, 10.5, and 10.6.

1. Show that if G is a bipartite simple graph with $v$ vertices and $e$ edges, then $e \le v^2/4$. 
2. Show that if $G$ is a simple graph with $n$ vertices, then the union of $G$ and $\bar G$ is $K_n$. 
3. Describe an algorithm to decide whether a graph is bipartite based on the fact that a graph is bipartite if and only if it is possible to color its vertices two different colors so that no two vertices of the same color are adjacent.
4. Show that if $G = (V , E)$ is a directed graph, then the strong components of two vertices $u$ and $v$ of $V$ are either the same or disjoint. 
5. Show that all vertices visited in a directed path connecting two vertices in the same strongly connected component of a directed graph are also in this strongly connected component.
6. Show that a simple graph $G$ with $n$ vertices is connected if it has more than $(n − 1)(n − 2)/2$ edges.
7. Show that a directed multigraph having no isolated vertices has an Euler circuit if and only if the graph is weakly connected and the in-degree and out-degree of each vertex are equal.
8. Devise an algorithm for constructing Euler circuits in directed graphs and use some sort of induction to prove that your algorithm succeeds.
9. Show that Dijkstra’s algorithm may not work if edges can have negative weights.
10. Pick one of the three graphs from either Figure 1 or Figure 2 of section 10.6 the text and run Dijkstra's algorithm showing the full trace, i.e., the value of all labels and how they change as the algorithm progresses. 


## Written Homework 12: Trees
**Instructions** Pick a selection of four of the following for Written Homework 11. You may select your own "written" problems, but they must be related to counting as presented in chapter 11, sections 11.1, 11.2, 11.4, and 11.5.

1. A labeled tree is a tree where each vertex is assigned a label. Two labeled trees are considered isomorphic when there is an isomorphism between them that preserves the labels of vertices. How many nonisomorphic trees are there with three vertices labeled with different integers from the set $\{1, 2, 3\}$? How many nonisomorphic trees are there with four vertices labeled with different integers from the set $\{1, 2, 3, 4\}$?
2. a) How many nonisomorphic unrooted trees are there with four vertices? 
   b) How many nonisomorphic rooted trees are there with four vertices (using isomorphism for directed graphs)?
3. Let $G$ be a simple graph with $n$ vertices. Show that 
   a) $G$ is a tree if and only if it is connected and has $n − 1$ edges. 
   b) $G$ is a tree if and only if $G$ has no simple circuits and has $n − 1$ edges. 
   **Hint**: To show that $G$ is connected if it has no simple circuits and $n − 1$ edges, show that $G$ cannot have more than one connected component.
4. Take a piece of text with at least 100 characters including spaces and punctuation, but ignoring case. Build a Huffman encoding for the alphabet of the text and then encode the text. 
    **Hint**: The first step is to get a relative frequency distribution for the letter in the test.
5. Describe the trees produced by breadth-first search and depth-first search of the complete graph $K_n$, where $n$ is a positive integer. Justify your answers. 
6. Describe the trees produced by breadth-first search and depth-first search of the complete bipartite graph $K_{m,n}$, starting at a vertex of degree $m$, where $m$ and $n$ are positive integers. Justify your answers. 
7. Describe the tree produced by breadth-first search and depth-first search for the $n$-cube graph $Q_n$, where $n$ is a positive integer.
8. When must an edge of a connected simple graph be in every spanning tree for this graph?
9. Use Prim's algorithm to find a minimal spanning tree got each of the following graphs: 

    |Graph 1|Graph 2|
    |:--:|:--:|
    |![](https://hackmd.io/_uploads/ryCrShUd2.png =200x)|![](https://hackmd.io/_uploads/SkNoH3I_h.png =250x)|
    
    Provide a trace of the algorithm.
10. Use Kruskal's algorithm to find minimum spanning trees for each of the trees in (9). Provide a complete trace of the algorithm.

    




###### tags: `215`