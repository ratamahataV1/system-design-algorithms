# System design algorithms

#### Requirements
- Know when to use ☑️
- Know how it works ✅

#### Table of contents

- Bloom filter ✅
- Consistent hashing ✅
- Geohash / S2 Geometry ✅
- Leaky bucket / Token bucket ✅
- Inverted index ✅
- Distributed Consensus Algorithms (e.g., Paxos, Raft) ✅
- Cache Eviction Policies (e.g., LRU, LFU) ✅
- Rsync algorithm ✅
- HyperLogLog ✅
- Trie algorithm ✅
- Lossy Counting ☑️
- Frugal Streaming ☑️
- Operational transformation ☑️
- Quadtree / Rtree ☑️
- Ray casting ☑️

### Bloom filter
A Bloom filter is a data structure designed to tell you, rapidly and memory-efficiently, whether an element is present in a set.

- [Supercharging the Git Commit Graph IV: Bloom Filters](https://devblogs.microsoft.com/devops/super-charging-the-git-commit-graph-iv-bloom-filters/)

### Consistent hashing
Consistent hashing is an algorithm designed to distribute data across a cluster in a way that minimizes re-distribution when nodes are added or removed. It is particularly useful in distributed systems, such as distributed caches, distributed storage systems, and load balancing.

- [A Guide to Consistent Hashing](https://www.toptal.com/big-data/consistent-hashing)

### Geohash / S2 Geometry
Geohash can used by 1) dating apps to find romantic matches within a particular cell, and to create chat apps.2) Find nearby locations, and identify places of interest, restaurants, shops and accommodation establishments in an area. 3) Geohashers go on global expeditions to meet people and explore new places.

- [Location-based search results with DynamoDB and Geohash](https://read.acloud.guru/location-based-search-results-with-dynamodb-and-geohash-267727e5d54f)

### Leaky bucket / Token bucket
A mechanism to control the amount and the rate of the traffic sent to the network

- [Everything You Need To Know About API Rate Limiting](https://nordicapis.com/everything-you-need-to-know-about-api-rate-limiting/)
- [How to Design a Scalable Rate Limiting Algorithm](https://konghq.com/blog/how-to-design-a-scalable-rate-limiting-algorithm/)

### Ieversed index
An inverted index is a data structure used primarily in text search engines.

- [How search engines work: Crawling, Indexing, And Ranking](https://moz.com/beginners-guide-to-seo/how-search-engines-operate)
- [Building a complete Tweet index](https://blog.twitter.com/engineering/en_us/a/2014/building-a-complete-tweet-index.html)

### Distributed Consensus Algorithms
Distributed consensus algorithm that enables nodes to agree on a value despite failures, requiring a majority for safety and progress.

### Cache Eviction Policies
Cache eviction policies determine which items to remove from a cache when it reaches its capacity, with common strategies including Least Recently Used (LRU), First In First Out (FIFO), and Least Frequently Used (LFU).

- [Caching in theory and practice](https://dropbox.tech/infrastructure/caching-in-theory-and-practice)

### Rsync algorithm
The rsync algorithm is a technique for reducing the cost of a file transfer by avoiding the transfer of blocks that are already at the destination.

- [Streaming File Synchronization](https://dropbox.tech/infrastructure/streaming-file-synchronization)

### HyperLogLog
HyperLogLog is an algorithm for the count-distinct problem, approximating the number of distinct elements in a multiset.

- [Redis HyperLogLog Explained](https://www.youtube.com/watch?v=MunL8nnwscQ)

### Trie algorithm
Trie is an efficient information reTrieval data structure. Using Trie, search complexities can be brought to optimal limit (key length)

- [How to Design an Autocomplete System](https://dzone.com/articles/how-to-design-a-autocomplete-system)
- [Spell Checkers](https://stackoverflow.com/questions/21366631/how-do-i-use-a-trie-for-spell-checking)
- [prefix matching words (IP Addresses, Phone Numbers)](https://www.geeksforgeeks.org/longest-common-prefix-using-trie/)
- [Auto-complete feature using Trie](https://www.geeksforgeeks.org/auto-complete-feature-using-trie/)

### Lossy Counting
The lossy count algorithm is an algorithm to identify elements in a data stream whose frequency count exceed a user-given threshold.

- [Fast and Reliable Ranking in Datastore](https://cloud.google.com/datastore/docs/articles/fast-and-reliable-ranking-in-datastore)
- [Frequency Counts over Data Streams](https://www.cse.ust.hk/vldb2002/VLDB2002-proceedings/slides/S10P03slides.pdf)
- [How we built rate limiting capable of scaling to millions of domains](https://blog.cloudflare.com/counting-things-a-lot-of-different-things/)
- [Rate-limiting strategies and techniques](https://cloud.google.com/solutions/rate-limiting-strategies-techniques)

### Frugal Streaming
Frugal Streaming uses only one unit of memory per group to compute a quantile for each group

- [Find the nth percentile of the data stream](https://research.neustar.biz/2013/09/16/sketch-of-the-day-frugal-streaming/)

### Operational transformation
Operational transformation (OT) is a technology for supporting a range of collaboration functionalities in advanced collaborative software systems.

- [How Google docs handle editing collisions](https://stackoverflow.com/a/36366174)
- [Collaborative editing](https://www3.ntu.edu.sg/home/czsun/projects/otfaq/#_Toc321146127)

### Quadtree / Rtree
- [Spatial Indexing with Quadtrees](https://medium.com/@waleoyediran/spatial-indexing-with-quadtrees-b998ae49336)
- Find nearby interest points

### Ray casting
Ray casting is the most basic of many computer graphics rendering algorithms that use the geometric algorithm of ray tracing. Given a point with longitude and latitude, return the Country of the point.

- [Ray Casting Algorithm](http://philliplemons.com/posts/ray-casting-algorithm)



