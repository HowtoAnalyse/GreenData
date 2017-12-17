---
layout: page
sidebar: right
title: "Decision Tree"
tags:
  - classification
categories:
  - Machine Learning
---

Decision tree classifiers are incredibly simple in theory. In their simplest form, decision tree classifiers ask a series of Yes/No questions about the data — each time getting closer to finding out the class of each entry — until they either classify the data set perfectly or simply can't differentiate a set of entries. Think of it like a game of Twenty Questions, except the computer is much, much better at it.

The nice part about decision tree classifiers is that they are scale-invariant, i.e., the scale of the features does not affect their performance.

A common problem that decision trees face is that they're prone to overfitting: They complexify to the point that they classify the training set near-perfectly, but fail to generalize to data they have not seen before.
Random Forest classifiers work around that limitation by creating a whole bunch of decision trees (hence "forest") — each trained on random subsets of training samples (drawn with replacement) and features (drawn without replacement) — and have the decision trees work together to make a more accurate classification.