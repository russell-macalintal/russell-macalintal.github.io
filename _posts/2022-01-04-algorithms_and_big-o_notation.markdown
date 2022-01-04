---
layout: post
title:      "Algorithms and Big-O Notation"
date:       2022-01-04 08:37:14 +0000
permalink:  algorithms_and_big-o_notation
---


This is a topic that is only briefly touched upon in the central curriculum of the coding bootcamp. And it makes sense. The main objective of the course is to teach students the practical side of software development and to get them to practice coding as early and as much as possible. There is already an abundance of topics on that front and they need to be covered in a relatively short period of time. Data structures and algorithms, on the other hand, delve into the more theoretical aspects of computer science and could be quite difficult to fully grasp. But they certainly do have practical applications too, and knowing about them -- how and when to use them to best tackle the problem at hand -- and their associated time complexities is definitely something that every software engineer should have in their tool belt.

The use of algorithms is very common in the tech world. From big companies that employ (tens of) thousands of software engineers all the way down to single-employee startups, algorithms are utilized in all sorts of applications. However, they are not always implemented efficiently or to their full potential. One key element and step to doing so is understanding the mathematics behind them. Algorithms are one of those things that determine whether your application will scale gracefully as its use becomes more widespread or crumble under the weight of ever expanding datasets and inputs.

Having just started learning about these concepts myself, I decided to blog about what I've learned so far (mainly just the basics) and hopefully build on this knowledge (along with follow-up blog posts) in the future while offering a bit of guidance to those early career software developers who may be on the same boat.

To get started, I will summarize the primary concepts of algorithms and one of the metrics used to evaluate their performance, big-O notation, along with some examples. In the future, I plan on expanding on this knowledge and diving deeper into the concepts to get a better understanding of the details and nuances.

There are three definitions that should be covered first:
1. Algorithm = a process or set of rules to be followed in calculations or other problem-solving operations. In broad and simple terms, this is just a set of instructions used to perform a task.
2. Time Complexity = amount of time taken by an algorithm to run, taken as a function of the length of the input (usually denoted by **n**). This is a metric based on the number of operations performed, rather than time, as it is device-agnostic.
3. Big-O Notation = used to classify algorithms based on the upper bound of the growth rate of a function (defined by the Time Complexity). This refers to the highest order (big O) that will make the most difference in a given function as its input approximates to the infinite (evalution known as **asymptotic analysis**).

Algorithms are measured based on the worst-case scenario growth rate or time complexity. Essentially this just means that performance is evaluated based on the longest possible outcome toward a solution.

The 8 most common Time Complexities along with a helpful graph visualization:
1. Constant = O(1) 
2. Logarithmic = O(log n)
3. Linear = O(n)
4. Linearithmic = O(n log n)
5. Quadratic = O(n^2)
6. Cubic = O(n^3)
7. Exponential = O(2^n)
8. Factorial = O(n!)

![](https://i.imgur.com/nB0xRq0.png)

*Source: https://adrianmejia.com/most-popular-algorithms-time-complexity-every-programmer-should-know-free-online-tutorial-course/*


The next blog post in this series will cover each of these in more detail, along with some examples of the algorithms associated with each runtime.
