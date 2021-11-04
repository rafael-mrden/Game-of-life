# Game of life

My implementation of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life) - the final assignment for the PhD course [*Advanced Scientific Programming in Python*](https://github.com/uu-python) I took at Uppsala University, 23-27 March 2020.

See `Demonstration.ipynb`.

Uploaded to https://pypi.org/ under the name `Project1_Game-of-life`.

I run it on python 3.7.6, Jupyter Notebook (Anaconda) on Windows 10.

TODO:
- "Add CI using Travis, and running one game of 1000 iterations checking that it matches a pre known pattern."


KNOWN BUGS:
- Matrix that has all entries 1 is drawn all in blue. This is the same as the matrix with all entries 0. This is a problem in `matplotlib.pyplot`, and I should check color setting there. It does not affect Game of life much, since such a matrix would die anyway, just one step later.
 
