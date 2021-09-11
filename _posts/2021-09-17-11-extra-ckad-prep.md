---
layout: post
title: CKAD Exam Prep
---

Hi folks! This is the first blog post in War(un)lock where I'll post some extra info that may not fit well with the regularly blog posts. This post will be dedicated on the *Certified Kubernetes Application Developer (CKAD) exam*. Since I will be renewing my certification this month, and folks have regularly asked me about the certification exam, I wanted to post my experience and study plan out.

### Background

I have been interested in learning Kubernetes since I first learned about it in around 2017. I have had the opportunity to work on applications that were deployed to Kubernetes since then. However, my knowledge around the software was rather shallow, and I often mixed up what was Kubernetes standard and what was company in-house customization or Kubernetes extensions (i.e. Helm).

At mid-2018, I booked a trip to Berlin to go to the Velocity conference. I also wanted to attend a workshop alongside the conference talks, and I came across a CKAD certification preparation course. Thus, I was now set to learn Kubernetes fundamentals!

Original study plan

My CKAD certification test was set in late November, and I had some tighter project deadlines after the conference. I had to form a study plan that would give me enough time to learn the concepts and prepare for the test. My study looked like this:

I studied for 2 months in total. On average, I spent 2-3 hours per day for 3-4 days per week. (Note that I’m recalling this information from 2 years ago, so YMMV.)
One month was dedicated to learning Kubernetes fundamentals. This included some hands-on work after conceptual learning to understand what the heck the YAML configuration files were doing.
The other month was dedicated to test preparation. The test itself is 2 hours long with 20 questions to live code. It’s open book to the kubernetes.io website. It’s a very short amount of time to complete the questions, so you have to know the materials AND be comfortable typing and editing on the terminal.
For extra credit to myself, I came across a GitHub repo for creating a Kubernetes cluster from scratch on a Raspberry Pi. Since I had a Raspberry Pi gathering dust in my home, I decided to try out the tutorial. It was a cool learning experience to know how simple it was to set it up.

Current study plan

My current study plan is:
Since I learned that the CKAD test will change at the end of September, my goal was to take the test a few days before that deadline. The CKAD exam offers a free retake if you fail the first time, so I left buffer room in case I’ll need to do a retake. This has given me roughly 3.5 weeks for studying.
I’ve spent around two weeks reviewing concepts and refreshing my brain on the syntax. 95% of the studying has been the latter - concepts don’t go away as quickly in my brain! I’ve spent around 1-2 hours per day for 5 days per week.
I plan to have the remaining week and change be dedicated to exam prep. The CKAD exam now offers 2 practice exam attempts through killer.sh. This would give me enough time to do practice exams and review.

There are a lot of resources I’ve used to prepare myself for the CKAD exam.
General resources
The CKAD certification website. For registrations, information, etc.
CNCF CKAD exam curriculum. An important resource for knowing what Kubernetes topics to focus on for the exam.
The official Kubernetes documentation website. It’s a really good reference by itself. The CKAD exam also allows you to use this website during the exam, you should also be familiar with it.
If you’re not familiar with Kubernetes
Docker Desktop. I installed Docker Desktop and enabled the Kubernetes settings, so I can practice CKAD exam questions on my laptop. I have the displeasure of having an older Windows laptop, so I’ve used Chocolatey and Windows Powershell to emulate a more Linux-like environment.
Docker getting started and Docker overview. Docker is a type of container that Kubernetes can manage. It’s not necessarily required to know about Docker, but it’s important to distinguish between the two.
Learn Kubernetes Basics tutorial. A “baby’s first” Kubernetes cluster. An interactive guide to learning about the basic components.
Kubernetes: Up and Running. I had a free subscription to O’Reilly, so I went through this book to learn Kubernetes concepts.
kelseyhightower/kubernetes-the-hard-way. Highly recommended for the CKA exam but not so much for the CKAD. Definitely recommend trying this if you have access to a Raspberry Pi, or want to try it out through cloud resources.
Exam prep
dgkanatsios/CKAD-exercises. My favorite GitHub repo for CKAD exam practice questions. My goal is to be able to run through the questions in less than 100 minutes.
bmuschko/ckad-prep. Another GitHub repo for CKAD exam practice questions.
twajr/ckad-prep-notes. Another GitHub repo for tips and tricks.
kubectl cheat sheet. A useful reference for learning Kubernetes terminal commands. Speed is key in this exam!
In addition, I went through a few tutorials learning about Vim and Bash. I’m comfortable with using Vim, but I’m quite rusty on Bash syntax. Learning both helps with getting comfortable with the terminal.
Finally, eating right and sleeping well before the exam always helps!
