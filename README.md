# ai-agent-releases

> **Official release artifacts for ai-agent.**
> Source code: https://github.com/colbertlee/langChain_langGraph

---

## What is ai-agent?

ai-agent is a **production-ready Multi-Agent framework** with 10 built-in Workers (Chat, RAG, Tool, Code, Schedule, Message, File, OS, Media, Commerce) and a complete **A2A protocol** for cross-process/cross-language communication.

- **Latest Version**: 2.0.4
- **License**: MIT
- **Python**: 3.11+
- **Tests**: 107 passing

---

## Download v2.0.4 (latest)

Each release below has all the artifacts attached.

### `ai-agent-python-v2.0.4.zip` (recommended for new users)

676 KB — the complete package containing:

- `ai_agent-2.0.4-py3-none-any.whl` (391 KB) — pip install wheel
- `AgentCore_*.pdf` (266 KB) — architecture + test report
- 6 markdown docs (ONBOARDING, ARCHITECTURE, USER_GUIDE, CHANGELOG, RELEASE_GUIDE, VERSION_MANAGEMENT)
- `examples/example.py` — 5-minute quickstart script
- `verify_release.bat` — SHA256 verification script
- `.env.example` — API key configuration template
- `README.md` — quickstart guide
- `RELEASE_NOTES.md` — version notes

### Other artifacts

- `ai_agent-2.0.4-py3-none-any.whl` (391 KB) — pip install
- `ai_agent-2.0.4.tar.gz` (532 KB) — source distribution
- `AgentCore_*.pdf` (266 KB) — architecture report

---

## What's new in v2.0.4

- **Bug fix**: `publish_to_github.py` NameError (missing `os` import)
- **Bug fix**: subprocess timeout protection
- **Bug fix**: non-zero exit code on failure
- **New**: detailed logging with timestamps and tracebacks
- **New**: `--verbose` flag and `GH_LOG_LEVEL` env var
- **New**: `simulate_publish.py` test harness (mock / dry-run / real)

See [CHANGELOG.md](https://github.com/colbertlee/langChain_langGraph/blob/main/ai_agent/CHANGELOG.md) for full version history.

---

## 5-minute Quickstart

```bash
# 1. Download ai-agent-python-v2.0.4.zip from this release page
# 2. Unzip
unzip ai-agent-python-v2.0.4.zip
cd ai-agent-python-v2.0.4

# 3. Verify integrity
# Windows:
verify_release.bat
# Linux/macOS:
sha256sum -c *.sha256

# 4. Install
pip install ai_agent-2.0.4-py3-none-any.whl

# 5. Configure (set your LLM API key)
cp .env.example .env
# Edit .env and set OPENAI_API_KEY=sk-...

# 6. Run the example
python examples/example.py
```

---

## System Requirements

- Python 3.11+
- At least one LLM API key (OpenAI, DeepSeek, Anthropic, or other compatible)
- Windows / macOS / Linux

---

## Source Code

- **Repository**: https://github.com/colbertlee/langChain_langGraph
- **Source code at this version**: `src-snapshots/v2.0.4/ai-agent-source-v2.0.4.tar.gz` (2.2 MB)

---

## Documentation

The release zip includes:

- **ONBOARDING.md** — 5-minute quickstart
- **USER_GUIDE.md** — detailed user manual
- **ARCHITECTURE.md** — deep architecture
- **CHANGELOG.md** — version history
- **VERSION_MANAGEMENT.md** — version management SOP

---

## Version History

```
v2.0.0  First complete release (10 Workers + A2A + 108 tests)
v2.0.1  One-click install experience
v2.0.2  Fixed wheel missing packages + full zip + CI/CD
v2.0.3  Version management SOP standardized
v2.0.4  Bug fixes + publish tools enhanced  ⬅️ Current
```

## License

MIT