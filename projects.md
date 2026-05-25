---
layout: post
title: "Projects"
permalink: /projects/
---

#### AliceDB

Alicedb is incremental in process database library for C++, that works by executing transformations on changes in streaming model.

Supports many core operations : projecion, filter, union, except, intersect, join product, distinc, aggregation

Persistent storage, bufferpool with io uring, 
internaly consiset via timestamps

#### rpiOS
Operating system designed for the Raspberry Pi 3b+, targeting the ARMv8-A (AArch64) architecture.

Features:
Virtual Memory
Interrupts handling
Process scheduling
Read only file syste

Still lacks many importannt stuff like more syscall signal handling and multicore support

link:  https://github.com/robert72127/rpiOS


#### Inference engine
LLMs serving engine

Supported model:

qwen2_5_0_5b_instruct
Supported backends:
cpu
cuda

Radix kv cache
chunked prefill, continous batching
Multi process with communication via zmq

Fast api server GET /v1/models
POST /v1/chat/completions

link https://github.com/robert72127/inference_engine

#### Raft Consensus Algorithm 
    * Distributed consensus algorithm written in GO
    * Replicated state machine.
    * Leader election.
    * Log replication.

https://github.com/robert72127/raft

#### Deep learning framework
    * Cpu only deep learning framework using numpy as backend.
    * Autograd on N-dimensional Matrices.
    * SGD with momentum and Adam optimizers.
    * Dataloader
    * Custom weight initialization.


#### Diffusion model for image denoising
    * Writen as 3 person, team project for deep learnign course.
    * I was responsible for implementing sampling algorithm based on sciencific papers.
    * Trained model on google cloud using TPU's

link https://github.com/bullyhunter1917/DDRM

https://github.com/robert72127/simple_dl

#### Xi compiler
    * Lexer and parser in ocamllex and menhir.
    * Bidirectional typechecker.
    * Codegenerator translating AST into intermediate low level language.
    * Register allocation algorithm that allow languange to be executed on real architecture with finite amount of registers.
    * Live variable analysis optimalization.

since this was done as university project its not available publicly

#### Other smaller projects:
* HTTP Webserver serving static files in pure c
* Simple unix shell
* Linked-list based Malloc
* Traceroute
* Few linux device drivers
* Map-reduce algorithm implemenation in go 
