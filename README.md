# Formal automated verification of Lace's work-stealing deque using VerCors

An implementation of Lace's work-stealing framework has been written in PVL to verify the functional correctness of the deque using VerCors. Currently, the verification passes assuming a strongly consistent memory model. However, the specification should be validated before a correct proof can be induced. The next step is to rewrite the specification to hold in the TSO (Total Store Order) weakly consistent memory model.
