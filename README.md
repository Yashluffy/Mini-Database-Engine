# 🗄️ Mini Database Engine

**Mini Database Engine** is a lightweight, high-performance, transactional, and scalable embedded database system.  
It is designed to efficiently handle large-scale data storage, indexing, and transaction management — ideal for learning and experimentation in database internals.

---

### 🚀 Key Features
- Record-level locking and concurrency control  
- ACID-compliant transactions  
- Index-based data retrieval (ordered key-value mappings)  
- Custom cache configuration for optimized performance  
- Supports cursors for fast sequential access  
- Fault-tolerant and durable with configurable persistence modes  
- Compression, replication, and hot backup support  
- Designed for scalability and low-latency data access  

---

### ⚙️ Getting Started

#### **1. Open a Non-Durable Database**
```java
var config = new DatabaseConfig().maxCacheSize(100_000_000);
Database db = Database.open(config);
