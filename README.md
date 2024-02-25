# jupyturtle
Python Turtle graphics for Jupyter notebooks

For a quick demo, open [the lab notebook](lab.ipynb).

The idea and some of the code for this module was inspired by
[Tolga Atam](https://github.com/tolgaatam)'s
[ColabTurtle](https://github.com/tolgaatam/ColabTurtle/tree/master),
via [Allen Downey](https://github.com/allendowney)'s book
_Think Python, Third Edition_ (O'Reilly, 2024).

This is a rewrite from scratch, using classes to model the turtle
and canvas—to make it easier to test, maintain and evolve by
avoiding numerous global variables to keep program state.

I used metaprogramming techniques to build the procedural API
with global functions like `fd()` to move the turtle.
The techniques are easier to understand in the didactic project
[abacus](https://github.com/fluentpython/abacus).


@ramalho
