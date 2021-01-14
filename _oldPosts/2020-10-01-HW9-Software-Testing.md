---
layout: post
title: HW9 Chapter 8 and reflections on testing
---

HW9: Ex 8.7, 8.10, reflections on readings

8.7.  Write a scenario that could be used to help design tests for the wilderness weather station system. 

A scenario that could be used to design tests for the wilderness weather station are the most extreme circumstances.  Say the weather station was located in the frozen tundra of north Canada. If a user had extremely slow internet speeds but was checking the local weather to see if a storm was coming would the slow connection speed render the software useless. Similarly, if the user was requesting many requests to the central server could the system handle an increase of traffic from a given location. 

8.10.  A common approach to system testing is to test the more important functionalities of a system first, followed by the less important functionalities until the testing budget is exhausted. Discuss the ethics involved in identifying what “more important” means. 

By testing the most important functionalities of the software first, developers hope to make it look like a significant amount of test coverage was achieved. However, emphasized in the question, the concept of what “most important” means is tricky. Thinking about this with ethics in mind I believe it is crucial to communicate between the user, the client, management, and the developer. It is unrealistic to assume software can even be tested in every possible way given the nature of modern day computing, although testing should not be seen as an afterthought and I truly think that test driven development makes all parties more satisfied with the final product.  

Reflection: 
This week’s readings, Chapter 8 Software Testing and “intro to testing” educated me on thinking about tests differently. Before the reading I often though of debugging as a form of manual tests while testing was thought-out plans for what would prove your code does what you say it does.  Testing is the process of surfacing bugs. Debugging depends on testing and more about the act of correcting bugs after finding them. It must be misunderstood for the simple reason that people say “I’m going to debug my code” but no one mentions that they already tested it. Of course, looking back it is clear to see that testing the code is the only way to truly know that I need to be debugged.  
