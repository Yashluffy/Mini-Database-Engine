# 🗄️ Mini Database Engine

**Mini Database Engine** is a lightweight, high-performance, and fully transactional embedded database system built in Java.  
It is designed to explore the fundamentals of **database architecture, data handling, and scalable storage systems**, offering an end-to-end understanding of how modern databases manage, store, and retrieve data efficiently.

---

## 🔍 Overview

The project focuses on building a **custom low-level database engine** capable of handling large-scale structured data through efficient **indexing, caching, and transaction management**.  
It mimics the core principles of industrial-grade systems such as **SQLite** and **RocksDB**, but with simplified and educationally transparent design choices — allowing clear insight into each component of a functioning storage engine.

Through this project, the goal is to design and optimize mechanisms that ensure **reliability, fault-tolerance, and performance** under concurrent operations.

---

## 🚀 Core Features

- **Efficient Storage Layer**  
  Implements a key-value store architecture using page-based file storage for compact and fast data persistence.

- **Indexing and Query Execution**  
  Supports ordered indexes to provide efficient query execution, data retrieval, and range queries using cursor-based traversal.

- **Transactional Operations**  
  Fully supports **ACID** properties with mechanisms for atomic commits, rollback, and isolation through record-level locking.

- **Concurrency and Locking**  
  Enables concurrent transactions using **upgradable locks** and **deadlock detection**, ensuring both safety and performance.

- **Cache and Memory Management**  
  Custom-configurable cache layer to optimize performance for different workloads, reducing disk I/O and improving throughput.

- **Durability and Fault Tolerance**  
  Offers multiple durability modes — including write-ahead logging and deferred flush — to balance performance and data reliability.

- **Cursors and Views**  
  Provides an efficient cursor-based interface for scanning data ranges, supporting prefix-based views and filtered queries.

- **Scalability and Extensibility**  
  Modular architecture that can be extended to simulate components of higher-level systems such as SQL or NoSQL databases.

---

## ⚙️ Technical Highlights

- **Language:** Java  
- **Core Concepts Implemented:** Indexing, Transaction Management, Locking Mechanisms, Query Execution, Data Caching  
- **Design Pattern:** Layered system with separate modules for storage, indexing, transactions, and caching  
- **Performance Optimization:**  
  - Memory-mapped file I/O  
  - Fixed-size cache configuration for predictable resource usage  
  - Batched write operations for reduced latency  

---

## 🎯 Learning Objectives and Motivation

The **Mini Database Engine** was developed to gain a deep, hands-on understanding of:
- How **low-level data storage systems** operate under the hood  
- The balance between **performance and data consistency** in real-world systems  
- The implementation of **transactional safety and isolation** using locks  
- The principles of **query optimization, indexing, and caching** that power scalable database backends  

This project serves as a strong foundation for working on **core database engineering, distributed systems, and backend optimization**, aligning perfectly with roles focused on **data handling, scalability, and high-performance computing** such as Amazon’s *Software Development Engineer – Database Intern*.

---

## 📚 Key Takeaways

- Built a fully functional embedded database capable of handling structured key-value data  
- Implemented efficient indexing, query execution, and transaction management mechanisms  
- Achieved high data reliability and scalability through modular, fault-tolerant design  
- Gained practical experience in writing performance-oriented, low-level system code  
- Developed a strong understanding of how **real-world databases** like MySQL, PostgreSQL, and LevelDB work internally  

---

## 👨‍💻 Author
**Yash Mahendia**  
*B.Tech, Mathematics and Computing — IIT Patna*  
Focused on **Data Systems, Scalable Storage, and Machine Learning Infrastructure**

---

> ⚡ *Mini Database Engine* — a simple yet powerful journey into the heart of database engineering.  
> Learn how systems handle data at scale — from indexing and transactions to durability and caching — all in one modular, educational project.
