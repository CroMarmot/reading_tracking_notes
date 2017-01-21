Trinity RDF
---

dgraph engine for web scale rdf data

# ABSTRACT

  现有的对于网络范围的RDF数据现有依然不是高效的,内部存储不用bitmap,other operations,

# INTRODUCTION

挑战:可扩展性(急切)和普遍性,需要分布式,现有依然三元组,join巨大中间结果,过大的开销 通常指数级 ,现有不支持更有意义的查询 仅仅对SPARQL优化

作者的成就:分布式,处理billion even trillion triples ,不用 relational tables and bitmap matrices,build on top of a memory cloud,首先说 随机访问的情况下 用硬盘储存三元组不够优良 ,就算有好的索引也会因为额外的join操作,作为主要的查询中 耗时,in-memory graph exploration instead of join operations for SPARQL processing ,作为对比 之前的系统 孤立使用自己划分的三元组 没有用已有的 造成了很大的中间额外开销,介绍如何降低join 数量 如何降低中间过程的大小,并且就算没有足够好的划分 也有优秀的性能,我们允许大范围的图分析

 1. 新的基于图表的管理RDF数据 ,有对于RDf 高效基于图查询 和 图分析 的可能性
 2. 新的查询规范(相对于SPARQL)有效的提高性能 减少总监结果 和提高系统可扩展性
 3. 新的价值模型 新的基数估计基数 分布式查询生成的优化算法 ,这些成果提供 在web 范围 RDF数据上 出色的性能

Section 2 describes the difference between join operations and graph exploration. Section 3 presents the architecture of the Trinity.RDF system. Section 4 describes how we model RDF data as native graphs. Section 5 describes SPARQL query processing techniques. Section 6 shows experimental results. We conclude in Section 8.






