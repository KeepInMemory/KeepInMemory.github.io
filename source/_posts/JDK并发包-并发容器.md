---
title: JDK并发包-并发容器
date: 2019-09-14 12:00:00
tags:
  - 实战Java高并发程序设计
  - 容器
---

ConcurrentHashMap：一个高效安全的并发HashMap。

CopyOnWriteArrayList：用在读多写少的场合，是性能最好的list

ConcurrentLinkedQueue：一个高效安全的并发的链表实现的队列

BlockingQueue：阻塞队列，作为数据共享的通道，ArrayBlockingQueue、LinkedBlockingQueue实现了这个接口

ConcurrentSkipListMap：跳表实现的Map，对其遍历是有序的。