# DISMATH-Daily-Learnings
What I Learned Last Class

DISMATH CLASSES Week 1

We were formally introduced to the world of Discrete Mathematics. The first part would be dealing with proof, specifically mathematical proof.


There are 6 basic operators in DISMATH:
    1) Negation="not"
    2) Conjunction="and"
    3) Disjunction="or"
    4) Exclusive or="xor"
    5) Conditional="implies"
    6) Biconditional="if and only if"
    
Truth tables were introduced. You can evaluate a mathematical statement using it's truth or false value, and those values can be presented in a truth table.

There are always two sets of variables (let them be x and y) in a statement or argument. 
    If a negation operator precedes any of them, the truth values are opposite. 
    Conjunction finds the minumum requirement (which in this case is false, as false represents 0 and true represents 1). If x and y, as long as any of them is false, the statement is false. 
    If x or y, as long as any of them is true, the whole statement is true, since disjunction looks for the maximum requirement (in this case, it is 1 = true). 
    If x xor y, if the truth values are different between them, statement is true; if equal, false. 
    If x implies y (conditional), if x is false: statement is true; if both are true: statement is true. 
    If y if and only if x (biconditional), if both are true or false: statement is true.


DISMATH CLASSES Week 2

Let variables be m, n & o.

Logical Equivalences:
1) Identity Laws: m or/and F/T is m

2) Domination Laws: m or/and T/F is T/F

3) Negation Laws: m or/and (not m) is T/F

4) Double Negation Law: not (not m) is m

5) Idempotent Laws: m or/and m is m

6) Commutative Laws: m or/and n is n or/and m

7) Associative Laws: (m or/and m) or/and o is
   m or/and (n or/and o)
   
8) Distributive Laws: p or/and (n or/and o) is
  (m or/and n) and/or (m or/and o)
  
9) De Morgan's Laws: not (m and/or n) is (not m) or/and (not n)

10) Absorption Laws: p or/and (m and/or n) is m

The 10 logical equivalences listed down above and the concepts of truth table can be used to do proof, much like you can use trigonometric identities to do proof.

To understand what we ae prooving more, we can look at statements using predicate logic; looking at it as 2 components paired together as subject and predicate in a sentence instead of seeing it as a whole.

Quantifiers
Existential Quantifiers = "There Exists"
Universal Qunatifiers = "for All"
Example of usage: "<For all>* counting numbers, <there exists>* a perfect square of 16."#
                *quantifiers
                #an example of a nested quantifier (a quantifier placed with another quantifier)

Existential Quantifiers - Difficult to disprove - done by citing that all values are false.
Universal Quantifiers - Easy to disprove - done by citing one value that is false.

Rules of Inference
-Used to test validity of an argument
-If it is valid: Tautology
-If it is invalid: Fallacy

Let variables be a, b, & c.
8 Rules of Inference
1) Modus Ponens: a. a implies b, therfore b.

2) Modus Tollens: not b. a implies b, therfore not p.

3) Hypothetical Syllogism: a implies b. b implies c, therefore a implies c.

4) Disjunction Syllogism: Either a or b. Not a, therefore b.

5) Addition: a, therefore a or b.

6) Simplification: a and b, therefore a.

7) Conjunction: a. b, therefore a and b.

8) Resolution: Either a or b. Either not a or c, therefore b or c.

The eight above are will all make tautologies - completely valid arguments. Just put clauses or mathematicals statements in place of the variables, and you can make any valid argument.


DISMATH CLASSES Week 3

Proof:
There are 5 main methods that we can use to do mathematical proof.

Direct Proof
Method: In an p implies q statement, we assume p to be true. Using definitions we know about the statement in p, we try to proove or disproove the statement.

Indirect Proof using Contraposition
Method: In a p implies q statement, we assume q to be not true. Using definitions we know about q, we try to disproove p by prooving not q to be true.

Indirect Proof using Contradiction
Method: In a p implies q statement, we assume the whole arguement to be false. Using definitions we know about the pand q, we try to proove the negated statement. If, it is disprooved, than the original statement is true.

Vacuous Proof
Method: We just need to disproove p to proove the whole statement, since as long as p is false, according to truth table concepts, the statement is true.

Trivial Proof
Method: Very related to vacuous proof, we just need to proove q to be true, since as long as q is true, the statement is true.


DISMATH CLASSES Week 4

Proof by Equivalence
Method: If the statement is biconditional, we proove using definitions of p and q that p implying q and q implying p are both true. We can use any method previously learned to proove the two conditional statements separately.

Mathematical Induction (proof)
Method: Usually, this method deals with series (arithmetic and geometric). It is prooving that a series is equivalent to a certain given function. (Example: 1, 2, 3, 4,...,n = sqrt(n)+2) Ideally, the method of proof used is direct proof.

DISMATH CLASSES Week 5
Recursive Algorithms
Method: When given a set of values - Two steps:
        1) A value will be specified as 0;
        2) As if in a sequence, what rule would you make that would define the sequence given?;

Program correctness
We use algorithms to test if a certain program is error-free or not; test if it is giving correct output; 
We verify a program with 2 ways:
1. Show that correct answer is obtained when the program runs;
2. Show if the program terminates or not;

Sets:
-Finite list of numbers;
Similar operators as connectives and rule under the same equivalences. ;
    Negation = prime;
    Conjunction = intersection;
    Disjunction = union;
    Additional equivalence: Complement Laws: A Union/Intersection B = U/0;
Relationships can be well visualised using venn diagrams, where the common region is the intersection;
Sets can be empty (null);
Set builder notation: {x|Definition of x};
Part of a set = subset; Union of 2 sets = sum of sets minus their intersection; Intersection of 2 sets = sum of sets minus exclusive values per set;
Set Cardinality = number of elements in set;

Functions: 
Exclusive relationship between 2 numbers A to B;
A is domain; B is Codomain; Set of all elements where A exists is Range;

3 Function types:
One-to-One = All elements in A has exclusively one B each;
Onto = several elements in A have 1 element B;
One-to-One Correspondence = Combination of One-to-One concept and Onto concept;

Discrete Function Example: Greatest integer; Least integer function

DISMATH CLASSES Week 6:
Algorithms:

Steps on making any Algorithm:
1) Determine the domain and desired output of the Algorithm (the preconditions);
2) Make the pseudocode of the algorithm (patterned much after C programming language)

Basic Examples of Algorithms:
Search (Binary & linear);
-Binary search is faster than linear. Linear goes through the list one by one. Binary searches the list by halfing.

DISMATH CLASSES Week 7:
More Algorithm Examples
Sorting (Insertion & Bubble);
Bubble Sort Pseudocode:
Precondition: {a1,...,an = real numbers};
    for i=1 to n-1
        for j=1+n{
        if aj>aj+i, 
    interchange}
Output {ai...an in increasing order}

Insertion Sort Pseudocode:
Precondition: (a1,...,an = real numbers);
    for i=1
    while aj>ai
        i=i+1;
        m=aj;
    for k=0 to j-i-1{
    aj-k=aj-k-i-1
        ai=m;}
    Output {ai...an in increasing order}

Growth functions:
3 types:
1. Big-O function;
    When x is 0y, y is the upper boundary of x;
2. Big-Omega function;
    When x is OMEGAy, y is the lower boundary of x;
3. Big-Theta function;
    When x is THETAy, y is both upper the boundary and lower boundary;

DISMATH CLASSES Week 8:
Graph Theory:

A graph is a finite set of vertices with lines called edges connecting edges in several many possible ways.
A degree is the number of connections to a vertex. If a vertex were an intersection, the degree would be the number of possible entry and exit ways to it. A vertex with a degree 0 is isolated. A pendant is a degree 1 vertex (as if hanging).

Handshaking theorem: Twice the edges is equivalent to the product of the summation of degrees and the number of vertices.

Planar graph - a graph without intersecting edges.

Euler:
-Circuit: A closed path where all the edges in a graph are crossed exactly once.
-Path: A general path where all the edges are crossed exactly once without really having to go back to the starting point

Hamilton:
-Circuit: A closed path where all the vertices in a graph are crossed exactly once.
-Path: A general path where all the vertices are crossed exactly once without really having to go back to the starting point

When a graph has a Hamilton circuit or path primarily, it is "Hamiltonian". It's Euler counterpart is "Eulerian".

Incidence Matrix: Matrix that represents how many vertices there are and how many connecting edges each has.

Adjacency Matrix: Matrix that represents which vertices are connected.

Isomorphic Graphs: Graphs can be twisted and bent to look like a totally different graph.

Homeomorphic Graphs: If a graph has many unnecessary vertices and edges, we can remove those to come up with a simpler graph.

DISMATH CLASSES Week 9:

Graph Coloring: The vertices can be colored to represent how the vertices are connected with each other.

Tree: A graph that starts from a single isolated vertex and extends downward to child-branches and further descendant branches.
