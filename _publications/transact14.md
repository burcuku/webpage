---
title: "Verifying Programs under Snapshot Isolation and Similar Relaxed Consistency Models"
collection: publications
permalink: /publication/transact14
excerpt: ''
date: 2014-03-02
venue: '9th ACM SIGPLAN Workshop on Transactional Computing, TRANSACT'
paperurl: ''
citation: 'Ismail Kuru, Burcu Kulahcioglu Ozkan, Suha Orhun Mutluergil, Serdar Tasiran, Tayfun Elmas, Ernie Cohen.
&quot;Verifying Programs under Snapshot Isolation and Similar Relaxed Consistency Models. 9th ACM SIGPLAN Workshop on Transactional Computing, TRANSACT.'
---

[pdf](http://transact2014.cse.lehigh.edu/kuru.pdf)

**Abstract.** Abstract
We present a static verification approach for programs running under snapshot isolation (SI) and similar relaxed transactional semantics. Relaxed conflict detection schemes such as snapshot isolation
(SI) are used widely. Under SI, transactions are no longer guaranteed to be serializable, and the simplicity of reasoning sequentially
within a transaction is lost. In this paper, we present an approach
for statically verifying properties of transactional programs operating under SI. Differently from earlier work, we handle transactional
programs even when they are designed not to be serializable.
We present a source-to-source transformation which augments
the program with an encoding of the SI semantics. Verifying the
resulting program with transformed user annotations and specifications is equivalent to verifying the original transactional program running under SI – a fact we prove formally. Our encoding preserves the modularity and scalability of VCC’s verification
approach. We applied our method successfully to benchmark programs from the transactional memory literature.


