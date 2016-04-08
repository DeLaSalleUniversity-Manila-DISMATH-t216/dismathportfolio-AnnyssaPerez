# dismathportfolio-AnnyssaPerez
dismathportfolio-AnnyssaPerez created by Classroom for GitHub

# Week 1
- During the first meeting, our professor, Engr. Melvin Cabatuan, introduced the course Discrete Mathematics to us along with the purpose of studying it as future electronics engineers.
- During the introduction, we were informed that this course only deals with MATHEMATICAL truths.
- We were able to discuss the following topics:
 - **Truth Tables**
 
 | p | q | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q |    
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| F | F | F | F | F | T | T |
| F | T | F | T | T | T | F |
| T | F | F | T | T | F | F |
| T | T | T | T | F | T | T |

  - **Logical Operations/Connectives**
  
  | Logical Symbol  |  Operator | Usage |
| :---: |:--------:|:-----:|
| ¬ |Negation | not |
| ∧ | Conjunction | and |
| ∨ | Disjunction | or |
| ⊕ | Exclusive disjunction | xor | 
| → | Conditional | if, then & only if|
| ⇔| Biconditional | iff |

  - **Propositional Logic** (p → q)
  
  | Implication Equivalence | Contrapositive | Inverse | Converse |
  | :----: | :----: | :----: | :----:|
  | p → q ≡ ¬p ∨ q | ¬q → ¬p | ¬p → ¬q | q → p |
  
  # Week 2
- In our second week, we got to delve more on propositional logic.
- These are the topics we discussed:
  
  - **Terminologies**
    
      1. Argument - sequence of statements that end with a conclusion
      2. Valid - a conclusion follows from the truth of the premises
      3. Fallacy - incorrect reasoning
      4. Tautology - a statement that is always true
  
 - **Logical Equivalences**
    
    | Name | Logical Equivalence |
| :----: | :-------: |
| Identity Laws | p ∧ <b>T</b> ≡ p <p>p ∨ <b>F</b> ≡ p</p> |
| Domination Laws | p ∨ <b>T</b> ≡ <b>T</b> <p>p ∧ <b>F</b> ≡ <b>F</b> |
| Negation Laws | p ∨ ¬p ≡ <b>T</b> <p>p ∧ ¬p ≡ <b>F</b> |
| Double Negation Law | ¬(¬p) ≡ p |
| Idempotent Laws | p ∨ p ≡ p <p>p ∧ p ≡ p |
| Commutative Laws | p ∨ q ≡ q ∨ p <p>p ∧ q ≡ q ∧ p</p> |
| Associative Laws | (p ∨ q) ∨ r ≡ q ∨ (p ∨ r) <p>(p ∧ q) ∧ r ≡ q ∧ (p ∧ r)</p> |
| Distributive Laws | p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (q ∨ r) <p> p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (q ∧ r)</p> |
| De Morgan's Law | ¬(p ∧ q) ≡ ¬p ∨ ¬q <p>¬(p ∨ q) ≡ ¬p ∧ ¬q</p> |
| Absorption Laws | p ∨ (p ∧ q) ≡ p <p>p ∧ (p ∨ q) ≡ p</p> |

 - **Two kinds of quantifiers**
 
 | Existential | Universal |
 | :-----: | :-----: |
 | "there exists" | "for all" |
 | ∃(x) | ∀(x) |
 
 # Week 3
 - We were then introduced to the rules of interference. I found this topic confusing, especially with the names, but I've come to learn that these rules are very useful for proving mathematical logic.
 
 - **Rules of Interference**

| Name  |  Formula    | Tautology |
|:----------:|:--------------:|:-----------------------:|
| Addition |  p ∴ p ∨ q  | p → (p ∨ q) |
| Simplication  |  p ∧ q ∴ p  | (p ∨ q) → p |
| Conjunction | p, q ∴ p ∧ q  | ((p) ∨ (q)) → (p ∨ q) |
| Resolution  | p ∨ q, ¬p ∨ r ∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |
| Modus ponens | p, p→q ∴ q | (p ∧ (p → q)) → q |
| Modus tollens | ¬q, p→q ∴ ¬p | (¬q ∧ (p → q)) → ¬p |
| Hypothetical syllogism | p → q, q → r ∴ p → r  | ((p → q) ∧ (q → r)) → (p → r) |
| Disjunctive syllogism | p ∨ q, ¬p ∴ q | ((p ∨ q) ∧ ¬p) → q |

# Week 4
 - During this week, we discussed the different methods of proof and the procedure on how to solve mathematical logic equations using them.
 - I have learned that there is usually more than one way to prove problems.
 
  **Methods of proof**
 
1. Direct Proof
2. Indirect Proof
3. Vacuous Proof
4. Trivial Proof
5. Proof by Cases
6. Proof by contradiction
7. Proof by induction
8. Proof by contraposition

# Week 5
- The discussion for methods of proof was continued during this week. As we were given more examples to practice on, I got to understand the topic more. It made me understand the importance of practicing on different types of problems in order to fully grasp the topic discussed in class.

# Week 6

**Mathematical Induction**
 1. The basis step is to prove that P(1) is true.
 2. The inductive step is done by proving the whole sequence to be true given the basis step.
 The example given in class is a basic mathematical equation although it helped in letting the class understand the topic further.
    Prove P(n) = 1 + 2 + 3 + ... + n = n(n+1)/2

 **Hoare Triple**
- p{S}q
- A method of proving the partial correctness of a program segment **S** with respect to **p** which is the initial assertion and **q** which is the final assertion when **p** is a true input value for **S** and **q** is a true output value for **S**.

# Week 7 
  - No class for the week.
 
# Week 8

** Set Theories**
- Set theories is one of the easy topics although it requires multiple terms to remember.
- General form of sets: {1, 2, 3}
- Empty set: { } = ∅

 **SET IDENTITIES**
 
 
|  Law  |  Identity  |
| :-------: | :---------------------------: |
| Identity Laws |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
| Domination Laws |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
| Idempotent Laws |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
| Complementation Law |  (A¯)‾ ≡ A  |
| Commutative Laws |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
| Associative Laws |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
| Distributive Laws |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
| De Morgan's Laws |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
| Absorption Laws |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
| Complement Laws |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

**Terminology**
 1. Cardinality
 - Defined as the number of elements contained in a set. 
 - Denoted by |S| for set S.
 2. Functions
 - Assignment of exactl one element from A to B.
 3. Image
 - If f(**a**) = **b**, **b** is the image of **a
 
**Types of Functions**
 1. One-to-one (Injective)
 - Functions that have exactly one assigned value to two different domains
 2. Onto (Surjective)
 - Functions with equal range and codomain.
 3. One-to-one correspondence (Bijection)
 - Functions that is one-to-one and onto.
  
# Week 9
**Algorithms & Pseudocodes**
  - Initially, I thought this topic was interesting because I get to further understand all my programming classes but I ended up having a hard time understanding the topic.
  - The most difficult part is that the pseudocodes cannot be compiled or debugged in a program to check for errors.

  - **Properties of Algorithm**
 1. Input
  - Input values from a set
 2. Output 
  - Produced output from the given input values
 3. Definiteness
  - Precision of the steps of an algorithm
 4. Correctness
  - Ability of the algorithm to produce the proper output from the given input
 5. Finiteness
  - Ability of the algorithm to produce the output from a finite number of steps
 6. Generality
  - Ability of the algorithm to be applicable for all problems of the desired form
  - 

# Week 10
  - The topic on algorithm was continued.
  
  **Searching Algorithms**
   - Locating an element in an ordered list.
  1. Linear Search Algorithm
   - Determines whether the location and element matches.
  2. Binary Search
   - Compares the element to the middle term of the list and determining whether it is larger or smaller.
 
  **Sorting Algorithms**
   - Sorting the elements in increasing order.
  1. Bubble Sort
   - Comparing adjacent elements and interchanging them until the right order is met.
  2. Insertion Sort
   - Comparing the first two elements and places the smaller element before the other element.
 
# Week 11

 **Growth of Functions**
  1. Big-O: |f(x)| ≤ |C(g(x))| ; upper bound 
  2. Big-Omega: |f(x)| ≥ |C(g(x))| ; lower bound
  3. Big-Theta: |C1(g(x))| ≤ |f(x)| ≤ |C2(g(x))| ; lower and upper bound

# Week 12

**Graph Theory**
  - G = (V,E) where V is the set of vertices or nodes and E is the set of edges
  
  - **Handshaking Theorem** 
  - 2e=∑deg(v)
   - 
  - **Euler's Formula**
  - r - e + v = 2
   
  - **Euler Circuit** - A graph that consists an even number of degree for all vertices.
  - **Euler Path** - A graph that has exactly two vertices with odd degrees.
  - **Hamilton Circuit/Path** - Similar to the Eulerian but passes through the vertices instead of the edges
  - **Isomorphism** - A graph that remains the same when the orientation is changed.
  - **Planar Graphs** - Graphs that do not overlap or cross edges.
  - **Kuratowski's Theorem** - A graph that is nonplanar if and only if it has a homeomorphic subgraph to another graph.

# Week 13

**Graph Coloring**
  - Accomplished by assigning a color where there are no sharing vertices.
**Four Color Heorem**
  - A planar graph's chromatic number must not be greater than 4.
  - 
  
**Trees**
  - A graph with no simple circuits.
