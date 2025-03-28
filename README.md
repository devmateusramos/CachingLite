# CachingLite

CachingLite is an open-source caching and SQLite database built on top of SQLite, written in Rust. It aims to deliver a highly optimized solution that balances memory usage with file reads, combining the full functionality of SQLite with advanced caching in a single library. The project is designed to be highly performant by dynamically managing the trade-off between loading data from memory or files, targeting offline-first applications like desktop and mobile, with plans to eventually support distributed systems.

## Vision
The vision of CachingLite is to provide a seamless, performant caching database that integrates SQLite’s persistence with an optimized caching layer. By offering both caching and SQLite functionalities in one library, it enables developers to leverage:

Dynamic Trade-off Optimization: Intelligent decisions on when to fetch data from memory (for speed) or from files (for persistence).

High Performance: A solution that maximizes efficiency and minimizes latency.

Ease of Use: A unified interface for caching and database operations.

The goal is to create a tool that excels in resource management while retaining all the powerful features of SQLite, making it a go-to choice for applications requiring fast, reliable data access.

## Current Status
CachingLite is in its early stages of development. The current focus is on building a foundational caching layer, similar to Redis, which will later be optimized and integrated with SQLite. This initial step sets the stage for implementing the trade-off mechanisms and performance enhancements that will define the project.

## Planned Features
Unified Caching and SQLite: A single library that combines caching with SQLite’s full feature set, simplifying data management.

Optimized Trade-off Management: Algorithms that dynamically decide whether to serve data from an in-memory cache or query the SQLite database, balancing performance and resource usage.

High Performance: Low-latency, high-throughput access tailored for demanding applications.

Offline-First Focus: Ideal for desktop and mobile apps that need robust data access without network reliance.

Future Distributed Systems: Plans to scale the solution for high-performance distributed environments.
