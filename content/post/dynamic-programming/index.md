+++
title = "Dynamic Programming"
subtitle = ""

# Add a summary to display on homepage (optional).
summary = "Just some random notes on Dynamic Programming"

date = 2019-04-08T13:21:02+02:00
draft = true

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Is this a featured post? (true/false)
featured = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Algorithms"]
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

### Introduction
The topic of *dynamic programming* sounds really fancy and obscure but it's not a big deal afterall :)

DP problems usually appear in your favourite course on Algorithms and Data Structure, in Algorithmic Competitions or in Technical Interviews, but it also has lots of real life applications, we will see some of them at the end of this blog post.

### What is DP?
We first need to introduce the concept of *divide-and-conquer*.

*Divide-and-conquer* is a technique for solving a complex problem by breaking it down into a collection of simpler sub-problems until these become simple enough to be solved directly. The solutions to the sub-problems are then combined to give a solution to the original problem.

Some examples of the application of this techinque are:

* [Binary Search](https://en.wikipedia.org/wiki/Binary_search_algorithm)
* [Euclidean Algorithm for computing the GCD](https://en.wikipedia.org/wiki/Euclidean_algorithm)
* [Merge Sort](https://en.wikipedia.org/wiki/Merge_sort)
* [Fast Fourier Transform](https://en.wikipedia.org/wiki/Fast_Fourier_transform)

But what if we have a lot of overlapping sub-problems? Do we really need to compute them everytime?

This is the concept of *dynamic programming*, **once we have a recursive formulation of the problem** (and sometimes this is not a pieace of cake) let's just simply cache every value we compute so we don't need to compute it again in the future.