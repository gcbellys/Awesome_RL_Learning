# My-RL-Journey

本项目是我学习强化学习 (Reinforcement Learning) 的个人代码库，用于记录和实现从基础到进阶的各种经典算法。

## 核心参考资料

* ** Sutton & Barto 教材:** [Reinforcement Learning: An Introduction (第2版)](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)
* **数学基础 - 来自西湖大学赵世钰老师的课程教材官方 github 仓库:** [Mathematical Foundations of Reinforcement Learning (配套代码与视频)](https://github.com/MathFoundationRL/Book-Mathematical-Foundation-of-Reinforcement-Learning)  

    [Bilibili : Mathematical Foundations of Reinforcement Learning (配套视频)](https://www.bilibili.com/video/BV1sd4y167NS/?spm_id_from=333.337.search-card.all.click)

* **经典课程 - David Silver:** [UCL 强化学习课程](https://davidstarsilver.wordpress.com/teaching/)
* **代码实践参考:** [Code-of-RL-Beginning (中文实践)](https://github.com/ziwenhahaha/Code-of-RL-Beginning/tree/main)

## 文件夹结构

根据算法类型，本仓库的代码组织如下：
## 学习路线图

### 阶段一：RL 基础（数学基础）与 MDP

**核心目标：** 理解“决策过程”的形式化，掌握 Bellman 方程。

**学习目标：**
* **数学基础：** 掌握概率论、期望、马尔可夫链、动态规划（Bellman方程）。
* **核心概念：**
    * 马尔可夫决策过程（MDP）：状态 $S$、动作 $A$、转移概率 $P(s'|s,a)$、奖励函数 $R(s,a)$、折扣因子 $\gamma$。
    * 价值函数 $V(s)$、状态–动作价值函数 $Q(s,a)$。
    * Bellman 方程与最优性原理。

**对应参考章节：**

| 资源 | 对应章节/内容 |
| :--- | :--- |
| **Sutton & Barto** | **Chapter 1-3** (The RL Problem, Finite MDPs) |
| **Zhao《数学基础》** | **Chapter 1-3** (Basic Concepts, Bellman Equation, Bellman Optimality) |
| **David Silver 课程** | **Lecture 1** (Introduction to RL), **Lecture 2** (MDPs) |

---

### 阶段二：经典算法与在线学习

**核心目标：** 掌握传统的“表格型”RL算法，理解无模型学习和探索-利用。

**学习目标：**
* **动态规划 (DP)：** Value Iteration, Policy Iteration（已知模型）。
* **蒙特卡洛方法 (MC)：** 基于采样、无模型。
* **时序差分 (TD) 学习：** TD(0), SARSA, Q-learning（在线学习代表）。
* **探索–利用平衡：** $\epsilon$-greedy, UCB, softmax 策略。

**对应参考章节：**

| 资源 | 对应章节/内容 |
| :--- | :--- |
| **Sutton & Barto** | **Chapter 4** (DP), **Chapter 5** (MC), **Chapter 6** (TD Learning) |
| **Zhao《数学基础》** | **Chapter 4** (DP), **Chapter 5** (MC), **Chapter 7** (TD Methods) |
| **David Silver 课程** | **Lecture 3** (DP), **Lecture 4** (MC/TD Prediction), **Lecture 5** (MC/TD Control) |
| **代码实践参考** | 对应仓库中的 `2-Policy_Iteration`, `3-Value_Iteration`, `4-MC`, `5-TD` 等文件夹 |