Name: Concurrent programming
Status: published

## Description

**Concurrency** is the ability of a program to deal with multiple things simultaneously. For example, a browser that downloads files while rendering pages and doing million other things at the same time is a highly concurrent program. Concurrent computations may happen at the same physical time – this is called **parallelism** – it improves overall speed of execution. Concurrent computations can also happen in an interleaved manner: a CPU runs one task for some time, then runs another task, then continues with the first one from where it stopped. Programs use this approach to improve responsiveness and to do more things simultaneously than the number of available CPU cores.

Links: [Concurrency (Wikipedia)](https://en.wikipedia.org/wiki/Concurrency_(computer_science)), [Concurrent computing (Wikipedia)](https://en.wikipedia.org/wiki/Concurrent_computing).

## Resources

[Seven Concurrency Models in Seven Weeks](https://pragprog.com/titles/pb7con/seven-concurrency-models-in-seven-weeks/)
paid • book • by Paul Butcher • 2014-07-01
This book is an excellent survey of different approaches to concurrency and parallelism: traditional threads and locks, functional programming, Clojure's separation of identity and state, the actor model, Communicating Sequential Processes (CSP), data parallelism, and the Lambda Architecture.

[Java Concurrency in Practice](https://www.amazon.com/dp/0321349601)
paid • book • by Brian Goetz, Tim Peierls, Joshua Bloch, and others • 2006-05-09
This book is the best guide on concurrent programming with threads. It covers threads-and-locks fundamentals, concurrent collections, the producer-consumer pattern, and thread pools among other things, and gives a lot of practical advice on how to design, test, and debug multithreaded programs. Despite being focused on Java 5, the content applies to any other language and remains very much relevant today.
