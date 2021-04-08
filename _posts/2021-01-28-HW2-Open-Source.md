---
layout: post
date: '2021-01-28'
title: Reflections on Open Source in Today's World
---

Howdy! Today I am blogging about what I learned and my response to 2 articles from www.opensource.com.

The first article I found that interested me is called "Find security issues in Go code using gosec" and is found at <https://opensource.com/article/20/9/gosec>

Being a fan of containers and k8s I am naturally interested in Golang. Similarly, since I do a lot of cybersecurity training through the cofc club I thought this topic would pair well with my skills and interests.

In its most basic form, gosec is simply a Static analysis tool that works by parsing source code written in go and looking for issues. This to me sounds like a glorified linter but apparently it has some serious power underneath the hood. After a brief description of some use cases and the overall scheme for how to use the tool the article goes into a deep dive on how to install, configure, and test go code. In this example, they test the Docker community edition for possible security vulnerabilities. The tool has the ability to label segments of code with various severity levels and even suggests possible ways to address the vulnerabilities if it is already known to the larger community. Overall I very much enjoyed reading this hands-on article and may even use the tool in my dev life.

The second article I found that interested me is called "How to adopt DevSecOps successfully" and is found at <https://opensource.com/article/21/2/devsecops>

The first time I heard this term was actually just the other week at the SECCDC (South East Collegiate Cyber Defense Competition) when one of the red teamers was mentioning how he had multiple roles opening up for devsecops positions. My ears immediately perked up because I love devops and I also love security.

Before we talking about securing the DevOps workflow let's quickly define what we mean when we talk about devops. DevOps is a set of practices that combines software development and IT operations. It aims to shorten the systems development life cycle and provide continuous delivery with high software quality.

DevSecOps takes this principle one step further in that it seeks to add the clause that everyone at every stage (whether you are dev or ops or security) should be focused on making the whole system bulletproof. As more and more of our pipelines become automated it is increasingly important that they are robustly secured in an automated way from all angles.
