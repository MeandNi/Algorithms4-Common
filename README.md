![cover](assets/cover.png)

JVM 是 java 程序员永远的考题，算法是所有程序员永久的考题。这应该是很多人的共识，不管是谁，学习的路上我们时常遇到迷茫阶段，抓住最根本的东西你永远不会觉得迷失。

年假之前，我就规定自己要完成多少多少的任务，要做一些些有意义的事情，读书，练习，输出一些有价值的文字和笔记正是这一理念的实现，这样不仅让自己的经历更漂亮一点，也能帮助很多其他人！

《算法（第4版）》是一本晦涩的书，特别是中文版！我要强烈吐槽一下中文版的翻译，因为这本书业内评价都极高，当我兴致勃勃准备开始复习时，却被绕口的中文读的喘不过气，导致我推迟好久终于在今年年假期间才又拿出来慢慢对着英文原版啃起来！

除去基础数据结构的介绍，从大的方面讲，全书共有 4 大块，分别是排序、搜索、图、字符串，每大块基本都有 5 节的内容，每节又会有 4～5 种算法的实现与讲解，总共超过 80 道算法类型，图文并茂，确实是本好书（除了翻译）。

我希望能用这种方式激励我自己把这本书啃完，也希望帮助到一些正在准备面试和同样准备复习算法的同学。笔记内容除去了书中晦涩难懂的部分，截取的书中精华部分，我认为这本书的精华就是一张张插图，所以我几乎把所有的帮助理解的图都用上了，这一点你可以看[3-3-平衡查找树](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter03-Searching/3-3-%E5%B9%B3%E8%A1%A1%E6%9F%A5%E6%89%BE%E6%A0%91.md)的笔记，其次是每段都会贴出相应的关键代码，以便让我以后复习时不理解可以直接看代码。这本笔记在我反复复习也会随时更新，预计以后刷 LeetCode 时，也会将对应题型放在对应章节里，如果有其他建议欢迎提 issue 。



## 笔记目录

- [Chapter02-Sorting](./Chapter02-Sorting)

  - [2-1-初级排序算法](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter02-Sorting%20/2-1-%E5%88%9D%E7%BA%A7%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95.md)

  - [2-2-归并排序](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter02-Sorting%20/2-2-%E5%BD%92%E5%B9%B6%E6%8E%92%E5%BA%8F.md)

  - [2-3-快速排序](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter02-Sorting%20/2-3-%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F.md)

  - [2-4-优先队列](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter02-Sorting%20/2-4-%E4%BC%98%E5%85%88%E9%98%9F%E5%88%97.md)

  - [2-5-排序应用](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter02-Sorting%20/2-5-%E6%8E%92%E5%BA%8F%E5%BA%94%E7%94%A8.md)
- [Chapter03-Searching](https://github.com/MeandNi/Algorithms4-Common/tree/master/Chapter03-Searching)

  - [3-1-符号表](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter03-Searching/3-1-%E7%AC%A6%E5%8F%B7%E8%A1%A8.md)

  - [3-2-二叉查找树](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter03-Searching/3-2-%E4%BA%8C%E5%8F%89%E6%9F%A5%E6%89%BE%E6%A0%91.md)
  - [3-3-平衡查找树](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter03-Searching/3-3-%E5%B9%B3%E8%A1%A1%E6%9F%A5%E6%89%BE%E6%A0%91.md)
  - [3-4-散列表](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter03-Searching/3-4-%E6%95%A3%E5%88%97%E8%A1%A8.md)
  - [3-5-小结与应用](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter03-Searching/3-5-%E5%B0%8F%E7%BB%93%E4%B8%8E%E5%BA%94%E7%94%A8.md)
- [Chapter04-Graphs](https://github.com/MeandNi/Algorithms4-Common/tree/master/Chapter04-Graphs)
  - [4-2-有向图](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter04-Graphs/4-2-%E6%9C%89%E5%90%91%E5%9B%BE.md)
  - [4.1 无向图](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter04-Graphs/4.1%20%E6%97%A0%E5%90%91%E5%9B%BE.md)
- [Chapter05-String](https://github.com/MeandNi/Algorithms4-Common/tree/master/Chapter05-String)
  - [5-1-字符串排序](https://github.com/MeandNi/Algorithms4-Common/blob/master/Chapter05-String/5-1-%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%8E%92%E5%BA%8F.md)




## 书中所有算法集合

**排序**：

| ALGORITHM    | CODE                                                         | IN PLACE | STABLE | BEST         | AVERAGE      | WORST        | REMARKS                                                  |
| ------------ | ------------------------------------------------------------ | -------- | ------ | ------------ | ------------ | ------------ | -------------------------------------------------------- |
| **选择排序** | [Selection.java](https://algs4.cs.princeton.edu/21elementary/Selection.java.html) | ✔        |        | ½ *n* 2      | ½ *n* 2      | ½ *n* 2      | *n* exchanges; quadratic in best case                    |
| **插入排序** | [Insertion.java](https://algs4.cs.princeton.edu/21elementary/Insertion.java.html) | ✔        | ✔      | *n*          | ¼ *n* 2      | ½ *n* 2      | use for small or partially-sorted arrays                 |
| **冒泡排序** | [Bubble.java](https://algs4.cs.princeton.edu/21elementary/Bubble.java.html) | ✔        | ✔      | *n*          | ½ *n* 2      | ½ *n* 2      | rarely useful; use insertion sort instead                |
| **希尔排序** | [Shell.java](https://algs4.cs.princeton.edu/21elementary/Shell.java.html) | ✔        |        | *n* log3 *n* | unknown      | c *n* 3/2    | tight code; subquadratic                                 |
| **合并排序** | [Merge.java](https://algs4.cs.princeton.edu/22mergesort/Merge.java.html) |          | ✔      | ½ *n* lg *n* | *n* lg *n*   | *n* lg *n*   | *n* log *n* guarantee; stable                            |
| **快速排序** | [Quick.java](https://algs4.cs.princeton.edu/23quicksort/Quick.java.html) | ✔        |        | *n* lg *n*   | 2 *n* ln *n* | ½ *n* 2      | *n* log *n* probabilistic guarantee; fastest in practice |
| **堆排序**   | [Heap.java](https://algs4.cs.princeton.edu/24pq/Heap.java.html) | ✔        |        | *n* †        | 2 *n* lg *n* | 2 *n* lg *n* | *n* log *n* guarantee; in place                          |

**优先队列**

| DATA STRUCTURE | CODE                                                         | INSERT     | DEL-MIN        | MIN  | DEC-KEY    | DELETE         | MERGE   |
| -------------- | ------------------------------------------------------------ | ---------- | -------------- | ---- | ---------- | -------------- | ------- |
| **数组**       | [BruteIndexMinPQ.java](https://algs4.cs.princeton.edu/24pq/BruteIndexMinPQ.java.html) | 1          | *n*            | *n*  | 1          | 1              | *n*     |
| **二叉堆**     | [IndexMinPQ.java](https://algs4.cs.princeton.edu/24pq/IndexMinPQ.java.html) | log *n*    | log *n*        | 1    | log *n*    | log *n*        | *n*     |
| **d-way heap** | [IndexMultiwayMinPQ.java](https://algs4.cs.princeton.edu/99misc/IndexMultiwayMinPQ.java.html) | log*d* *n* | *d* log*d* *n* | 1    | log*d* *n* | *d* log*d* *n* | *n*     |
| **二项堆**     | [IndexBinomialMinPQ.java](https://algs4.cs.princeton.edu/99misc/IndexBinomialMinPQ.java.html) | 1          | log *n*        | 1    | log *n*    | log *n*        | log *n* |
| **斐波那契堆** | [IndexFibonacciMinPQ.java](https://algs4.cs.princeton.edu/99misc/IndexFibonacciMinPQ.java.html) | 1          | log *n* †      | 1    | 1 †        | log *n* †      | log *n* |

**查找**

|                         |                                                              | worst case | average case |         |         |         |           |
| ----------------------- | ------------------------------------------------------------ | ---------- | ------------ | ------- | ------- | ------- | --------- |
| DATA STRUCTURE          | CODE                                                         | SEARCH     | INSERT       | DELETE  | SEARCH  | INSERT  | DELETE    |
| **顺序查找** (无序列表) | [SequentialSearchST.java](https://algs4.cs.princeton.edu/31elementary/SequentialSearchST.java.html) | *n*        | *n*          | *n*     | *n*     | *n*     | *n*       |
| **二分查找** (有序列表) | [BinarySearchST.java](https://algs4.cs.princeton.edu/31elementary/BinarySearchST.java.html) | log *n*    | *n*          | *n*     | log *n* | *n*     | *n*       |
| **二叉树** (不平衡)     | [BST.java](https://algs4.cs.princeton.edu/32bst/BST.java.html) | *n*        | *n*          | *n*     | log *n* | log *n* | sqrt(*n*) |
| **红黑二叉树** (左倾)   | [RedBlackBST.java](https://algs4.cs.princeton.edu/33balanced/RedBlackBST.java.html) | log *n*    | log *n*      | log *n* | log *n* | log *n* | log *n*   |
| **散列表** (分离链接法) | [SeparateChainingHashST.java](https://algs4.cs.princeton.edu/34hash/SeparateChainingHashST.java.html) | *n*        | *n*          | *n*     | 1 †     | 1 †     | 1 †       |
| **散列表** (线性探测)   | [LinearProbingHashST.java](https://algs4.cs.princeton.edu/34hash/LinearProbingHashST.java.html) | *n*        | *n*          | *n*     | 1 †     | 1 †     | 1 †       |

**图**

| PROBLEM                       | ALGORITHM                 | CODE                                                         | TIME                | SPACE     |
| ----------------------------- | ------------------------- | ------------------------------------------------------------ | ------------------- | --------- |
| **路径**                      | DFS                       | [DepthFirstPaths.java](https://algs4.cs.princeton.edu/41graph/DepthFirstPaths.java.html) | *E* + *V*           | *V*       |
| **最短路径(最少边缘)**        | BFS                       | [BreadthFirstPaths.java](https://algs4.cs.princeton.edu/41graph/BreadthFirstPaths.java.html) | *E* + *V*           | *V*       |
| **环**                        | DFS                       | [Cycle.java](https://algs4.cs.princeton.edu/41graph/Cycle.java.html) | *E* + *V*           | *V*       |
| **有向路径**                  | DFS                       | [DepthFirstDirectedPaths.java](https://algs4.cs.princeton.edu/42digraph/DepthFirstDirectedPaths.java.html) | *E* + *V*           | *V*       |
| **最短有向路径 (最少边缘)**   | BFS                       | [BreadthFirstDirectedPaths.java](https://algs4.cs.princeton.edu/42digraph/BreadthFirstDirectedPaths.java.html) | *E* + *V*           | *V*       |
| **有向环**                    | DFS                       | [DirectedCycle.java](https://algs4.cs.princeton.edu/42digraph/DirectedCycle.java.html) | *E* + *V*           | *V*       |
| **拓扑排序**                  | DFS                       | [Topological.java](https://algs4.cs.princeton.edu/42digraph/Topological.java.html) | *E* + *V*           | *V*       |
| **bipartiteness / odd cycle** | DFS                       | [Bipartite.java](https://algs4.cs.princeton.edu/41graph/Bipartite.java.html) | *E* + *V*           | *V*       |
| **连通分量**                  | DFS                       | [CC.java](https://algs4.cs.princeton.edu/41graph/CC.java.html) | *E* + *V*           | *V*       |
| **强连通分量**                | Kosaraju–Sharir           | [KosarajuSharirSCC.java](https://algs4.cs.princeton.edu/42digraph/KosarajuSharirSCC.java.html) | *E* + *V*           | *V*       |
| **强连通分量**                | Tarjan                    | [TarjanSCC.java](https://algs4.cs.princeton.edu/42digraph/TarjanSCC.java.html) | *E* + *V*           | *V*       |
| **强连通分量**                | Gabow                     | [GabowSCC.java](https://algs4.cs.princeton.edu/42digraph/GabowSCC.java.html) | *E* + *V*           | *V*       |
| **欧拉回路**                  | DFS                       | [EulerianCycle.java](https://algs4.cs.princeton.edu/41graph/EulerianCycle.java.html) | *E* + *V*           | *E* + *V* |
| **定向欧拉循环**              | DFS                       | [DirectedEulerianCycle.java](https://algs4.cs.princeton.edu/42digraph/DirectedEulerianCycle.java.html) | *E* + *V*           | *V*       |
| **传递闭包**                  | DFS                       | [TransitiveClosure.java](https://algs4.cs.princeton.edu/42digraph/TransitiveClosure.java.html) | *V* (*E* + *V*)     | *V* 2     |
| **最小生成树**                | Kruskal                   | [KruskalMST.java](https://algs4.cs.princeton.edu/43mst/KruskalMST.java.html) | *E* log *E*         | *E* + *V* |
| **最小生成树**                | Prim                      | [PrimMST.java](https://algs4.cs.princeton.edu/43mst/PrimMST.java.html) | *E* log *V*         | *V*       |
| **最小生成树**                | Boruvka                   | [BoruvkaMST.java](https://algs4.cs.princeton.edu/43mst/BoruvkaMST.java.html) | *E* log *V*         | *V*       |
| **最短路径(非负权)**          | Dijkstra                  | [DijkstraSP.java](https://algs4.cs.princeton.edu/44sp/DijkstraSP.java.html) | *E* log *V*         | *V*       |
| **最短路径(无负循环)**        | Bellman–Ford              | [BellmanFordSP.java](https://algs4.cs.princeton.edu/44sp/BellmanFordSP.java.html) | *V* (*V* + *E*)     | *V*       |
| **s最短路径（无环）**         | topological sort          | [AcyclicSP.java](https://algs4.cs.princeton.edu/44sp/AcyclicSP.java.html) | *V* + *E*           | *V*       |
| **所有节点对之间的最短路**    | Floyd–Warshall            | [FloydWarshall.java](https://algs4.cs.princeton.edu/44sp/FloydWarshall.java.html) | *V* 3               | *V* 2     |
| **最大流/最小割**             | Ford–Fulkerson            | [FordFulkerson.java](https://algs4.cs.princeton.edu/64maxflow/FordFulkerson.java.html) | *E* *V* (*E* + *V*) | *V*       |
| **二分图匹配**                | Hopcroft–Karp             | [HopcroftKarp.java](https://algs4.cs.princeton.edu/65reductions/HopcroftKarp.java.html) | *V* ½ (*E* + *V*)   | *V*       |
| **任务分配问题**              | successive shortest paths | [AssignmentProblem.java](https://algs4.cs.princeton.edu/65reductions/AssignmentProblem.java.html) | *n* 3 log *n*       | *n* 2     |