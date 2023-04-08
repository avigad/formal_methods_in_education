---
title: Resources for Teaching with Formal Methods
layout: page
---

*This page is no longer being maintained. It has not been updated since March 2020. See, instead, the [Formal Methods Teaching Committee](https://fme-teaching.github.io/) web pages.*

This page collects resources for anyone considering the use of formal methods and formal tools in a classroom. The effort grew out of a discussion that was held during the [Big Proof](https://www.newton.ac.uk/event/bpr) program at the Isaac Newton Institute in Cambridge, UK. A [recording](https://www.newton.ac.uk/seminar/20170724153017302) of the discussion is available.

There are many axes along which one can organize such a list, such as the level of expertise of the intended audience (from experts to the public at large) or disciplinary orientation (computer science, mathematics, mathematical logic, etc.). Here I have chosen to classify the material by subject matter:

- computer science: material for teaching students to use formal methods for computational purposes, e.g. courses on software design and verification.

- mathematics: material for teaching mathematics, e.g. courses on discrete mathematics or introductions to mathematical proof.

- logic and formal methods: materials for teaching logic and formal methods themselves, e.g. courses on dependent type theory and automated reasoning.

If you would like add something, just send the text as you would like it to appear to <avigad@cmu.edu>, preferrably already formatted in [markdown](https://daringfireball.net/2004/12/markdown_101). Entries should provide a link to the relevant resources, which in turn should make use of formal tools (theorem provers, SAT solvers, model checkers, etc.) in some way.

The source for this page is [here](https://github.com/avigad/formal_methods_in_education), based on a [template](http://kbroman.org/simple_site/) by Karl Broman.

### Computer Science

- Benjamin Pierce at al., [Software Foundations](https://softwarefoundations.cis.upenn.edu).

  A book on designing reliable software, using Coq.

- Adam Chlipala, [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/)

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

- Tobias Nipkow and Peter Lammich, [Verified Functional Data Structures](http://www21.in.tum.de/teaching/FDS/SS17/)

  A course on the design and analysis of data structures for functional programming languages, using Isabelle. The resources are available [here](https://bitbucket.org/plammich/fds_ss17).

- Yves Bertot, [Software Verification and Computer Proof](https://team.inria.fr/marelle/en/coq-winter-school-2017/)

  An introductory course on functional programming and program verification using Coq.

- Yves Bertot, Cyril Cohen, Laurence Rideau, and Enrico Tassi, [Advanced Software Verification and Computer Proof](https://team.inria.fr/marelle/en/advanced-coq-winter-school-2016-2017/)

  A course on describing mathematical concepts and algorithms using Coq and the mathematlcal Components library.

- [Dafny Tutorial](https://rise4fun.com/dafny)

  An online tutorial for the Dafny program verification system.

- Rustan Leino and colleagues, [Verification Corner](https://www.youtube.com/channel/UCP2eLEql4tROYmIYm5mA27A)

  Videos on topics in verification, based on Dafny.

- Jasmin Blanchette and Alexander Bentkamp, [Logical Verification](https://lean-forward.github.io/logical-verification/2019/)

  An introduction to Lean, with applications to both computer science and mathematics.

- Jasmin Blanchette and Robert Lewis, [Logic and Modelling](https://www.vu.nl/en/study-guide/2018-2019/bachelor/computer-science/index.aspx?view=module&origin=50049126&id=50049663)

  A course based on Lean.

- Maria Knobelsdorf, Christiane Frede, Sebastian Böhne, and Christoph Kreitz, [Theorem Provers as a Learning Tool in Theory of Computation](https://dl.acm.org/doi/10.1145/3105726.3106184)

  A paper on using Coq to teach proof in CS.




### Mathematics

- Jeremy Avigad, Robert Y. Lewis, and Floris van Doorn, [Logic and Proof](https://leanprover.github.io/logic_and_proof/)

  An introduction to mathematical proof and symbolic logic, with exercises in Lean.

- Daniel Velleman, [Proof Designer](https://app.cs.amherst.edu/~djvelleman/pd/pd.html)

  A Java applet designed to help students write proofs.

- [The STACK Project](https://stack.maths.ed.ac.uk/demo/question/type/stack/doc/doc.php/About/index.md)

  A system for designing sophisticated computer-aided assessments in mathematics.

- Chris Sangwin, [Computer Aided Assessment of Mathematics](https://global.oup.com/academic/product/computer-aided-assessment-of-mathematics-9780199660353?cc=gb&lang=en&)

  A book on the use of computer aided assessment.

- Patrick Massot, [Introduction aux mathématiques formalisées](https://www.math.u-psud.fr/~pmassot/enseignement/math114/)

  An introduction to formalized mathematics, using Lean.

- Benjamin C. Pierce et al, [Discrete Math in Coq](Benjamin C. Pierce)

  A textbook.

- Jeremy Avigad, Kevin Buzzard, Robert Y. Lewis, and Patrick Massot,
[Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/)

  An interactive textbook.


### Logic and Formal Methods

- Jon Barwise and John Etchemendy, [Hyperproof](https://web.stanford.edu/group/cslipublications/cslipublications/site/1881526119.shtml)

  An introduction to logic, proof, and diagrammatic reasoning.

- Femke van Raamsdonk, Hermann Guevers, et al., [Type Theory and Coq](http://www.cs.ru.nl/~freek/courses/tt-2016/)

  An introduction to logic, type theory, and metatheory, using Coq.

- Jacques Fleuriot, [Automated Reasoning](http://www.inf.ed.ac.uk/teaching/courses/ar/)

  A course on automated reasoning, using Isabelle.

- N. Shankar, L. de Moura, H. Ruess, and A. Tiwari, [Little Engines of Proof](http://www.csl.sri.com/users/shankar/LEP.html)

  A course on automated deduction and decision procedures.

- Josef Urban, Chad E. Brown, and Ondřej Kunčar, [Formal Mathematics and Proof Assistants](http://arg.ciirc.cvut.cz/fmpa/)

  A course using Mizar, Isabelle, and Coq.

- [The AProS project](http://www.phil.cmu.edu/projects/apros/)

  Includes a web-based introductory course on Logic and Proof.

- Jeremy Avigad, Soonho Kong, and Leonardo de Moura, [Theorem Proving in Lean](https://leanprover.github.io/theorem_proving_in_lean/).

  An introduction to dependent type theory and Lean.
