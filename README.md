<p align="center">
  <img src="./profile-header.svg" width="100%" alt="Lizhengzhong — Python、NLP、大语言模型与 AI Agents">
</p>

<p align="center">
  你好，我是 Lizhengzhong。我的主线很明确：用 Python 做 NLP、大语言模型和智能体。<br>
  希望模型不只会回答问题，也能记住上下文、调用工具，最后把事情做完。<br>
  时序建模是偶尔探索的支线——毕竟除了模型的下一句话，人也总想知道下一秒会发生什么。
</p>

<p align="center">
  <img src="./current-status.svg" width="100%" alt="当前正在构建 ScalarPulse，学习大语言模型智能体与评估方法">
</p>

## 👋 关于我

我正在沿着 **Python × NLP × LLM × AI Agents** 这条路学习和构建。比起把技术名词排成一堵墙，我更喜欢做一个真的能点、能跑、能复现的小项目——最好 README 还能让第一次来的朋友顺利跑起来。

> **输入：** 一段自然语言　·　**目标：** 一件真正被完成的事　·　**中间过程：** 模型、记忆、工具与评估

PyTorch 和实验可观测性工具，是我把想法变成项目的主要工程支撑。看到 loss 稳定下降会开心；看到 Agent 一次把工具调对，会更开心。

<p align="center">
  <img src="./focus-pills.svg" width="100%" alt="Python、NLP、大语言模型、AI Agents 与 PyTorch 技术方向">
</p>

## 🤖 我怎样理解一个 Agent

我喜欢的 Agent 不是“把同一句提示词多跑几遍”，而是能理解任务、寻找上下文、调用工具，并知道结果是否靠谱的完整工作流。

<p align="center">
  <img src="./agent-loop.svg" width="100%" alt="从用户输入、检索记忆、大模型推理、工具调用到结果评估的智能体工作流">
</p>

## 🚀 精选项目

<a href="https://github.com/lizhengzhong20-sketch/scalarpulse">
  <img src="./scalarpulse-card.svg" width="100%" alt="ScalarPulse 本地实时训练指标可视化工具">
</a>

ScalarPulse 是一个轻量、本地优先的 Python 训练指标看板。它不负责训练模型，而是把训练过程照亮：loss、F1、学习率、延迟、Token 用量和任意标量都可以实时画出来。

<p align="center">
  <a href="https://github.com/lizhengzhong20-sketch/scalarpulse"><strong>查看源码</strong></a>
  ·
  <a href="https://github.com/lizhengzhong20-sketch/scalarpulse#readme"><strong>中文文档</strong></a>
  ·
  <a href="https://github.com/lizhengzhong20-sketch/scalarpulse#30-%E7%A7%92%E4%BD%93%E9%AA%8C"><strong>30 秒体验</strong></a>
  ·
  <a href="https://github.com/lizhengzhong20-sketch/scalarpulse/actions/workflows/tests.yml"><strong>CI 状态</strong></a>
</p>

<details>
<summary><strong>📊 展开查看真实仪表盘</strong></summary>

<br>

[![ScalarPulse 实时训练指标看板](https://raw.githubusercontent.com/lizhengzhong20-sketch/scalarpulse/main/assets/dashboard.jpg)](https://github.com/lizhengzhong20-sketch/scalarpulse)

</details>

<details>
<summary><strong>🧭 当前任务队列</strong></summary>

<br>

- [x] 发布 ScalarPulse 的第一个可用版本。
- [x] 把项目文档改成中文主文档，让第一次来的朋友更容易跑起来。
- [ ] 用小型项目验证 NLP 与大语言模型的核心方法。
- [ ] 做一个会规划、会调用工具、而且能被评估的 Agent。
- [ ] 用 ScalarPulse 观察 Agent 的成功率、延迟与 Token 用量。
- [x] 从简单任务开始探索时序预测与异常检测 —— 已长成 TSBackLab 回测工作台。

</details>

<details>
<summary><strong>🧪 开发者运行日志</strong></summary>

<br>

- 对“先跑起来，再慢慢变漂亮”有一点执念。
- Debug 时经常先怀疑模型，最后发现是自己少写了一个参数。
- 喜欢小而清楚的工具，也相信好文档是功能的一部分。
- 正在努力把“它理论上可以”改成“你现在就能跑”。

</details>


<a href="https://github.com/lizhengzhong20-sketch/TSBackLab">
  <img src="./tsbacklab-card.svg" width="100%" alt="TSBackLab 时序预测训练与回测实验室">
</a>

TSBackLab 是那条"支线"长出来的工作台：一个时序预测的训练与回测框架。它最在乎的不是指标好看，而是时间语义诚实——可知性严格早于截点、验证固定取时间尾部、缺值不补零、任务账单执行前冻结；三种入口（YAML / CLI / Python / 页面）跑同一份配置，预测逐行一致。基线、梯度提升树、GRU 都通过同一个适配器协议接入，训练在独立进程里跑，关掉浏览器也不停。

<p align="center">
  <a href="https://github.com/lizhengzhong20-sketch/TSBackLab"><strong>查看源码</strong></a>
  ·
  <a href="https://github.com/lizhengzhong20-sketch/TSBackLab#readme"><strong>中文文档</strong></a>
  ·
  <a href="https://github.com/lizhengzhong20-sketch/TSBackLab/blob/main/docs/user-guide/quickstart.md"><strong>快速开始</strong></a>
  ·
  <a href="https://github.com/lizhengzhong20-sketch/TSBackLab/blob/main/docs/compatibility.md"><strong>兼容矩阵</strong></a>
</p>

<details>
<summary><strong>📊 展开查看真实页面</strong></summary>

<br>

[![TSBackLab 任务监控页](https://raw.githubusercontent.com/lizhengzhong20-sketch/TSBackLab/main/docs/screenshots/ui-monitor.png)](https://github.com/lizhengzhong20-sketch/TSBackLab)

</details>

<details>
<summary><strong>🧭 TSBackLab 待办</strong></summary>

<br>

- [x] 三入口一致性、防泄漏语义、任务服务与页面全部落地（159 项 Python 测试 + 端到端）。
- [ ] 在 Ubuntu 22.04 / 24.04 上实测 CPU 全量。
- [ ] 找一台真 NVIDIA 机器跑 GPU 验收与容器构建。

</details>

---

<p align="center">
  <sub>让模型听懂，让 Agent 动手；如果哪里不对，就打开 ScalarPulse 看看。</sub>
</p>
