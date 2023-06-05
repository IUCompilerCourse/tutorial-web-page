
# Teaching and Learning Compilers Incrementally

Instructor: Jeremy Siek

Welcome to the half-day tutorial for Essentials of Compilation (EoC)!

This tutorial introduces the participants to the joys of teaching and
learning about compilers using the incremental approach. The tutorial
provides a sneak-preview of a compiler course based on the new
textbooks from MIT Press:

[Essentials of Compilation: An Incremental Approach in Racket](https://mitpress.mit.edu/9780262047760/essentials-of-compilation/)
[Essentials of Compilation: An Incremental Approach in Python](https://mitpress.mit.edu/9780262048248/essentials-of-compilation/)

PDFs for the books are available for free from my web page:

[PDF for EoC (Racket)](https://www.dropbox.com/s/ktdw8j0adcc44r0/book.pdf?dl=1)
[PDF for EoC (Python)](https://www.dropbox.com/s/mfxtojk4yif3toj/python-book.pdf?dl=1)


## About Essential of Compilation

The EoC course takes students on a journey through constructing their
own compiler for a small but powerful language. The standard approach
to describing and teaching compilers is to proceed one pass at a time,
from the front to the back of the compiler. Unfortunately, that
approach obfuscates how language features motivate design choices in a
compiler. In the EoC course we instead take an incremental approach in
which we build a complete compiler every two weeks, starting with a
small input language that includes only arithmetic and variables. We
add new language features in subsequent iterations, extending the
compiler as necessary. Student get immediate positive feedback as they
see their compiler passing test cases and then learn important lessons
regarding software engineering as they grow and refactor their
compiler throughout the semester.

## Tutorial

The first half of the tutorial will provide an overview of the EoC
course and textbook with plenty of time for questions and answers. 

The second half of the tutorial will be a hands-on activity in which
the tutorial participants implement one of the compiler passes
described in the Chapter 2 of the book: the "Remove Complex Operands"
pass. The activity can be completed in either Python (version 3.10 or
higher) or Racket (version 8.0 or higher), so make sure to have one of
them installed on your laptop.

Download the supporting code from github:

[Python](https://github.com/IUCompilerCourse/python-student-support-code)
[Racket](https://github.com/IUCompilerCourse/public-student-support-code)

UNDER CONSTRUCTION
