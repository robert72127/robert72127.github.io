---
layout: post
title: "Projects"
permalink: /projects/
---

#### AliceDB [link](https://github.com/robert72127/alicedb)

* Alicedb is incremental in process database library for C++, that works by executing transformations on changes in streaming model.
* Supports many core operations: projection, filter, union, except, intersect, join, product, distinct, aggregation.
* Persistent storage and bufferpool with io_uring.
* Internaly consiset via timestamps.

#### rpiOS [link](https://github.com/robert72127/rpiOS)

* Operating system primitives for the Raspberry Pi 3b+, targeting the ARMv8-A (AArch64) architecture.
* Virtual memory.
* Interrupts handling.
* Process scheduling.
* Read only file system.
* Still lacks many importannt stuff like more syscall, signal handling and multicore support.


#### Inference engine [link](https://github.com/robert72127/inference_engine)

* LLMs serving engine.
* Supported model: qwen2_5_0_5b_instruct.
* Supported backends: cpu, cuda.
* Radix kv cache.
* Chunked prefill, continous batching.
* Multi process with communication via zmq.
* Fast api server with `GET /v1/models` and `POST /v1/chat/completions`.

#### Raft Consensus Algorithm [link](https://github.com/robert72127/raft)

* Distributed consensus algorithm written in GO
* Replicated state machine.
* Leader election.
* Log replication.

#### simple dl [link](https://github.com/robert72127/simple_dl)

* Cpu only deep learning framework using numpy as backend.
* Autograd on N-dimensional Matrices.
* SGD with momentum and Adam optimizers.
* Dataloader
* Custom weight initialization.

#### Diffusion model for image denoising [link](https://github.com/bullyhunter1917/DDRM)

* Writen as 3 person, team project for deep learnign course.
* I was responsible for implementing sampling algorithm based on sciencific papers.
* Trained model on google cloud using TPU's

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
