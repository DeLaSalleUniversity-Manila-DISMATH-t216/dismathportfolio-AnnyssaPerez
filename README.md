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
 
  - **Methods of proof**
  
  1. Direct Proof
  2. Indirect Proof
  3. Vacuous Proof
  4. Trivial Proof
  5. Proof by Cases
  6. Proof by contradiction
  7. Proof by induction
  8. Proof by contraposition

  
