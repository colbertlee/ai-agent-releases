# ai-agent v2.0.3 — GitHub mirror

> **GitHub mirror of the official Gitee repository.**
> **Official releases: https://gitee.com/colbertlee/ai-agent-releases** (recommended for users in China)
> **Source code: https://gitee.com/colbertlee/langChain_langGraph**

## What is ai-agent?

ai-agent is a **production-ready Multi-Agent framework** with 10 built-in Workers (Chat, RAG, Tool, Code, Schedule, Message, File, OS, Media, Commerce) and a complete **A2A protocol** for cross-process/cross-language communication.

- **Version**: 2.0.3
- **License**: MIT
- **Python**: 3.11+
- **Tests**: 107 passing

## Download v2.0.3

You can download artifacts from either Gitee or GitHub (this repository):

### Option 1: Download from Gitee (recommended for users in China)

| Artifact | Size | Download |
|---|---|---|
| **`ai-agent-python-v2.0.3.zip`** ⭐ (recommended for new users) | 676 KB | [Gitee](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/ai-agent-python-v2.0.3.zip) |
| `ai_agent-2.0.3-py3-none-any.whl` | 391 KB | [Gitee](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/ai_agent-2.0.3-py3-none-any.whl) |
| `ai_agent-2.0.3.tar.gz` | 532 KB | [Gitee](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/ai_agent-2.0.3.tar.gz) |
| `AgentCore_架构与测试报告.pdf` | 266 KB | [Gitee](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/AgentCore_架构与测试报告.pdf) |
| `ai-agent-source-v2.0.3.tar.gz` (full source code) | 2214 KB | [Gitee](https://gitee.com/colbertlee/ai-agent-releases/raw/master/src-snapshots/v2.0.3/ai-agent-source-v2.0.3.tar.gz) |

### Option 2: Download from GitHub (recommended for international users)

The same artifacts are mirrored to this GitHub repository at `products/v2.0.3/`. Use the GitHub UI to download.

### Option 3: Git clone the entire repository

```bash
git clone https://github.com/colbertlee/langChain_langGraph.git
cd langChain_langGraph/ai_agent
pip install -e ".[dev]"
```

## 5-minute Quickstart

After downloading `ai-agent-python-v2.0.3.zip`:

```bash
# 1. Unzip
unzip ai-agent-python-v2.0.3.zip
cd ai-agent-python-v2.0.3

# 2. Verify integrity (Windows)
verify_release.bat
# Or on Linux/macOS:
python -c "import hashlib; print(hashlib.sha256(open('ai_agent-2.0.3-py3-none-any.whl','rb').read()).hexdigest())"

# 3. Install
pip install ai_agent-2.0.3-py3-none-any.whl

# 4. Configure (set your LLM API key)
cp .env.example .env
# Edit .env and set OPENAI_API_KEY=sk-...

# 5. Run the example
python examples/example.py
```

## Repository Layout

This GitHub repository contains:

- `products/v2.0.3/` — Pre-built artifacts (wheel, sdist, zip, PDF, source snapshot)
- `products/v2.0.2/` — Previous version artifacts
- `src-snapshots/v2.0.3/` — Full source code at v2.0.3 tag
- `src-snapshots/v2.0.2/` — Full source code at v2.0.2 tag
- `RELEASE_NOTES.md` — Release notes for all versions
- `VERSION_MANAGEMENT.md` — Version management SOP
- `VERSION_AUTOMATION.md` — Automation overview

## Source Code

The full source code lives in a separate repository:

- **GitHub**: https://github.com/colbertlee/langChain_langGraph
- **Gitee (primary)**: https://gitee.com/colbertlee/langChain_langGraph

## Documentation

- **ONBOARDING** (5-minute quickstart): see source repo
- **USER_GUIDE** (detailed user manual): see source repo
- **ARCHITECTURE** (deep architecture): see source repo
- **CHANGELOG**: see source repo

## Version History

```
v2.0.0  First complete release (10 Workers + A2A + 108 tests)
v2.0.1  One-click install experience
v2.0.2  Fixed wheel missing packages + full zip + CI/CD
v2.0.3  Version management SOP standardized  ⬅️ Current
```

## License

MIT