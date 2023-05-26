---
content_type: project
flavours:
- java
prerequisites:
  hard:
  - topics/java-specific/concurrency
  - topics/java-specific/functional-interface
  soft:
  - projects/java-specific/functional-interface
ready: true
submission_type: repo
title: Java Threads
---

## The Chicken and the Farmer

In this project you are going to create a two functions, one should be called `chicken` and the other should be called `farmer`. Both these functions should follow the following rules:

1. They should run on different threads.

2. The chicken function should put eggs in a Basket ***(static array/list of size 1)*** and the farmer function should take eggs from the basket.

3. The Farmer cannot take from an empty basket.

4. The Chicken cannot add to a full basket.

5. The basket is considered full if it has 1 egg.

We kept the instructions open-ended on purpose. This is meant to have a bit of room for interpretation, there is no one perfect solution to this. We are very interested to see how you structure your solution.

Remember to test your work. Always.