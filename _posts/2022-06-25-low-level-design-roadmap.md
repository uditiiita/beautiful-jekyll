---
layout: post
title: Roadmap for Low Level Design Interviews Preparation
tags: [Interviews, Low Level Design, LLD, Design, System Design]
comments: true
categories: Learning
---

## What is a system design interview?
* In such kind of an interview, you are given a real-world problem and you are expected to come up with the required design for it. 
* Since no system in this world is best, so you are expected to come up with the tradeoffs of your design. Like where a design will work well and where not. Its pros and cons.
* One of the major goals of system design interviews is to see whether candidate is able to identify these tradeoffs and fix cons.
* More details on system design interviews you can find in this video: https://youtu.be/zkVll74UwGY

## Low level design interviews
In such kind of interviews, we talk about low level design of the system being discussed. It mostly includes discussing the class structure that you will create for the problem. 
You will have to use some good design patterns and principles in this round to excel at it.  
Expectations:
* Whether you are able to come up with some good requirements or not. This involves requirement Gathering and defining system constraints.
* Identifying and defining Entities and their associations.
* Major criteria: Coupling, Extensibility, and System Maintainability.
* Whether your design is following good design principles and patterns or not.

## Low-Level Design Learning strategy:
* **Concepts:** Understanding concepts is really important here. We have seen people trying to solve problems directly. That will not work. Try to learn underlying concepts first and then do practice problems.
    * Design principles - Used for analysis.
        * SOLID: Learn principles of good designing like SOLID etc. Try to understand how they are helping you in coming up with some good designs.
    * Design patterns - User for implementation
        * Most important design patterns needed to start with. If you can get good hold on these, then you can do really good design:
            * Strategy
            * [Builder](https://youtube.com/watch?v=6Wi2XZeAf-Q&list=PL564gOx0bCLqTolRIHIsR2JPv11w8LESW)
            * Singleton
            * Factory
            * [Composition over inheritance](https://www.youtube.com/watch?v=ltENzdsbsdA&list=PL564gOx0bCLqTolRIHIsR2JPv11w8LESW)
            * [Command Pattern](https://www.youtube.com/watch?v=G7ErX_0eCkU&list=PL564gOx0bCLqTolRIHIsR2JPv11w8LESW)
* **Practice problems:** Practicing problems and try to come up with trade-offs in the design. Try to see how your designs compare to other people’s designs and try to find pros and cons in each one of them.

## Steps in a low level design interview:
* Step 1: Start with the model classes first. This about the entities that you have in the system that you are building. Create classes for those entities in the design.
* Step 2: Then think about the properties of those classes. Try to what all fields those classes should have and create them.
* Step 3: Then we have to think about the behavior of those classes. This means you have to define the methods in the classes. 
   * But coming up with the methods for each model class is difficult to start with. 
   * So, its always better to start top down here. 
   * First think about the top level method you need, start implementing it and keep discovering new and new methods that you would need.


## Good Luck for your Interviews :)
