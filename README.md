# RadioSim Agent 论文阅读笔记

&gt; 课题组论文阅读记录

## 论文信息

| 项目 | 内容 |
|:---|:---|
| **论文标题** | RadioSim Agent: Combining Large Language Models and Deterministic EM Simulators for Interactive Radio Map Analysis |
| **作者** | Sajjad Hussain, Conor Brennan |
| **来源** | arXiv:2511.05912v1, 2025 |
| **投稿会议** | EuCAP 2026 |
| **GitHub** | [sajjadhussa1n/radio-sim-agent](https://github.com/sajjadhussa1n/radio-sim-agent) |

## 核心内容

**一句话总结**：让大模型自己调用射线追踪工具做信号覆盖仿真，还能看懂热力图给你解释。

### 主要亮点
- 🤖 **LLM 规划器**：听懂自然语言指令，自动提取仿真参数
- 📡 **仿真工具库**：封装射线追踪，支持 LOS/REF/GREF/NLOS/BEL 多种传播机制
- 👁️ **视觉推理**：自动分析路径损耗热力图，生成语义描述
- 🔄 **完整闭环**：从"说人话"到"出结果"全自动

### 与课题组方向的关联
这篇论文的 **Agent + 仿真器** 思路和在做的多 Agent 协作通信信道仿真高度相关，可以作为技术参考。

## 文件说明

| 文件 | 说明 |
|:---|:---|
| `论文2.pdf` | 原始论文 PDF |
| `论文阅读：RadioSim Agent笔记.pdf` | 详细阅读笔记（含概念解释、流程拆解） |

## 阅读日期

2025年5月
