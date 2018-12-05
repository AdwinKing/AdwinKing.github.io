---
layout: post
title: kNN for Image Classification
---

[Just see this](http://cs231n.github.io/classification/)

# Key point
kNN algorithm regards target's label(output) as the mean of its neighbors'.

## Evaluate Distance
There are two methods often used.
L1: distance = sum of abs(difference of pixels' color)
L2: distance = sum of square(difference of pixels' color)

## Determine How Many Neighbors We Need to Evaluate the mean
Approach 1: Iterate k from 1 to N

## How to Evaluate the Mean of Labels
Approach 1: Take the most often appeared label

## Drawbacks of kNN
1. The classifier needs to remember all of training data. It's space inefficient.
2. It's expensive to make a prediction as it's compared to all the other images.
