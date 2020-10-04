
---
title: "Consistency-Aware Scheduling for Weakly Consistent Programs"
collection: publications
permalink: /publication/sigsoft18
excerpt: ''
date: 2018-01-01
venue: 'ACM SIGSOFT Software Engineering Notes 42(4): 1-5'
paperurl: ''
citation: 'Maryam Dabaghchian, Zvonimir Rakamaric, Burcu Kulahcioglu Ozkan, Erdal Mutlu, Serdar Tasiran.
&quot;Consistency-Aware Scheduling for Weakly Consistent Programs. ACM SIGSOFT Software Engineering Notes 42(4): 1-5.'
---

[pdf](https://dl.acm.org/doi/10.1145/3149485.3149493)

**Abstract.** Modern geo-replicated data stores provide high availability by relaxing the underlying consistency requirements. Programs layered
over such data stores are called weakly consistent programs. Due
to the reduced consistency requirements, they exhibit highly nondeterministic behaviors, some of which might violate program invariants. Therefore, implementing correct weakly consistent programs and reasoning about them is challenging. In this paper, we
present a systematic scheduling approach that is aware of the underlying consistency model. Our approach dynamically explores
all possible program behaviors allowed by the used data store consistency model, and it evaluates program invariants during the
exploration. We implement the approach in a prototype model
checker for Antidote, which is a causally consistent key-value data
store with convergent conflict handling. We evaluate our tool on
several benchmarks. The results show that our approach is effective in detecting buggy behaviors in weakly consistent programs.