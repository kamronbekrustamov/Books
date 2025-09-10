# Algorithms and Data Structures for Massive Datasets

> This repository contains a summary of the key concepts and algorithms for processing massive datasets. The notes are organized by chapter and subchapter, following the structure of a typical course on this topic.

---

## Book Summary

This book provides a comprehensive overview of the algorithms and data structures that are essential for working with massive datasets. It covers the challenges of scale (the "3 Vs": Volume, Velocity, and Variety), the importance of the memory hierarchy, and the trade-offs between accuracy, space, and time.

The book then dives into the core techniques for handling massive datasets, including:

*   **Hashing:** The foundation of many big data algorithms, including hash tables, consistent hashing, and probabilistic data structures.
*   **Probabilistic Data Structures:** Space-efficient data structures like Bloom filters, Quotient filters, Count-Min Sketch, and HyperLogLog, which provide approximate answers to common questions with provable error bounds.
*   **Streaming Algorithms:** Techniques for processing data in a single pass with limited memory, including methods for sampling and finding quantiles.
*   **External Memory Algorithms:** Algorithms and data structures that are optimized for datasets that are too large to fit into main memory, such as external sorting and B-Trees.
*   **Modern Data Structures:** An exploration of the data structures that power modern databases, including B-Trees and Log-Structured Merge-Trees (LSM-Trees).

---

## Table of Contents

### Part 1: Hash-based Sketches

*   **Chapter 1: Introduction**
    *   [1.1 Challenges of scale](./Chapter%2001%20-%20Introduction/1.1%20-%20Challenges%20of%20scale.md)
    *   [1.2 The memory hierarchy](./Chapter%2001%20-%20Introduction/1.2%20-%20The%20memory%20hierarchy.md)
    *   [1.3 Trade-offs](./Chapter%2001%20-%20Introduction/1.3%20-%20Trade-offs.md)
    *   [1.4 Introduction to probabilistic data structures](./Chapter%2001%20-%20Introduction/1.4%20-%20Introduction%20to%20probabilistic%20data%20structures.md)
*   **Chapter 2: Review of hash tables and modern hashing**
    *   [2.1 Review of fundamental hash table concepts](./Chapter%2002%20-%20Review%20of%20hash%20tables%20and%20modern%20hashing/2.1%20-%20Review%20of%20fundamental%20hash%20table%20concepts.md)
    *   [2.2 Advanced hashing methods for uniform data distribution](./Chapter%2002%20-%20Review%20of%20hash%20tables%20and%20modern%20hashing/2.2%20-%20Advanced%20hashing%20methods%20for%20uniform%20data%20distribution.md)
*   **Chapter 3: Approximate membership: Bloom and quotient filters**
    *   [3.1 Bloom Filters](./Chapter%2003%20-%20Approximate%20membership%20Bloom%20and%20quotient%20filters/3.1%20-%20Bloom%20Filters.md)
    *   [3.2 Quotient Filters](./Chapter%2003%20-%20Approximate%20membership%20Bloom%20and%20quotient%20filters/3.2%20-%20Quotient%20Filters.md)
*   **Chapter 4: Frequency estimation and count-min sketch**
    *   [4.1 Count-Min Sketch](./Chapter%2004%20-%20Frequency%20estimation%20and%20count-min%20sketch/4.1%20-%20Count-Min%20Sketch.md)
*   **Chapter 5: Cardinality estimation and HyperLogLog**
    *   [5.1 HyperLogLog](./Chapter%2005%20-%20Cardinality%20estimation%20and%20HyperLogLog/5.1%20-%20HyperLogLog.md)

### Part 2: Real-time Analytics

*   **Chapter 6: Streaming data: Bringing everything together**
    *   [6.1 The streaming model of computation](./Chapter%2006%20-%20Streaming%20data%20Bringing%20everything%20together/6.1%20-%20The%20streaming%20model%20of%20computation.md)
    *   [6.2 Challenges of single-pass data processing](./Chapter%2006%20-%20Streaming%20data%20Bringing%20everything%20together/6.2%20-%20Challenges%20of%20single-pass%20data%20processing.md)
    *   [6.3 Combining various streaming techniques](./Chapter%2006%20-%20Streaming%20data%20Bringing%20everything%20together/6.3%20-%20Combining%20various%20streaming%20techniques.md)
*   **Chapter 7: Sampling from data streams**
    *   [7.1 Techniques for selecting a representative subset of data from a stream](./Chapter%2007%20-%20Sampling%20from%20data%20streams/7.1%20-%20Techniques%20for%20selecting%20a%20representative%20subset%20of%20data%20from%20a%20stream.md)
    *   [7.2 Reservoir sampling and other methods](./Chapter%2007%20-%20Sampling%20from%20data%20streams/7.2%20-%20Reservoir%20sampling%20and%20other%20methods.md)
*   **Chapter 8: Approximate quantiles on data streams**
    *   [8.1 Algorithms for finding medians, percentiles, and other quantiles](./Chapter%2008%20-%20Approximate%20quantiles%20on%20data%20streams/8.1%20-%20Algorithms%20for%20finding%20medians,%20percentiles,%20and%20other%20quantiles.md)

### Part 3: Data structures for databases and external memory algorithms

*   **Chapter 9: Introducing the external memory model**
    *   [9.1 Introduction to the external memory model](./Chapter%2009%20-%20Introducing%20the%20external%20memory%20model/9.1%20-%20Introduction%20to%20the%20external%20memory%20model.md)
*   **Chapter 10: Data structures for databases: B-trees, Bε-trees, and LSM-trees**
    *   [10.1 B-Trees](./Chapter%2010%20-%20Data%20structures%20for%20databases%20B-trees,%20Bε-trees,%20and%20LSM-trees/10.1%20-%20B-Trees.md)
    *   [10.2 LSM-Trees](./Chapter%2010%20-%20Data%20structures%20for%20databases%20B-trees,%20Bε-trees,%20and%20LSM-trees/10.2%20-%20LSM-Trees.md)
*   **Chapter 11: External memory sorting**
    *   [11.1 External memory sorting](./Chapter%2011%20-%20External%20memory%20sorting/11.1%20-%20External%20memory%20sorting.md)
