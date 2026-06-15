# Walmart Global Tech USA — Advanced Software Engineering Job Simulation

[![Language](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.java.com)
[![Topic](https://img.shields.io/badge/Architecture-UML%20%26%20ERD-0073B1?style=for-the-badge)](https://www.uml.org/)
[![Simulation](https://img.shields.io/badge/Simulated%20By-Forage-0071CE?style=for-the-badge)](https://www.theforage.com)

## 📌 Overview
This repository contains the enterprise-grade engineering deliverables completed during the **Walmart Global Tech USA Advanced Software Engineering Job Simulation**. The program involved tackling high-scale backend engineering challenges faced by Walmart’s core platforms, focusing heavily on **algorithmic optimization**, **distributed system architecture (UML)**, and **relational database modeling (ERD)**.

* **Verification Reference:** Program Completion Code: `KxPGdSEmEG2weCCeP` / `pfx986kDP2x89GLgq`

---

## 🛠️ Core Engineering Tasks & Deliverables

### 1. Algorithmic Optimization: Power-of-Two Max Heap
* **Problem Statement:** Walmart's high-throughput inventory and shipping pipelines require low-latency data structures. Traditional binary heaps ($2^n$) can introduce processing bottlenecks under massive, parallel reads and writes.
* **Solution Built:** Engineered a highly performant, generic **Power-of-Two Max Heap** data structure in Java. The data structure dynamically configures its branching factor as a power of two ($2^x$), significantly optimizing CPU cache locality and minimizing tree height for massive retail datasets.
* **Key Implementations:** 
  * Replaced costly arithmetic multiplication and division with high-performance bit-shifting operations (`index << x`) for rapid parent/child index lookups.
  * Overrode and optimized heapify-up and heapify-down mechanics to ensure strict $O(\log_d n)$ operational bounds.

### 2. Distributed System Architecture (UML)
* **Problem Statement:** Designing a resilient, decoupled, and asynchronous communication layer between Walmart's internal inventory tracking system and external shipping logistics fulfillment nodes.
* **Solution Built:** Modeled a comprehensive **UML Class Diagram** detailing the distributed system architecture. Defined strict component boundaries, explicit interface contracts, and secure access modifiers to gracefully handle high-volume transactional state changes when shipments are generated, updated, or dispatched.

### 3. Relational Database Modeling (ERD)
* **Problem Statement:** Structuring relational data efficiently to support a fast-growing retail ecosystem spanning entirely distinct logistical domains—specifically, the **Shipping Department** and the **Pet Department**.
* **Solution Built:** Architected a comprehensive **Entity-Relationship Diagram (ERD)** completely normalized to Third Normal Form (3NF).
* **Key Implementations:**
  * Created normalized transactional schemas capturing clear one-to-many ($1:N$) and many-to-many ($M:N$) enterprise relationships.
  * Incorporated strict foreign key constraints, indexing strategies for optimized primary lookups, and explicit cascading rules to enforce absolute data integrity across isolated department lines.

---

## 🚀 Key Technologies & Concepts Utilized
* **Languages & Runtimes:** Java (JDK 17+)
* **System Design & Modeling:** Unified Modeling Language (UML), Entity-Relationship Diagram (ERD)
* **Computer Science Core:** Data Structures & Algorithms (DSA), Custom Heaps, Cache Locality, Relational Database Normalization (3NF)

---

## 📂 Repository Organization
```text
├── 🧠 algorithmic-optimization/
│   ├── src/
│   │   └── PowerOfTwoMaxHeap.java       # Custom Java heap implementation
│   └── README.md                        # Analysis on time/space complexity bounds
│
├── 📐 system-architecture/
│   ├── diagrams/
│   │   ├── system_architecture_uml.png  # Visual UML Class Diagram export
│   │   └── database_schema_erd.png      # Visual 3NF ERD Design export
│   └── README.md                        # System architectural pattern justifications
