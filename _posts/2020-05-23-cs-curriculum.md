---
title: "A Computer Science Curriculum for Self Taught programmer"
mathjax: true
layout: post
categories:
    - curriculum
---

# Why learn computer science instead of programming

Computer Science if all about learning the fundamental concepts of programming.
It really focusses on the 'WHY' rather than the 'HOW' stuffs works.

A big misconception is that computer science is all about programming. It is 
not. In fact, the [Association for Computing Machinery](https://www.acm.org/education/curricula-recommendations)
distinguish [18 different branches](https://www.britannica.com/science/computer-science)
in computer science, programming being one of them.

If your goal is to only learn programming, this curriculum is not suited 
for you. However, if your goals is to set the foundation that will allow 
you to be a lifelong student of programming as a whole, I think you can 
benefit from this stuffs.

# Some tips to keep in mind when learning computer science

### Tip #1: Remember to work on projects

Always remember that you are learning those fundations so that you can 
program things in a better way. You didn't really understand the concept 
if you didn't apply it to a project.

### Tip #2: 





# Branches in Computer Science

**Algorithms and Complexity [AL]**

1. Data Structures: Big O, Sorting Algorithms, heap, binary search tree, 
   self-balancing BST, hashmaps, treap
2. Algorithms: greedy algorithms, dynamic programming, backtracking, heuristic
3. Operation Research: modelisation, simplex, graph and network problems, 
   hungarian algorithms, queue MM1/MMs, camelot, inventory 
4. Theory of Computation: langagues, computation, time and space complexity

**Architecture and Organization [AR]**

1. Systems Fundamentals
2. Computer Architecture

**Computational Science [CN]**


**Graphics and Visualisation [GV]**

1. Computer Graphics
2. Discrete Geometry

**Human Computer Interaction [HCI]**

1. Human-Computer Interactions

**Information Assurance and Security [IAS]**


**Information Management [IM]**

1. Introduction to Databases
2. Advanced Databases Systems

**Intelligent Systems [IS]**

1. Machine Learning
2. Deep Learning
3. Computer Vision
4. Natural Language Processing
5. Reinforcement Learning



**Networking and Communication [NC]**

1. Network and Communications

**Operating Systems [OS]**

1. Operating Systems


**Platform-based Development [PBD]**

1. Web Development

**Parallel and Distributed Computing [PD]**

1. Parallel Computing
2. Distributed Computing
3. Cloud Computing

**Programming Languages [PL]**

1. Programmation I:
2. Programmation II: object-oriented programming
3. Programming Langages Concepts
4. Compilers and Interpreters

**Software Engineering [SE]**






# Courses Contents


### Algorithms and Complexity [AL]

Algorithms and complexity can be taught in 4 courses:

1. Data Structures: How can we store data efficiently
2. Algorithms: How can we solve problem efficiently
3. Operation Research: How can we modelize models
4. Theory of Computation: what problem can we solve

Although I really like my class on operation research, I feel like it 
could be an optional course because most of what we see is an amalgam 
of other course.

**Data Structures**

The course on data structure introduces us to the concept of time and 
space complexity analysis for heap, binary tree, balanced binary trees (AVL, 
red-black tree, B-Trees) and hashmaps operations. Therefore, when learning 
a new data structures, it is a good idea to be able to answer the following 
questions:

- how are the operations of search, insertion and deletion implemented in 
  the data structure?
- what properties does my data structure have?
- What makes this data structure better/worse than another one to solve a 
  particular problem?

A prerequisite for this course would be to take discrete maths, as one should be 
familiar with the notion of proofs and set theory.

The lecture video I used was [Robert Sedgewick's Data Structure Course Part I](https://www.coursera.org/learn/algorithms-part1) and [Robert Sedgewick's Data Structure Course Part II](https://www.coursera.org/learn/algorithms-part2) with the 
source code which can be found [their website](https://algs4.cs.princeton.edu/home/)

Although I didn't used that book when I first started to learn about data structures, I really wished I had [Pat Morin's - Open Data Structure Book](https://opendatastructures.org/ods-java.pdf) to follow along.

I also like [William Fiset's - Data Structure Playlist](https://www.youtube.com/playlist?list=PLDV1Zeh2NRsB6SWUrDFW2RmDotAfPbeHu), as it summarise the key elements 
to remember.


- Video Lectures: [Robert Sedgewick's Data Structure Course Part I](https://www.coursera.org/learn/algorithms-part1) and [Robert Sedgewick's Data Structure Course Part II](https://www.coursera.org/learn/algorithms-part2).
- Textbook:



**Algorithms**

The course on algorithms is about the techniques that can be employed to 
solve algorithms and the theorems we can use to evaluate their time complexity.
This is probably the most important course you should take because companies 
will usually test your algorithms and problem solving skills.

- Time Complexity Evaluation: 
  + Asymptotic theorems for Big O, Big Omega and Big Theta 
  + characteristic method for linear recurrence
  + power of two lemma and master theorem
- Problems Solving Techniques:
  + Greedy Algorithms
  + Divide-and-Conquer
  + Dynamic Programming
  + Backtracking
  + Probabilistic algorithms (monte carlo and las vegas)

A tip to keep in mind when learning algorithms is that all problems are 
derived by a 'typical' problem. Therefore, to solve any problem, we only 
need to (1) recognize the original problem (2) tweak the template of the 
original template to solve the new problem.

The lecture video I would recommend would be [Tim Roughgarden's Algorithms Illuminated Course](http://www.algorithmsilluminated.org/)

Although Roughgardent's textbook looks good, I found that [Jeff Erickson - Algorithms](http://jeffe.cs.illinois.edu/teaching/algorithms/) textbook really 
encapsulates the way I like to learn about algorithms, as it:

1. Explain what the problem is about
2. Suggesting a solution and its pseudocode
3. Time Complexity Analysis

Although this book doesn't provide a complete code, I still think we can 
follow along. The code for each algorithm can always be found with a quick 
Google search.

- Video Lectures: [Tim Roughgarden - Algorithms Illuminated](http://www.algorithmsilluminated.org/)
- Textbook:
- Exams and Homeworks: [Jeff Erickson - Exams](http://jeffe.cs.illinois.edu/teaching/algorithms/hwex.html)
- LeetCode: [Top 75 currated List](https://neetcode.io/)

I would also recommend using doing some Leetcode questions to get familiar 
with some common problems solving problems, which can be found at 
[Grokking the coding interview](https://www.educative.io/courses/grokking-the-coding-interview). To get better at problems solving, I would suggest choosing 
one pattern at a time and find a bunch of suggested problems with their 
solutions (use youtube, google, ...).

**Operation Research**

The course on operation research has 3 parts:

- Part 1: Solving problems with simplex algorithms, sensitivity analysis and 
  base method
- Part 2: Modelling graphs and networks problems as optimization problems,
  solving with hungarian algorithm
- Part 3: Solving deterministic and probabilistic problems with dynamic 
  programming


**Theory of Computation**

The course on Computation theory has 3 parts:

- Part I: Automatas and Languages
  + What are the closure properties of regular and context free languages
  + How can we prove that a langage is REG/CFL or not
- Part II: Computatibility Theory
  + Church-Turing Thesis: lambda calculus, turing machine and while programs 
    are equivalent
  + How can we prove that a language is decidable/recognizable or not
- Part III: Complexity Theory
  + Time Complexity: What makes a problem P, NP, NP-complete
  + Space Complexity: What makes a problem, PSPACE, PSPACE-complete, L, NL, NL-complete
  + Intractability:



I think Michael Sipser in the man when it comes to theory of computation. His 
[MIT 18.404 - Theory of Computation](https://ocw.mit.edu/courses/mathematics/18-404j-theory-of-computation-fall-2020/index.htm)
lectures and his book [Michael Sipser - Introduction to the Theory of Computation](https://www.mog.dog/files/SP2019/Sipser_Introduction.to.the.Theory.of.Computation.3E.pdf)
is an easy read and great to follow along.


- Video Lectures: [MIT 18.404 - Theory of Computation](https://ocw.mit.edu/courses/mathematics/18-404j-theory-of-computation-fall-2020/index.htm)
- Textbook: [Michael Sipser - Introduction to the Theory of Computation](https://www.mog.dog/files/SP2019/Sipser_Introduction.to.the.Theory.of.Computation.3E.pdf)
- Textbook Solutions: [Instructor Manual's for Michael Sipser - Theory of Computation](https://www.cin.ufpe.br/~lfmb/gdi/qq.pdf)
- Textbook Solutions: [gaurangsaini Solutions to Michael Sipser Theory of Computation](https://github.com/gaurangsaini/sipser-computation-3rd-solutions)

### Architecture and Organization [AR]

**Systems Fundamentals**



**Computer Architecture**

The course on computer architecture has 5 parts:

- Part I: Digital Logic
- Part II: Assembly/MIPS Programming
- Part III: Designing a processor with VHDL
- Part IV: Microarchitecture and data path
- Part V: Memory Hierarchy

- Textbook: [Joseph D. Dumas II - Computer Architecture]
- Textbook:
- Video Lectures: 


## Computational Science [CN]


## Graphics and Visualisation [GV]

**Computer Graphics**


**Discrete Geometry**



## Human Computer Interaction [HCI]

**Human-Computer Interactions**




## Information Assurance and Security [IAS]


## Information Management [IM]

**Introduction to Databases**



- Video Lectures: 


**Advanced Databases Systems**


## Intelligent Systems [IS]

**Machine Learning**



**Deep Learning**


- Book: [Deep Learning - Ian Goodfellow, Yoshua Bengio, Aaron Courville]



**Computer Vision**



**Natural Language Processing**




**Reinforcement Learning**




## Networking and Communication [NC]

**Network and Communications**

## Operating Systems [OS]

**Operating Systems**


## Platform-based Development [PBD]

**Web Development**

The most common framework used for web development is probably React, which 
is based on javascript.

- [Full Stack Open](https://fullstackopen.com/)


**Game Development**

One of the biggest game engine for game development is Unity, so you first 
have to learn C#.

- Unity Tutorial
- C# Tutorial



## Parallel and Distributed Computing [PD]

**Parallel Computing**



**Distributed Computing**



**Cloud Computing**



## Programming Languages [PL]

**Programmation I**



**Programmation II: object-oriented programming**



**Programming Langages Concepts**



**Compilers and Interpreters**


- Textbook: [Compilers - Principles, Techniques and Tools by Alfred Aho]
- Video Lectures: [Compiler Course - Nicolas Laurent](https://www.youtube.com/playlist?list=PLOech0kWpH8-njQpmSNGSiQBPUvl8v3IM)
- Coding Compilers: [Building a Compiler - Immo Landwerth](https://www.youtube.com/playlist?list=PLRAdsfhKI4OWNOSfS7EUu5GRAVmze1t2y)




## Software Engineering [SE]


# More Fields


## Quantum Computing

I was fortunate enough to be taught by Gilles Brassard, one of the most 
influential researcher in Quantum Computing. His book, [Quantum Informatics 
for Computer Scientist], takes a more theoritical view on the subject, but 
really present the material in a comprehensive way, without jumping into 
all the maths first. The book contains only a few exercices with no solutions, 
so I would suggest using __________ for solutions


## Bioinformatics

I have first explored the field of bioinformatics during the first wave of 
the pandemic.


- Video Series: [Simon Cockell - Bioinformatics Code Along](https://www.youtube.com/playlist?list=PLzfP3sCXUnxEu5S9oXni1zmc1sjYmT1L9)
- Book Series: [Bioinformatics Algorithms - An Active Learning Approach Vol I-IV by Phillip Compeau & Pavel Pevzner](https://www.bioinformaticsalgorithms.org/)
- Reddit Link: [Ressources for learning bioinformatics](https://www.reddit.com/r/bioinformatics/comments/191ykr/resources_for_learning_bioinformatics/)
- Coding Exercices: [ROSALIND](https://rosalind.info/problems/list-view/)

## Finance

- [Books to read for quantitative finance](https://quant.stackexchange.com/questions/38862/what-are-the-quantitative-finance-books-that-we-should-all-have-in-our-shelves)





## Game Development



# Ressources


