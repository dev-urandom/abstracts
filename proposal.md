Raft for Learning Go
====
As a new user of a language, finding interesting problems to solve in order to
learn the language can be difficult. Choose a project too easy and you learn
nothing about the language. Choose a project too hard and you can make very
little progress.

Implementing Raft in Go is the perfect project to learn about both Go and
distributed systems. There is an excellent fit between Go's strengths and the
tools needed to build a successful Raft implementation. Furthermore, because
Raft is a protocol designed first and foremost to be understandable and
implementable.

In implementing Raft in Go, we developed a deeper understanding of Go's
concurrency model. And we developed a few
interesting techniques, particularly around test-driven development of a
distributed system in Go.


Test-driven development of Distributed systems.
====
In writing an implementation of the Raft consensus protocol, we extracted
several interesting patterns which we found interesting.

* Cluster Simulation
* Behavioral Style Testing
* Clock Control

