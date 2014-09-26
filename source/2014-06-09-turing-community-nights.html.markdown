---
title: EmployMe Pivot project technical retro
date: 2014-06-09 23:10 UTC
tags:
author: Corey Davis, Alan Smith, Robert Gu, Horacio Chavez
layout: post
---
# The Pivot aka, making muffins out of car parts . . .

Our latest project for [Turing](http://turing.io) involves pivoting a code legacy to a multi-tenant app. Specifically we are taking a previous single-tenant restaurant app and turning it into a multi-tenant employment app (think miniature Monster.com.) Working with legacy code comes with a lot of challenges. The obvious problem was the architecture and design of our codebase was directed to meet the needs of a single restaurant, not an employment site


So to start, what is a pivot? Well from our seat (that of students at Turing) a pivot is taking something and making into something TOTALLY different. Which from our perspective seems totally ludacris. But the truth of it is that this is something that actually happens to us (developers) especially in the consultancy side of our world. So what does it mean.

## Legacy code

To provide a definition, legacy code is a code based that currently exists. Jumping into legacy code is very common. In fact it is more common that not. It comes with a host of positives and a set of negatives. But all in all for the most part its pretty straight forward, you work to add on improve or modify some currently existing code so as to keep a product up to date and forward moving. It’s pretty straight forward, except when it’s not. . .into the pivot. In our most recent project we jumped into a code base from a previous project. Which brought about a whole host of adventures. But to focus, lets look at the concept of clearing the white board. 

It’s like you’re going through an abandoned junkyard, and there are a lot of great parts some of which you can salvage, others you can tweak, but the rest is for discard. The challenge is not fitting your project to the current code, but instead fitting the current code to your project. You have to look at each part not for what it is, but what it could be. Often you can reuse parts to fit your purposes, and this becomes your default. But you can’t let this keep you from clearing the whiteboard. Sometimes the right choice is to take an existing structure and burn it to the ground. Often it means dumping the whole file, waiting a minute, and then approaching the problem as if it was the first time.

## Bug hunting

So hopefully the code base is relatively bug free. This is good for the existing app, but really its indifferent for the pivot, because as soon as you start ripping and nailing at it you are most likely going to start inventing bugs on the fly. Inevitably you jack everything up! This is a unique feeling because you know that you started off with a nice clean app and green tests, so you kind of have to brace for this. Especially if you don’t fully understand how the legacy worked to begin with. It worked, it seems like it should still work, but it doesn’t.

## Pivot points

One would think that by name a “pivot” would be obvious. But the thing is that depending on how far the pivot is intended to swing these points may be highly convoluted. In the case of this project they were not clear from the start. We took a resturant ordering app and pivoted over to a Monster.com like hireing platform. This was a big swing, and our originally ideas on where the pivot points were often proved to be way off base. This is where applying the Agile idea of flexibility becomes so critical. If you think that you can see the outcome you probably are already lost, instead dream the outcome, then evolve with the process.

