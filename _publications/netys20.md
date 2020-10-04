---
title: "Verifying Weakly Consistent Transactional Programs using Symbolic Execution"
collection: publications
permalink: /publication/netys20
excerpt: ''
date: 2020-03-06
venue: 'In  Proc. 8th Int. Conference on Networked Systems'
paperurl: ''
citation: 'Burcu Kulahcioglu Ozkan. &quot;Verifying Weakly Consistent Transactional Programs using Symbolic Execution.&quot; In  Proc. 8th Int. Conference on Networked Systems
(NETYS), 2020.'
---


[pdf](../files/netys20.pdf)
[video](https://youtu.be/S-YPo2bJghY)


**Abstract.** We present a method for verifying whether all executions
of a set of transactions satisfy a given invariant when run on weakly
consistent systems. Existing approaches check that all executions under
weak consistency are equivalent to some serial execution of the transactions, and separately that the serial executions satisfy the invariant.
While sound, this can be overly strict. Programs running on systems
with weak guarantees are usually designed to tolerate some anomalies
w.r.t. the serial semantics and yet maintain some expected program invariants even on executions that are not serializable. In contrast, our
technique does not restrict possible executions to be serializable, but directly checks whether given program properties hold w.r.t. all executions
allowed under varying consistency models.
Our approach uses symbolic execution techniques and satisfiability checkers. We summarize the effects of transactions using symbolic execution
and build a satisfiability formula that precisely captures all possible valuations of the data variables under a given consistency model. Then, we
check whether the program invariants hold on the resulting symbolic set
of behaviors. Our encoding is parameterized over the underlying consistency specification. Hence, the programmer can check the correctness of a
program under several consistency models—eventual consistency, causal
consistency, (parallel) snapshot isolation, serializability— and identify
the level of consistency needed to satisfy the application-level invariants.


