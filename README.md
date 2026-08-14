<div align="center">

<img src="https://raw.githubusercontent.com/catiseyeqaq/catiseyeqaq/main/assets/google-gemini-hero.svg?v=20260814" alt="YuXuanLin · AI × Engineering" width="100%" />

# YuXuanLin

### AI × Engineering · Multimodal Agents · Computer Vision · Local LLM · Generative AI

**Building deployable AI systems for real-world engineering scenarios.**  
面向真实工程场景，构建可部署、可审计、可扩展的智能体与多模态 AI 系统。

<a href="https://github.com/catiseyeqaq?tab=followers"><img src="https://raw.githubusercontent.com/catiseyeqaq/catiseyeqaq/main/assets/pill-followers.svg?v=20260814" alt="Followers" /></a>
<a href="https://github.com/catiseyeqaq?tab=stars"><img src="https://raw.githubusercontent.com/catiseyeqaq/catiseyeqaq/main/assets/pill-stars.svg?v=20260814" alt="Stars" /></a>
<a href="mailto:catiseyeqaq@163.com"><img src="https://raw.githubusercontent.com/catiseyeqaq/catiseyeqaq/main/assets/pill-email.svg?v=20260814" alt="Email" /></a>

</div>

---

## About

我是 **YuXuanLin**，人工智能方向硕士研究生，长期关注 **行业智能体、计算机视觉、多模态推理、大模型私有化部署与生成式 AI**。

我更关注“把模型做成系统”而不是只停留在单模型 Demo：从感知、证据聚合、规则推理与 RAG，到 Agent 编排、工具调用、人工复核、报告/台账与本地部署，形成可以持续迭代的完整闭环。

> **Current focus:** Engineering Agents · Multimodal Reasoning · Local AI Infrastructure · AI Film / Short Drama

---

## Flagship Projects

<table>
<tr>
<td width="100%">

### 🚁 Land-Air Integrated Safety Inspection Agent

[![Status](https://img.shields.io/badge/STATUS-ACTIVE-1a73e8?style=flat-square)](https://github.com/catiseyeqaq/lu-kong-yi-ti-hua-an-quan-zhi-neng-xun-jian-agent)
[![Agent](https://img.shields.io/badge/Agent-Orchestration-4285F4?style=flat-square)](https://github.com/catiseyeqaq/lu-kong-yi-ti-hua-an-quan-zhi-neng-xun-jian-agent)
[![CV](https://img.shields.io/badge/CV-Detector%20%2B%20VLM-34A853?style=flat-square)](https://github.com/catiseyeqaq/lu-kong-yi-ti-hua-an-quan-zhi-neng-xun-jian-agent)
[![RAG](https://img.shields.io/badge/RAG-Safety%20Knowledge-FBBC04?style=flat-square)](https://github.com/catiseyeqaq/lu-kong-yi-ti-hua-an-quan-zhi-neng-xun-jian-agent)

面向施工现场与低空无人机巡检的多模态安全智能体。将 **影像接入 → 目标/场景识别 → 结构化证据 → 风险研判 → 安全知识检索 → 整改台账** 编排为可追踪闭环。

<p align="center">
  <img src="https://raw.githubusercontent.com/catiseyeqaq/catiseyeqaq/main/assets/flagship-landair-architecture.svg?v=20260814" alt="Land-Air Inspection Agent Architecture" width="100%" />
</p>

**Highlights**
- `InspectionAgentOrchestrator`：统一单图、批量架次、问答与整改流程
- `ToolRegistry + SiteMemory + Trace`：工具协议、会话记忆与全过程审计
- 外部视觉推理内核与 Agent 层解耦，可替换检测器 / VLM / 知识库 / 报告适配器
- 生产边界明确：私有模型、真实数据、现场媒体与知识库均由部署侧受控提供

➡️ **[Open Repository](https://github.com/catiseyeqaq/lu-kong-yi-ti-hua-an-quan-zhi-neng-xun-jian-agent)**

</td>
</tr>

<tr>
<td width="100%">

### 💧 Smart Water Management Agent

[![Release](https://img.shields.io/badge/RELEASE-v1.0.0-0f766e?style=flat-square)](https://github.com/catiseyeqaq/zhihui-shuiwu-zonghe-guanli-agent-xitong)
[![Topology](https://img.shields.io/badge/Graph-Topology-4285F4?style=flat-square)](https://github.com/catiseyeqaq/zhihui-shuiwu-zonghe-guanli-agent-xitong)
[![Forecast](https://img.shields.io/badge/Time--Series-Forecasting-34A853?style=flat-square)](https://github.com/catiseyeqaq/zhihui-shuiwu-zonghe-guanli-agent-xitong)
[![Local](https://img.shields.io/badge/LLM-Local%20Deployment-A142F4?style=flat-square)](https://github.com/catiseyeqaq/zhihui-shuiwu-zonghe-guanli-agent-xitong)

面向供水管网分析与运维辅助的公开示例 Agent。围绕 **管网拓扑、运行时序、风险关系、证据约束分析与可视化** 构建可复现流水线，并提供 CLI / Python API / HTML Dashboard / Open WebUI 适配。

<p align="center">
  <img src="https://raw.githubusercontent.com/catiseyeqaq/catiseyeqaq/main/assets/flagship-water-dashboard.svg?v=20260814" alt="Smart Water Management Agent Dashboard" width="100%" />
</p>

**Highlights**
- 拓扑与时序联合分析，支持部署侧真实数据 ETL / 校准接口
- 风险关系保留来源与人工核验状态，避免将生成内容直接当作生产事实
- 公开仓库默认使用合成数据，真实管网与监测资料不进入 Git
- 面向本地私有化部署，适合数据敏感的工程场景

➡️ **[Open Repository](https://github.com/catiseyeqaq/zhihui-shuiwu-zonghe-guanli-agent-xitong)**

</td>
</tr>

<tr>
<td width="100%">

### 🎬 AI Film & Short Drama Generation System

[![Status](https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-FBBC04?style=flat-square)](https://github.com/catiseyeqaq/ai-manju-shengcheng-xitong)
[![ComfyUI](https://img.shields.io/badge/ComfyUI-Workflow-4285F4?style=flat-square)](https://github.com/catiseyeqaq/ai-manju-shengcheng-xitong)
[![H3](https://img.shields.io/badge/MiniMax--H3-T2V%20%7C%20I2V%20%7C%20R2V-EA4335?style=flat-square)](https://github.com/catiseyeqaq/ai-manju-shengcheng-xitong)
[![PPU](https://img.shields.io/badge/Local-8%C3%97PPU--ZW810E-34A853?style=flat-square)](https://github.com/catiseyeqaq/ai-manju-shengcheng-xitong)

面向 **写实 AI 电影 / 短剧 / 商业视频** 的本地生产流水线。以 ComfyUI 为编排层，整合 MiniMax-H3、Qwen、角色一致性与关键帧工作流，覆盖从创意到镜头生成的完整链路。

<p align="center">
  <img src="https://raw.githubusercontent.com/catiseyeqaq/catiseyeqaq/main/assets/flagship-aifilm.gif?v=20260814" alt="AI Film & Short Drama — real generated footage showcase" width="100%" />
</p>

**Highlights**
- 中文创意 / 分镜 → Prompt Polish → Keyframe → T2V / I2V / R2V → 音画对齐
- `majicFlus + PuLID + FaceDetailer`：角色定妆、跨镜脸锁与细节修复
- MiniMax-H3 首尾帧桥接与原生音视频生成
- 已沉淀 **33 套 ComfyUI 工作流**，支持本地 PPU 多卡生产

➡️ **[Open Repository](https://github.com/catiseyeqaq/ai-manju-shengcheng-xitong)**

</td>
</tr>
</table>

---

## Selected Engineering Projects

<table>
<tr>
<td width="33%" valign="top">

### 🛸 UAV Thermal Detection

高空热成像小目标人员检测。基于改进 YOLO，引入 `SPDConv / BiFPN / P2 / NWD` 等结构，公开项目记录 **mAP50 ≈ 0.94**（基于项目文档化评估配置）。

**[Repository →](https://github.com/catiseyeqaq/wurenji-gaokong-rechengxiang-dimian-renyuan-jiance-xitong)**

</td>
<td width="33%" valign="top">

### ⛏️ Coal Gangue Recognition

煤块 / 矸石智能识别与端到端应用，集成改进 YOLO、Gradio 可视化、语音播报与串口联动。

**[Repository →](https://github.com/catiseyeqaq/meikuai-yu-gangshi-zidong-shibie-xitong)**

</td>
<td width="33%" valign="top">

### 🐱 Pet Behavior Monitoring

视觉 + 音频多模态宠物行为分析，覆盖行为识别、声音理解、风险提示与饲养建议。

**[Repository →](https://github.com/catiseyeqaq/Real-time-Monitoring-and-Analysis-of-Pet-Behavior)**

</td>
</tr>
</table>

> 🌉 **Bridge Inspection Agent** — 城市路桥隧边坡结构病害识别、描述生成、知识检索与分级评定，当前持续开发中。

---

## What I Build

| Layer | Focus |
|---|---|
| **Perception** | Object Detection · Small Object Detection · UAV Vision · Multimodal Perception |
| **Reasoning** | VLM · Evidence Aggregation · Spatial / Rule Reasoning · RAG |
| **Agent** | Tool Calling · Workflow Orchestration · Memory · Trace · Human Review |
| **Generation** | ComfyUI · T2V / I2V / R2V · Character Consistency · AI Film Pipeline |
| **Infrastructure** | Local LLM / VLM · SGLang · OpenAI-compatible API · Linux · Docker · PPU |
| **Delivery** | CLI · Python API · Web UI · Dashboard · Report / Ledger · Commercial Integration |

---

## Engineering Principles

- **Local-first when data is sensitive** — 对工程私有数据优先采用本地推理与受控存储。
- **Evidence before conclusion** — 重要结论尽量保留来源、结构化证据与可审计 trace。
- **Model-agnostic architecture** — Agent、工具协议与模型服务解耦，允许替换 detector / VLM / LLM。
- **Human-in-the-loop for high-stakes outputs** — 安全、运维与生产决策保留人工确认边界。
- **Reproducible engineering** — 用版本、配置、测试、日志和明确的数据边界保证可复现性。

---

## Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-4285F4?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EA4335?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-34A853?style=for-the-badge&logo=opencv&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1A73E8?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-5F6368?style=for-the-badge&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-EA4335?style=for-the-badge&logo=git&logoColor=white)

![YOLO](https://img.shields.io/badge/YOLO-111111?style=for-the-badge)
![Qwen](https://img.shields.io/badge/Qwen-VLM%20%2F%20LLM-7B61FF?style=for-the-badge)
![SGLang](https://img.shields.io/badge/SGLang-Serving-A142F4?style=for-the-badge)
![ComfyUI](https://img.shields.io/badge/ComfyUI-111111?style=for-the-badge)
![MiniMax](https://img.shields.io/badge/MiniMax--H3-Video-FBBC04?style=for-the-badge)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)

</div>

---

## Open Source & Commercial Boundary

公开仓库主要用于展示 **Agent 架构、工程实现、工作流、接口与可复现示例**。

模型权重、真实工程数据、现场媒体、私有知识库、密钥与生产部署配置不会随公开仓库分发。各项目的开源 / 商用边界以对应仓库的 `LICENSE` 与说明文件为准。

---

## GitHub Overview

<div align="center">

<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=catiseyeqaq&theme=github" alt="GitHub Stats" />
<img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=catiseyeqaq&theme=github" alt="Top Languages" />

</div>

---

## Connect

<div align="center">

**Research Collaboration · Industrial AI · Engineering Agents · Commercial Delivery**

<a href="https://github.com/catiseyeqaq"><img src="https://img.shields.io/badge/GitHub-catiseyeqaq-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
<a href="mailto:catiseyeqaq@163.com"><img src="https://img.shields.io/badge/Email-catiseyeqaq%40163.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<sub>Build systems, not demos.</sub>

</div>
