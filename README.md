# SASUF Workshop 2019

## Workshop "Making systems trustworthy by model checking and symbolic execution"

**Tuesday, May 7, University of Stellenbosch**

**Committee Room A521, 5th floor, [Main Engineering Building](http://www.cs.sun.ac.za/contact/)**

[Use Google Maps for directions.](https://www.google.com/maps?ll=-33.929752,18.865683&z=16&t=m&hl=en&gl=US&mapclient=embed&q=33%C2%B055%2746.6%22S+18%C2%B051%2756.2%22E+-33.929597,+18.865600@-33.9295972,18.8656)

**We welcome students and researchers to present their projects!**
Talks between 3 and 30 minutes are welcome. No slides are required for short talks.

### Speakers

<details>
  <summary><font color="red"><b>You!</b></font> Please contact us (click for details)</summary>
  We encourage researchers and students to give a presentation on their own work related to model checking and symbolic execution. Please e-mail <tt>artho</tt> (at) <tt>kth.se</tt> with your name and the title and duration of your presentation to register. Short presentation don't need an abstract.
</details>
  
<details>
  <summary>
<b>Willem Visser (University of Stellenbosch): Searching Fast and Slow: Fuzzing and Symbolic Execution</b>
  </summary>
Abstract: </br>
The past few years a number of research groups built tools where they combined fuzzing and symbolic execution, and in this talk we will discuss yet another case. The combination of these two technologies for bug finding is a no-brainer: fuzzing covers lots of cases with very little effort, but can get stuck generating inputs to highly constrained behaviours, for which symbolic execution is good. What makes our approach (COASTAL) somewhat unique is that it uses concolic execution rather than classic symbolic execution and that the fuzzer and the concolic execution were built into the same framework, from scratch (in other words it is not two existing tools that are being combined). In this talk we will discuss the design decisions, the integrated architecture and show some examples.
</details>

<details>
<summary><b>Cyrille Artho (KTH Royal Institute of Technology): Java Pathfinder and some of its applications</b>
  </summary>
  Abstract: </br>
  This talk gives an overview of Java Pathfinder and then presents the case study "Verifying Nested Lock Priority Inheritance in RTEMS with Java Pathfinder". That work analyzes a Java model of the priority inheritance protocol for mutual exclusion, as implemented in the RTEMS open-source real-time operating system. We verified this model using Java Pathfinder to detect potential data races, deadlocks, and priority inversions. JPF detected a known bug in the RTEMS implementation, which we modified along with the Java model. Verification of the modified model showed the absence of data races, deadlocks, and established nine protocol-specific correctness properties.
</details>

<details>
  <summary><b>Moeketsi Raselimo (University of Stellenbosch): An Empirical Comparison of Systematic and Random Grammar-based Fuzzing</b></summary>
</details>
   
<details>
  <summary><b>Bernd Fischer (University of Stellenbosch): Systematic Generation of Programs with Guaranteed Syntax Errors</b></summary>
</details>

<details>
  <summary><b>Kostis Sagonas (Uppsala University): An Overview of Recent Progress in Stateless Model Checking</b></summary>
Abstract: </br>
A successful technique for finding concurrency bugs (i.e., defects that
arise only under some thread schedulings) and for
verifying their absence is stateless model checking (SMC).  Given a
terminating program, which may be annotated with assertions, SMC
systematically explores the set of all thread schedulings that are
possible during runs of this program. A special runtime scheduler drives
the SMC exploration by making decisions on scheduling whenever such
choices may affect the interaction between threads. Given enough time,
the exploration covers all possible executions and detects any
unexpected program results, program crashes, or assertion violations.
The technique is entirely automatic, has no false positives, does not
consume excessive memory, and can quickly reproduce the concurrency bugs
it detects.  SMC faces the problem that the number of possible thread
schedulings grows exponentially with the length of program execution,
and must therefore be equipped with techniques to reduce the number of
explored executions. This talk will overview algorithms and tools for
stateless model checking, focusing on recent progress in algorithms for
dynamic partial order reduction (DPOR), both under Sequential
Consistency and Weak Memory Models. 
</details>

<details>
  <summary><b>Kostis Sagonas (Uppsala University): Concolic Testing of Higher-order Functional Languages</b></summary>
Abstract: </br>
Concolic testing is a fully automatic software testing technique that
combines concrete and symbolic execution of a program unit in an attempt
to explore all the code paths in this unit or at least explore all its
paths up to a depth bound. In this talk, we will describe how concolic
testing can be applicable to high-level languages in general and to
functional programming languages in particular. For such languages, the
concolic engine needs to efficiently support pattern matching, recursive
data types such as lists, recursion and higher-order functions. We will
also briefly talk about the engineering effort that concolic testing
tools require, in particular in interfacing with SMT solvers.
<br>
The talk will also include a demo of CutEr (as in “more cute”), a
concolic testing tool for Erlang, and will briefly report on some of the
bugs in the implementation of Erlang/OTP that CutEr has discovered and
the coverage that it manages to achieve. 
</details>

<details>
  <summary><b>Jaco Geldenhuys (University of Stellenbosch): A day at the beach: From Java PathFinder to COASTAL</b></summary>
</details>

<details>
  <summary><b>Stefan Gruner and Nils Timm (University of Pretoria): Multi-agent systems</b></summary>
</details>
   
<details>
  <summary><b>Jan Taljaard (University of Stellenbosch): SMT Result Caching for Symbolic Execution</b></summary>
</details>
 
<details>
  <summary><b>Phillip van Heerden (University of Stellenbosch): Symbolic Automata Learning</b></summary>
</details>
