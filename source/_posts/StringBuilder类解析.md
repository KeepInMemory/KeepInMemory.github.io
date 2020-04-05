---
title: StringBuilder类解析
date: 2019-08-31 12:00:03
tags:
  - Java核心卷
  - StringBuilder
---

StringBuilder的出现的原因是需要由若干小字符串构建大的字符串，而通过字符串连接的方法，每次连接都需要指向构建的一个新的字符串，浪费时间浪费空间。

```java
StringBuilder builder = new StringBuilder();
builder.append(ch1);
builder.append(ch2);
String completedString = builder.toString()；
```

首先建一个空的字符串构造器，将需要添加的部分加入，最后用toString方法得到一个String对象。