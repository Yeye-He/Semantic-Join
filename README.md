# Semantic-Join
SEMA-JOIN: Joining Semantically-Related Tables Using Big Table Corpora

### Overview
This is the benchmark data set used in our experiments described [here](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/p2045-he.pdf).

There are 50 test cases of joinable web tables, collected from [Google Tables](https://research.google.com/tables). Each test case has two key columns taken from two seperate tables, which while not equi-join-able, have semantic relationships that can be used to produce joins.

### Data set description
There are two files per test case:

* CaseN_input.txt: this is a test case containing two key columns from two seperate tables, separated by an empty line.
* CaseN_ground.txt: this is the ground truth join results manually labelled, with join-able keys in the same row.
