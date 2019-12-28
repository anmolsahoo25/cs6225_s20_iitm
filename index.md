---
layout: default
---

<div class="home">

<h1>{{ site.subtitle }}</h1>

</div>

## Course Objectives

This course is about an approach to bringing software engineering up to speed
with more traditional engineering disciplines, **providing a mathematical
foundation for rigorous analysis of realistic computer systems**. As civil
engineers apply their mathematical canon to reach high certainty that bridges
will not fall down, the software engineer should apply a different canon to
argue that programs behave properly. 

As other engineering disciplines have their computer-aided-design tools,
computer science has proof assistants, IDEs for logical arguments and
solver-aided languages that automatically verify logical arguments. We will
learn how to apply these tools to certify that programs behave as expected.

Specifically, we will look at

1. Formal logical reasoning about program correctness through
2. [Coq proof assistant](https://coq.inria.fr/), a tool for machine checked
   mathematical theorem proving and
3. [F\*](https://www.fstar-lang.org), a general-purpose programming language
   aimed at program verification

**Is this a program verification course?** 

Yes, but let's stick to [Program
Proofs](https://blog.sigplan.org/2019/09/12/program-verification-has-it-lost-its-punch/).

## Course Contents 

* **Foundations (1 week):** Induction principles, logic and propositions,
  Curry-Howard correspondence.
* **Specification and Verification (2 weeks):** Program Equivalence – Transition
  Systems – Operational Semantics - Compiler Verification – Model Checking –
  Simply Typed Lambda Calculus.
* **Program Logics (2 weeks):** Hoare logic: an approach to verifying imperative
  programs - Separation logic: reasoning about aliasing and pointer-based data
  structures – Deep Embeddings, Shallow Embeddings and options in between.
* **Programming with F\* (3 weeks):** Programming in F\* - Inductive Types -
  Verified Functional Programming – Termination - Programming with Effects
* **Proving with F\* (3 weeks):** Verifying Stateful Programs – Dijkstra Monad -
  Higher Kinds, Indexed Types, Type-level functions – Cryptography examples with
  Authentication – Cryptography examples with confidentiality - Verifying
  low-level code using Low\*, a subset of F\*
* **Concurrency (3 weeks):** Operational semantics for concurrent programs -
  Concurrent Separation Logic and rely-guarantee reasoning: verifying concurrent
  shared-memory programs - Pi-calculus and behavioral refinement: modular
  reasoning about message-passing functional programs – Session Types for
  distributed programming.

## Text Books

We will be closely following 

* *Formal Reasoning about Programs*, Adam Chlipala. Freely available
  [online](http://adam.chlipala.net/frap/).

for the Coq part of the course. For F\*, there is no prescribed text book. We
will look at examples from the [tutorials](https://www.fstar-lang.org/tutorial/)
and other [lectures](https://www.cs.uoregon.edu/research/summerschool/summer19/topics.php#Swamy).

Other reference books are:

* *Software Foundations*, Benjamin Pierce et al. Freely available [online](https://softwarefoundations.cis.upenn.edu/).
* *Types and Programming Languages*, Benjamin Pierce, MIT Press, 1st edition,
  2002. Ebook is available in IITM library.
* *Practical Foundations for Programming Languages*, Robert Harper, Cambridge
  University Press, 2nd edition, 2016. Freely available [online](https://www.cs.cmu.edu/~rwh/pfpl/2nded.pdf).

## Other Info

### Class info

Location: CS26
Time: 
  * M 1100 - 1150
  * Tu 1000 - 1050
  * W 0900 - 0950
  * Th 1300 - 1350

### Credits

3-1-0-0-8-12

### Evaluation Plan 

* Weekly Assignments: 60%
* Midterm: 20%
* Finals: 20%

### Pre-requisite

[CS3100](http://kcsrk.info/cs3100_f19/) (only the OCaml parts) or Equivalent. 

You should feel comfortable with functional programming concepts. If you are
able to get through the assignments 1 to 4, you are ready for this course. All
the course materials, and assignments are available on the [CS3100
website](http://kcsrk.info/cs3100_f19/). 

**I highly recommend that you complete assignments 1 to 4 before the start of
this course**.

If you are unsure, please come talk to me. 
