# HW 4: Prim's algorithm

In this assignment, you'll implement Prim's algorithm, a non-trivial greedy algorithm used to construct minimum spanning trees. 

## Tasks

### Coding

* [TODO] Complete the `construct_mst` method found in `mst/graph.py`. All necessary modules have already been imported. You should not rely on any other dependencies (e.g. networkx). 

### Development

* [TODO] Add more assertions to the `check_mst` function in `test/test_mst.py`.
* [TODO] Write at least one more unit test (in the `test_mst.py` file) for your `construct_mst` implementation. (Two unit tests have already been provided: the first operates on a small graph of four nodes, and the second on a larger graph of 140 single cells, projected onto a lower dimensional subspace.)
* [TODO] Make your package `pip` installable. (Refer to prevous assignments for more in-depth information.)
* [TODO] Automate testing with `pytest` and GitHub Actions, and add a status badge to this README file. (Refer to previous assignments for more in-depth information.)

## Getting started

Fork this repository to your own GitHub account. Work on the codebase locally and commit changes to your forked repository. 

You will need following packages:

- [numpy](https://numpy.org/)
- [scikit-learn](https://scikit-learn.org/)
- [pytest](https://docs.pytest.org/en/7.2.x/)

We also strongly recommend you use the built-in [heapq](https://docs.python.org/3/library/heapq.html) module.

## Completing the assignment

Push your code to GitHub with passing unit tests, and submit a link to your repository through Google Classroom.

## Grading

### Code (6 points)

* Minimum spanning tree construction works correctly (6)
    * Correct implementation of Prim's algorithm (4)
    * Produces expected output on small graph (1) 
    * Produces expected output on single cell data (1) 

### Unit tests (3 points)

* Added additional checks in `check_mst` to ensure correctness of your implementation (2)
* Added effective unit tests (1)

### Style (1 points)

* Readable code with clear comments and method descriptions
