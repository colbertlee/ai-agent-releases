# ai-agent-releases (GitHub mirror)

> **GitHub mirror of the official Gitee repository.**
> This repository contains metadata, SHA256 checksums, and download pointers.
> **All actual artifacts (wheel/sdist/zip/PDF) live on Gitee.**

---

## Why Gitee is primary, GitHub is mirror

| Platform | Purpose | Note |
|---|---|---|
| **Gitee** | Primary download (China) | Fast for Chinese users, all binaries hosted |
| **GitHub** | International visibility + open-source presence | Metadata only (binaries too large for MCP upload) |

Source: https://gitee.com/colbertlee/langChain_langGraph
Releases: https://gitee.com/colbertlee/ai-agent-releases/releases

---

## What is ai-agent?

ai-agent is a **production-ready Multi-Agent framework** with 10 built-in Workers (Chat, RAG, Tool, Code, Schedule, Message, File, OS, Media, Commerce) and a complete **A2A protocol** for cross-process/cross-language communication.

- **Version**: 2.0.3
- **License**: MIT
- **Python**: 3.11+
- **Tests**: 107 passing

---

## Download v2.0.3 (from Gitee)

### Direct download links (Gitee)

| Artifact | Size | Download |
|---|---|---|
| **`ai-agent-python-v2.0.3.zip`** ⭐ (recommended for new users) | 676 KB | [Download](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/ai-agent-python-v2.0.3.zip) |
| `ai_agent-2.0.3-py3-none-any.whl` | 391 KB | [Download](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/ai_agent-2.0.3-py3-none-any.whl) |
| `ai_agent-2.0.3.tar.gz` | 532 KB | [Download](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/ai_agent-2.0.3.tar.gz) |
| `AgentCore_架构与测试报告.pdf` | 266 KB | [Download](https://gitee.com/colbertlee/ai-agent-releases/raw/master/products/v2.0.3/AgentCore_架构与测试报告.pdf) |
| `ai-agent-source-v2.0.3.tar.gz` (full source code) | 2214 KB | [Download](https://gitee.com/colbertlee/ai-agent-releases/raw/master/src-snapshots/v2.0.3/ai-agent-source-v2.0.3.tar.gz) |

### SHA256 checksums (available on GitHub)

Each `.sha256` file in `products/v2.0.3/` is mirrored from Gitee and contains the authoritative checksum. Use these to verify downloaded files:

- [`ai_agent-2.0.3-py3-none-any.whl.sha256`](products/v2.0.3/ai_agent-2.0.3-py3-none-any.whl.sha256)
- [`ai_agent-2.0.3.tar.gz.sha256`](products/v2.0.3/ai_agent-2.0.3.tar.gz.sha256)
- [`AgentCore_架构与测试报告.pdf.sha256`](products/v2.0.3/AgentCore_架构与测试报告.pdf.sha256)

### Why are binaries NOT hosted here?

GitHub MCP upload tools only support text content (no binary upload). Until a proper binary upload channel is set up (via GitHub Actions with a real token), the binaries remain on Gitee only. SHA256 files are mirrored as text.

If you want to host binaries on GitHub too, see [GITHUB_PUSH.md](GITHUB_PUSH.md) for the recommended approach using `gh release upload` with a personal access token.

---

## 5-minute Quickstart

After downloading `ai-agent-python-v2.0.3.zip` from Gitee:

```bash
# 1. Unzip
unzip ai-agent-python-v2.0.3.zip
cd ai-agent-python-v2.0.3

# 2. Verify integrity (Windows)
verify_release.bat
# Or on Linux/macOS:
sha256sum -c *.sha256

# 3. Install
pip install ai_agent-2.0.3-py3-none-any.whl

# 4. Configure (set your LLM API key)
cp .env.example .env
# Edit .env and set OPENAI_API_KEY=sk-...

# 5. Run the example
python examples/example.py
```

---

## Repository Layout

This GitHub repository contains:

- `products/v2.0.3/` — SHA256 checksums + download instructions (binaries on Gitee)
- `products/v2.0.2/` — Previous version (similar layout)
- `src-snapshots/v2.0.3/README.md` — Pointer to source code snapshot
- `src-snapshots/v2.0.2/README.md` — Pointer to source code snapshot
- `RELEASE_NOTES.md` — Release notes for all versions
- `VERSION_MANAGEMENT.md` — Version management SOP
- `VERSION_AUTOMATION.md` — Automation overview
- `GITHUB_PUSH.md` — How to properly push binaries to GitHub

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