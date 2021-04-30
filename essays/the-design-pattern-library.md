---
layout: essay
type: essay
draft: true
title: The Design Pattern Library
# All dates must be YYYY-MM-DD format!
date: 2020-04-29
labels:
- Design Patterns
- Meteor
---

Everyone loves a good dramatic film or books, and the best ones are those that give the sensation of leaving hooked from beginning to the end.  If you've seen Avengers: Infinity War and Endgame or read through the entire collection of Harry Potter books, then certainly you've experienced such a sensation.  Maybe you've also experienced memorable stories in places outside of mainstream media.  Either way, there's a certain pattern of how these stories keep you engaged and why you can become attached to your favorite characters; patterns that become useful tools in narrative storytelling.  Software engineering is also no stranger to having such patterns within development.  As film and books have design patterns in telling dramatic stories, design patterns are also part of software development and in creating functional applications.  

## The Norm

Design patterns within software engineering are the tried and true means of creating functional software.  Being able to create something from scratch can often present many approaches on how to make the said something.  So much so that going in blind without a plan may yield to frustration and failure.  The design patterns in software engineering solves this potential problem by providing structure on how to design applications.  Through trial and error of the software engineering field, various design patterns have been introduced such as: prototype, observer, Model-View-Controller as well as many more.  Going over all of them may turn this essay into an encyclopedia, but they are the norm of how software can be implemented, and going over a few of them may be worth diving into.

##  Dramatic Designs

Perhaps a prominent design pattern within software development is that of the Model-View-Controller which is heavily present in many modern frameworks of today.  In storytelling, there is the pattern of implementing dramatic structure that is the standard of creating tension and suspense.  Similarly, the pattern of the Model-View-Controller is perhaps the standard of displaying system information in a way that is presentable to the user via views, controllers and models.  While the thought process of the model can be complex, in short, the view that a user sees can create an event that affects the controller which in turn affects the model that will affect the view.  Yet, there are multiple ways these three pieces can interact with one another.  An application that I am currently working called "Easy Chef" allows users to create budget recipes, and part of its design includes the Model-View-Controller.  For example, a user can view can click on a page with React that presents their created recipes to which a controller with React router manipulates the model that is MongoDB to retrieve the appropriate information where it is then presented for the user to view.   However, this is just one of many ways the the Model-View-Controller can be implemented.

## Observer from Afar 

In battles of good and evil, the heroes may often observe the acts of their adversaries and react accordingly based on the threat level of their opponent to which the villains themselves may also do the same.  Within software development, there is a similar design pattern called the observer.  The observer design pattern presents two types of objects called observers react accordingly based on the state of another type of object called subjects.  This is often utilized when certain type of events have to handled.  The Meteor framework is one type of framework that is centered around this design pattern.  More specifically, it takes on a variation of the observer design pattern that involves publishers that can provide messages to various subscribers.  In my own work in the "Easy Chef" application, certain collections of documents get published by publishers in which a published set of data becomes published based on the role of the user that is logged in.

## Everywhere at Once

Another design pattern worth noting is that of the Singleton pattern.  As stories can tell the tales of multiple characters (heroes or villains) that all come together under one story, applications can present variables that all come together within one system.  Specifically, the Singleton pattern is the means to create global variables that holds information such as a class and take them anywhere in the system where it can be utilized and presented.  An application for instance may present collections that each present a plethora of documents in which each collection is handled by class assigned to a variable to which it can then be exported to pages to present the information of the class (or more specifically the collections).  In fact, this same approach is also utilized in the previously mentioned "Easy Chef" app that allows the system to handle and present certain information within the database.

## A Tangled Weave

However, as stories have the potential to create a jumbled mess of characters and their journeys, a system with global variables can leave a tangled mess.  Such cases present a different design pattern called the Anti-Design pattern, and if not handled with care, the Singleton pattern can fall under such category.  Even other tried and true design pattern can fall ill to being anti-design if not used in the appropriate system design.  These patterns may be tried and true but only when in the proper context will they be of benefit to application that they are being applied to.

## Idle Heroes Can't Save the World

When it comes to making anything from scratch, perhaps the hardest part is actually knowing where to begin.  Given enough time, an idea may spark on where to start. However, at the end of the day, there's a client that expects a functional app as there are people that expect the hero to defeat the villain.  To them, how you begin does not matter.  Software design patterns avoids the pitfall of being stuck when it comes to knowing where to begin.  However, what makes the design patterns of software engineering unique is that given the differing complexities of various projects sizes, there's always a pattern to use due to their open ended nature, and at times, these patterns may be used without ever being realized.  With my contributions to the "Easy Chef" project, I only realized well into the development that I have been utilizing the design patterns discussed above.  Without these patterns, my team and I would most likely be lost without a plan, yet thankfully design patterns are the guiding light in the vast open nature of software development.











