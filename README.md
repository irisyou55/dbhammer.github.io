# DBHammer组简介

实验室主要研究数据库系统实现核心技术，如高冲突事务处理框架、自适应数据分区等；数据库系统质量保证的关键技术，如面向应用的大规模负载仿真、Benchmark等。

![方向](https://tva1.sinaimg.cn/large/007S8ZIlgy1ggjwsk32phj30jg0jcqg9.jpg) 


## Woodpecker

为了提高数据库测试效率，缓解测试对测试人员的专业性要求，Woodpecker是一款高效的通用数据库测试框架。通过语义明确的测试定义语言(Testing definition language, TDL)实现高效编写测试任务，支持事务、预编译执行、Shell调用、分支和逻辑循环以及高并发下的功能测试，分布式系统测试等功能。Woodpecker同时支持数据库功能测试、性能测试和分布式数据库系统测试。

联系人：[项兆坤](mailto:zkxiang@stu.ecnu.edu.cn)

## Touchstone
用于解决面向OLAP应用的数据库性能测试中真实数据和负载不可得问题，帮助企业进行数据库选型、PoC测试以及做面向应用的性能优化。Touchstone是面向OLAP应用的合成负载生成器，支持多节点全并行数据生成，目前支持TPC-H前16个查询的完整支持，为业界领先水平。为保证自动化数据生成任务，我们提供自动化采集工具TouchstoneToolChain用于配置收集。

联系人：[王清帅](mailto:qswang@stu.ecnu.edu.cn)

## Artemis

服务于分析型数据库功能测试的自动化测试套件生成工具，是第一个将数据生成、负载生成、结果生成集成到一起并兼具可扩展性、有效性、高效性的测试工作。与传统的基于差异测试的方法相比，在保证最大化测试空间的同时，极大的节约了存储、计算资源，显著提高了测试效率。

联系人：[米凯铭](mailto:mkm@stu.ecnu.edu.cn)

## Lauca

用于解决面向OLTP应用的数据库性能测试中真实数据和负载不可得问题，帮助企业进行数据库选型、PoC测试以及做面向应用的性能优化。在评估数据库系统服务于特定应用的性能时，定义评估的可靠性（负载仿真程度）由合成负载与实际应用负载之间的执行性能相似性决定。Lauca是面向OLTP应用的第一个合成负载生成器，能够实现生成和实际应用负载性能指标高度相似的合成负载，同时保证应用数据的隐蔽性、工具可扩展性和负载可拓展性。

联系人：[张舒燕](mailto:syzhang@stu.ecnu.edu.cn)

## Orca

隔离级别由数据库的并发控制模块实现，涉及到数据库中数据的一致性和完整性，因此隔离级别的正确性对于数据库系统的一致性至关重要；然而，目前对于隔离级别的正确性测试方法存在诸多缺陷，导致难以发现隐藏具体实现中的BUG，从而破坏了数据的一致性，会给数据库用户带来严重的损失。为了解决事务型（OLTP）数据库隔离级别正确性测试中测试效率低下、测试深度不够的问题，我们提出了Orca，一个全面评测数据库隔离级别实现正确性的自动化测试工具，完成高效的、充分的以及有效的OLTP数据库测试。Orca可以帮助数据库生产商完成数据库的开发以及帮助数据库用户进行数据库选型。



联系人：[李可强](mailto:kqli@stu.ecnu.edu.cn)

# 人员介绍

## 导师

> ### [张蓉](http://dase.ecnu.edu.cn/dase-module-gateway/dase/teacher/single_teacher.html?teacherId=23) `教授` `博士生导师` 
>
> **联系电话**：021-62235006
>
> **电子邮箱**：[rzhang@dase.ecnu.edu.cn](mailto:rzhang@dase.ecnu.edu.cn)
>
> **办公地点**：地理馆317
>
> **通讯地址**：上海市普陀区中山北路3663号华东师范大学地理馆317
>
> **研究兴趣**： 主要包括分布式数据管理，数据库基准评测，数据流管理。

## 在读学生


> ### 王晓桐 `博士`
>
> **研究方向**：分布式流处理系统负载均衡与容错
>
> **代表工作**: 
> + Cost-effective data partition for distributed stream processing
> + Evaluating fault tolerance of distributed
stream processing systems
>
> **联系方式**：[wxt@stu.ecnu.edu.cn](mailto:wxt@stu.ecnu.edu.cn)

> ### 张春熙 `博士`
>
> **研究方向**：数据库性能评测
>
> **代表工作**: 
> + Quantitative Contention Generation for Performance Evaluation on OLTP Databases
> + Benchmarking on Intensive Transaction Processing
>
> **联系方式**：[cxzhang@stu.ecnu.edu.cn](mailto:cxzhang@stu.ecnu.edu.cn)

> ### 李可强 `博士`
> **研究方向**：数据库基准评测
>
> **联系方式**：[kqli@stu.ecnu.edu.cn](mailto:kqli@stu.ecnu.edu.cn)

> ### 王清帅 `博士`
> **研究方向**：面向AP应用的负载模拟、数据分区、HTAP数据库
>
> **联系方式**：[qswang@stu.ecnu.edu.cn](mailto:qswang@stu.ecnu.edu.cn)

> ### 张舒燕 `专硕`
> **研究方向**：数据库事务处理、并发控制、面向应用的性能测试
> 
> **联系方式**：[syzhang96@163.com](mailto:syzhang96@163.com)

> ### 米凯铭 `专硕`
> **研究方向**：数据库功能测试、自动化测试案例生成
>
> **联系方式**：[mkm@stu.ecnu.edu.cn](mailto:mkm@stu.ecnu.edu.cn)

> ### 项兆坤 `学硕`
> **研究方向**：数据库基准评测
>
> **联系方式**：[zkxiang@stu.ecnu.edu.cn](mailto:zkxiang@stu.ecnu.edu.cn)

> ### 瞿璐祎 `学硕`
> **研究方向**：推荐有代表性的负载、模拟负载生成
>
> **联系方式**：[luyiquu@163.com](mailto:luyiquu@163.com)

> ### 游舒泓 `学硕`
> **研究方向**：数据库慢查询的分析与诊断
>
> **联系方式**：[shuhongiris@outlook.com](mailto:shuhongiris@outlook.com)

> ### 连薛超 `专硕`
> **研究方向**：面向OLTP负载的分布式数据库自适应分区
>
> **联系方式**：

> ### 陈婷 `专硕`
> **研究方向**：
>
> **联系方式**：
