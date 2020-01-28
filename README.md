# ABC
AI,BigData,Cloud


## AI


## BigData
### 大数据基础组件介绍。
#### HDFS
HDFS（Hadoop Distributed File System）基于Google发布的GFS论文设计开发，其具备其他分布式文件系统相同特性外，还有自己的特性：
* 高容错：认为硬件总是不可靠的
* 高吞吐量：为有大量数据访问的应用提供高吞吐量支持
* 大文件存储：支持存储TB-PB级别的数据
#### MapReduce&YARN
MapReduce：基于Google发布的分布式计算框架MapReduce论文设计开发，用于大规模数据集（大于1TB）的并行计算：
* 易于编程：开发者仅需编写简单的程序，系统的执行框架会处理细节
* 良好的扩展性：可以通过添加主机达到扩展集群能力的目的
* 高容错性：通过计算迁移或者数据迁移等提高集群的可用性与容错性

YARN：是Hadoop2.0中的资源管理系统，它是一个通用的资源管理模，可为各类应用程序进行资源管理和调度。可支持MapReduce，Spark，Storm等多种框。
Yarn的优势有：资源利用率低；运维成本低；数据共享方便。

#### EleasticSearch

## CloudComputing
