# Introduction to Spark and ShARc

## Where Does Big Data come from
* 发生在网络世界，能记录一切东西
* 用户也会产生内容如社交媒体

## graph Data(图形数据)
* 许多有趣的数据都有图形结构
    * 社交网络
    * 电脑网络
    * Road network
    
## Key Data Management Concept(关键的数据管理概念)
* 一个data model(数据模型)是一个描述数据概念的集合
* 一个schema(模式)是一个使用给定数据模型的特定数据集合的描述

[什么是schema](https://blog.csdn.net/u010429286/article/details/79022484)

## The Structure Spectrum

![数据结构光谱]()

## 结构化数据（数据库）
* Database：一个关系数据模型，用来描述一个数据库是如何结构化和使用的
* Schema： 是数据结构的组织的蓝图，这个蓝图是用来让人知道一个数据库是如何建立起来的
* 程序员必须静态指定架构

## Semi-Structured Data
* 是一种自描述结构而不是正式的结构， 标签或者标记是用来分割语义元素。
* the column types(柱的种类) ——> 是数据的模式
    * Spark在读取每一行数据时都在动态地推断该数据的schema(模式)
    * 程序员静态指定架构
* 出现的越来越多如： XML, JSON

## 非结构化数据
*
    




[结构化数据，半结构化数据，非结构化数据说明](https://blog.csdn.net/liangyihuai/article/details/54864952)