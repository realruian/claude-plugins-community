[English](README.md) | [简体中文](README.zh-CN.md)

# Claude Plugins — 社区版

面向 [Claude Cowork](https://claude.com/product/cowork) 与 [Claude Code](https://claude.com/product/claude-code) 的社区贡献插件库。

## 仓库简介

本仓库是社区插件市场的**只读镜像**。仓库中的 `.claude-plugin/marketplace.json` 列出了所有可安装的社区插件，每晚从 Anthropic 内部审核流水线自动同步。

此处列出的每个插件均已通过 [claude.ai](https://clau.de/plugin-directory-submission) 提交，完成自动化安全扫描并获准分发。

## 使用此插件市场

### Claude Cowork

前往 [claude.com/plugins](https://claude.com/plugins/) 安装插件。

### Claude Code

```bash
claude plugin marketplace add anthropics/claude-plugins-community
claude plugin install <plugin-name>@claude-community
```

## 提交插件

请通过 **[clau.de/plugin-directory-submission](https://clau.de/plugin-directory-submission)** 提交。直接向本仓库发起的 Pull Request 会被自动关闭——所有更新均由内部审核流水线同步生成。

## 相关仓库

- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) — Anthropic 官方维护的插件
- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) — 面向特定知识工作角色的插件
