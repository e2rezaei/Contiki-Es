It is the logic of code:
1- Define a datastructure in dag to save the Tx.
2- Give the value to Tx in rpl-join-dag function in rpl-dag.c and wherever you change the Tx register.
3- Update rank-calculation and calculate-path-metric mechanisms accordingly.
4- add parent-monitor().
