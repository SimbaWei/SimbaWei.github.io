## Xing Wei (Ph.D. Candidate)
![](profile.png)
#### Personal Information

Office: Room 314, Geographical Building, East China Normal University, 3663 N. Zhongshan Rd, Shanghai, China.

Email: simba_wei@stu.ecnu.edu.cn

Short Bio: I got my bachelor's degree from Nanjing Tech University in 2016. I am currently working toward the PhD degree in East China Normal University. My research interests include in-memory computing, distributed query optimization and high-performance distributed system.

#### Readings
I share my readings on key words: DSM/KVS/New hardwares/NUMA/Query Optimization as a list. Welcome to discuss with me.


#### Projects

* **Hash Reusing**
In-memory query processing can be accelerated by caching intermediate query results. Among various types of intermediate results, hash tables used by hash join are ideal objects for caching, as they can benefit a wide range of queries. In this system, we introduce a fine-grained hash table caching method to benefit the hash-join operator. Our insight is that the
fine-grained management of cached hash tables at the granularity of chunks can achieve optimal caching efficiency. As hash chunks can be reused more effectively, we propose a cache-enabled hash join operator to accelerate in-memory hash join. Furthermore, previous studies do not study caching intermediate result for the concurrent workloads.We consider concurrent accesses to cached hash chunks and present the scheduling strategy to improve throughput of concurrent query processing. We integrated our caching method into a prototype to evaluate its performance. Our system shows that it can achieve significant performance improvement over brute force caching methods.

* **Shared Cache**

* **Distributed Page-based Memeory Management**

#### Publication
* **Xing Wei**, Huiqi Hu: Parallel Strategy for Multiple Scan Operations with Data Replication, appear in [WWWJ'2019](<https://link.springer.com/article/10.1007/s11280-018-0625-7>)
