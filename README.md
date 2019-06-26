# Combination-Algorithm-Writer-with-Predicates

Combination-Algorithm-Writer-with-Predicates readme

Combination Algorithm Writer with Predicates
Combination Algorithm Writer with Predicates is a SWI-Prolog algorithm that finds combinations of predicates (in algdict.pl) that satisfy the given input and output.

# Getting Started

Please read the following instructions on how to install the project on your computer for writing code.

# Prerequisites

None

# Installing

* Download this repository.
* In SWI-Prolog, enter:
['caw5 copy 12'].
['listprologinterpreter1listrecursion4 copy 52'].
['listprologinterpreter3preds5 copy 52'].

* Running
Example
caw00(off,function3,[],5,7,[[a,1],[b,1]],[[c,2]],[],Program),writeln(Program).
Example Output
[[function3,[a,b,c],:-,[[function1,[b,b,d]],[=,[c,d]]]],[function1,[a,b,c],:-,[[c,is,a+b]]]]

**Note:**

Use (:-) instead of :-.

# Versioning

We will use SemVer for versioning.

# Authors

Lucian Green - Initial programmer - <a href="https://www.lucianacademy.com/">Lucian Academy</a>
