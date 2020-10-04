---
title: "iDeA: An Immersive Debugger for Actors"
collection: publications
permalink: /publication/erlang18
excerpt: ''
date: 2018-09-29
venue: '17th Erlang Workshop'
paperurl: ''
citation: 'Aman Shankar Mathur, Burcu Kulahcioglu Ozkan, Rupak Majumdar. (2018). &quot;iDeA: An Immersive Debugger for Actors. 17th Erlang Workshop. '
---

[pdf](https://dl.acm.org/doi/10.1145/3239332.3242762)
[videos](https://vr.mpi-sws.org/idea)

**Abstract.** We present iDeA, an immersive user interface for debugging concurrent actor programs communicating through
asynchronous message passing. iDeA is based on the hypothesis that debugging and understanding actor programs
is a cognitive task which can be greatly facilitated by the visualization and interaction capabilities of modern immersive
environments. The fundamental abstraction for visualization
in iDeA is a concurrent trace: a partially ordered sequence of
asynchronous messages exchanged in the execution. iDeA
provides a 3D interface in virtual reality for users to visualize
and manipulate program traces: users can set breakpoints,
query actor state, step through traces forward and backward,
and perform causal history of messages in a trace.
While the modularity of iDeAenables debugging any actor
program provided that the program events are collected and
communicated to the visualization end, our implementation
of iDeA targets actor programs written in Akka framework
in Scala.