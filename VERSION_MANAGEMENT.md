# 版本管理规范（指向 Gitee）

完整版本管理规范见 Gitee 源码仓库：

- **完整版本管理规范**: https://gitee.com/colbertlee/langChain_langGraph/blob/master/ai_agent/VERSION_MANAGEMENT.md
- **GitHub mirror**: https://github.com/colbertlee/langChain_langGraph/blob/main/ai_agent/VERSION_MANAGEMENT.md

## 一句话总结

```bash
cd ai_agent
python release_full.py X.Y.Z "feat: 描述"
```

7 步全自动化，5 分钟发一个正式版。

## 详细规范

见主仓库 `ai_agent/VERSION_MANAGEMENT.md`（10 节）：
1. SemVer 2.0 版本号格式
2. 何时发布新版
3. 版本号变更 SOP（改 2 处 + 加 1 处 CHANGELOG）
4. 完整发布 SOP（一键）
5. 发布工具一览
6. 自动化工具
7. 版本对照表
8. 故障排查
9. 团队成员职责
10. 一句话总结