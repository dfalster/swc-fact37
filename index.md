---
title: Fact 37
subtitle: Rigorous inspections can remove up to 90 percent of errors from a software product before the first test case is run
author: Daniel Falster
framework: deck.js
theme: swiss
transition: horizontal-slide
url:
  assets: .
widgets: []
github:
  user: dfalster
  repo: swc-37
highlighter: highlight.js
hitheme    : github
mode : selfcontained
---

## Fact 37 - Rigorous inspections can remove up to 90 percent of errors from a software product before the first test case is run

---

## What is code review?

1. <h3> Inspection of code by a group </h3>
Presnetation of code, followed by intensive review. 

2. <h3> Close to 'breakthrough tool'</h3>

3. <h3> Catches between 30-90% of defects </h3>
Depeneding on ([Boehm & Basili 2001](http://www.cs.umd.edu/projects/SoftEng/ESEG/papers/82.78.pdf)):   - number and type of peer reviews, 
 - size and complexity of the system,
 - frequency of defects better caught by execution.

---

## Why Does it work?

1.  <h3>Encourgaes you to solve it yourself.</h3>
Explaining something to someone else forces you to focus on details, so you notice the problem. 

2.  <h3> Tests programmers logic</h3>
Can reviewer see what it is meant to do?

3.  <h3>Two brains better than one.</h3>
People think in different ways, make different assumptions, notcie different things.

---

## Why so un popular?

1. <h3> It's cheap </h3>
Companies hype tools they can sell. Code review is cheap.

2. <h3> It's hard </h3>
Reviewing code is strenuous, and thus easily avoided.

3. <h3> Backend part of software development ignored </h3>
People asssume it is done, but no one's checking or teaching it.

4. <h3> Could lead to bad morale if done badly </h3>
Need to encourage positive atmosphere.

---

## Guidelines

1. <h3> Do it early </h3>
Cheaper to fix problems when caught early ([Boehm & Basili 2001](http://www.cs.umd.edu/projects/SoftEng/ESEG/papers/82.78.pdf))

2. <h3> Combine with other error detection tools</h3>
Code review, analysis tools, and testing catch different classes of
defects at different points in the development cycle.