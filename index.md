---
title: Facts and fallacies - Fact 37
subtitle: Rigorous inspections can remove up to 90 percent of errors from a software product before the first test case is run
author: Daniel Falster
job         : Post-doctoral research fellow, Macquarie University
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user: dfalster
  repo: swc-fact37
---

## What is code review?

1. <h3> Inspection of code by a group </h3>
Presnetation of & intensive review of your code. 

2. <h3> A 'breakthrough tool' [Glass, 2003]()</h3>

3. <h3> Catches between 30-90% of defects </h3>
Depeneding on:
 - number and type of peer reviews, 
 - size and complexity of the system,
 - frequency of defects better caught by execution. ([Boehm & Basili 2001](http://www.cs.umd.edu/projects/SoftEng/ESEG/papers/82.78.pdf))

---

## Why does it work?

1.  <h3>Two brains better than one.</h3>
People think in different ways, make different assumptions, notice different things.

2.  <h3> Tests programmers logic</h3>
Can someone else follow your logic?

3.  <h3>Encourgaes you to solve problems yourself.</h3>
Explaining something to someone else forces you to focus on details.

---

## Why so un-popular?

1. <h3> It's cheap, so not promoted </h3>
Companies hype tools they can sell. 

2. <h3> It's hard, so eagerly avoided </h3>
Reviewing code is strenuous.

3. <h3> Backend part of software development often ignored </h3>
Or taken for granted.

4. <h3> Could lead to bad morale</h3>
Need to encourage positive, non-competitive atmosphere.

---

## Guidelines

1. <h3> Do it early and often </h3>
Cheaper to fix problems when caught early. 

2. <h3> Combine with other error detection tools</h3>
Code review, analysis tools, and testing catch different classes of defects at different points in the development cycle. ([Boehm & Basili 2001](http://www.cs.umd.edu/projects/SoftEng/ESEG/papers/82.78.pdf))
