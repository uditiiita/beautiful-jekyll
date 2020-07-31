---
layout: post
title: Amazon Interview Experience
tags: [Interview, Preparation, Placements, Job, Experience, Amazon]
comments: true
categories: Interview Experience
---

I recently gave interview in Amazon for the position of Software development engineer. The overall experience was pretty good, so I thought of sharing the experience with everyone.  

## Summary
**Total number of rounds: 4**
* **Round 1**: Focussed on Problem Solving and DS/Algo.
* **Round 2**: Focussed on Low Level Design.
* **Round 3**: Focussed on solving for a vague problem. Needed good logical abilities.
* **Round 4**: Focussed on High Level Design.

## Details
## Round 1:

#### Question 1:
Assume that weather.com is providing a list of forecasts. At any day, you want to find when the next warmer day is available.  
Example: 
* **input**: [60, 90, 76, 80, 100, 62, 90]
* **output**: [1, 3, 1, 1, 0, 1, 0]

Solution:  
* Expected Complexity: O(N)
* Approach: Solved by using a stack.

#### Question 2:
Given a complete binary tree, compute the number of nodes in the tree.  
Solution:
* Expected complexity: O(Height^2)
* Approach: We can count number of nodes intelligently by discarding half of tree at each level thus bringing down the complexity to H^2. We are able to reduce our space by using the special property of complete binary tree.

## Round 2:
Design the score calculator system of Bowling alley game. The system should be invoked after player chance,  should update the scores of all the players, should provide a dashboard for viewing. Some rules of bowling were given.
* Expectation: Mostly the discussion went around how to make design scalable so that multiple types of scores like Spare, Strike are handled easily.

## Round 3: 
Given a link to a page, find out what all different links are reachable from this link. Also, keep a count of how many pages refer to a single page.  
It was more like solving a real world vague scenario.

## Round 4:
Design a system for messaging service like WhatsApp.  
You can learn how to solve this problem here: [https://youtu.be/0QfGpx7jDYw](https://github.com/daattali/beautiful-jekyll.git)

## Behaviour questions in all rounds:
All rounds had some behaviour questions in them. Some example of these questions are:
1. What is most complex problem you have solved?
2. Most interesting conflict you had?
3. How did you convince of your design choices?  
etc.
