---
title: "Randomized Testing of Distributed Systems with Probabilistic Guarantees"
collection: publications
permalink: /publication/oopsla18
excerpt: ''
date: 2018-11-04
venue: 'Proceedings of the ACM on Programming Languages (PACMPL), volume 2, number OOPSLA'
paperurl: ''
citation: 'Burcu Kulahcioglu Ozkan, Rupak Majumdar, Filip Niksic, Mitra Tabaei Befrouei, Georg Weissenbacher. &quot;Randomized Testing of Distributed Systems with Probabilistic Guarantees.&quot;Proceedings of the ACM on Programming Languages (PACMPL), volume 2, number OOPSLA.'
---

(Recipient of the Distinguished Paper Award)

[pdf](https://dl.acm.org/doi/10.1145/3276530)
[talk](https://www.youtube.com/watch?v=sF1fcpn4Z48)

**Abstract.** Several recently proposed randomized testing tools for concurrent and distributed systems come with theoretical guarantees on their success. The key to these guarantees is a notion of bug depthÐthe minimum length of
a sequence of events sufficient to expose the bugÐand a characterization of d-hitting families of schedulesÐa
set of schedules guaranteed to cover every bug of given depth d. Previous results show that in certain cases
the size of a d-hitting family can be significantly smaller than the total number of possible schedules. However,
these results either assume shared-memory multithreading, or that the underlying partial ordering of events
is known statically and has special structure. These assumptions are not met by distributed message-passing
applications.
In this paper, we present a randomized scheduling algorithm for testing distributed systems. In contrast
to previous approaches, our algorithm works for arbitrary partially ordered sets of events revealed online
as the program is being executed. We show that for partial orders of width at most w and size at most n
(both statically unknown), our algorithm is guaranteed to sample from at most w^2.n^(d-1) schedules, for every
fixed bug depth d. Thus, our algorithm discovers a bug of depth d with probability at least 1/(w^
2.n^(d−1)). As a special case, our algorithm recovers a previous randomized testing algorithm for multithreaded programs. Our
algorithm is simple to implement, but the correctness arguments depend on difficult combinatorial results
about online dimension and online chain partitioning of partially ordered sets.
We have implemented our algorithm in a randomized testing tool for distributed message-passing programs.
We show that our algorithm can find bugs in distributed systems such as Zookeeper and Cassandra, and
empirically outperforms naive random exploration while providing theoretical guarantees.