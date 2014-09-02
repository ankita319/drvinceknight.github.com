---
layout        : post
name          : Christina Thomas
categories    : [research, students, current]
project_title : Modelling a game of rugby using Markov processes
keywords      : Rugby, WRU, Python, Sage, Markov decision processes
type          : BSc.
start_date    : 2014-09-30
finish_date   : 2015-06-30
comments      : true
---

This is a project supervised by [Professor Harper](http://www.profpaulharper.com/) and myself aiming to use stochastic methods to model a rugby game.

**Project Description**

Operational Research has been widely applied to various sports, especially for fixture scheduling, tactics and strategy, and forecasting.  For an extensive review of past research, see Wright (2009).

Relatively little OR has been applied to rugby union.  Recently the School of Mathematics has established collaborative links with the Welsh Rugby Union (WRU) which has resulted to-date in several UG and MSc projects on topics such as line-out strategies, optimal match scheduling and player rankings.

In this project we consider the problem of modelling a rugby union match to help explore what strategies a team should adopt.  This will be through the development of a multi-state Markov process.  
A game of rugby could be considered as progressing through a series of phases of play, whereby one of the teams has possession of the ball and is trying to score.  Progression of the match then would be a through a set of stochastic transitions occurring due to change of  possession or a team scoring.   If one assumes exponential transition times, in which each phase of play occurs independently of past play, this may be a fairly good approximation of reality, is computationally tractable, and thus permits the representation of the game using Markov processes.  

A previously published paper by Wright and Hirotsu (2002) developed a similar approach to modelling a soccer game.  They adopted a four-state model:

- State 0: team A scores a goal
- State 1: team A is in possession of the ball
- State 2: team B is in possession of the ball
- State 3: team B scores a goal.

The authors then used the Markov model in order to estimate the optimal time to change tactics using dynamic programming, either by making a substitution or by some other conscious change of plan.

For rugby, factors to consider might include:

1. The match consists of a number of phases of play that take place in different defined geographical regions of the pitch (distance from the try line, for example).  
2. The state of the game is represented by which phase we are up to, the points difference and the region (or distance from the try line).
3. At the beginning of each phase the attacking team must choose from a number of strategies, based on the state of the game.


Estimation of transition probabilities would be a challenge for the project and would require reviewing match data from the WRU.

The specific requirements of the project are thus:

Understand previous related research including the Wright and Hirotsu (2002) paper.
Learn about Markov processes.
Consider how best to capture a game of rugby as a multi-state Markov process.
Obtain transition probabilities.
Develop a model of a rugby match and use this to explore various strategies that could be adopted by the teams.
Programming will be required and the student will be expected to learn Sage and/or Python.

Those interested in selecting this project are encouraged to contact the supervisors to discuss suitability.

**References:**

Wright, M B. & Hirotsu, N. 2002, Using a Markov process model of an association football match to determine the optimal time of substitution and tactical decisions.  Journal of the Operational Research Society. 53, 1, p. 88-96.

Wright, M B. (2009), 50 years of OR in sport.  Journal of the Operational Research Society. 60, S161 –S168.