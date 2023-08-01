---
title: "Learn Message Mysql"
date: 2023-04-17T21:13:01+08:00
draft: false
---


## 相关链接

https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/MySQL%E5%AE%9E%E6%88%9845%E8%AE%B2

https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/MySQL%E5%AE%9E%E6%88%98%E5%AE%9D%E5%85%B8

## 知识点


### 慢 SQL 分析
[提高 SQL 的性能](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/Java%E5%B9%B6%E5%8F%91%E7%BC%96%E7%A8%8B%E5%AE%9E%E6%88%98/32%20%20MySQL%E8%B0%83%E4%BC%98%E4%B9%8BSQL%E8%AF%AD%E5%8F%A5%EF%BC%9A%E5%A6%82%E4%BD%95%E5%86%99%E5%87%BA%E9%AB%98%E6%80%A7%E8%83%BDSQL%E8%AF%AD%E5%8F%A5%EF%BC%9F.md)


InnoDB存储引擎不直接支持Hash索引，它支持的索引类型包括：
- B+树索引：是InnoDB默认的索引类型，用于支持普通索引和唯一索引。
- 全文索引：用于支持全文搜索功能。
- 空间索引：用于支持空间数据类型的查询。
- 主键索引：用于支持主键查询，实际上是B+树索引的一种特殊形式。
  
