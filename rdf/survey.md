贡献
 * 提供了系统分类的RDF存储管理器实现
 * 容易检测到特定RDF存储管理器实现之间的差异
 * 通过多进程环境获取有关有效进程的属性。

Single(T,I,Q,S,J,C,D,F)

Table
 * vertical
 * property
 * horizontal

Indexx structure
 * 6-independent
 * GSPO-PGPS
 * matrix

Query type
 * SPARQL
 * original

String translation method
 * URI
 * literal
 * long
 * none

Join optimization method
 * RDBMS-based
 * column-strore-based
 * conventional ordering
 * pruning
 * none

Cache type 
 * materialized-path-index
 * reified-statement
 * none

Dabase engine type
 * RDB
 * custom

inference Feature type
 * TBox 本体推断
 * ABox 断言推断
 * no

Multiple(D,Q,S,A)

Data distribution method
 * hash
 * data-source
 * none

Query process distribution method type
 * data-parallel
 * data-replication
 * none

Stream process
 * pipeline
 * none

sharing Architecture
 * memory
 * disk
 * nothing


|name|T|I|Q|S|J|C|D|F|D|Q|S|A|
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|3store|v||S|U|R||R|T|n|n|n||
|4store|v||S|U|o||R||h|p||n|
|Virtuoso|v|G|S|Ulo|R||R|TA|n|n|n||
|RDF-3X|v|6|S|Ul|o||R||n|n|n||
|Hexastore|v|6|o|Ul||n|||n|n|n||
|Apache Jena|p||S|Ulo|R|r|R||n|n|n||
|SW-store|h|||Uo|c|m|c||n|n|n||
|BitMat|v|m|S|Ul|p||c||||p||
|AllegroGraph|||S||||c||h|p||m|
|Haddop/HBase|h||||||c|||p||m|
|wukong|v|???|S|Ul|c+?|?|R?|?|dh?|p|p|m|

