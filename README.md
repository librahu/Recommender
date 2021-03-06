﻿Recommender [![Build Status](https://secure.travis-ci.org/GHamrouni/Recommender.png)](http://travis-ci.org/GHamrouni/Recommender)
=======================

![status](http://stillmaintained.com/GHamrouni/Recommender.png)

A C library for product recommendations/suggestions using collaborative filtering (CF).

Recommender analyzes the feedback of some users (implicit and explicit) and their 
preferences for some items. It learns patterns and predicts the most suitable products 
for a particular user.

Features
--------
 * Collaborative Filtering
 * User and Item based recommenders
 * No external dependencies 
 * Fast running time ~ 81 seconds for 10 million ratings (on MovieLens Data Sets)
 * Memory footprint under 160 MB for 10 million ratings

Webpage
--------
http://ghamrouni.github.com/Recommender/

Building
--------
To compile Recommender:

    make

The compilation will produce libRecommender.a

To compile an example:

    gcc test/test.c libRecommender.a -lm -o test/t1

Alternatively you can use clang

    clang test/test.c libRecommender.a -lm -o test/t1


Keywords
--------
Collaborative filtering, recommender system

References
--------
1. http://en.wikipedia.org/wiki/Recommendation_system
1. http://public.research.att.com/~volinsky/netflix/kdd08koren.pdf
1. http://research.yahoo.com/files/ieeecomputer.pdf





