Summary
=======

Software engineer with a particular interest in large-scale
infrastructure and distributed systems, working on development through
to production.

Work Experience
===============

- San Francisco, CA\
Software Engineer\

-   Designed key aspects of the backing storage engine that enables
    iCloud to scale to hundreds of millions of users each month.

-   Architected the new multi-tenant online compaction system which
    provides higher throughput guarantees and reliability by
    distributing workloads over backend resources evenly.

-   Engineered a proactive solution to data loss prevention. Led to the
    discovery of several undiscovered, subtle bugs in the underlying
    frameworks and data store.

-   Vastly reduced database load by introducing a job framework that
    allows numerous scheduled jobs share the same pooled
    resources concurrently.

-   Languages / tools used: Scala, Java, Cassandra,
    MapReduce Frameworks.

- San Francisco, CA\
Software Engineer Intern\

-   Implemented network performance increases in Apache Spark that
    reduced traffic by over 90%.

-   Integrated Apache Avro as a first-class citizen into Spark core for
    use in RDDs.

-   Languages / tools used: Scala, Java, Apache Spark.

- New York, NY\
SRE Engineering Practicum Intern\

-   Implemented load testing infrastructure for newly released software,
    allowing for early detection of bugs and performance defects.

-   Reduced request latency for back-end monitoring services by 70%.

-   Languages / tools used: Java, Python Protocol Buffers, Google
    data stores.

- Seattle, WA\
Software Developer Engineer Intern\

-   Overhauled internal search capabilities for the Enterprise Data
    Warehouse team, allowing for near real-time searching for financial
    datasets and results.

-   Designed the new search system to be fault tolerant to preserve
    data integrity.

-   Languages / tools used: Java, various AWS products, including
    Cloud-Search and SNS.

Education
=========

- Rochester, NY\
Bachelors of Science in Computer Science\

Graduated *Cum Laude*

Skills & Certifications
=======================

Scala, Java, Python

C, Go, Rust

Git, Spark, Avro, Gradle, PostgreSQL, Cassandra, Protocol Buffers,
Thrift, OpenJDK JMH

Developed a solution to allow for Spark to efficiently read / write
Apache Avro data formats. Worked on features in the Spark SQL engine.

Self-Directed Projects Include
==============================

**Raft Key-Value Store**

-   Distributed key-value store that provides linearizability guarentees
    for all type of operations.

-   Out of the box support for leader election, transparent handling of
    failing nodes, and correctness under network partition.

**CRDT Distributed Tally Service**

-   Distributed backend counting service that is capable of withstanding
    large amounts of concurrent requests.

-   Uses G-Counters as the backing asynchronous replication model.

-   Utilizes a combination of lightweight threads for the request
    handling, Zookeeper for cluster state, and Thrift as the shared
    communication protocol.


