---
title: 2025春夏开源操作系统训练营第一二阶段总结报告-Levio-z
date: 2025-05-16 15:20:18
tags:
---
# 第一阶段

- 为什么来这个训练营

  - 最初是在寻找 Rust 的练手项目过程中，偶然了解到本训练营。自己本就对系统级编程充满兴趣，因此毫不犹豫地报名参加。

- 官方通过要求：
  - rustlings+10道算法题
- 主要参考资料：

  - https://rust-book.cs.brown.edu/

  - https://course.rs/about-book.html

- 学习过程

  - 基于一定的编程基础，我通读了一本 Rust 入门教材，同时刷了约 100 道 LeetCode 算法题，作为语言练习。尤其链表类题目虽然困难，但反而非常适合加深对 Rust 所有权模型的理解。

- 感想

  - 第一次参与开源社区形式的学习训练营，整体学习路线、资料与交流氛围都非常优质。opencamp 社区内容丰富、质量上乘，是一次令人愉快的学习体验。后续还会继续参与类似项目。

# 第二阶段

- 官方通过要求
  - rCore-Camp-Guide-2025S 文档（通过要求）的课后练习

- 参考资料
  - CSAPP
    - 重点补充：第 7 章 链接过程
  - 操作系统导论
    - 快速回顾前 19 章内容
  - RISV手册
    - 重点理解：解特权级切换
  - rCore-Tutorial-Book-v3 3.6.0-alpha.1 文档（核心）
  - rCore-Camp-Guide-2025S 文档（通过要求）
- 学习过程
  - 这一阶段持续了约一个月，重点围绕 rCore-Tutorial 详读源码与注释。课后题本身难度不大，但深入理解 rCore 的执行过程与实现细节则颇具挑战。计划后续通过整理文档、写文章的方式进一步复习与巩固。
- 感想
  - 从“移除应用执行环境支持”出发，到手动链接最简调度系统、构建时间片轮转机制、物理内存页帧管理与多级页表，再到文件系统、线程管理与用户态支持……整个过程让我系统性理解了操作系统的核心构件。以往只是停留在八股文式的“理解层面”，这次才真正从源码出发理解了“为什么这样设计”，并洞察背后的一致性原则与设计哲学。现代软件系统中常见的“新框架”“新技术”，本质上很多都是对底层原理的重新组合与包装。打牢这些底层基础，将对未来应对复杂系统设计提供极大帮助。第二阶段的 rCore 项目就是一个极佳的底层能力训练平台。

# 第三阶段
- 官方通过要求
  - 6道练习题，一道挑战题
- 参考资料
  - 学习视频
  - 文档：https://oslearning365.github.io/arceos-tutorial-book/
- 学习过程
  - 得益于第二阶段的深入积累，第三阶段在约三周内顺利完成任务。以文档为主导，同时配合源码阅读与实验。
- 感想
  - 这一阶段让我初步建立了对“组件化操作系统设计”的理解。ArceOS 的设计将 Rust、OS 内核抽象与组件化思想结合在一起，是极具前沿性的操作系统实践。ArceOS 所体现的“组件化操作系统设计”核心在于：如何在保障各模块职责边界清晰的同时，实现高度解耦却协同有序的组合机制。看似简单，但背后依赖于扎实的底层系统知识与成熟的架构设计思想。ArceOS 不仅是对底层操作系统设计理念的前沿探索，更启发我思考如何在不同工程场景中抽象、迁移并落地组件化设计思想。
# 总结
  - 总之，确实学到了很多，希望能完成四阶段，最后感谢开源训练营，感谢陈渝老师
