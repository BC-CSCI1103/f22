# CSCI 1103 Computer Science 1 Honors

### Fall 2022

Robert Muller — Boston College

---

[About](resources/about.md) — [Textbooks](resources/textbooks.md) — [Grading](resources/grading.md) — [Canvas](https://bostoncollege.instructure.com/courses/1634611) — [Piazza](https://piazza.com/class/l7c8612dv3v2ez) — [Cornell CS3110](https://www.cs.cornell.edu/courses/cs3110/2020sp/) — [SVM](https://dogfishbar.github.io/dogfishbar.github.io/)

[Manual](http://caml.inria.fr/pub/docs/manual-ocaml/index.html) — [OCaml.org](https://ocaml.org/) — [Stdlib](http://caml.inria.fr/pub/docs/manual-ocaml/libref/Stdlib.html) — [Lib](resources/libraries/lib.mli) — [Animate](resources/libraries/animate.mli) — [Image](resources/libraries/image.mli) — [Color](resources/libraries/color.mli) — [Animate Notes](./resources/libraries/animate/README.md)

[CSCI 2103](./resources/2103.md) — [Lab Meetings](./resources/labs.md)

---

<details>
  <summary>Administration</summary>

+ **Lecture Meets:** Tuesdays and Thursdays 12PM - 1:15PM, 245 Beacon St. Rm 125.

+ **Lab Meets:** Wednesdays 3PM - 3:50PM, 245 Beacon St. Rm 103.

+ **Instructor:** [Robert Muller](https://dogfishbar.github.io )

+ **email**: robert DOT muller AT BC DOT EDU

+ **Office Hours**: Tuesdays 3PM - 5PM, Wednesdays 4PM - 5PM, 245 Beacon St. Rm 508.

**Teaching Assistants:**

<details open> <summary>Liam Murphy, Head Teaching Assistant</summary>

+ **email**: murpaue AT BC DOT EDU
Nicole Lockwood <lockwoni@bc.edu>,

  + **Office Hours** Thursdays 2PM - 4PM.
</details>

<details open> <summary>Nicole Lockwood</summary>

+ **email**: lockwoni AT BC DOT EDU

+ **Office Hours** Mondays 2PM - 3PM, Wednesdays 5PM - 7PM, Fridays 2PM - 3PM.

</details>

</details>

---

## Schedule

<details>
  <summary>At a Glance</summary>

  #### Month by Month

1. Learning to code, writing functions;
2. Bits, bytes & machines
3. Applications

#### Week by Week
1. Logisitics; base types and expressions
2. Naming; Writing Functions; Branching 
3. Repetition; Graphics; Lists
4. Repetition
5. Repetition
6. Animation; Model-View-Update
7. Digital Representations
8. Machines
9. Storage
10. Applications in Imperative Style: Digital Audio
11. Applications in Imperative Style: Digital Images
12. Applications of Strings, Text & Files
13. Sorting Algorithms
14. Developing new Types, Review & Wrap-up

</details>



<details open>
  <summary>Details</summary>

| Week | Mtng |     | Topic  |
| :--: | :--: | :-- | :--------------------------------------- |
|  [1](https://github.com/BC-CSCI1103/Week01)  |  1   | T 08/30/22 | Introduction and Overview; Development logistics -- Workflow: Unix,  git & GitHub, vscode |
|      |  2  | R 09/01/22 | OCaml & Dune; Base types; literals & expressions; simplification & work; values |
|  [2](https://github.com/BC-CSCI1103/Week02)  |  3   | T 09/06/22 | Symbolic names: `let` and `let-in`; functions, libraries, function definitions and calls; replacement; explicit types or implicit types with type inference |
|      |    | R 09/08/22 | **No Meeting** |
| [3](https://github.com/BC-CSCI1103/Week03) |  4  | T 09/13/22 | More on function definitions; tuples; polymorphism;; Branching & sum types; match expressions; the `bool` type;; Lists; repetition & recursive list processing, List.mem & List.append |
|      |  5  | R 09/15/22 | learning from `List.rev`; computational shapes; local functions |
| [4](https://github.com/BC-CSCI1103/Week04) |  6  | T 09/20/22 | More on working with lists |
|      |  7  | R 09/22/22 | Repetitive images; the Animate library & the Model-View-Update pattern; Record Types |
| [5](https://github.com/BC-CSCI1103/Week05) |  8  | T 09/27/22 | PS4: The Best Candidate Algorithm; The List.map function; More repetitive algorithms: Insertion Sort |
|      |  9  | R 10/02/22 | Numerical Algorithms: Primality & factoring; The Bisection Algorithm for Approximating the Square Root; Applications of the third built-in Sum Type: 'a option |
| [6](https://github.com/BC-CSCI1103/Week06) |  10  | T 10/04/22 | Some cairns on the path to good code; Recursion & Mathematical Induction -- learning from`sublists` |
|      |  11  | R 10/06/22 | Functions are values: List.map, List.for_all and List.exists.: function slope, Riemann sums |
| [7](https://github.com/BC-CSCI1103/Week07) |    | T 10/11/22 | **No Meeting** |
|      |  12  | R 10/13/22 | Symbols and Digital Representations; Positional Numeral Systems, Binary & Hexadecimal |
| [8](https://github.com/BC-CSCI1103/Week08)    | 13 | T 10/18/22 | Logic Gates; a Ripple-Carry Adder, Machines & Storage Architecture, Bits, Bytes & Words |
|      |  14  | R 10/20/22 | SVM — A Simple Virtual Machine, Working with Memory: LOD & STO |
| [9](https://github.com/BC-CSCI1103/Week09)    |  15  | T 10/25/22 | Dynamic Memory Diagrams |
|      |  16  | R 10/27/22 | Imperative Forms in OCaml, Arrays |
|  [10](https://github.com/BC-CSCI1103/Week10)  |  17  | T 11/01/22 | Example: PCM & Digital Audio, Working with Digital Audio |
|      |  18  | R 11/03/22 | Working with 2D-Arrays; Bitmaps, Search: 8-Queens, Sudoku & Complexity |
|  [11](https://github.com/BC-CSCI1103/Week11)  |  19  | T 11/08/22 | Backtracking in 8-Queens; More Digital Images: zooming;; Review of Storage Diagrams; Dictionaries: Associative Arrays, Association Lists |
|      |  20  | R 11/10/22 | Dictionaries, Binary Search Trees |
|  [12](https://github.com/BC-CSCI1103/Week12)  |  21  | T 11/15/22 | More on Dictionaries & BSTs; Balanced BSTs; Performance;; Working with Text Strings; The String Module |
|      |  22  | R 11/17/22 | Working with Text: Shannon's Markov Model of English Text |
|  [13](https://github.com/BC-CSCI1103/Week13)  |  23  | T 11/22/22 | Working with Text: The Needleman-Wunsch DNA Sequence Alignment Algorithm |
|      |      | R 11/24/22 | **Thanksgiving: No Meeting** |
|  [14](https://github.com/BC-CSCI1103/Week14)  |  24  | T 11/29/22 | Data Integrity; Exposing Data Constraints to the Type Checker;; Message Passing Style; Object-Oriented Programming |
|      | 25 | R 12/01/22 | Abstract Data Types in OCaml |
|  15  |  26  | T 12/06/22 | Abstract Data Types in Java |
|      |  27  | R 12/08/22 | **Last Meeting, review and wrap-up** |

</details>



