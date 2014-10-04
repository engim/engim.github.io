---
layout: post
title:  "Start of Devcar project"
date:   2014-10-04
categories: devcar project info
---

So here we are, some friends that after years of trying to do something and ending having beers and playing multiplayer internet games, finally have started toghether, and as a first step, we ahve created a common github project and a github organization.

Some months ago, we finally meet around a table and do those famous activity that avary enterpreneur or buissness school student must do, that is brainstorming. After some ideas that were **cool as fuck ®**, like the Ironman helmet or the homemade quadcopter, we aimed to a lower budget and ended up developing a remote controlled car, with a Raspberry and a Arduino in his heart.

We call this car from now on, *Devcar* (we had to name it somehow, hadn't we?).

System design
-----------
The idea was to create a remote controlled car, so we need to have some kind of connectivity to accomplish that. As a first step, we opted to use wifi as a solution. This allows us to controll the car over areas where wifi signal is continuosly recived. The university where we have studied is a perfect place, altough in the future we are considering the options to connect the raspberry over 3g (using an android phone or something similar). Anyway, this isn't part of the topic right now.

So, once resolved the communication problem, the idea was to deisgn a simple protocol over TCP to maintain a conexion, send orders to the Devcar, (to be continued)
