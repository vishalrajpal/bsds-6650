# Week 10: Strong Consistency and Distributed Databases

## Learning Objectives

1. Explain how 2 phase commit works and how it handles failures
2. Explain the implications of the FLP result
3. Describe the Raft consensus algorithm
4. Explain causal consistency in Neo4j

## Mandatory Lecture Materials

Slides are on Canvas.

Video lessons for the materials  are [here](https://sites.google.com/view/scalability/lessons)

## Mandatory Reading

1. Chapter 12 of course book
2. Chapter 9, Designing Data-Intensive Applications, Martin Kleppmann, O'Reilly Publishing (available online at Snell library)

## Optional Reading

1. Chapter 7, Designing Data-Intensive Applications, Martin Kleppmann, O'Reilly Publishing (available online at Snell library)
2. [Raft versus Paxos from MIT Lecture Series](https://www.youtube.com/watch?v=9QGGB5sCr1g)
3. [Raft Features in MongoDB](https://www.youtube.com/watch?v=jCk0FCbqCz0)

## Labs

**Class Exercises:** 
Work through the Raft explanation [here](http://thesecretlivesofdata.com/raft/) and make sure you understand how the protocol works.

Install Redis on EC2. The Quickstart is [here](https://redis.io/topics/quickstart).

More install instructions on AWS Linux are [here](https://shawn-shi.medium.com/how-to-install-redis-on-ec2-server-for-fast-in-memory-database-f30c3ef8c35e) or if Medium access is painful [here](https://www.phaedrasolutions.com/blog/setup-redis-on-aws).

Choose and test a Redis Java client from [here](https://redis.io/clients#java). [Jedis](https://github.com/redis/jedis) is popular,

[Back to Course Home Page](https://gortonator.github.io/bsds-6650/)
