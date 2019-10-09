when we describe a language, we should pay particular attention to the means that the language provides for combining simple ideas to form more complex ideas. Every powerful language has three mechanisms for accomplishing this:

- **primitive expressions,** which represent the simplest entities the language is concerned with,
- **means of combination,** by which compound elements are built from simpler ones, and
- **means of abstraction,** by which compound elements can be named and manipulated as units.

To evaluate a combination, do the following:
1. Evaluate the subexpressions of the combination.

2. Apply the procedure that is the value of the leftmost subexpression (the operator) to
the arguments that are the values of the other subexpressions (the operands).

- the values of numerals are the numbers that they name,
- the values of built-in operators are the machine instruction sequences that carry out the

    corresponding operations, and

- the values of other names are the objects associated with those names in the environment.

`(define (square x) (* x x))`
We can understand this in the following way:
`(define (square x) (* x	x))`

To square something, multiply it by itself.

We have here a compound procedure, which has been given the name square. The procedure represents
the operation of multiplying something by itself. The thing to be multiplied is given a local name, x, which
plays the same role that a pronoun plays in natural language. Evaluating the definition creates this
compound procedure and associates it with the name square.
