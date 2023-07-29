---
description: 本笔记基于王道操作系统课程，适用于408中操作系统部分
---

# 408操作系统考察范围

## 考查目标

1.掌握操作系统的基本概念、基本原理和基本功能，理解操作系统的整体运行过程。

2.掌握操作系统进程、内存、文件和I/O管理的策略、算法、机制以及相互关系。

3.能够运用所学的操作系统原理、方法与技术分析问题和解决问题，并能利用C语言描述相关算法。

## **一、操作系统概述**

### \(一\)操作系统的概念、特征、功能和提供的服务

### \(二\)操作系统的发展与分类

### \(三\)操作系统的运行环境

1.内核态与用户态

2.中断、异常

3.系统调用

### \(四\)操作系统体系结构

## **二、进程管理**

### \(一\)进程与线程

1.进程概念

2.进程的状态与转换

3.进程控制

4.进程组织

5.进程通信

* 共享存储系统;
* 消息传递系统;
* 管道通信。

6.线程概念与多线程模型

### \(二\)处理机调度

1.调度的基本概念

2.调度时机、切换与过程

3.调度的基本准则

4.调度方式

5.典型调度算法

* 先来先服务调度算法;
* 短作业\(短进程、短线程\)优先调度算法;
* 时间片轮转调度算法;
* 优先级调度算法;
* 高响应比优先调度算法;
* 多级反馈队列调度算法。

### \(三\)同步与互斥

1.进程同步的基本概念

2.实现临界区互斥的基本方法

* 软件实现方法;
* 硬件实现方法。

3.信号量

4.管程

5.经典同步问题

* 生产者-消费者问题;
* 读者-写者问题;
* 哲学家进餐问题。

### \(四\)死锁

1.死锁的概念

2.死锁处理策略

3.死锁预防

4.死锁避免

* 系统安全状态
* 银行家算法

5.死锁检测和解除

## **三、内存管理**

### \(一\)内存管理基础

1.内存管理概念

* 程序装入与链接;
* 逻辑地址与物理地址空间;
* 内存保护。

2.交换与覆盖

3.连续分配管理方式

4.非连续分配管理方式

* 分页管理方式;
* 分段管理方式;
* 段页式管理方式。

### \(二\)虚拟内存管理

1.虚拟内存基本概念

2.请求分页管理方式

3.页面置换算法

* 最佳置换算法\(OPT\);
* 先进先出置换算法\(FIFO\);
* 最近最少使用置换算法\(LRU\);
* 时钟置换算法\(CLOCK\)。

4.页面分配策略

5.工作集

6.抖动

## **四、文件管理**

### \(一\)文件系统基础

1.文件概念

2.文件的逻辑结构

* 顺序文件;
* 索引文件;
* 索引顺序文件。

3.目录结构

* 文件控制块和索引节点;
* 单级目录结构和两级目录结构;
* 树形目录结构;图形目录结构。

4.文件共享

5.文件保护

* 访问类型;
* 访问控制。

### \(二\)文件系统实现

1.文件系统层次结构

2.目录实现

3.文件实现

### \(三\)磁盘组织与管理

1.磁盘的结构

2.磁盘调度算法

3.磁盘的管理

## **五、输入输出\(I/O\)管理**

### \(一\)I/O管理概述

1.I/O控制方式

2.I/O软件层次结构

### \(二\)I/O核心子系统

1.I/O调度概念

2.高速缓存与缓冲区

3.设备分配与回收

4.假脱机技术\(SPOOLing\)



