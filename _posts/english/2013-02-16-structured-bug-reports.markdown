---
layout: post
title:  "Structured steps to reproduce for a bug report"
date:   2013-02-16 12:27:01

categories: blog cs
---


Steps to reproduce of a bug or flaw not in free text form:

0. there are combos for features, and also intelligently they change based on what the user has chosen in previous step, and what is possible as next step accordingly. 

We have a tree of application features: from high-level features down to UI interactions. For example Mail Application --> Send Mail --> Send Mail with CC --> ... and so on. 

In the bug report user starts by selecting which high-level feature he wanted to use. The rest steps are then filtered accordingly, showing only those possible sub-features (steps) that are children of the selected node. 

Advantage over free text: better processing, clear steps of what user did