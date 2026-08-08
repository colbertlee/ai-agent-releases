# 版本自动化总览（指向 Gitee）

完整文档见 Gitee 源码仓库：

- **完整版本自动化总览**: https://gitee.com/colbertlee/langChain_langGraph/blob/master/ai_agent/VERSION_AUTOMATION.md

## 一句话发布

```bash
python release_full.py X.Y.Z "feat: 描述"
```

## 7 步 SOP

1. 验证版本号 + CHANGELOG 一致性
2. 构建 wheel + sdist + PDF + zip
3. 跑 107 测试（必须全 PASS）
4. SHA256 校验
5. push 源码到 langChain_langGraph
6. push 产物 + 源码到 ai-agent-releases
7. 创建 Gitee Release