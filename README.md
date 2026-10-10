# Hermes Skills Master

A complete, production-ready collection of 121 procedural skills for [Hermes Agent](https://hermes-agent.nousresearch.com/docs).
It provides system instructions, automation workflows, architectural patterns, and reference code snippets across AI engineering, desktop automation, web scraping, MLOps, software development, and productivity.

Interface & Documentation: English. Fully anonymized and safe for public deployment.

**Requires:** Hermes Agent (v0.5.0+) · Python 3.10+ · Windows 10/11 / macOS / Linux

## Quick start

### Load into Hermes Agent

To use the full master collection in your local Hermes Agent instance, you can either reference the single consolidated file or split skills into your profile directory:

```bash
# Clone the repository
git clone https://github.com/MohammadMehdiSadeghi/hermes-skills-master.git
cd hermes-skills-master

# Copy the master skills pack to your desktop or workspace
cp hermes_skills_master.md ~/Desktop/
```

### Install Skills into Hermes Profile

To copy individual skills directly into your Hermes Agent active skills directory:

```bash
# On Linux/macOS
cp -r skills/* ~/.hermes/skills/

# On Windows (Command Prompt / PowerShell)
xcopy /E /I /Y skills %LOCALAPPDATA%\hermes\skills
```

## What it contains

The master skills collection spans **121 specialized modules** across 20 primary domains:

* 🤖 **Autonomous AI Agents (9 skills)** — Orchestrate subagents using Claude Code, Codex, and OpenCode; drive Windows GUI and Chrome via PyWinAuto, CDP, and CUA background automation.
* 🎨 **Creative & Visual Design (9 skills)** — Author dark-mode architecture diagrams, Baoyu infographics, Figma UI design tokens, Excalidraw JSON drawings, and throwaway HTML mockups.
* 💻 **Software Development (44 skills)** — Pre-commit code reviews, Test-Driven Development (TDD), Next.js / Vite migrations, TypeScript setups, security auditing (OWASP Top 10, PHP), and automated refactoring.
* 🌐 **Networking & Infrastructure (5 skills)** — Deploy Cloudflare Workers VLESS VPNs, provision proxy nodes, configure v2rayN / SOCKS5 proxies, and diagnose network drops.
* 📊 **MLOps & AI Model Serving (4 skills)** — Verify AI API providers, interact with HuggingFace Hub, serve local GGUF models via llama.cpp, and optimize 9router local model routing.
* 📄 **Productivity & Document Processing (19 skills)** — Generate and edit Word `.docx`, Excel `.xlsx`, and PDF files; execute natural language OCR; integrate with Notion and Google Workspace APIs.
* 🔬 **Research & Knowledge Retrieval (6 skills)** — Search arXiv papers, monitor competitor news with cited digests, build Karpathy-style LLM wikis, and enforce grounded citation standards.
* 📩 **Messaging & Telegram Gateway (5 skills)** — Build Telegram bots (PTB / API), manage Hermes Telegram Gateway instances, scrape public channels, and automate digest delivery.
* 🔒 **Security & Disk Audit (2 skills)** — Audit local Windows disk usage, clean application caches, and review PHP/Web API security postures.

## Structure

* **`README.md`** — Overview, installation instructions, and category breakdown.
* **`hermes_skills_master.md`** — Consolidated single-file markdown containing all 121 skills, complete with YAML frontmatter, detailed instructions, and embedded scripts.

## Privacy & Safety

All skills in this repository are **100% anonymized**:
* User home paths (`C:\Users\...`) replaced with `<USER_HOME>`.
* Personal names, emails, and handles replaced with standard placeholders (`<USERNAME>`, `<USER_EMAIL>`, `<TELEGRAM_HANDLE>`).
* Private API keys, server IP addresses, and tokens replaced with `<API_TOKEN>` and `<SERVER_IP>`.

## License

MIT License — free for personal, team, and commercial use.
