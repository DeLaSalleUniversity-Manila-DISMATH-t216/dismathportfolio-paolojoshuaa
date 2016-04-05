# dismathportfolio-paolojoshuaa
dismathportfolio-paolojoshuaa created by Classroom for GitHub

#Week 1:
- Dismath was introduced to me by discussing about basic terms
    - Proof
    - Propositions
    - Logical deduction
    - Axiom
- We were told to check our GITHUB daily
  
- Logical Connectives was taught to us:
    - Negation (¬, not)
    - Conjunction (∧, and)
    - Disjunction (∨, or)
    - Exclusive Or (⊕, xor)
    - Conditional (→, if,then)
    - Biconditional (↔, iff)
- Note: 
  - ∧ - means "and" can also be known as "multiply"
  - ∨ - means "or" can also be known as "add"

#Week 2:
- Logical Equivalences was also discussed 
    - Identity Law
    - Domination Law
    - Negation Law
    - Double Negation Law
    - Idempotent Law
    - Commutative Law
    - Associative Law
    - Distributive Law
    - De Morgan's Law
    - Absorption Law

- note: implication equivalence
  - p→q = ¬p∨q
  
- Predicate logic was discussed.
- It tells us that it is concerned not only with the logic relations between sentences, but also their internal structure.
    - The Internal structure of the proposition itself is important.
    - This is required to understand Rules of Inference
- Rules of Inference were taught to us.
    - argument: a sequence of statements that end with a conclusion
    - valid: the conclusion, must follow from the truth of the preceding statements, or premises, of the argument.
    - fallacy: common form of incorrect reasoning leading to invalid arguments.

#Week 3:
- We talked about the 4 methods of Proof:
    - Direct Proof
    - Proof by Contraposition (Indirect)
    - Proof by Contradiction (Indirect)
    - Proof by Equivalence 

- Direct Proof:
    - First, we assume P is true.
    - Then, we show that q is also true.
    
- Proof by Contraposition:
    - First, we assume ¬q is true.
    - Then, we show that ¬p is true.
    
- Proof by Contradiction:
    - First assume ¬p is true.
    - Then, show that ¬q is true.
    
- We also talked about the Vacaous and Trivial Proof.
- For Vacuous Proof, we show that p is false, because p→q must be true when p is false.
- For Trivial Proof, we show that q is true, it follows that p→q must also be true.

#Week 4:
- Proof by Equivalence:
    - p→q and q→p are both true.

- This week, we discussed a new lesson, Mathematical Induction.
- Mathematical Induction has two steps:
    - Basis Step
    - Inductive Step

- Recursive Algorithms:
    - an algorithm is called recursive if it solves a problem by reducing it to an instance of the same problem with smaller input.

#Week 5:
- We continued talking about Recursive Algorithms:
- Program Correctness:
    - Uses the rules of inferences and various proof techniques.
    - Verification:
        - Shows that the correct answer is obtained if the program terminates and shows that the program always terminates.
        - The Initial Assertion, p, gives the properties that the input values must have.
        - The Final Assertion, q, shows the output that it should have.
- Set Theory:
    - A set is an unordered collection of distinct objects which may be anything.
    - In sets, the order is not important.
    - An Empty Set is a set that contains no elements.
    - Cardinality: no. of elements in a set.
    - Power Set: set of all the subset.

#Week 6:
- We started discussing about Functions.
- We talked about the different types of functions:
    - Injective (one-to-one)
    - Subjective (Onto)
    - Bijective (bot one-to-one and onto)

#Week 7:
- No classes during this week.

#Week 8:
- We were introduced to Algorithms.
- An algorighthm is a finite set of precise instructions for performing a computation or for solving a problem.
- Properties of an Algorithm:
    - Correctness
    - Finiteness
    - Generality
- Searching Algorithms:
    - Linear
    - Binary

#Week 9:
- We continued talking about Algorithms.
- Bubble Sort Algorithms: An algorithm that sorts a set of numbers in order. What it does is that it compares each pair of numbers first, and change it if the order is incorrect.
- Greedy Algorithm:
    - Selects the best choice at each step.
    - applied in optimization problems where the solution either minimizes or maximizes the value.

#Week 10:
- We started discussing about Growth Of Functions:
    - Described using Big-O Notation.
- Big-O: upper bound of a function. Can be determined by the highest degree of exponent in a function.
- Big-Omega: lower bound of a function.
- Big-Theta: both upper and lower bound of a function.
- Algorithm Time Complexity:
    - Constant
    - Logarithmic
    - Linear
    - nlogn
    - Polynomial
    - EXponential
    - Factorial

#Week 11:
- No classes this week

#Weel 12:
- We started with a new lesson: The Graph Theory.
    - Graph: discrete structures consisting of vertices and edges that connect these vertices.
    - Degree: number of edges incident with the vertex of the undirected graph, except that a loop at a vertex contributes twice to the degree of that vertex.
    - Path: sequence of edges that begins at a vertex of a graph and travels from vertex to vertex along edges of the graph.
    - Euler Circuit: starts and ends @ one particular point and passes through all edges once. (all nodes must have even degrees).
    - Euler Path: contains every edge and nodes. (exactly only 2 nodes with odd degrees).
    - Hamilton Circuit: Passes through every nodes, starts and ends at the same certain node.
    - Hamilton Path: passes through all nodes once.
    - Planar Graphs: graphs that can be drawn without edges having to cross.
    - Euler's Formula: r = e - v + 2
