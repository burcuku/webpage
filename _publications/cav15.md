---
title: "Systematic Asynchrony Bug Exploration for Android Apps"
collection: publications
permalink: /publication/cav15
excerpt: ''
date: 2015-07-16
venue: '27th Int. Conference on Computer Aided Verification (CAV)'
paperurl: ''
citation: 'Burcu Kulahcioglu Ozkan, Michael Emmi, Serdar Tasiran.
&quot;Systematic Asynchrony Bug Exploration for Android Apps. 27th Int. Conference on Computer Aided Verification (CAV).'
---

[pdf](https://link.springer.com/chapter/10.1007/978-3-319-21690-4_28)

**Abstract.** Smartphone and tablet “apps” are particularly susceptible to asynchrony bugs. In order to maintain responsive user interfaces, events are handled asynchronously. Unexpected schedules of event handlers can result in apparently-random bugs which are notoriously difficult to reproduce, even given the user-event sequences that trigger them.

We develop the AsyncDroid tool for the systematic discovery and reproduction of asynchrony bugs in Android apps. Given an app and a user-event sequence, AsyncDroid systematically executes alternate schedules of the same asynchronous event handlers, according to a programmable schedule enumerator. The input user-event sequence is given either by user interaction, or can be generated by automated ui “monkeys”. By exposing and controlling the factors which influence the scheduling order of asynchronous handlers, our programmable enumerators can explicate reproducible schedules harboring bugs. By enumerating all schedules within a limited threshold of reordering, we maximize the likelihood of encountering asynchrony bugs, according to prevailing hypotheses in the literature, and discover several bugs in Android apps found in the wild.