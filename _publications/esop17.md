---
title: "Verifying Robustness of Event-Driven Asynchronous Programs against Concurrency"
collection: publications
permalink: /publication/esop17
excerpt: ''
date: 2017-04-22
venue: '26th European Symposium on Programming (ESOP)'
paperurl: ''
citation: 'Ahmed Bouajjani, Michael Emmi, Constantin Enea, Burcu Kulahcioglu Ozkan, Serdar Tasiran.
&quot;Verifying Robustness of Event-Driven Asynchronous Programs against Concurrency. 26th European Symposium on Programming (ESOP)'
---

[pdf](https://link.springer.com/chapter/10.1007/978-3-662-54434-1_7)

**Abstract**. We define a correctness criterion, called robustness against concurrency, for a class of event-driven asynchronous programs that are at the basis of modern UI frameworks in Android, iOS, and Javascript. A program is robust when all possible behaviors admitted by the program under arbitrary procedure and event interleavings are admitted even if asynchronous procedures (respectively, events) are assumed to execute serially, one after the other, accessing shared memory in isolation. We characterize robustness as a conjunction of two correctness criteria: event-serializability (i.e., events can be seen as atomic) and eventdeterminism (executions within each event are insensitive to the interleavings between concurrent tasks dynamically spawned by the event). Then, we provide efficient algorithms for checking these two criteria based on polynomial reductions to reachability problems in sequential programs. This result is surprising because it allows to avoid explicit handling of all concurrent executions in the analysis, which leads to an important gain in complexity. We demonstrate via case studies on Android apps that the typical mistakes programmers make are captured as robustness violations, and that violations can be detected efficiently using our approach.