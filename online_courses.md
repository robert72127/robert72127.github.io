---
layout: post
title: "Online courses"
author: "Robert"
permalink: /books/
---


I am big believer in open education
here are list of courses online that I did, I think are very good and will broaden your horizons in given subjects.
From my & collegues experience it's generally better to pick courses at your uni, 
hovewer many universities don't focus that much on system programming and don't offer such courses
or if you are from non traditional background

# Linux & beginner tooling:
The Missing Semester of Your CS Education
https://missing.csail.mit.edu//

teaches you how to use tooling that will make you more productinve & you will find usefull in your everyday tasks as programmer

# Computer Architecture:

15-213/14-513/15-513: Introduction to Computer Systems

https://www.cs.cmu.edu/~213/

Intensive introduction to computer systems

teaches you stuff from assembly to user space linux programming,

labs can be found at 
https://csapp.cs.cmu.edu/3e/labs.html

and lectures are accessible via web archive (for example 2023 edition), they probably also can be found on github


there is also very good acommpanion book that i highly recommend buying
Computer Systems: A Programmer's Perspective
https://www.amazon.com/Computer-Systems-Programmers-Perspective-3rd/dp/013409266X

Another cool book explaining the topics of system programming by students from university of Illinois, can be found at (link)[https://raw.githubusercontent.com/illinois-cs241/coursebook/pdf_deploy/main.pdf]

 # Parallel Programming

15-418/15-618: Parallel Computer Architecture and Programming

slides and labs can be accesed via web archive, for example 2023 edition, they probably also can be found on github

Theaches you concepts like simd, mpi, programming cuda

## Operating Systems implementation:

* nycu Operating System Capstone

Operating systems are very important subject in CS & CE, there are lectures on this subject available from many unis online, but most of them don't have labs accesible for people outside.

Labs focuses on building small operating system, very cool

If you decide to pursue this course, here are usefull additional resources:
Arm peripherals[link](https://cs140e.sergio.bz/docs/BCM2837-ARM-Peripherals.pdf)
Bare metal raspberry pi 3 tutorials [link](https://github.com/bztsrc/raspi3-tutorial/tree/master)

# Distributed systems:

* MIT 6.824: Distributed Systems

nice lectures, can be found on youtube, publicly available labs where you implement raft consesus protocol and later build K/V storage on top of that

http://nil.csail.mit.edu/6.824/2022/

# Database Systems

The GOAT of database courses, it's also excellent pick for one of few first system programming courses you might want to take after you already finish introduction to computer systems (link)[https://www.cs.cmu.edu/~213/]

You will work on existing system called bustub, there you will implement core parts of database engine
Submission is also available for people outside of CMU which is really nice.

This course also has one of best slides, highly recommed

https://15445.courses.cs.cmu.edu/

note: this link will point to the newest offering but if you want to complete past one cause maybe labs or lecture aren't accesible yet, there is archive page with past offerigs

If you find database systems interesting, after that you might want to also take a look at 
https://15721.courses.cs.cmu.edu/ which is advanced continuation

If you want to also learn how lsm-tree based databases work, and like programming in rust or you are looking for some project to start your jurney with this language
https://github.com/skyzh/mini-lsm is worth checking too


# Compilers

This is one of core topics that i don't actually have one definitive resource, as in my case the course was actually ofered in my uni where we wrote compiler for źi which is modifiex [xi compiler](https://www.cs.cornell.edu/courses/cs4120/2011fa/handouts/language.pdf)

Also despite my best efforts i wasn't able to find good course that offered publicly accesible lectures.
However there is really cool book from nostarch press that is about building C compiler.
I only scrolled the book but i really like their approach where you build all parts in incremental way.
Book can be bought here (link)[https://nostarch.com/writing-c-compiler]


# Computer Networks

great starter are beej guides

(Beej's Guide to Networking Concepts
)[https://beej.us/guide/bgnet0/]

(Beej's Guide to Network Programming
)
[https://beej.us/guide/bgnet/]


Book
https://www.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/


As a project good idea would be to implement simple web server in c/c++ from tcp sockets up to htpp serving

# Deep learning systems

Deep Learning Systems CMU

teaches you basic building blocks of deep learning framework

In labs you will learn how to implement such system yourself

https://dlsyscourse.org/


CS336: Language Modeling from Scratch

more advanced course focusing on core parts of building blocks of modern LLM training,

publicly available labs focus on tokenization, training, kernels, distributed traing, data preparation and reinforcement learning

https://cs336.stanford.edu/

# other topics worth mentioning

HDL bits introduction to verilog through small online exercises  https://hdlbits.01xz.net/wiki/Problem_sets

JPEG : https://parametric.press/issue-01/unraveling-the-jpeg/

https://browser.engineering/

buliding debugger https://nostarch.com/building-a-debugger

containers https://blog.lizzie.io/linux-containers-in-500-loc.html