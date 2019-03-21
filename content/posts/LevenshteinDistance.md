+++
type = "posts"
title = "Levenshtein Distance"
description = "MM - Levenshtein Distance"
date = "2019-02-06" 
+++

In one of my project, I had to make a matching solution for customers in 2 different, unconnected tables. At the beginning, I did the string comparison on customer names, but the plan failed before it even started. People make mistake, and one typo will render the string comparison useless.

The next best thing that I could think of (and actually implemented) is using <a href="https://en.wikipedia.org/wiki/Levenshtein_distance">Levenshtein Distance</a> to calculate the similarity and suggest the best match.



