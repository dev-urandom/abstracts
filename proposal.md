## Raft for Learning Go

### Description

As a new user of a language, finding interesting problems to solve in order to
learn the language can be difficult. Choose a project too easy and you learn
nothing about the language. Choose a project too hard and you can make very
little progress.

Raft is a consensus protocol developed by Diego Ongaro and John Ousterhout at Stanford
University. One of the stated design goals for Raft is to be easy to understand and
implement. This makes it a perfect pedagogical project. It is understandable, but it is
also a meaty problem and implementations can be used in real production systems.

Go is well suited to the problems presented in implementing Raft. Channels and goroutines
provide sensible and intuitive tools for managing currency.

Because of the fit between Go's strengths and Raft's focus on understandability, Raft makes
an excellent first "real" project for learners of Go.

In implementing Raft in Go, we developed a deeper understanding of Go's
concurrency model. And we developed a few
interesting techniques, particularly around test-driven development of a
distributed system in Go.

In this talk, we will share our experiences in implementing this protocol. We will focus on the protocol itself, challenges we experienced implementing it, and some of the interesting patterns we discovered and extracted.

### Notes to the Planning Committee

As the rate of new users coming to Go increases, it will become more and more important
to think about how these new users increase their skills with this language.

## Test-driven development of Distributed systems.

### Description

In writing an implementation of the Raft consensus protocol, we extracted
several interesting patterns which we found interesting.

* Cluster Simulation
* Behavioral Style Testing
* Clock Control

### Notes to the Planning Committee

todo

## Building Distributed Systems in Go for Fun and Relaxation.

### Description

Over the past few years development and research of distributed systems has
dramatically increased. While there are many reasons why developing distributed
systems is challenging, two interesting challenges are how to decompose the system
so it's reliable and ensure all possible failures are accounted for. Using Go
to build distributed systems provides advantages for both of these challenges.

While implementing the consensus protocol Raft we discovered a number of valuable
properties that Go has for distributed system development. Such as building a
test harness using Go's concurrency primitives to exercise the system in a number
of failures states by emulating partitions. In this session we will walk through
some of the challenges we faced while implementing Raft and how Go helped us
solve them.

### Notes to the Planning Committee

todo
