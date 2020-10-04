---
title: "Exploiting Synchronization in the Analysis of Shared-Memory Asynchronous Programs"
collection: publications
permalink: /publication/spin14
excerpt: ''
date: 2014-07-21
venue: 'International SPIN Symposium on Model Checking of Software (SPIN)'
paperurl: ''
citation: 'Michael Emmi, Burcu Kulahcioglu Ozkan, Serdar Tasiran.
&quot;Exploiting Synchronization in the Analysis of Shared-Memory Asynchronous Programs. International SPIN Symposium on Model Checking of Software (SPIN).'
---

[pdf](https://dl.acm.org/doi/10.1145/2632362.2632370)

**Abstract.** As asynchronous programming becomes more mainstream,
program analyses capable of automatically uncovering programming errors are increasingly in demand. Since asynchronous program analysis is computationally costly, current
approaches sacrifice completeness and focus on limited sets
of asynchronous task schedules that are likely to expose
programming errors. These approaches are based on parameterized task schedulers, each of which admits schedules
which are variations of a default deterministic schedule. By
increasing the parameter value, a larger variety of schedules
is explored, at a higher cost. The efficacy of these approaches
depends largely on the default deterministic scheduler on
which varying schedules are fashioned.
We find that the limited exploration of asynchronous program behaviors can be made more efficient by designing
parameterized schedulers which better match the inherent
ordering of program events, e.g., arising from waiting for an
asynchronous task to complete. We follow a reduction-based
“sequentialization” approach to analyzing asynchronous programs, which leverages existing (sequential) program analysis
tools by encoding asynchronous program executions, according to a particular scheduler, as the executions of a sequential
program. Analysis based on our new scheduler comes at no
greater computational cost, and provides strictly greater behavioral coverage than analysis based on existing parameterized schedulers; we validate these claims both conceptually,
with complexity and behavioral-inclusion arguments, and
empirically, by discovering actual reported bugs faster with
smaller parameter values.


