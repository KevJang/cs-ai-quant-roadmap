# CS/AI/Quant 转轨日程表

适用对象：金融工程大四、几乎无课程压力、目标是 AI infra 型 AI 研究员或量化私募 ML 研究员。

总节奏：每周 6 天主学习 + 1 天复盘；每天 6-8 小时。若当天状态差，执行“保底版”。

## 每日固定模板

### 标准日，6-8 小时

- 09:00-10:30：课程视频/讲义
- 10:45-12:15：课程作业/代码实现
- 14:00-16:00：项目或 lab
- 16:15-17:15：LeetCode/Kaggle/论文
- 19:30-20:30：复盘、README、Git commit

### 保底日，2 小时

- 45 分钟：看 1 个 lecture 或读讲义
- 60 分钟：写代码/做作业
- 15 分钟：写打卡日志

### 每日打卡

```text
日期：
今日主线：
完成：
代码提交：
卡点：
明天第一步：
```

## 资源总入口

### 编程与数据结构

- Berkeley CS61A：https://cs61a.org/
- CS61A Projects：https://cs61a.org/projects/
- Berkeley CS61B：https://sp25.datastructur.es/
- CS61B Projects：https://sp25.datastructur.es/projects/

### 算法

- MIT 6.006 OCW：https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/
- 6.006 Assignments：https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/pages/assignments/

### ML/DL/NLP

- Stanford CS229：https://cs229.stanford.edu/
- Stanford CS231n：https://cs231n.stanford.edu/
- CS231n Assignments：https://cs231n.github.io/
- Stanford CS224n：https://web.stanford.edu/class/cs224n/
- Karpathy Zero to Hero：https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ
- Stanford CS336：https://stanford-cs336.github.io/spring2025/

### 计算机系统

- CSAPP 官网：https://csapp.cs.cmu.edu/
- CMU 15-213 课程：https://www.cs.cmu.edu/~213/
- MIT 6.S081：https://pdos.csail.mit.edu/6.S081/
- MIT 6.824/6.5840：https://pdos.csail.mit.edu/6.824/
- CMU 15-445：https://15445.courses.cs.cmu.edu/
- Stanford CS149：https://gfxcourses.stanford.edu/cs149/fall23/

### AI Infra

- CMU 10-414/714 Deep Learning Systems：https://dlsyscourse.org/
- DLSys Assignments：https://dlsyscourse.org/assignments/
- Full Stack Deep Learning：https://fullstackdeeplearning.com/course/

### Quant / Kaggle

- Kaggle Learn：https://www.kaggle.com/learn
- Kaggle Competitions：https://www.kaggle.com/competitions
- Georgia Tech ML4T：https://lucylabs.gatech.edu/ml4t/
- Udacity ML for Trading：https://www.udacity.com/course/machine-learning-for-trading--ud501

## 24 周路线总表

| 周数 | 主线 | 交付物 |
|---|---|---|
| 0 | 环境搭建 + Python/数据基线 | Titanic baseline repo |
| 1 | CS61A 编程抽象 | Hog 或等价 Python 项目 |
| 2 | CS61A OOP/递归/树 | 文本分析或股票数据分析项目 |
| 3 | CS61B 数据结构 I | Deque/Map 项目 |
| 4 | CS61B 数据结构 II | Gitlet 简化版或图算法项目 |
| 5 | MIT 6.006 排序/哈希/二分 | 算法 notebook + 20 题 |
| 6 | MIT 6.006 树/堆/图 | DAG 调度器 |
| 7 | 动态规划 | DP 题集 + 总结 |
| 8 | 数学补强 | NumPy logistic/softmax |
| 9 | CS229 监督学习 | House Prices pipeline |
| 10 | 树模型/Kaggle | LightGBM/XGBoost pipeline |
| 11 | 神经网络基础 | NumPy MLP + PyTorch MLP |
| 12 | CS231n CNN | CIFAR-10 classifier |
| 13 | CS224n/Transformer | character LM |
| 14 | Karpathy mini-GPT | mini-gpt repo |
| 15 | CSAPP/组成 I | cache simulator |
| 16 | CSAPP/组成 II | malloc/memory demo |
| 17 | MIT 6.S081 OS I | xv6 util/syscall |
| 18 | MIT 6.S081 OS II | page table/lock lab |
| 19 | CMU 15-445 DB | buffer pool/B+tree |
| 20 | MIT 6.824 分布式 | MapReduce lab |
| 21 | DLSys autograd | mini-autograd |
| 22 | DLSys NN framework | mini-pytorch MNIST |
| 23 | CS149/CUDA | matmul/softmax kernel |
| 24 | AI Infra 综合 | LLM inference 或 kernel benchmark |

## 第 0 周：从今天开始

### Day 1：工具链和总仓库

- 安装/确认：Python、Git、VS Code、Jupyter、PyTorch。
- 注册：GitHub、Kaggle、Hugging Face。
- 创建仓库：`cs-ai-quant-roadmap`。
- 文件结构：

```text
cs-ai-quant-roadmap/
  week00_setup/
  cs61a/
  cs61b/
  algorithms/
  ml/
  dl/
  systems/
  ai_infra/
  quant/
  kaggle/
  notes/
```

交付：

- `week00_setup/README.md`
- 一次 Git commit

### Day 2：Python + Titanic baseline

- 打开 Kaggle Learn Python：https://www.kaggle.com/learn/python
- 完成 Python 前 4 节。
- 下载 Titanic 数据并跑通 sklearn baseline。

交付：

- `kaggle/titanic_baseline.ipynb`
- 提交一次 Kaggle submission。

### Day 3：NumPy/Pandas

- Kaggle Pandas：https://www.kaggle.com/learn/pandas
- 完成前 4 节。
- 给 Titanic baseline 加 EDA：缺失值、类别特征、年龄分箱。

交付：

- `kaggle/titanic_eda.ipynb`

### Day 4：Git + README

- 学会 `clone/add/commit/push/branch`。
- 给 Titanic 项目写 README：
  - 问题
  - 数据
  - 特征
  - 模型
  - 分数
  - 下一步

交付：

- `kaggle/README.md`

### Day 5：CS61A 入门

- 打开 CS61A：https://cs61a.org/
- 看 Week 1 lecture。
- 做对应 lab/discussion 中的基础题。

交付：

- `cs61a/week01_notes.md`
- `cs61a/week01_solutions.py`

### Day 6：CS61A Hog 项目启动

- 打开 CS61A Projects：https://cs61a.org/projects/
- 开始 Hog。
- 目标：完成 Phase 1。

交付：

- `cs61a/hog/`

### Day 7：复盘日

- 整理本周卡点。
- 写第一篇博客草稿：
  - 我从金融工程转 CS/AI 的第 1 周
  - 我补了什么
  - 我还不会什么
  - 下周怎么做

交付：

- `notes/week00_review.md`

## 每周复盘模板

```text
本周主题：
完成的课程：
完成的代码：
完成的项目：
最难的 3 个点：
下周必须解决：
作品集更新：
```

## 规则

- 只看课不做作业，算未完成。
- 没有 README 的项目，算半完成。
- 没有 Git commit 的学习，算不可追踪。
- Kaggle 不追求一开始排名，先追求完整 pipeline。
- 系统课不要跳过。AI infra 的壁垒就在组成、OS、分布式、并行计算。

