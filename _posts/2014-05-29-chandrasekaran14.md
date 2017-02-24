---
title: Finding a most biased coin with fewest flips
abstract: We study the problem of learning a most biased coin among a set of coins
  by tossing the coins adaptively. The goal is to minimize the number of tosses until
  we identify a coin whose posterior probability of being most biased is at least
  1-δfor a given δ. Under a particular probabilistic model, we give an optimal algorithm,
  i.e., an algorithm that minimizes the expected number of future tosses. The problem
  is closely related to finding the best arm in the multi-armed bandit problem using
  adaptive strategies. Our algorithm employs an optimal adaptive strategy—a strategy
  that performs the best possible action at each step after observing the outcomes
  of all previous coin tosses. Consequently, our algorithm is also optimal for any
  given starting history of outcomes. To our knowledge, this is the first algorithm
  that employs an optimal adaptive strategy under a Bayesian setting for this problem.
  Our proof of optimality employs mathematical tools from the area of Markov games.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: chandrasekaran14
month: 0
firstpage: 394
lastpage: 407
page: 394-407
sections: 
author:
- given: Karthekeyan
  family: Chandrasekaran
- given: Richard
  family: Karp
date: 2014-05-29
address: Barcelona, Spain
publisher: PMLR
container-title: Proceedings of The 27th Conference on Learning Theory
volume: '35'
genre: inproceedings
issued:
  date-parts:
  - 2014
  - 5
  - 29
pdf: http://proceedings.mlr.press/v35/chandrasekaran14/chandrasekaran14.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
