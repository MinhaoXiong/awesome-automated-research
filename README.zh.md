<div align="center">

# Awesome Automated Research

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![GitHub Stars](https://img.shields.io/github/stars/MinhaoXiong/awesome-automated-research?style=for-the-badge&logo=github&color=gold)](https://github.com/MinhaoXiong/awesome-automated-research/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/MinhaoXiong/awesome-automated-research?style=for-the-badge&logo=github)](https://github.com/MinhaoXiong/awesome-automated-research/issues)
[![Projects](https://img.shields.io/badge/Projects-40-blue?style=for-the-badge)](https://github.com/MinhaoXiong/awesome-automated-research)
[![Snapshot](https://img.shields.io/badge/Snapshot-2026--03--22-green?style=for-the-badge)](https://github.com/MinhaoXiong/awesome-automated-research)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

**一份关于自主科研系统与工具的精选清单。**

*40 个项目 · 8 个类别 · 端到端 AI Scientist · 实验循环 · 科研副驾 · 技能包 · 论文工具 · 基准评测*

[English](./README.md) | [中文](#)

</div>

---

<a id="what-is-this"></a>
## 这是什么？

AI 现在已经可以自主承担科研流程中的很多关键环节，从生成想法、运行实验，到撰写完整论文。这份仓库追踪的就是推动这件事发生的开源生态。

| 没有这些工具时 | 有了这些工具后 |
|---|---|
| 你要花几周读文献 | AI 可以在 10 分钟内读完 500 篇论文 |
| 你手动迭代实验 | AI 可以整夜循环：修改 → 运行 → 打分 → 保留或回滚 |
| 你从零开始写论文 | AI 可以生成带图表的接近 camera-ready 的 LaTeX 草稿 |
| 你只能靠自己发现盲点 | AI 可以自我审阅、交叉核对并继续迭代 |

> 截至 2026-03-22，当前共收录 **40 个项目**。

---

<a id="quick-guide"></a>
## 快速导航

| 如果你想要…… | 先看这里 |
| --- | --- |
| 全自动跑通 idea → paper | [端到端 AI Scientists](#end-to-end-ai-scientists) |
| 夜间自动优化代码指标 | [实验优化循环](#experiment-optimization-loops) |
| 找一个 AI 科研副驾 | [科研副驾与交互式智能体](#research-co-pilots--interactive-agents) |
| 搭一个科研工作台 | [科研工作台](#research-workspaces) |
| 给你的 agent 加科研技能 | [技能与工作流包](#skill--workflow-packs) |
| 搜论文或自动出图 | [文献检索、引文与论文工具](#literature-search-citation--paper-tools) |
| 深入生物医药方向 | [垂直领域智能体](#vertical-domain-agents) |
| 评估 AI 的科研质量 | [基准与评测](#benchmarks--evaluation) |

<!-- Hidden for now: | 搭 agent 基础设施 | [Agent Infrastructure & Runtimes](#agent-infrastructure--runtimes) | -->

<a id="contents"></a>
## 目录

- [值得关注的人](#people-to-follow)
- [项目类型概览](#project-type-overview)
- [分类表格](#category-tables)
- [活动与会议](#events--conferences)
- [X 新闻与趋势](#x-news--trends)
- [相关列表](#related-lists)
- [贡献与推荐](#contributing)

---

<a id="people-to-follow"></a>
## 值得关注的人

<table>
<tr>
<td align="center" width="180"><a href="https://www.xiaohongshu.com/user/profile/60a27d65000000000101ecaa"><b>戴眼镜的小胖</b></a><br><code>dr-claw</code><br><sub>小红书 · 9.1K</sub></td>
<td align="center" width="180"><a href="https://www.xiaohongshu.com/user/profile/63380adf000000001802e9f9"><b>万万万水吟</b></a><br><code>ARIS</code><br><sub>小红书 · 7.9K</sub></td>
<td align="center" width="180"><a href="https://www.xiaohongshu.com/user/profile/594dfada82ec3952750f8cf8"><b>Huaxiu Yao</b></a><br><code>MetaClaw</code><br><sub>小红书 · 4.2K</sub></td>
<td align="center" width="180"><a href="https://www.xiaohongshu.com/user/profile/6978249e00000000240096b2"><b>日行迹Analemma</b></a><br><code>FARS official</code><br><sub>小红书 · 3K</sub></td>
</tr>
<tr>
<td align="center"><a href="https://www.xiaohongshu.com/user/profile/5d26440200000000110247ea"><b>刘思源</b></a><br><code>ThesisAgent owner</code><br><sub>小红书 · 2K</sub></td>
<td align="center"><a href="https://www.xiaohongshu.com/user/profile/5cd05b9c0000000011039a2d"><b>孙天祥</b></a><br><code>FARS / Analemma</code><br><sub>小红书 · 1千+</sub></td>
<td align="center"><a href="https://www.xiaohongshu.com/user/profile/68fd89fa00000000370286c4"><b>Intern Science</b></a><br><code>DrClaw</code><br><sub>小红书</sub></td>
<td align="center"><a href="https://www.xiaohongshu.com/user/profile/62ea8db7000000001f004043"><b>谷昊昊</b></a><br><code>PaperClaw</code><br><sub>小红书</sub></td>
</tr>
<tr>
<td align="center"><a href="https://x.com/karpathy"><b>Andrej Karpathy</b></a><br><code>autoresearch</code><br><sub>𝕏 · 1.98M</sub></td>
<td align="center"><a href="https://x.com/hardmaru"><b>David Ha</b></a><br><code>AI-Scientist</code><br><sub>𝕏 · 392K</sub></td>
<td align="center"><a href="https://x.com/SakanaAILabs"><b>Sakana AI</b></a><br><code>AI-Scientist series</code><br><sub>𝕏 · 63K</sub></td>
<td align="center"><a href="https://x.com/k_dense_ai"><b>K-Dense-AI</b></a><br><code>claude-scientific-skills</code><br><sub>𝕏 · 2.3K</sub></td>
</tr>
<tr>
<td align="center"><a href="https://x.com/davebcn87"><b>davebcn87</b></a><br><code>pi-autoresearch</code><br><sub>𝕏 · 1.1K</sub></td>
<td align="center"><a href="https://x.com/JiaqiLiu835914"><b>Jiaqi Liu</b></a><br><code>AutoResearchClaw</code><br><sub>𝕏</sub></td>
<td align="center"></td>
<td align="center"></td>
</tr>
</table>

---

<a id="project-type-overview"></a>
## 项目类型概览

| 类别 | 数量 | 代表项目 |
| --- | ---: | --- |
| 端到端 AI Scientists | 8 | AI-Scientist, AutoResearchClaw, InternAgent, NanoResearch |
| 实验优化循环 | 5 | autoresearch, pi-autoresearch, codex-autoresearch |
| 科研副驾与交互式智能体 | 3 | EvoScientist, Amadeus, ScienceClaw |
| 科研工作台 | 3 | dr-claw, Research-Claw, DrClaw |
| 技能与工作流包 | 8 | claude-scientific-skills, AI-Research-SKILLs, ARIS, uditgoenka/autoresearch |
| 文献检索、引文与论文工具 | 5 | paper-search-mcp, PaperBanana, CitationClaw |
| 垂直领域智能体 | 2 | MedgeClaw, BioClaw |
| 基准与评测 | 2 | ResearchClawBench, paperreview.ai |

<!-- Hidden for now: | Agent Infrastructure & Runtimes | 4 | ToolUniverse, infiAgent, station | -->

---

<a id="category-tables"></a>
## 分类表格

接口：![CLI][i-cli] 命令行工具 · ![Skill][i-skill] agent 插件 / skill 包 · ![Web][i-web] 浏览器 · ![ChatOps][i-chatops] 消息入口 · ![MCP][i-mcp] MCP server · ![Runtime][i-runtime] 后台守护进程 · ![OC][i-oc] OpenClaw

<a id="end-to-end-ai-scientists"></a>
### 端到端 AI Scientists

这类系统尽量把科研闭环从想法或文献起点一路推进到类似论文的输出，中间不需要人类在每一步都亲自接管。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [AI-Scientist](https://github.com/SakanaAI/AI-Scientist) | 12.5K | 第一套真正开源的系统，能自主生成想法、运行实验并撰写科研论文 | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![DeepSeek][ds] ![Open-weight][ow] | 1 年内 |
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | 7.5K | 给它一个研究想法，它会返回完整论文、图表和审稿结果 | ![CLI][i-cli] ![ChatOps][i-chatops] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![DeepSeek][ds] | 1 周内 |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | 2.3K | 下一代 AI Scientist，通过树搜索探索研究方向，不再依赖固定模板 | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] | 1 年内 |
| [InternAgent](https://github.com/InternScience/InternAgent) | 1.2K | 统一的长时程自主科研框架，把 deep research、可执行验证和记忆驱动演化串成算法发现与实证发现闭环 | ![CLI][i-cli] ![Web][i-web] | ![GPT][gpt] ![DeepSeek][ds] ![InternS1][is1] | 1 周内 |
| [SibylSystem](https://github.com/Sibyl-Research-Team/AutoResearch-SibylSystem) | 185 | 你给一个主题，它会跑完 19 个阶段，产出会议风格论文，并能在多轮运行中自我改进 | ![CLI][i-cli] ![Skill][i-skill] ![Web][i-web] | ![Claude][cl] ![GPT][gpt] | 1 周内 |
| [NanoResearch](https://github.com/OpenRaiser/NanoResearch) | 160 | 9 阶段流水线，能跑真实 GPU/SLURM 实验、分析结果，并基于证据撰写 LaTeX 论文 | ![CLI][i-cli] ![Skill][i-skill] ![ChatOps][i-chatops] | ![Claude][cl] ![GPT][gpt] ![DeepSeek][ds] ![Gemini][gem] | 1 周内 |
| [FARS](https://analemma.ai/) | — | Analemma 对外公开的多智能体系统，能规模化完成想法、规划、实验和短论文写作 | ![Web][i-web] | ![Any][any] | 1 个月内 |
| [Kosmos](https://github.com/jimmc414/Kosmos) | 471 | 自主发现引擎，会在沙盒容器里测试假设，并用知识图谱追踪发现过程 | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![LiteLLM][ll] | 3 个月内 |

---

<a id="experiment-optimization-loops"></a>
### 实验优化循环

这类项目强调紧凑的“修改 - 运行 - 打分 - 保留或丢弃”闭环，目标是持续提升可运行对象的指标，而不是覆盖完整科研全流程。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [autoresearch](https://github.com/karpathy/autoresearch) | 48.8K | 最原始的 overnight loop：AI 改代码、跑实验、保留有效改动、回滚无效改动 | ![CLI][i-cli] | ![Claude][cl] ![Codex][cdx] | 1 周内 |
| [pi-autoresearch](https://github.com/davebcn87/pi-autoresearch) | 2.7K | autoresearch 循环的通用版本，适用于任何可度量的优化目标 | ![Skill][i-skill] | ![Any][any] | 1 周内 |
| [codex-autoresearch](https://github.com/leo-lilinxiao/codex-autoresearch) | 473 | 面向 OpenAI Codex 的 autoresearch 循环，带有卡住时的智能恢复能力 | ![Skill][i-skill] | ![Codex][cdx] | 1 周内 |
| [autoresearch-mlx](https://github.com/trevin-creator/autoresearch-mlx) | 941 | Karpathy 的 autoresearch 循环在 Apple Silicon + MLX 上的适配版 | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] | 1 个月内 |
| [autoresearch-claude-code](https://github.com/drivelineresearch/autoresearch-claude-code) | 182 | 移植到 Claude Code 的 autoresearch 循环，可直接作为 skill 使用 | ![Skill][i-skill] | ![Claude][cl] | 1 个月内 |

---

<a id="research-co-pilots--interactive-agents"></a>
### 科研副驾与交互式智能体

这类研究智能体更偏和人协作，而不是完全无人值守。包括交互式框架、发现引擎和多用途科研助手。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [EvoScientist](https://github.com/EvoScientist/EvoScientist) | 1.4K | 可通过终端、Telegram、Slack 或 WeChat 交互的科研助手 | ![CLI][i-cli] ![ChatOps][i-chatops] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![Ollama][ol] | 1 周内 |
| [Amadeus](https://github.com/CurryTang/Amadeus) | 49 | 个人科研助手，负责读取、总结和组织论文，并做多轮 AI 分析与 ARIS 工作流衔接 | ![Web][i-web] ![MCP][i-mcp] | ![Claude][cl] ![Gemini][gem] ![Codex][cdx] | 1 周内 |
| [ScienceClaw](https://github.com/beita6969/ScienceClaw) | 301 | 长时运行的科研搭子，能在运行时生成新技能，并跨会话保持上下文 | ![Skill][i-skill] ![OC][i-oc] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] | 1 个月内 |

---

<a id="research-workspaces"></a>
### 科研工作台

这类项目提供持续性的科研操作界面，例如 IDE、仪表板、多智能体团队面板，让人和 agent 可以长期协同推进研究。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [dr-claw](https://github.com/OpenLAIR/dr-claw) | 598 | 浏览器内科研 IDE，把聊天、文件浏览器、终端和研究看板整合在同一窗口 | ![Web][i-web] | ![Claude][cl] ![Gemini][gem] ![Codex][cdx] | 1 周内 |
| [Research-Claw](https://github.com/wentorai/Research-Claw) | 369 | 学术工作台，自带文献管理、任务看板和 arXiv 监控能力 | ![Web][i-web] | ![Claude][cl] ![GPT][gpt] | 1 周内 |
| [DrClaw](https://github.com/InternScience/DrClaw) | 127 | 一个 24/7 的 AI 科研团队，你可以通过浏览器、桌面应用或聊天入口来管理 | ![Web][i-web] ![ChatOps][i-chatops] | ![Claude][cl] ![Codex][cdx] ![GLM][glm] ![Kimi][km] | 1 周内 |

---

<a id="skill--workflow-packs"></a>
### 技能与工作流包

这类项目提供可复用的技能包、工作流模板、agent 插件和脚手架，可被科研 agent 直接消费。它们本身不是独立应用，而是扩展宿主 agent 的能力。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | 15.8K | 170+ 即插即用科研技能，适用于 Claude Code、Cursor、Codex 等各类 agent | ![Skill][i-skill] | ![Any][any] | 1 周内 |
| [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 5.4K | 覆盖完整 ML 科研生命周期的可复用技能，从文献综述到论文写作都有 | ![Skill][i-skill] | ![Any][any] | 1 周内 |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | 3K | 38 个一级技能可以串成完整夜间科研工作流：找想法、跑实验、审阅、写论文 | ![Skill][i-skill] | ![Claude][cl] ![Codex][cdx] | 1 周内 |
| [uditgoenka/autoresearch](https://github.com/uditgoenka/autoresearch) | 1.7K | 面向 Claude Code 的多用途插件：优化循环、调试、修复、安全审计、发布、预测都放在一个 skill 里 | ![Skill][i-skill] | ![Claude][cl] | 1 周内 |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | 1.5K | 面向 OpenClaw agent 的生物医学技能包，覆盖临床、制药和精准医学 | ![Skill][i-skill] ![OC][i-oc] | ![Any][any] | 1 周内 |
| [LabClaw](https://github.com/wu-yc/LabClaw) | 835 | 240 个偏实验室场景的技能，覆盖生物、药学、医学、文献和可视化 | ![Skill][i-skill] ![OC][i-oc] | ![Any][any] | 1 周内 |
| [autoresearch-skill](https://github.com/olelehmann100kMRR/autoresearch-skill) | 429 | 一个专门优化其他 skill 的 skill：会变异 prompt，并保留得分更高的版本 | ![Skill][i-skill] | ![Claude][cl] | 1 周内 |
| [PaperClaw](https://github.com/guhaohao0991/PaperClaw) | 169 | 脚手架工具，可从模板生成面向特定领域的论文阅读 agent | ![Skill][i-skill] ![OC][i-oc] | ![Any][any] | 1 个月内 |

---

<!--
<a id="agent-infrastructure--runtimes"></a>
### Agent 基础设施与运行时

更底层的一层：工具平台、长时运行时、监督器和仿真环境，其他系统往往构建在它们之上。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [infiAgent](https://github.com/polyuiislab/infiAgent) | 1.1K | 面向长达数小时或数天任务的 agent 运行时，不会轻易丢失进度 | ![Runtime][i-runtime] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![Qwen][qw] | 1 周内 |
| [ToolUniverse](https://github.com/mims-harvard/ToolUniverse) | 1.1K | 统一接入 1000+ 科学工具，可通过 CLI、MCP server 或 Python SDK 使用 | ![MCP][i-mcp] ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![Qwen][qw] ![DeepSeek][ds] ![Open-weight][ow] | 1 周内 |
| [ArgusBot](https://github.com/waltstephen/ArgusBot) | 249 | 守护器，帮你让 Codex 或 Claude 的 agent 循环一直跑到任务完成 | ![Runtime][i-runtime] | ![Claude][cl] ![Codex][cdx] | 1 周内 |
| [station](https://github.com/dualverse-ai/station) | 111 | 开放世界仿真环境，让多个 AI agent 一起探索并做研究 | ![Web][i-web] | ![Claude][cl] ![GPT][gpt] | 3 个月内 |

---
-->

<a id="literature-search-citation--paper-tools"></a>
### 文献检索、引文与论文工具

这类项目聚焦科研流程的文献侧和产出侧，包括论文检索、引文分析、学术可视化和发表包装。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [PaperBanana](https://github.com/dwzhu-pku/PaperBanana) | 5.3K | 将论文内容转换成可发表级别的学术插图和示意图 | ![CLI][i-cli] ![Web][i-web] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] | 1 个月内 |
| [paper-search-mcp](https://github.com/openags/paper-search-mcp) | 857 | 通过 MCP 一次搜索 20+ 学术数据库，如 arXiv、PubMed、Semantic Scholar 等 | ![MCP][i-mcp] | ![Agnostic][ag] | 1 周内 |
| [CitationClaw](https://github.com/VisionXLab/CitationClaw) | 200 | 分析谁在引用你的论文、为什么引用，并生成可视化影响力面板 | ![Web][i-web] ![CLI][i-cli] | ![OpenAI-compatible][oaic] | 1 周内 |
| [ClawPhD](https://github.com/ZhihaoAIRobotic/ClawPhD) | 136 | 将论文转换成海报、图示、网站等更易传播的外部呈现形式 | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![DeepSeek][ds] | 1 周内 |
| [autoresearcher](https://github.com/eimenhmdt/autoresearcher) | 423 | 输入一个研究问题，自动基于 Semantic Scholar 产出文献综述 | ![CLI][i-cli] | ![GPT][gpt] | 1 年以上 |

---

<a id="vertical-domain-agents"></a>
### 垂直领域智能体

这类项目通过深入单一科学领域取胜，而不是试图做一个覆盖所有学科的通用系统。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [BioClaw](https://github.com/Runchuan-BU/BioClaw) | 243 | 生物信息学聊天机器人，集成 BLAST、SAMtools、FastQC 等生信工具，并在隔离容器中运行 | ![ChatOps][i-chatops] ![Web][i-web] | ![Claude][cl] ![OpenAI-compatible][oaic] | 1 周内 |
| [MedgeClaw](https://github.com/xjtulyc/MedgeClaw) | 925 | 生物医学科研助手，内置 140 个专业技能，并支持多平台消息入口 | ![ChatOps][i-chatops] ![Web][i-web] | ![Claude][cl] ![Ollama][ol] ![GLM][glm] ![DeepSeek][ds] | 1 个月内 |

---

<a id="benchmarks--evaluation"></a>
### 基准与评测

这类框架和服务用于衡量 AI agent 的科研能力，包括论文打分、和人类基线对比，以及对 agent 产出的整体评分。

| 项目 | Stars | 简介 | 接口 | LLM | 最近更新 |
| --- | ---: | --- | --- | --- | --- |
| [ResearchClawBench](https://github.com/InternScience/ResearchClawBench) | 21 | 一个包含 10 个领域、40 个真实科研任务的 benchmark，用来评估 AI agent 是否能产出接近发表质量的研究 | ![Web][i-web] ![CLI][i-cli] | ![Any][any] | 1 周内 |
| [paperreview.ai](https://paperreview.ai) | — | 来自 Stanford 的 agentic 论文审稿器，对论文的新颖性、严谨性和清晰度进行评分 | ![Web][i-web] | — | 1 周内 |

---

---

<a id="events--conferences"></a>
## 活动与会议

> 最后更新：2026-03-22

| 类型 | 活动 | 日期 | 为什么重要 |
| --- | --- | --- | --- |
| Conference | [CAISc 2026](https://caisc2026.github.io/) | `2026-04-15 开放投稿` | AI 作者 + AI 审稿人，直接测试 agent 驱动科研的上限 |
| Conference | [Claw4S Conference 2026](https://claw4s.github.io/) | `2026-04-05 截止` | 提交的是可执行 `SKILL.md`，不是 PDF；奖金总额 5 万美元，最多 364 个获奖名额 |
| Hackathon | [SciMaster 上海西岸科研黑客松](https://mp.weixin.qq.com/s/example) | `2026-03-27` | SciMaster + BohrClaw + OpenClaw，48 小时内产出一篇论文 |
| Hackathon | [Stanford AI × Scientific Replication](https://datascience.stanford.edu/events/center-decoding-universe/hackathon-human-meets-ai-scientific-research-replication) | `2026` | 用 AI agent 复现实验论文关键结果，连接 KIPAC、SLAC、HAI 和 CS 社群 |

<a id="x-news--trends"></a>
## X 新闻与趋势

<table>
<thead>
<tr>
<th width="110">日期</th>
<th>事件</th>
<th width="88">点赞</th>
<th width="72">链接</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>03-19</code></td>
<td>DARPA expMath 推出 OpenGauss，自动化形式化数学探索正式进入机构级项目阶段</td>
<td>2.2K</td>
<td><a href="https://x.com/i/web/status/2034700606498083025">𝕏</a></td>
</tr>
<tr>
<td><code>03-18</code></td>
<td>OpenAI Parameter Golf challenge 成为 agent 自动调参的热门战场</td>
<td>4K</td>
<td><a href="https://x.com/i/web/status/2034315401438580953">𝕏</a></td>
</tr>
<tr>
<td><code>03-17</code></td>
<td>面向 arXiv 的 MCP 发布，科研 agent 的论文检索基础设施开始升温</td>
<td>3K</td>
<td><a href="https://x.com/i/web/status/2034003206217601375">𝕏</a></td>
</tr>
<tr>
<td><code>03-16</code></td>
<td>NVIDIA 发布 NemoClaw，面向企业的 OpenClaw agent 部署方案出现</td>
<td>4.1K</td>
<td><a href="https://x.com/i/web/status/2033642064009957725">𝕏</a></td>
</tr>
<tr>
<td><code>03-16</code></td>
<td>AutoResearchClaw 爆火：“一个想法输入，整篇论文输出”</td>
<td>2.4K</td>
<td><a href="https://x.com/i/web/status/2033584901858202073">𝕏</a></td>
</tr>
<tr>
<td><code>03-15</code></td>
<td>AutoResearchClaw 官方发布：“一条消息输入，完整会议论文输出”</td>
<td>1.5K</td>
<td><a href="https://x.com/i/web/status/2033038170653405308">𝕏</a></td>
</tr>
<tr>
<td><code>03-14</code></td>
<td>Hyperspace 将 Karpathy 的循环范式推广成自然语言驱动的群体优化网络</td>
<td>5.1K</td>
<td><a href="https://x.com/i/web/status/2032671842230501729">𝕏</a></td>
</tr>
<tr>
<td><code>03-12</code></td>
<td>MetaClaw 爆火，持续学习并热切换技能的部署型 agent 开始进入大众视野</td>
<td>1.1K</td>
<td><a href="https://x.com/i/web/status/2032012243915980900">𝕏</a></td>
</tr>
<tr>
<td><code>03-11</code></td>
<td>autoresearch 被用于市场交易，25 个 agent 通过 Sharpe 反馈日更策略</td>
<td>3.9K</td>
<td><a href="https://x.com/i/web/status/2031821234795659717">𝕏</a></td>
</tr>
<tr>
<td><code>03-10</code></td>
<td>Karpathy 的 <code>autoresearch.md</code> 持续传播，成为这套方法论的入口帖子</td>
<td>3K</td>
<td><a href="https://x.com/i/web/status/2031473248320311326">𝕏</a></td>
</tr>
</tbody>
</table>

<a id="related-lists"></a>
## 相关列表

我们也推荐下面这些整理过的论文列表和仓库：

- [handsome-rich/Awesome-Auto-Research-Tools](https://github.com/handsome-rich/Awesome-Auto-Research-Tools)
- [WangRongsheng/awesome-LLM-resources](https://github.com/WangRongsheng/awesome-LLM-resources)

<a id="contributing"></a>
## 贡献与推荐

如果你有值得推荐的项目、人物或列表，欢迎提交 PR。

<!-- Interface badge references -->
[i-cli]: ./assets/icons/cli.svg
[i-skill]: ./assets/icons/skill.svg
[i-web]: ./assets/icons/web.svg
[i-chatops]: ./assets/icons/chatops.svg
[i-mcp]: https://img.shields.io/badge/MCP-E65100?style=flat-square
[i-runtime]: https://img.shields.io/badge/Runtime-B91C1C?style=flat-square
[i-oc]: ./assets/icons/oc.svg

<!-- LLM badge references -->
[cl]: https://img.shields.io/badge/Claude-cc785c?logo=anthropic&logoColor=white&style=flat-square
[gpt]: https://img.shields.io/badge/GPT-412991?logo=openai&logoColor=white&style=flat-square
[cdx]: https://img.shields.io/badge/Codex-412991?logo=openai&logoColor=white&style=flat-square
[oaic]: https://img.shields.io/badge/OpenAI--compatible-412991?logo=openai&logoColor=white&style=flat-square
[gem]: https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white&style=flat-square
[ds]: https://img.shields.io/badge/DeepSeek-536AF5?style=flat-square
[qw]: https://img.shields.io/badge/Qwen-6E3AFF?style=flat-square
[glm]: https://img.shields.io/badge/GLM-3D5AFE?style=flat-square
[km]: https://img.shields.io/badge/Kimi-000?style=flat-square
[ol]: https://img.shields.io/badge/Ollama-000?logo=ollama&logoColor=white&style=flat-square
[ow]: https://img.shields.io/badge/Open--weight-2EA44F?style=flat-square
[ll]: https://img.shields.io/badge/LiteLLM-7C3AED?style=flat-square
[is1]: https://img.shields.io/badge/InternS1-1F6FEB?style=flat-square
[any]: https://img.shields.io/badge/Any-888?style=flat-square
[ag]: https://img.shields.io/badge/Agnostic-888?style=flat-square
