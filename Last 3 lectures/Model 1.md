# Expert Systems Review Questions  
**Based on Lectures 4, 5, and 6**  

---

## **Lecture 4: Knowledge Representation & Foundational Structures**

1. **Which of the following is an example of an Object-Attribute-Value triple?**  
   a) (Car, Red, Color)  
   b) (Student, Age, 20)  
   c) (Apple, Fruit, Sweet)  
   d) (Book, Title, Author)

2. **In a frame-based representation, what does a “slot” represent?**  
   a) The object name  
   b) An attribute or property  
   c) A default value  
   d) A procedural method

3. **Which knowledge representation technique uses nodes and links?**  
   a) Production Rules  
   b) Frames  
   c) Semantic Networks  
   d) Logic

4. **What is the main purpose of logic in knowledge representation?**  
   a) To store large amounts of data  
   b) To enable automated reasoning and unambiguous representation  
   c) To visualize relationships  
   d) To define syntax only

5. **Which type of logic deals with predicates and quantifiers?**  
   a) Propositional Logic  
   b) First-Order Logic  
   c) Semantic Logic  
   d) Descriptive Logic

6. **In a Venn diagram, what does the overlapping area of two circles represent?**  
   a) Union of sets  
   b) Intersection of sets  
   c) Complement of a set  
   d) Subset relationship

7. **Which of the following is a proposition in propositional logic?**  
   a) x + 2 = 5  
   b) “It is raining”  
   c) ∀x Human(x)  
   d) Loves(John, Mary)

8. **What is the truth value of P → Q when P is false and Q is true?**  
   a) True  
   b) False  
   c) Undefined  
   d) Invalid

9. **Which of the following is NOT a logical connective in propositional logic?**  
   a) ∧  
   b) ∨  
   c) →  
   d) ∀

10. **In a graph, what is a simple path?**  
    a) A path with repeated nodes  
    b) A path that starts and ends at the same node  
    c) A path with no repeated nodes  
    d) A path that visits every edge exactly once

11. **What is an Eulerian circuit?**  
    a) A path that visits every node exactly once  
    b) A path that visits every edge exactly once and returns to start  
    c) A simple path between two nodes  
    d) A cycle with odd-degree nodes

12. **A Hamiltonian circuit must:**  
    a) Visit every edge exactly once  
    b) Visit every node exactly once and return to start  
    c) Have all nodes with even degree  
    d) Be a non-simple path

13. **A connected graph is one where:**  
    a) There is at least one cycle  
    b) There is a path between every pair of nodes  
    c) All nodes have the same degree  
    d) It contains a Hamiltonian circuit

14. **A tree is defined as:**  
    a) A graph with at least one cycle  
    b) A disconnected graph  
    c) A connected, acyclic graph  
    d) A graph where every node has exactly two children

15. **In a binary tree, each node can have at most:**  
    a) One child  
    b) Two children  
    c) Three children  
    d) Unlimited children

---

## **Lecture 5: Logic Representation Systems**

16. **What are the two pillars of any formal logical language?**  
    a) Grammar and Vocabulary  
    b) Syntax and Semantics  
    c) Truth and Falsehood  
    d) Constants and Variables

17. **In propositional logic, which of the following is a well-formed formula (WFF)?**  
    a) P ∧ Q →  
    b) (P ∧ Q) → R  
    c) ∧ P Q  
    d) P →→ Q

18. **Which logical connective represents “implies”?**  
    a) ∧  
    b) ∨  
    c) →  
    d) ¬

19. **What is a limitation of propositional logic?**  
    a) It cannot represent negation  
    b) It cannot look inside propositions or represent objects and relations  
    c) It has no semantics  
    d) It cannot use truth tables

20. **Which of the following is a predicate in first-order logic?**  
    a) Socrates  
    b) Human(x)  
    c) ∀x  
    d) ∧

21. **What does the universal quantifier (∀) mean?**  
    a) There exists at least one  
    b) For all  
    c) Not  
    d) Or

22. **In FOL, what is a term?**  
    a) A predicate applied to arguments  
    b) A quantifier  
    c) A constant, variable, or function applied to terms  
    d) A logical connective

23. **Which of the following is a valid FOL formula?**  
    a) ∀x Human(x) ∧ Mortal(x)  
    b) Human(Socrates)  
    c) P → Q  
    d) ∧∨¬

24. **What does a model in FOL consist of?**  
    a) A set of truth tables  
    b) A domain and an interpretation  
    c) Variables and constants  
    d) Syntax rules only

25. **Which formula correctly represents “Every cat is an animal” in FOL?**  
    a) ∃x (Cat(x) ∧ Animal(x))  
    b) ∀x (Cat(x) → Animal(x))  
    c) ∀x (Cat(x) ∧ Animal(x))  
    d) ∃x (Cat(x) → Animal(x))

26. **In FOL, what does the interpretation (I) assign to a predicate?**  
    a) A truth value  
    b) A set of objects in the domain  
    c) A logical connective  
    d) A quantifier

27. **Which of the following is an example of a function in FOL?**  
    a) Human(x)  
    b) fatherOf(John)  
    c) ∀x  
    d) →

28. **What is the meaning of ∃x Loves(x, Mary)?**  
    a) Everyone loves Mary  
    b) There exists someone who loves Mary  
    c) Mary loves everyone  
    d) No one loves Mary

29. **Which of the following is NOT part of FOL syntax?**  
    a) Predicates  
    b) Quantifiers  
    c) Truth tables  
    d) Functions

30. **In FOL, when is ∀x P(x) true in a model?**  
    a) When at least one object satisfies P  
    b) When no object satisfies P  
    c) When all objects in the domain satisfy P  
    d) When exactly one object satisfies P

---

## **Lecture 6: Expert Systems & Inference Methods**

31. **What is unification in logic?**  
    a) The process of simplifying logical expressions  
    b) The process of making two logical expressions identical by finding a substitution  
    c) The process of resolving conflicts between rules  
    d) The process of forward chaining

32. **Which condition must be satisfied for two expressions to unify?**  
    a) They must have the same number of arguments  
    b) They must have different predicate symbols  
    c) They must contain no variables  
    d) They must be in different logical systems

33. **What is the conflict in unifying Loves(x, x) and Loves(Ali, Adel)?**  
    a) Different predicate symbols  
    b) Different number of arguments  
    c) x cannot be both Ali and Adel  
    d) No conflict—they unify easily

34. **What is the Match-Fire cycle?**  
    a) A method for parsing natural language  
    b) The core procedure of a rule-based expert system  
    c) A technique for drawing graphs  
    d) A semantic network traversal method

35. **In the Match phase, what does the inference engine do?**  
    a) Executes all rules simultaneously  
    b) Compares rule conditions against facts  
    c) Deletes facts from memory  
    d) Stops the system

36. **What happens in the Fire phase?**  
    a) Rules are matched against facts  
    b) The engine executes the selected rule’s action  
    c) New facts are ignored  
    d) The knowledge base is cleared

37. **What is forward chaining?**  
    a) Goal-driven reasoning  
    b) Data-driven reasoning from facts to conclusions  
    c) A method for unifying predicates  
    d) A type of semantic network

38. **In forward chaining, you start with:**  
    a) A hypothesis  
    b) A set of facts  
    c) A goal  
    d) A conflict set

39. **What is backward chaining?**  
    a) Reasoning from facts to goals  
    b) Goal-driven reasoning from hypothesis to needed facts  
    c) A method for matching rules  
    d) A type of frame-based system

40. **In backward chaining, you start with:**  
    a) Initial facts  
    b) A goal or hypothesis  
    c) A set of rules only  
    d) A unified expression

41. **Which chaining method is better for explanation?**  
    a) Forward chaining  
    b) Backward chaining  
    c) Both equally  
    d) Neither

42. **What is a conflict set?**  
    a) A set of facts that contradict each other  
    b) A set of rules whose conditions are satisfied and are ready to fire  
    c) A set of goals to be proven  
    d) A set of unified expressions

43. **Which strategy is used to select a rule from the conflict set?**  
    a) Unification  
    b) Conflict resolution strategy  
    c) Semantic matching  
    d) Backward chaining

44. **What does the inference engine do after firing a rule?**  
    a) Stops the system  
    b) Updates working memory with new facts  
    c) Deletes all previous facts  
    d) Ignores the result

45. **In the “Getting Ready for School” example, forward chaining starts with:**  
    a) “I am ready for school”  
    b) “Alarm is ringing” and “Feel hungry”  
    c) “You should brush your teeth”  
    d) “Why am I late?”

46. **In backward chaining, if a sub-goal cannot be proven, what happens?**  
    a) The system stops  
    b) The goal is considered false  
    c) The system tries another rule or reports failure  
    d) New facts are added automatically

47. **Which of the following is a key advantage of backward chaining?**  
    a) Efficient when there are many facts  
    b) Easy to explain “why” a question is asked  
    c) Always faster than forward chaining  
    d) Requires no conflict resolution

48. **What is the main difference between forward and backward chaining?**  
    a) Forward chaining uses rules, backward does not  
    b) Direction of reasoning: facts→goal vs. goal→facts  
    c) Only forward chaining uses unification  
    d) Backward chaining does not use a knowledge base

49. **In unification, what is a substitution?**  
    a) A logical connective  
    b) A set of variable assignments that make expressions identical  
    c) A conflict resolution method  
    d) A type of inference rule

50. **Which of the following pairs can be unified?**  
    a) Loves(John, Mary) and Hates(John, Mary)  
    b) Loves(x, y) and Loves(John, Mary)  
    c) Loves(x, x) and Loves(Ali, Adel)  
    d) Loves(John) and Loves(John, Mary)

---

## **Advanced & Combined Topics**

51. **Which knowledge representation method is most similar to a form with pre-defined slots?**  
    a) Semantic Networks  
    b) Production Rules  
    c) Frames  
    d) Propositional Logic

52. **A graph where every node has even degree is guaranteed to have:**  
    a) A Hamiltonian circuit  
    b) An Eulerian circuit  
    c) A simple path  
    d) No cycles

53. **In FOL, what is the correct representation for “Some humans are teachers”?**  
    a) ∀x (Human(x) → Teacher(x))  
    b) ∃x (Human(x) ∧ Teacher(x))  
    c) ∀x (Human(x) ∧ Teacher(x))  
    d) ∃x (Human(x) → Teacher(x))

54. **Which of the following is NOT a component of an expert system?**  
    a) Knowledge Base  
    b) Inference Engine  
    c) User Interface  
    d) Unification Engine

55. **What does the expression ∀x ∃y Loves(x, y) mean?**  
    a) Everyone loves one specific person  
    b) There is someone who loves everyone  
    c) Everyone loves someone (possibly different for each)  
    d) No one loves anyone

56. **A tree with n nodes has exactly how many edges?**  
    a) n  
    b) n-1  
    c) n+1  
    d) 2n

57. **Which logic system would you use to represent “All birds have wings”?**  
    a) Propositional Logic  
    b) First-Order Logic  
    c) Semantic Networks only  
    d) Production Rules only

58. **In a rule-based system, what is the role of the working memory?**  
    a) Store permanent rules  
    b) Hold current facts during inference  
    c) Perform unification  
    d) Resolve conflicts permanently

59. **What is the result of unifying P(x, f(y)) and P(a, f(b))?**  
    a) {x/a, y/b}  
    b) {x/f(y), y/b}  
    c) {x/a, f(y)/f(b)}  
    d) No unification possible

60. **Which of the following is true about both forward and backward chaining?**  
    a) They start with a goal  
    b) They use a knowledge base of rules  
    c) They do not use working memory  
    d) They never produce new facts

---

### **Answer Key**

1. **b** | 2. **b** | 3. **c** | 4. **b** | 5. **b** | 6. **b** | 7. **b** | 8. **a** | 9. **d** | 10. **c**
11. **b** | 12. **b** | 13. **b** | 14. **c** | 15. **b** | 16. **b** | 17. **b** | 18. **c** | 19. **b** | 20. **b**
21. **b** | 22. **c** | 23. **b** | 24. **b** | 25. **b** | 26. **b** | 27. **b** | 28. **b** | 29. **c** | 30. **c**
31. **b** | 32. **a** | 33. **c** | 34. **b** | 35. **b** | 36. **b** | 37. **b** | 38. **b** | 39. **b** | 40. **b**
41. **b** | 42. **b** | 43. **b** | 44. **b** | 45. **b** | 46. **c** | 47. **b** | 48. **b** | 49. **b** | 50. **b**
51. **c** | 52. **b** | 53. **b** | 54. **d** | 55. **c** | 56. **b** | 57. **b** | 58. **b** | 59. **a** | 60. **b**
