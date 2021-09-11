---
layout: post
title: CKAD Exam Prep
---

Hi folks! This is the first blog post in War(un)lock where I'll post some extra info that may not fit well with the regularly blog posts because:
1. The content is specific to a relatively small audience.
2. It's so much in-depth content that it would crowd out the day-to-day updates.

This post will be dedicated on the **Certified Kubernetes Application Developer (CKAD) exam**. Since I will be renewing my certification this month, and folks have regularly asked me about the certification exam, I wanted to post my experience and study plan. Note that I won't go into Kubernetes concepts - you'll have to learn that yourself with this helpful guide. ;)

### Background

Kubernetes is a container management platform software. It addresses the issue of managing how containers and applications are deployed, maintained, scaled, accessed, etc. in one big platform. It's a lot of nautical-themed jargon on top of a comprehensive and extensible platform.

I have been interested in learning Kubernetes since I first learned about it in around 2017. I have had the opportunity to work on applications that were deployed to Kubernetes since then. However, my knowledge around the software was rather shallow - I often mixed up what was Kubernetes standard, what was company in-house customization, and what were Kubernetes extensions (i.e. Helm).

At mid-2018, I booked a trip to Berlin to go to the [Velocity conference (now defunct)](https://www.oreilly.com/conferences/). I also wanted to attend a workshop alongside the conference talks, and I saw that the conference offered a CKAD certification preparation course. Thus, I was now set to learn Kubernetes fundamentals!

### Original study plan

My CKAD certification test was set in late November, and I had some tighter project deadlines not long after the conference. I formed a study plan that would give me enough time to learn the concepts and prepare for the test while working full-time. I studied for 2 months in total, 2-3 hours per day for 3-4 days per week. I’m recalling this information from 2 years ago, and I had some practical Kubernetes experience before, so YMMV with this study strategy. However, my intent was to be consistent with my studying so I retained the information better. I wanted to apply this knowledge to my data engineering job as well (and not that the company was also paying for my certification...)

**One month was dedicated to learning Kubernetes fundamentals.** This included hitting the books one chapter at a time, then doing some hands-on work on ther terminal. This helped me understand what the heck the YAML configuration files were doing, and how it related to the high-level concepts. I was fine taking my time to really learn how Kubernetes objects related to each other, and how I could relate Kubernetes concepts to what I already knew (i.e. Apache Spark).

**The other month was dedicated to test preparation.** The test itself is 2 hours long with 20 questions to live code. It’s also open book to the kubernetes.io website. BUT, it’s a very short amount of time to complete the questions. (In my first practice exam, I only got through half of the questions in two hours!) You have to know the materials AND be comfortable typing and editing on the terminal. There is also a little bit of exam strategy, such as picking which (weighted) questions to tackle first.

For extra credit to myself, I came across a GitHub repo for [creating a Kubernetes cluster from scratch on a Raspberry Pi](https://github.com/kelseyhightower/kubernetes-the-hard-way). Since I had a Raspberry Pi gathering dust in my home, I decided to try out the tutorial. It was a cool learning experience to know how relatively simple it was to set a one-node Kubernetes cluster up.

### Current study plan

Since I learned that the CKAD test will change at the end of September 2021, my goal was to take the test a few days before that deadline. The CKAD exam offers a free retake if you fail the first time (because that's how stressful the exam is to take), so I left buffer room in case I’ll need to do a retake. This has given me roughly 3.5 weeks of studying.

So far, I’ve spent around two weeks reviewing concepts (5%) and refreshing my brain on the syntax (95%). I’ve spent around 1-2 hours per day for 5 days per week, since there's only so much time I can tolerate practicing my typing and remembering words. I plan to have the remaining week and change be dedicated to taking practice exams, and simulating my testing environment. (This means no headphones and no breaks!) The CKAD exam now includes 2 free practice exam attempts through [killer.sh](https://killer.sh/), which is new to me this year. Having these two weeks to practice gives me enough time to review any other concepts I've missed, and to rest plenty.

### Resources

#### General resources

* [The CKAD certification website](https://www.cncf.io/certification/ckad/). For registrations, information, etc.
* [CNCF CKAD exam curriculum](https://github.com/cncf/curriculum/blob/master/CKAD_Curriculum_V1.21.pdf). An important resource for knowing what Kubernetes topics to focus on for the exam.
* [The official Kubernetes documentation website](https://kubernetes.io/). It’s a really good reference in general. The CKAD exam also allows you to use this website during the exam, you should also be familiar with it.

#### If you’re not familiar with Kubernetes

* [Docker Desktop](https://www.docker.com/products/docker-desktop). I installed Docker Desktop and enabled the Kubernetes settings, so I can practice CKAD exam questions on my laptop. I have the displeasure of having an older Windows laptop that might explode if I attempt to dual-boot it. Thus, I’ve used [Chocolatey](https://chocolatey.org/) and Windows Powershell to emulate a more Linux-like environment on my Windows OS.
* [Docker getting started](https://docs.docker.com/get-started/) and [Docker overview](https://docs.docker.com/get-started/overview/). Docker is a type of container that Kubernetes can manage. It’s not necessarily required to know about Docker, but it’s important to distinguish between the two.
* [Learn Kubernetes Basics tutorial](https://kubernetes.io/docs/tutorials/kubernetes-basics/). A “baby’s first” Kubernetes cluster. An interactive guide to learning about the basic components.
* [Kubernetes: Up and Running](https://www.oreilly.com/library/view/kubernetes-up-and/9781492046523/). I had a free subscription to O’Reilly, so I went through this book to learn Kubernetes concepts. Even if you don't pay for the book or subscription, the table of contents itself is a good outline.
* [kelseyhightower/kubernetes-the-hard-way](https://github.com/kelseyhightower/kubernetes-the-hard-way). Highly recommended for the CKA exam but not so much for the CKAD. Definitely recommend trying this if you have access to a Raspberry Pi, or want to try it out through cloud resources.

#### Exam prep

* [dgkanatsios/CKAD-exercises](https://github.com/dgkanatsios/CKAD-exercises). My favorite GitHub repo for CKAD exam practice questions. My goal is to be able to run through the questions in less than 100 minutes.
* [bmuschko/ckad-prep](https://github.com/bmuschko/ckad-prep). Another GitHub repo for CKAD exam practice questions.
* [twajr/ckad-prep-notes](https://github.com/twajr/ckad-prep-notes). A GitHub repo for CKAD tips and tricks.
* [kubectl cheat sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/). A useful reference for learning Kubernetes terminal commands. Speed is key in this exam!

In addition, I went through a few tutorials learning about Vim and Bash. I’m comfortable with using Vim, but I’m quite rusty on Bash syntax. Learning both helps with getting comfortable with the terminal. Again, YMMV depending on your prior experiences.

Finally, eating right and sleeping well before the exam is always recommended!

### Summary

As of time of writing, I am still in the process of preparing to renew my certification. After the exam, I will update this blog post on any other resources I've used, as well as a short summary of my experience.

Thanks for reading!
