<div align="center">

# Awesome Automated Research

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![GitHub Stars](https://img.shields.io/github/stars/MinhaoXiong/awesome-automated-research?style=for-the-badge&logo=github&color=gold)](https://github.com/MinhaoXiong/awesome-automated-research/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/MinhaoXiong/awesome-automated-research?style=for-the-badge&logo=github)](https://github.com/MinhaoXiong/awesome-automated-research/issues)
[![Projects](https://img.shields.io/badge/Projects-39-blue?style=for-the-badge)](https://github.com/MinhaoXiong/awesome-automated-research)
[![Snapshot](https://img.shields.io/badge/Snapshot-2026--03--22-green?style=for-the-badge)](https://github.com/MinhaoXiong/awesome-automated-research)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

**A curated list of autonomous research systems and tools.**

*39 projects · 8 categories · End-to-end AI scientists · Experiment loops · Research co-pilots · Skill packs · Paper tools · Benchmarks*

[English](#) | [中文](./README.zh.md)

</div>

---

## What Is This?

AI can now carry out research autonomously — from generating ideas and running experiments to writing full papers. This repository tracks the open-source ecosystem making that happen.

| Without these tools | With these tools |
|---|---|
| You spend weeks reading literature | AI reads 500 papers in 10 minutes |
| You manually iterate on experiments | AI runs overnight loops: tweak → run → score → keep or revert |
| You write papers from scratch | AI generates camera-ready LaTeX drafts with figures |
| You review your own blind spots | AI self-reviews, cross-checks, and iterates |

> **39 projects** tracked as of 2026-03-22.

---

## Quick Guide

| If you want to... | Start here |
| --- | --- |
| Fully automate idea → paper | [End-to-End AI Scientists](#end-to-end-ai-scientists) |
| Optimize code metrics overnight | [Experiment Optimization Loops](#experiment-optimization-loops) |
| Get an AI research co-pilot | [Research Co-pilots & Interactive Agents](#research-co-pilots--interactive-agents) |
| Set up a research workspace | [Research Workspaces](#research-workspaces) |
| Add research skills to your agent | [Skill & Workflow Packs](#skill--workflow-packs) |
| Search papers or make figures | [Literature Search, Citation & Paper Tools](#literature-search-citation--paper-tools) |
| Go deep in bio/med | [Vertical Domain Agents](#vertical-domain-agents) |
| Evaluate AI research quality | [Benchmarks & Evaluation](#benchmarks--evaluation) |

<!-- Hidden for now: | Build agent infrastructure | [Agent Infrastructure & Runtimes](#agent-infrastructure--runtimes) | -->

## Contents

- [People To Follow](#people-to-follow)
- [Project Type Overview](#project-type-overview)
- [Category Tables](#category-tables)
- [Events & Conferences](#events--conferences)
- [X News & Trends](#x-news--trends)
- [Related Lists](#related-lists)
- [Contributing](#contributing)

---

## People To Follow

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

## Project Type Overview

| Category | Count | Representative Repos |
| --- | ---: | --- |
| End-to-End AI Scientists | 7 | AI-Scientist, AutoResearchClaw, Kosmos, NanoResearch |
| Experiment Optimization Loops | 5 | autoresearch, pi-autoresearch, codex-autoresearch |
| Research Co-pilots & Interactive Agents | 3 | EvoScientist, Amadeus, ScienceClaw |
| Research Workspaces | 3 | dr-claw, Research-Claw, DrClaw |
| Skill & Workflow Packs | 8 | claude-scientific-skills, AI-Research-SKILLs, ARIS, uditgoenka/autoresearch |
| Literature Search, Citation & Paper Tools | 5 | paper-search-mcp, PaperBanana, CitationClaw |
| Vertical Domain Agents | 2 | MedgeClaw, BioClaw |
| Benchmarks & Evaluation | 2 | ResearchClawBench, paperreview.ai |

<!-- Hidden for now: | Agent Infrastructure & Runtimes | 4 | ToolUniverse, infiAgent, station | -->

---

## Category Tables

Interface: ![CLI][i-cli] terminal tool · ![Skill][i-skill] agent plugin / skill pack · ![Web][i-web] browser · ![ChatOps][i-chatops] messaging · ![MCP][i-mcp] MCP server · ![Runtime][i-runtime] background daemon · ![OC][i-oc] OpenClaw

### End-to-End AI Scientists

Fully autonomous pipelines that carry the research loop from idea or literature all the way to paper-like output without requiring human steering at each stage.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [AI-Scientist](https://github.com/SakanaAI/AI-Scientist) | 12.5K | First open-source system to autonomously generate ideas, run experiments, and write research papers | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![DeepSeek][ds] ![Open-weight][ow] | last 1 year |
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | 7.5K | Give it a research idea, get back a complete paper with figures and peer review | ![CLI][i-cli] ![ChatOps][i-chatops] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![DeepSeek][ds] | last 1 week |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | 2.3K | Next-gen AI Scientist that explores research directions via tree search without needing templates | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] | last 1 year |
| [SibylSystem](https://github.com/Sibyl-Research-Team/AutoResearch-SibylSystem) | 185 | Give it a topic, it runs 19 stages to produce a conference-style paper and self-improves across runs | ![CLI][i-cli] ![Skill][i-skill] ![Web][i-web] | ![Claude][cl] ![GPT][gpt] | last 1 week |
| [NanoResearch](https://github.com/OpenRaiser/NanoResearch) | 160 | 9-stage pipeline that runs real GPU/SLURM experiments, analyzes results, and writes LaTeX papers with grounded evidence | ![CLI][i-cli] ![Skill][i-skill] ![ChatOps][i-chatops] | ![Claude][cl] ![GPT][gpt] ![DeepSeek][ds] ![Gemini][gem] | last 1 week |
| [FARS](https://analemma.ai/) | — | Public Analemma deployment of a multi-agent system that runs ideation, planning, experiments, and short-paper writing at scale | ![Web][i-web] | ![Any][any] | last 1 month |
| [Kosmos](https://github.com/jimmc414/Kosmos) | 471 | Autonomous discovery engine that tests hypotheses in sandboxed containers and tracks findings in a knowledge graph | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![LiteLLM][ll] | last 3 month |

---

### Experiment Optimization Loops

Tight modify-run-score-keep/discard loops. The goal is repeated metric improvement on a runnable target, not broad research coverage.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [autoresearch](https://github.com/karpathy/autoresearch) | 48.8K | The original overnight loop: AI tweaks code, runs experiments, keeps what works, reverts what doesn't | ![CLI][i-cli] | ![Claude][cl] ![Codex][cdx] | last 1 week |
| [pi-autoresearch](https://github.com/davebcn87/pi-autoresearch) | 2.7K | Generic version of the autoresearch loop that works on any measurable optimization target | ![Skill][i-skill] | ![Any][any] | last 1 week |
| [codex-autoresearch](https://github.com/leo-lilinxiao/codex-autoresearch) | 473 | Autoresearch loop built for OpenAI Codex with smart recovery when stuck | ![Skill][i-skill] | ![Codex][cdx] | last 1 week |
| [autoresearch-mlx](https://github.com/trevin-creator/autoresearch-mlx) | 941 | Karpathy's autoresearch loop adapted for Apple Silicon Macs using MLX | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] | last 1 month |
| [autoresearch-claude-code](https://github.com/drivelineresearch/autoresearch-claude-code) | 182 | Autoresearch loop ported to Claude Code as a drop-in skill | ![Skill][i-skill] | ![Claude][cl] | last 1 month |

---

### Research Co-pilots & Interactive Agents

Capable research agents that work alongside humans rather than running fully unattended. Includes interactive frameworks, discovery engines, and multi-purpose research assistants.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [EvoScientist](https://github.com/EvoScientist/EvoScientist) | 1.4K | Interactive research assistant you chat with via terminal, Telegram, Slack, or WeChat | ![CLI][i-cli] ![ChatOps][i-chatops] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![Ollama][ol] | last 1 week |
| [Amadeus](https://github.com/CurryTang/Amadeus) | 49 | Personal research assistant that reads, summarizes, and organizes papers with multi-pass AI analysis and ARIS workflows | ![Web][i-web] ![MCP][i-mcp] | ![Claude][cl] ![Gemini][gem] ![Codex][cdx] | last 1 week |
| [ScienceClaw](https://github.com/beita6969/ScienceClaw) | 301 | Long-running research coworker that generates new skills at runtime and retains context across sessions | ![Skill][i-skill] ![OC][i-oc] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] | last 1 month |

---

### Research Workspaces

Persistent research operating surfaces — IDEs, dashboards, and multi-agent team environments where human and agent researchers coordinate work over time.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [dr-claw](https://github.com/OpenLAIR/dr-claw) | 598 | Browser-based research IDE with chat, file explorer, terminal, and research dashboard in one window | ![Web][i-web] | ![Claude][cl] ![Gemini][gem] ![Codex][cdx] | last 1 week |
| [Research-Claw](https://github.com/wentorai/Research-Claw) | 369 | Academic workspace with built-in literature manager, task board, and arXiv monitoring | ![Web][i-web] | ![Claude][cl] ![GPT][gpt] | last 1 week |
| [DrClaw](https://github.com/InternScience/DrClaw) | 127 | 24/7 AI research team you manage from browser, desktop app, or chat | ![Web][i-web] ![ChatOps][i-chatops] | ![Claude][cl] ![Codex][cdx] ![GLM][glm] ![Kimi][km] | last 1 week |

---

### Skill & Workflow Packs

Reusable skill bundles, workflow templates, agent plugins, and scaffolding that research agents can directly consume. These are not standalone applications — they extend host agents.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills) | 15.8K | 170+ plug-and-play research skills for Claude Code, Cursor, Codex, and other agents | ![Skill][i-skill] | ![Any][any] | last 1 week |
| [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 5.4K | Reusable skills covering the full ML research lifecycle from literature survey to paper writing | ![Skill][i-skill] | ![Any][any] | last 1 week |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | 3K | 38 first-level skills that chain into a full overnight workflow: find ideas, run experiments, review, write paper | ![Skill][i-skill] | ![Claude][cl] ![Codex][cdx] | last 1 week |
| [uditgoenka/autoresearch](https://github.com/uditgoenka/autoresearch) | 1.7K | Multi-purpose Claude Code plugin: optimization loop, debug, fix, security audit, ship, and predict in one skill | ![Skill][i-skill] | ![Claude][cl] | last 1 week |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | 1.5K | Biomedical skill pack for OpenClaw agents covering clinical, pharma, and precision medicine | ![Skill][i-skill] ![OC][i-oc] | ![Any][any] | last 1 week |
| [LabClaw](https://github.com/wu-yc/LabClaw) | 835 | 240 lab-oriented skills spanning biology, pharmacy, medicine, literature, and visualization | ![Skill][i-skill] ![OC][i-oc] | ![Any][any] | last 1 week |
| [autoresearch-skill](https://github.com/olelehmann100kMRR/autoresearch-skill) | 429 | A skill that optimizes other skills: mutates prompts and keeps versions that score higher | ![Skill][i-skill] | ![Claude][cl] | last 1 week |
| [PaperClaw](https://github.com/guhaohao0991/PaperClaw) | 169 | Scaffolding tool that generates domain-specific paper-reading agents from templates | ![Skill][i-skill] ![OC][i-oc] | ![Any][any] | last 1 month |

---

<!--
### Agent Infrastructure & Runtimes

The harder infrastructure layer: tool platforms, long-running runtimes, supervisors, and simulation environments that other systems build on.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [infiAgent](https://github.com/polyuiislab/infiAgent) | 1.1K | Agent runtime designed for tasks that run for hours or days without losing progress | ![Runtime][i-runtime] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![Qwen][qw] | last 1 week |
| [ToolUniverse](https://github.com/mims-harvard/ToolUniverse) | 1.1K | Unified access to 1000+ scientific tools via CLI, MCP server, or Python SDK | ![MCP][i-mcp] ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![Qwen][qw] ![DeepSeek][ds] ![Open-weight][ow] | last 1 week |
| [ArgusBot](https://github.com/waltstephen/ArgusBot) | 249 | Watchdog that keeps your Codex or Claude agent loops running until the job is done | ![Runtime][i-runtime] | ![Claude][cl] ![Codex][cdx] | last 1 week |
| [station](https://github.com/dualverse-ai/station) | 111 | Open-world simulation environment where multiple AI agents explore and do research together | ![Web][i-web] | ![Claude][cl] ![GPT][gpt] | last 3 month |

---
-->

### Literature Search, Citation & Paper Tools

Paper retrieval, citation analysis, academic visualization, and publishing layers. These tools focus on the literature-facing and output-facing sides of research.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [PaperBanana](https://github.com/dwzhu-pku/PaperBanana) | 5.3K | Turns paper content into publication-quality academic illustrations and diagrams | ![CLI][i-cli] ![Web][i-web] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] | last 1 month |
| [paper-search-mcp](https://github.com/openags/paper-search-mcp) | 857 | Searches 20+ academic databases (arXiv, PubMed, Semantic Scholar, etc.) at once via MCP | ![MCP][i-mcp] | ![Agnostic][ag] | last 1 week |
| [CitationClaw](https://github.com/VisionXLab/CitationClaw) | 200 | Analyzes who cites your papers, why, and generates visual impact dashboards | ![Web][i-web] ![CLI][i-cli] | ![OpenAI-compatible][oaic] | last 1 week |
| [ClawPhD](https://github.com/ZhihaoAIRobotic/ClawPhD) | 136 | Converts papers into posters, diagrams, websites, and other shareable assets | ![CLI][i-cli] | ![Claude][cl] ![GPT][gpt] ![Gemini][gem] ![DeepSeek][ds] | last 1 week |
| [autoresearcher](https://github.com/eimenhmdt/autoresearcher) | 423 | Takes a research question and produces an automated literature review from Semantic Scholar | ![CLI][i-cli] | ![GPT][gpt] | over 1 year |

---

### Vertical Domain Agents

Deep single-domain agents that win by specializing in one scientific vertical rather than trying to be universal.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [BioClaw](https://github.com/Runchuan-BU/BioClaw) | 243 | Bioinformatics chatbot with BLAST, SAMtools, FastQC and other bio tools in isolated containers | ![ChatOps][i-chatops] ![Web][i-web] | ![Claude][cl] ![OpenAI-compatible][oaic] | last 1 week |
| [MedgeClaw](https://github.com/xjtulyc/MedgeClaw) | 925 | Biomedical research assistant with 140 specialized skills and multi-platform messaging | ![ChatOps][i-chatops] ![Web][i-web] | ![Claude][cl] ![Ollama][ol] ![GLM][glm] ![DeepSeek][ds] | last 1 month |

---

### Benchmarks & Evaluation

Frameworks and services that measure how well AI agents do research — scoring papers, comparing against human baselines, and grading agent outputs.

| Project | Stars | Description | Interface | LLM | Update Recency |
| --- | ---: | --- | --- | --- | --- |
| [ResearchClawBench](https://github.com/InternScience/ResearchClawBench) | 21 | Benchmark with 40 real-science tasks across 10 domains that evaluates whether AI agents can produce publication-quality research | ![Web][i-web] ![CLI][i-cli] | ![Any][any] | last 1 week |
| [paperreview.ai](https://paperreview.ai) | — | Agentic paper reviewer by Stanford that scores research papers on novelty, rigor, and clarity | ![Web][i-web] | — | last 1 week |

---

---

## Events & Conferences

> Last updated: 2026-03-22

| Type | Event | Date | Why it matters |
| --- | --- | --- | --- |
| Conference | [CAISc 2026](https://caisc2026.github.io/) | `submissions open 2026-04-15` | AI authors + AI reviewers — directly tests the limits of agent-driven research |
| Conference | [Claw4S Conference 2026](https://claw4s.github.io/) | `deadline 2026-04-05` | Submit an executable `SKILL.md`, not a PDF — $50K prizes, up to 364 winners |
| Hackathon | [SciMaster 上海西岸科研黑客松](https://mp.weixin.qq.com/s/example) | `2026-03-27` | SciMaster + BohrClaw + OpenClaw, 48 hours to produce a paper |
| Hackathon | [Stanford AI × Scientific Replication](https://datascience.stanford.edu/events/center-decoding-universe/hackathon-human-meets-ai-scientific-research-replication) | `2026` | Reproduce key results from papers using AI agents — bridging KIPAC, SLAC, HAI, and CS |

## X News & Trends

<table>
<thead>
<tr>
<th width="110">Date</th>
<th>Event</th>
<th width="88">Likes</th>
<th width="72">Link</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>03-19</code></td>
<td>DARPA expMath launches OpenGauss — automated formal math exploration goes official</td>
<td>2.2K</td>
<td><a href="https://x.com/i/web/status/2034700606498083025">𝕏</a></td>
</tr>
<tr>
<td><code>03-18</code></td>
<td>OpenAI Parameter Golf challenge becomes an agent auto-tuning hotspot</td>
<td>4K</td>
<td><a href="https://x.com/i/web/status/2034315401438580953">𝕏</a></td>
</tr>
<tr>
<td><code>03-17</code></td>
<td>MCP for arXiv released — paper retrieval infrastructure for research agents heats up</td>
<td>3K</td>
<td><a href="https://x.com/i/web/status/2034003206217601375">𝕏</a></td>
</tr>
<tr>
<td><code>03-16</code></td>
<td>NVIDIA launches NemoClaw — enterprise-grade OpenClaw agent deployment</td>
<td>4.1K</td>
<td><a href="https://x.com/i/web/status/2033642064009957725">𝕏</a></td>
</tr>
<tr>
<td><code>03-16</code></td>
<td>AutoResearchClaw goes viral: "one idea in, full paper out"</td>
<td>2.4K</td>
<td><a href="https://x.com/i/web/status/2033584901858202073">𝕏</a></td>
</tr>
<tr>
<td><code>03-15</code></td>
<td>AutoResearchClaw official launch: "one message in, full conference paper out"</td>
<td>1.5K</td>
<td><a href="https://x.com/i/web/status/2033038170653405308">𝕏</a></td>
</tr>
<tr>
<td><code>03-14</code></td>
<td>Hyperspace generalizes Karpathy's loop into a plain-English swarm optimization network</td>
<td>5.1K</td>
<td><a href="https://x.com/i/web/status/2032671842230501729">𝕏</a></td>
</tr>
<tr>
<td><code>03-12</code></td>
<td>MetaClaw goes viral — deployed agents that continuously learn and hot-swap skills</td>
<td>1.1K</td>
<td><a href="https://x.com/i/web/status/2032012243915980900">𝕏</a></td>
</tr>
<tr>
<td><code>03-11</code></td>
<td>autoresearch applied to market trading — 25 agents iterate daily strategies via Sharpe feedback</td>
<td>3.9K</td>
<td><a href="https://x.com/i/web/status/2031821234795659717">𝕏</a></td>
</tr>
<tr>
<td><code>03-10</code></td>
<td>Karpathy's <code>autoresearch.md</code> continues spreading as the methodology gateway post</td>
<td>3K</td>
<td><a href="https://x.com/i/web/status/2031473248320311326">𝕏</a></td>
</tr>
</tbody>
</table>

## Related Lists

We refer to and recommend several curated paper lists and repositories:

- [handsome-rich/Awesome-Auto-Research-Tools](https://github.com/handsome-rich/Awesome-Auto-Research-Tools)
- [WangRongsheng/awesome-LLM-resources](https://github.com/WangRongsheng/awesome-LLM-resources)

## Contributing

If you have projects, people, or lists worth recommending, feel free to open a PR.

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
[any]: https://img.shields.io/badge/Any-888?style=flat-square
[ag]: https://img.shields.io/badge/Agnostic-888?style=flat-square
