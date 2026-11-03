# My Skill Hub

[简体中文](README.md)

A collection of open-source agent skills I created, covering browser and macOS automation, local data dashboards, and GPU utilities.

Choose a skill and visit its public repository for documentation, downloads, and installation. Each source repository maintains its own code, dependencies, versions, and release packages.

## Skills

### 🖥️ [Computer Use Skill](https://github.com/caseclose/computer-use-skill)

Operate webpages in a dedicated Chromium session and inspect or control native macOS apps through Accessibility. Useful for reading pages, filling forms, taking screenshots, and performing multi-step UI tasks.

- **Environment:** Codex, WorkBuddy, and other agents with terminal access; Node.js 20+. Native app control requires macOS and Accessibility permission.
- **Links:** [Source & installation](https://github.com/caseclose/computer-use-skill#readme) · [SKILL.md](https://github.com/caseclose/computer-use-skill/blob/main/skills/computer-use-skill/SKILL.md) · [Releases / WorkBuddy package](https://github.com/caseclose/computer-use-skill/releases)

### 📊 [HTML Viewer](https://github.com/caseclose/html-viewer-skill)

Turn local tables, JSON/JSONL, logs, images, and evaluation results into web pages or dashboards, served over a local HTTP server with optional LAN access.

- **Environment:** Claude Code and other agents that support `SKILL.md` and Python scripts; Python 3.8+, standard library only.
- **Links:** [Source & installation](https://github.com/caseclose/html-viewer-skill#readme) · [SKILL.md](https://github.com/caseclose/html-viewer-skill/blob/main/SKILL.md)
- **Usage note:** The server is LAN-accessible without authentication by default. Use `--local-only` for loopback access or `--require-key` for an access key.

### ⚡ [GPU Occupy](https://github.com/caseclose/gpu_utl_occupy_skill)

Run a controlled workload on selected NVIDIA GPUs, with multi-GPU support, target average utilization, background execution, and status queries.

- **Environment:** Claude / CodeBuddy and other agents with script execution, or standalone CLI use; Python 3, CUDA-enabled PyTorch, and NVIDIA GPUs.
- **Links:** [Source & usage](https://github.com/caseclose/gpu_utl_occupy_skill#readme) · [SKILL.md](https://github.com/caseclose/gpu_utl_occupy_skill/blob/main/SKILL.md)

## Getting started

1. Choose a skill above and open its source repository.
2. Follow that repository's README to install it for your agent and set up dependencies.
3. Use the source repository for updates, releases, downloads, and issue reports.

## About this hub

This repository collects skill descriptions and source repository links. Implementations and releases are maintained in each skill's public repository. To add a skill, add its description and public repository link here.
