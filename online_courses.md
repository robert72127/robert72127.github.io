---
layout: post
title: "System programming courses"
permalink: /online-courses/
---

I care a lot about open education. This page collects online courses and companion resources that I think are useful for students who want a stronger systems background, but did not have access to a university with a deep systems curriculum.

In general, if your university offers a good version of these subjects, take it. You will usually get better structure, and accountability. But many schools do not put much emphasis on systems programming. In that case, the resources below are very good substitutes.

## Linux and beginner tooling

### The Missing Semester of Your CS Education [link](https://missing.csail.mit.edu/)

Very good starting point if you are early in your programming journey. It teaches practical tools that make everyday work on Unix like systems much easier: shell usage, editors, version control, debugging, data wrangling, and automation.

## Computer architecture and systems

### 15-213 / 14-513 / 15-513: Introduction to Computer Systems [link](https://www.cs.cmu.edu/~213/)

One of the best entry points into systems programming. It covers the stack from machine representation and assembly to memory, linking, performance, and user-space Unix programming. If you only take one serious systems course, this is a very strong choice.

Course labs: [link](https://csapp.cs.cmu.edu/3e/labs.html)

For lectures, archived course pages are often the easiest route. If the main page does not expose a full past offering directly, check the Web Archive for a recent year such as 2023. Some lecture materials and mirrors also show up on GitHub, so it is worth checking there too.

Companion book: *Computer Systems: A Programmer's Perspective* [link](https://www.amazon.com/Computer-Systems-Programmers-Perspective-3rd/dp/013409266X)

Another useful companion resource is the Illinois CS 241 system programming coursebook [link](https://raw.githubusercontent.com/illinois-cs241/coursebook/pdf_deploy/main.pdf). It explains many core systems topics in a very approachable way.

## Computer networks

### Beej's Guide to Networking Concepts [link](https://beej.us/guide/bgnet0/)

Very accessible introduction to networking ideas if you do not yet have a strong intuition for protocols, addressing, and how machines talk to each other.

### Beej's Guide to Network Programming [link](https://beej.us/guide/bgnet/)

One of the best practical introductions to socket programming. It helps bridge the gap between networking theory and writing real networked programs in C.

Recommended companion textbook: *Computer Networking: A Top-Down Approach* [link](https://www.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)

A good starter project after this material is a simple web server in C or C++, beginning with raw TCP sockets and working up to basic HTTP static file serving.

## Database systems

### CMU 15-445 / 15-645: Database Systems [link](https://15445.courses.cs.cmu.edu/)

This is one of the best systems courses available online and a very good next step after an introductory computer systems course. You work on BusTub, an educational database system, and implement core pieces of a real database engine.

The course combines strong lectures, very good slides, and substantial programming assignments.

The main link points to the newest offering. If you want full version with all lectures, slides, and assignments available, it is better to pick a past offering from the course archive.

If you want to go further, the advanced follow up is CMU 15-721 [link](https://15721.courses.cs.cmu.edu/).

If you want to learn about LSM-tree-based storage engines and want a practical Rust project, `mini-lsm` is also worth a look [link](https://github.com/skyzh/mini-lsm).

## Compilers

### Writing a C Compiler [link](https://nostarch.com/writing-c-compiler)

I do not have one definitive public course recommendation for compilers. In my case, I took the subject at university. Public compiler courses often have lectures without accessible projects.

This book is the best practical resource I would suggest. Its strength is that it builds a compiler incrementally, so you can make steady progress without needing to understand the entire pipeline up front.

For language context, here is the Xi language handout that inspired the compiler course I took [link](https://www.cs.cornell.edu/courses/cs4120/2011fa/handouts/language.pdf).

## Operating systems implementation

### NYCU Operating System Capstone

Many operating systems courses have public lectures, but very few make the implementation side accessible to outsiders. The labs focus on building a small operating system, which makes this course very valuable.

Useful companion resources:

Arm peripherals reference [link](https://cs140e.sergio.bz/docs/BCM2837-ARM-Peripherals.pdf)

Bare-metal Raspberry Pi 3 tutorials [link](https://github.com/bztsrc/raspi3-tutorial/tree/master)

## Parallel programming

### 15-418 / 15-618: Parallel Computer Architecture and Programming

Good course for learning how modern hardware exposes parallelism and how software can take advantage of it. Expect topics such as SIMD, GPU programming, and distributed approaches like MPI.

Slides and labs are often easiest to find through archived course pages or public mirrors of past offerings. 2023 version is good start. GitHub mirrors sometimes also preserve assignment material.

## Distributed systems

### MIT 6.824: Distributed Systems [link](http://nil.csail.mit.edu/6.824/2022/)

One of the most famous distributed systems courses. The lectures and labs are strong: you implement the Raft consensus protocol and then build key/value storage on top of it.

## Deep learning systems

### Deep Learning Systems [link](https://dlsyscourse.org/)

Strong course on the implementation side of machine learning systems. It focuses on the building blocks behind deep learning frameworks.

The labs are especially useful because they let you implement core components yourself.

### CS336: Language Modeling from Scratch [link](https://cs336.stanford.edu/)

A more advanced course focused on the systems and engineering required to train modern language models. Public labs cover topics such as tokenization, kernels, training, distributed execution, data preparation, and reinforcement learning.

Good option once you already have a foundation in machine learning.

## Other resources worth mentioning

### HDLBits [link](https://hdlbits.01xz.net/wiki/Problem_sets)

Small hands-on exercises for learning Verilog and getting comfortable with hardware-description languages.

### Unraveling the JPEG [link](https://parametric.press/issue-01/unraveling-the-jpeg/)

A very readable explanation of how JPEG compression works.

### Web Browser Engineering [link](https://browser.engineering/)

A project-oriented resource that walks through building a small browser and teaches you about parsing, layout, networking, and rendering along the way.

### Building a Debugger [link](https://nostarch.com/building-a-debugger)

A practical systems project in book form. Good if you want to understand breakpoints, symbol information, and low-level program inspection.

### Containers from Scratch [link](https://blog.lizzie.io/linux-containers-in-500-loc.html)

A compact introduction to Linux containers through implementation.
