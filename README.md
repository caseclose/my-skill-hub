# My Skill Hub

[English](README_en.md)

我个人制作的开源 Agent Skills 合集，涵盖浏览器与 macOS 自动化、本地数据看板、GPU 工具和组会汇报准备。

选择需要的 skill，前往对应公开仓库查看说明、下载和安装。各 skill 的代码、依赖、版本和发布包均由原仓库维护。

## Skills

### 🗂️ [Explain Your Work](https://github.com/caseclose/explain-your-work)

把实验日志、评测代码和具体案例整理成一页组会底稿，每个关键数字都附上出处。开会前可以让 Agent 扮演同事，一次追问一题，比如“导出了多少样本，训练实际读了多少？”

- **用法示例**　`eyw，给这次实验出一页组会底稿。` 或 `eyw，扮演同事追问我。`
- **适用环境**　Codex、Claude Code 等支持 Agent Skills 的客户端。普通聊天也可使用[独立提示词](https://github.com/caseclose/explain-your-work/blob/main/PROMPT.md)。
- **入口**　[在线体验组会追问](https://caseclose.github.io/explain-your-work/zh.html) · [中文安装说明](https://github.com/caseclose/explain-your-work/blob/main/README.zh-CN.md#快速开始) · [SKILL.md](https://github.com/caseclose/explain-your-work/blob/main/skills/explain-your-work/SKILL.md)

### 🖥️ [Computer Use Skill](https://github.com/caseclose/computer-use-skill)

通过独立 Chromium 会话操作网页，通过 macOS 辅助功能接口读取和操作原生应用。适合网页信息读取、表单填写、截图和多步骤界面操作。

- **适用环境：** Codex、WorkBuddy 等支持终端执行的 Agent；Node.js 20+。原生应用操作需要 macOS 与辅助功能授权。
- **入口：** [原仓库与安装说明](https://github.com/caseclose/computer-use-skill#readme) · [SKILL.md](https://github.com/caseclose/computer-use-skill/blob/main/skills/computer-use-skill/SKILL.md) · [Releases / WorkBuddy 技能包](https://github.com/caseclose/computer-use-skill/releases)

### 📊 [HTML Viewer](https://github.com/caseclose/html-viewer-skill)

把本地表格、JSON/JSONL、日志、图片和评测结果生成为网页或看板，通过本机 HTTP 服务查看，支持局域网访问。

- **适用环境：** Claude Code 等支持 `SKILL.md` 和 Python 脚本执行的 Agent；Python 3.8+，仅使用标准库。
- **入口：** [原仓库与安装说明](https://github.com/caseclose/html-viewer-skill#readme) · [SKILL.md](https://github.com/caseclose/html-viewer-skill/blob/main/SKILL.md)
- **使用提示：** 服务默认可被局域网访问且无鉴权；可使用 `--local-only` 限制为本机访问，或使用 `--require-key` 添加访问密钥。

### ⚡ [GPU Occupy](https://github.com/caseclose/gpu_utl_occupy_skill)

在指定 NVIDIA GPU 上运行可控负载，支持多卡、目标平均利用率、后台运行与状态查询。

- **适用环境：** Claude / CodeBuddy 等支持脚本执行的 Agent，也可作为独立命令行工具；需要 Python 3、CUDA 版 PyTorch 与 NVIDIA GPU。
- **入口：** [原仓库与使用说明](https://github.com/caseclose/gpu_utl_occupy_skill#readme) · [SKILL.md](https://github.com/caseclose/gpu_utl_occupy_skill/blob/main/SKILL.md)

## 如何使用

1. 按任务选择上面的 skill，打开它的原仓库。
2. 阅读原仓库 README，按所用 Agent 的方式安装，并配置所需依赖。
3. 查看原仓库的更新、发布版本与 Issues；下载和反馈也直接在原仓库进行。

## 关于这个 Hub

本仓库收录各 skill 的介绍和原仓库入口，具体实现与发布版本在各自的公开仓库维护。新增 skill 时，在此添加简介和公开仓库入口即可。
