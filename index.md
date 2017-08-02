---
title: Resources
layout: page
---

This page collects resources for anyone considering the use of formal methods and formal tools in a classroom. The effort grew out of a meeting on formal methods in education that was held during the [Big Proof](https://www.newton.ac.uk/event/bpr) program at the Isaac Newton Institute in Cambridge, UK. A [recording](https://www.newton.ac.uk/seminar/20170724153017302) of the meeting is available.

There are many axes along which one can organize such a list, such as level of expertise of the intended audience (ranging from experts and graduate students to the public at large) or their disciplinary orientation (computer science, mathematics, mathematical logic, etc.).

Here I have chosen to classify the material by subject matter:

- computer science: courses that teach students to use formal methods for computational purposes, e.g. in hardware and software design and verification.

- mathematics: courses that use formal methods and tools to teach mathematics, e.g. in an introduction to discrete mathematics or mathematical proof. 

- logic and formal methods: using formal tools to teach logic and formal methods themselves, e.g. courses on dependent type theory and automated reasoning.

If you would like add something to the list, just send the text as you would like it to appear to <avigad@cmu.edu>, preferrably already formatted in [markdown](https://daringfireball.net/2004/12/markdown_101), or issue a pull request to the [github repository](https://github.com/avigad/formal_methods_in_education) that hosts this page. Entries should provide a link to the relevant resources, which in turn should make use of formal tools (theorem provers, SAT solvers, model checkers, etc.) in some way.

Computer Science
----------------

- Benjamin Pierce at al., [Software Foundations](https://softwarefoundations.cis.upenn.edu). 

  A book on designing reliable software, using Coq.

- Adam Chlipala, [Certified Programming with Dependendent Types](http://adam.chlipala.net/cpdt/)

  A book about software engineering, using Coq.

- Adam Chlipala, [Formal Reasoning About Programs](http://adam.chlipala.net/frap/)

  The early stages of a book on formal reasoning about program correctness, using Coq.

- Tobias Nipkow and Gerwin Klein, [Concrete Semantics](http://www.concrete-semantics.org/)

  A book on the semantics of programming languages, using Isabelle.    

- Peter Dybjer, [Types for Programs and Proofs](http://www.cse.chalmers.se/edu/year/2016/course/DAT140/)

  A course on types systems in programming language design, using Agda. 

- J. Strother Moore, [A Formal Model of the Java Virtual Machine](https://www.cs.utexas.edu/users/moore/classes/cs378-jvm/index.html)

  A course based on ACL2.

- Aaron Stump, [Verified Functional Programming in Agda](http://dl.acm.org/citation.cfm?id=2841316)

  A book on writing verified programs with Agda.

- Jacques Fleuriot, [Formal Verification](http://www.inf.ed.ac.uk/teaching/courses/fv/) 

  A course on formal verification, using model checking, SAT, and SMT.

- Mauricio Ayala-Rincón and Flávio L. C. de Moura, [Applied Logic for Computer Scientists](http://www.springer.com/gb/book/9783319516516)

  A book on hardware and software verification, using PVS.

- [The Summer School on Formal Techniques](http://fm.csl.sri.com/SSFT17/)

  An annual summer school emphasizing hands-on use.

- Philip Wadler, [Types and Semantics for Programming Languages](http://www.inf.ed.ac.uk/teaching/courses/tspl/)

  A course based on Coq.

Mathematics
-----------

- Jeremy Avigad, Robert Y. Lewis, and Floris van Doorn, [Logic and Proof](https://leanprover.github.io/logic_and_proof/)

  An undergraduate introduction to mathematical proof and symbolic logic, with exercises in Lean.

- Daniel Velleman, [Proof Designer](https://app.cs.amherst.edu/~djvelleman/pd/pd.html)

  A Java applet designed to help students write proofs. 

- [The STACK Project](https://stack.maths.ed.ac.uk/demo/question/type/stack/doc/doc.php/About/index.md) 

  A system for designing sophisticated computer-aided assessments in mathematics. See also Sangin, Chris, [Computer Aided Assessment of Mathematics](https://global.oup.com/academic/product/computer-aided-assessment-of-mathematics-9780199660353?cc=gb&lang=en&).


Logic and Formal Methods
------------------------

- Femke van Raamsdonk, Hermann Guevers, et al., [Type Theory and Coq](http://www.cs.ru.nl/~freek/courses/tt-2016/)

  An introduction to logic, type theory, and metatheory, using Coq.

- Jacques Fleuriot, [Automated Reasoning](http://www.inf.ed.ac.uk/teaching/courses/ar/)

  A course on automated reasoning, using Isabelle.

- N. Shankar, L. de Moura, H. Ruess, and A. Tiwari, [Little Engines of Proof](http://www.csl.sri.com/users/shankar/LEP.html)

  A course on automated deduction and decision procedures. 


