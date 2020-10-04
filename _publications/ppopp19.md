---
title: "Checking Linearizability Using Hitting Families"
collection: publications
permalink: /publication/ppopp19
excerpt: ''
date: 2019-02-16
venue: 'In  24th ACM SIGPLAN Symp. on Principles and Practice of Parallel Programming, PPoPP.'
paperurl: ''
citation: 'Burcu Kulahcioglu Ozkan, Rupak Majumdar, Filip Niksic. &quot;Checking Linearizability Using Hitting Families.&quot; 24th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming, (PPoPP).'
---

[pdf](https://dl.acm.org/doi/10.1145/3293883.3295726)

**Abstract.** Linearizability is a key correctness property for concurrent
data types. Linearizability requires that the behavior of concurrently invoked operations of the data type be equivalent
to the behavior in an execution where each operation takes
effect at an instantaneous point of time between its invocation and return. Given an execution trace of operations, the
problem of verifying its linearizability is NP-complete, and
current exhaustive search tools scale poorly.
In this work, we empirically show that linearizability of
an execution trace is often witnessed by a schedule that
orders only a small number of operations (the “linearizability
depth”) in a specific way, independently of other operations.
Accordingly, one can structure the search for linearizability
witnesses by exploring schedules of low linearizability depth
first. We provide such an algorithm. Key to our algorithm is a
procedure to generate a strong d-hitting family of schedules,
which is guaranteed to cover all linearizability witnesses
of depth d. A strong d-hitting family of schedules of an
execution trace consists of a set of schedules, such that for
each tuple of d operations in the trace, there is a schedule
in the family that (i) executes these operations in the order
they appear in the tuple, and (ii) as late as possible in the
execution.
We show that most linearizable execution traces from existing benchmarks can be witnessed by strongly d-hitting
schedules for d <= 5. Our result suggests a practical and automated method for showing linearizability of a trace based on
a prioritization of schedules parameterized by the linearizability depth.

