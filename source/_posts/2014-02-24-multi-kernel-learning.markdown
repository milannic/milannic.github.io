---
layout: post
title: "Multi-Kernel Learning"
date: 2014-02-24 23:41:41 -0500
comments: true
categories: [Machine Learning, Kernel Methods]
---
Due to the graph kernel projects, I got the change to know this method, the concept is quite natural. When you have some kernels, and you find a way, maybe linear or exponential, to combine them, then for the specified training data, you will take the advantage of each kernel, and the way to find the best combination is still a optimization problem, randomly assign a initial weight vector of each kernel, and use a numeral method to iterate it,such as gradient descent.  

The matlab code I am using is from [this](http://research.microsoft.com/en-us/um/people/manik/code/gmkl/download.html)
But I want to say the way the code is written is too strange, I mean that wrapper.
{% img http://placekitten.com/890/280 %}

