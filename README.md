# Walmart Global Tech USA — Advanced Software Engineering Job Simulation

[![Language](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.java.com)
[![Topic](https://img.shields.io/badge/Architecture-UML%20%26%20ERD-0073B1?style=for-the-badge)](https://www.uml.org/)
[![Simulation](https://img.shields.io/badge/Simulated%20By-Forage-0071CE?style=for-the-badge)](https://www.theforage.com)

## 📌 Overview
This repository contains the engineering deliverables completed during the **Walmart Global Tech USA Advanced Software Engineering Job Simulation** via Forage. The project showcases programmatic solutions to real-world backend challenges faced by Walmart’s digital retail infrastructure, organized into four key production tasks.

* **Verification Reference:** Program Completion Code: `KxPGdSEmEG2weCCeP`

---

## 🛠️ Simulation Core Tasks

### 📂 Task 1: Advanced Data Structures (Algorithmic Optimization)
* **Objective:** Address high-throughput latency bottlenecks in Walmart's core fulfillment systems caused by standard binary data structure limits under heavy parallel operations.
* **Implementation:** Engineered a generic, highly performant **Power-of-Two Max Heap** in Java. Configured dynamic branching factors ($2^x$) to optimize memory cache locality and reduce lookup tree depth.
* **Optimization:** Replaced arithmetic computations with fast bit-shifting operations (`index << x`) to streamline child and parent index traversal.

### 📂 Task 2: Software Architecture (Distributed System Design)
* **Objective:** Map a resilient, decoupled communication layer connecting internal inventory processing databases with external logistics and shipping nodes.
* **Implementation:** Designed a detailed **UML Class Diagram** defining component boundaries, interface contracts, and access modifiers to securely handle high-volume transactional state changes asynchronously.

### 📂 Task 3: Relational Database Design (Data Modeling)
* **Objective:** Structure relational schemas efficiently to store data across independent corporate ecosystems—specifically handling logistics for the Shipping and Pet departments.
* **Implementation:** Architected an **Entity-Relationship Diagram (ERD)** normalized to Third Normal Form (3NF). Created robust transactional tables establishing clean $1:N$ and $M:N$ relationships featuring strict foreign key indexing and cascading rules.

### 📂 Task 4: Data Munging (Pipeline Processing)
* **Objective:** Process, clean, and manipulate raw transactional streams to prepare disparate corporate datasets for downstream production analytics pipelines.
* **Implementation:** Developed data transformations to parse input logs, handle missing values, map schema fields correctly, and ensure data uniformity before target ingestion.

---

## 🚀 Technical Framework & Core Concepts
* **Languages & Scripting:** Java (JDK 17+)
* **System Design & Modeling:** Unified Modeling Language (UML), Entity-Relationship Diagram (ERD)
* **Computer Science Core:** Data Structures & Algorithms (DSA), Cache Locality, Relational Database Normalization (3NF), Data Preprocessing & Munging

---

## 📂 Repository Layout
* `/Task 1 Advanced Data Structures` — Source code, edge cases, and performance logic for the custom heap.
* `/Task 2 Software Architecture` — Visual exports of the UML Class Diagrams and architectural contracts.
* `/Task 3 Relational Database Design` — Entity-Relationship model mapping out the 3NF schema.
* `/Task 4 Data Munging` — Pipeline scripts handling dataset wrangling and processing.
* `Completion_Certificate.pdf` — Official program completion document.

---
*Disclaimer: This project was completed as part of an officially authorized, executive-recognized job simulation designed by Walmart Global Tech to mirror real-world engineering workflows.*
