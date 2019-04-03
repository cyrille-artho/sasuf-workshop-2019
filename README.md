# SASUF Workshop 2019

## Workshop "Making systems trustworthy by model checking and symbolic execution"

**Tuesday, May 7, University of Stellenbosch**

### Speakers

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
  <summary><font color="red"><b>You!</b></font> Please contact us (click for details)/summary>
  We encourage researchers and students to give a presentation on their own work related to model checking and symbolic execution. Please e-mail <tt>artho</tt> (at) <tt>kth.se</tt> with your name and the title and duration of your presentation to register. Short presentation don't need an abstract.
  </details>

TBC:
* Bernd Fischer (University of Stellenbosch)
* Jaco Geldenhuys (University of Stellenbosch)
* Nils Timm (University of Pretoria)
* Stefan Gruner (University of Pretoria)
* Kostis Sagonas (Uppsala University)
