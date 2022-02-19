# 数据结构（荣誉）课程 - STLite

## 内容概要

本学期大作业要求同学们完成下面五个任务：

1. vector (6 pts)
2. list (6 pts)
2. priority queue (6 pts)
2. linked hash map (8 pts)
3. map / B+ tree (12 pts)

实现代码的接口框架与头文件，助教已经给出，同学们需要给出补充完成，给出完整的实现。

同学们需要在每个任务的截止日期前，完成相应任务的实现，并提交到 OJ 上。助教会在截止日期后一段时间内安排 Code Review。

**注意：在本作业中，只允许使用`cstdio`，`cstring`，`iostream`，`cmath`四个C++标准库，如需使用其他功能请自行实现。**

**注意：对于每个任务，在 OJ 上通过测试数据可获得 80% 的分数，Code Review 占 20% 的分数。**

关于windows10下ubuntu wsl的使用，详见[windows10下ubuntu wsl的简单使用指南](./tutorials/windows10下ubuntu wsl的简单使用指南.md)

### 关于 priority queue 的评分说明

1. OJ 上会有两道题目：priority queue (easy) 和 priority queue (hard)，你需要**任选一个**完成
1. 在 OJ 上通过 priority queue (easy)，获得满分 6 分；
1. 在 OJ 上视 priority queue (hard) 的通过情况，最高获得 8 分；
2. 即便你完成了两个版本，**只有一个会计入分数**；
3. 多余的分数可以优先溢出到小作业或者机考。

### 关于 map / B+ tree 的评分说明

1. OJ 上会有三道题目：map (easy), map (hard) 和 B+ tree，你需要**任选一个**完成
3. 在 OJ 上通过 map (easy)，只能获得 10 分；
4. 在 OJ 上通过 map (hard)，获得满分 12 分；
5. 在 OJ 上视 B+ Tree 的通过情况，最高获得 15 分；
6. 即便你完成了多个，**只有一个会计入分数**；
7. 多余的分数可以优先溢出到小作业或者机考。


## 发布时间 & 截止时间

1. vector: 发布时间：第三周；截止时间：**第七周周六(4月3日)  23:00**
1. list: 发布时间：第三周；截止时间：**第七周周六(4月三日) 23:00**
1. priority queue: 发布时间：第七周；截止时间：**第十周周六(4月24日) 23:00**
1. linked hash map: 发布时间：第十周；截止时间：**第十二周周六(5月8日) 23:00**
1. map / B+ tree: 发布时间：第十二周；截止时间：**第十七周周六(6月12日) 23:00**（暂定）

请大家严格把握好时间！建议尽早开工尽早完成！

## 文件说明

以 vector 为例，在 vector 文件夹下分别有数据和接口文件。

* **其中 `vector.hpp` 是你仅需要实现的文件，也是最终提交的代码。**

* `exceptions.hpp` 与 `utility.hpp` 是两个辅助文件(**不可修改**)，提供了异常处理类与 pair 类，你可以在你的代码中自由使用。
* data 文件夹中有多组测试数据，分别位于各个文件夹中。

## 如何测试你的代码？

以 vector 为例，若要在本地测试，请将你的代码 `vector.hpp`、相应测试点下的 cpp 文件 `code.cpp`  和 `class-bint.hpp`, `class-integer.hpp`, `class-matrix.hpp`, `utility.hpp`, `exceptions.hpp` 放在同一个目录下编译运行。

### 内存泄漏？

如果你想在本地测试自己的代码是否存在内存泄漏，请点击[如何检测内存泄漏？](./tutorials/detect-memory-leak/detect-memory-leak.md)

当然，**你不一定非要在自己电脑上测**。如果你提交的代码中存在内存泄漏，OJ 会告诉你的。

## 评测及提交方式

评测采用 OJ 在线评测的方式，请在 OJ 上用注册账号，在题库中找到相应题目，提交你的代码。

OJ 地址：https://acm.sjtu.edu.cn/OnlineJudge/

* 以 vector 为例，你只需要将你 `vector.hpp` 中的代码贴到 OJ 上提交即可
* 评测**开 O2 优化**
* 由于 Valgrind 内存检测会导致程序运行时间增长，**OJ 上的 Memory Check 会相应扩大时限**。
