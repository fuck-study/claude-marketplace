# fuck-study Claude Marketplace

Long 项目的 Claude Code 插件 Marketplace。

## 使用

### 添加 Marketplace（仅首次）

```bash
claude plugin marketplace add fuck-study/claude-marketplace
```

### 安装插件

```bash
claude plugin install long-skills
```

### 更新插件

插件已安装时，`install` 不会拉取新版本，需要先刷新 marketplace 再更新插件：

```bash
claude plugin marketplace update fuck-study
claude plugin update long-skills
```

更新后需重启 Claude Code 会话才会生效。

## 插件列表

| 插件 | 说明 |
|------|------|
| [long-skills](https://github.com/fuck-study/long-skills) | Long 项目通用 Skills — deploy.yaml 描述更新、API 安全分析、运行日志规范化 |
