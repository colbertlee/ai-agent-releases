# ai-agent v2.0.3 发布

> **Mirror notice**: This is a GitHub mirror. See Gitee for actual binaries: https://gitee.com/colbertlee/ai-agent-releases/releases/tag/v2.0.3

## What's in v2.0.3

### One-line release script
- `release_full.py`: 7-step SOP
- `--dry-run`, `--skip-tests`, `--skip-build` flags

### Documentation
- `VERSION_MANAGEMENT.md` (10 sections)
- `VERSION_AUTOMATION.md` (overview)
- `CHANGELOG.md` (top-level)

### Source snapshot tool
- `push_source_snapshot.py` + `publish_to_releases.py`

## Version evolution

```
v2.0.0  First complete release (10 Workers + A2A)
v2.0.1  One-click install experience
v2.0.2  Fix wheel missing packages + full zip + CI/CD
v2.0.3  Version management SOP standardized (current)
```

Next:
- **v2.0.4**: continue bug fixes
- **v2.1.0**: new Worker (e.g. StockWorker)
- **v3.0.0**: breaking API changes