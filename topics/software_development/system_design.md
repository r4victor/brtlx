Name: System design
Status: published

## Description

In software development, **system design** (a.k.a. **systems design**) is the description of system's architecture, components, and interfaces that aim to meet specific requirements. When you develop a web application, split it into modules, define APIs, choose the data storage and processing stack, wire together cloud services that make up the infrastructure – when you do these things, you do system design.

System design often refers specifically to the design of scalable, distributed systems like Google or Dropbox. As such, the central questions typically considered are what computing and data storage and processing technologies to use and how to wire them together to achieve scalability, availability, and fault tolerance. This touches upon topics studied in the fields of [databases](/topics/databases/) and distributed systems: replication, partitioning, consistency and consensus. System design is the practical application of those studies that is also concerned with many other topics like networking, security, and cost-effectiveness.

"How would you design X?" is a popular kind of interview question for software engineering positions. The interviewer may ask to design a service the company has worked on, and that can lead to a fruitful discussion representative of the real working process. Or the interviewer may ask to design a popular service like Twitter to save time on listing the requirements and exercise candidate's system design skills. You'll see a lot of system design resources aimed specifically to grok interview questions.

With the advent of cloud computing, the knowledge of services offered by cloud providers like [AWS](/topics/aws/) became crucial for system design. Today, you probably won't build your own infrastructure and are less likely to host your own services and instead use managed, auto-scalable, and serverless solutions provided by the cloud. To be good at system design, you need less and less fundamental knowledge of distributed systems and more and more understanding of cloud providers' quirks and best practices.

Related topics: [AWS](/topics/aws/), [Computer networks](/topics/computer-networks/), [Databases](/topics/databases/).

## Resources

[Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
paid • book • by Martin Kleppmann • 2017-03-01
This book is universally considered a must read for software engineers (and a very enjoyable one). It explores diverse space of technologies for processing and storing data: relational and NoSQL databases, search indexes, message queues, batch and stream processing frameworks, and more. You'll be better at deciding which technologies to use for a particular application and you'll learn how to meet key challenges in the design of distributed systems that arise with replication and partitioning.

[The Architecture of Open Source Applications](http://aosabook.org/en/index.html)
free • book • series • 2016-07-29
This is a book in four parts in which the authors of open source applications explain how their software is structured. Volume 1 and Volume 2 include chapters on the design of LLVM, Bash, GHC, nginx, PyPy, and other popular projects. The third book focuses on building performant applications. The 500 Lines or Less book is about design decisions that programmers make when they are building something new from scratch.

[System Design Primer](https://github.com/donnemartin/system-design-primer)
free • resource • by Donne Martin
This repo is a high-level guide to designing large-scale systems and a collections of materials to prepare for a system design interview. It lists main system design topics, provides a system design interview questions with solutions, and contains a lot of useful references for further study.

[AWS re:Invent 2019: Scaling up to your first 10 million users](https://www.youtube.com/watch?v=kKjm4ehYiMs)
free • video • by Brian Farnhill, Hong Pham • 2019-12-07
This talk will walk you through the evolution of a typical AWS infrastructure that powers a web application as it grows from one user to thousands and millions of users. You'll learn about which AWS services you should start with, how to scale your app with auto-scaling and workload shifting, and when to go serverless.

[CNCF Landscape](https://landscape.cncf.io/)
free • resource • by CNCF
This is a catalog of widely used and emerging open-source and proprietary technologies for building cloud-native applications – tools for automation & configuration, container runtimes, container orchestration, message brokers, databases, monitoring, CI/CD, and other major components of a modern tech stack. Check out the [CNCF Landscape Guide](https://landscape.cncf.io/guide) for a gentle introduction to each category of tools.
