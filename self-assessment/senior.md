# Senior C++ Developer — Self‑Assessment Checklist

## Scoring Template

For each section, score yourself:
0 - No experience
1 - Basic understanding
2 - Can apply with guidance
3 - Independent and reliable
4 - Advanced; can work independently and mentor others
5 - Expert; Language Guru level


## C++ Skills

### Language Fundamentals
* [ ] I fully understand value categories (lvalue/xvalue/prvalue) and how they affect overload resolution
* [ ] I can explain and correctly use move semantics and perfect forwarding
* [ ] I can predict when RVO/NRVO will or will not occur
* [ ] I can design APIs that avoid unnecessary copies and allocations.
* [ ] I understand reference collapsing rules and forwarding references
* [ ] I can write constexpr code and know when it is beneficial

### Templates & Metaprogramming
* [ ] I know when to use templates and when not to
* [ ] I understand CRTP and can apply it to static polymorphism
* [ ] I can write SFINAE‑based optimization, detection idioms or use std::void_t
* [ ] I can write or understand type traits and compile‑time computations
* [ ] I can design templated code with good error messages (using static_assert, concepts, or SFINAE)

### Standard Library
* [ ] I know the performance characteristics of all major containers.
* [ ] I understand allocators and can implement custom ones if needed.
* [ ] I know how to efficiently use standard library algorithms and understand their complexity guarantees
* [ ] I understand ranges, views, and lazy pipelines

### Systems Programming & Performance
* [ ] I understand stack vs heap, alignment, padding, cache lines, and false sharing.
* [ ] I can diagnose memory corruption and memory leaks using tools like Valgrind or AddressSanitizer
* [ ] I can design memory pools, arenas, or custom allocators when needed
* [ ] I understand how CPU caches influence data structure design

### Concurrency & Parallelism
* [ ] I can write multithreaded code using threads, futures & stop tokens
* [ ] I understand the C++ memory model: sequencing, happens-before, and data race rules
* [ ] I know when to use atomics, memory orders, and fences
* [ ] I can explain the difference between lock-free and wait-free structures
* [ ] I understand meaning of SPSC, SPMC, MPSC & MPMC
* [ ] I can design a thread-safe queue
* [ ] I can design thread pools and async pipelines
* [ ] I can find deadlocks and race conditions using sanitizers

## Software Engineering Skills

### Software Architecture & API Design
* [ ] I can design APIs that are stable, minimal, and expressive.
* [ ] I can choose appropriate error models:
  * [ ] exceptions
  * [ ] status codes
  * [ ] std::expected
* [ ] I understand layering, dependency management, and ABI stability
* [ ] I can apply design patterns appropriately (not dogmatically)
* [ ] I can design scalable and maintainable systems
* [ ] I understand layered, microservices, and event-driven architecture patterns
* [ ] I can evaluate performance considerations and trade-offs at system level
* [ ] I can debug and profile complex systems at system level

### Testing & Quality
* [ ] I can design unit tests using GoogleTest or Catch2
* [ ] I can write fuzz tests using libFuzzer or AFL++
* [ ] I can benchmark code using Google Benchmark
* [ ] I can perform high‑quality code reviews with actionable feedback
