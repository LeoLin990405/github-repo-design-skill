# GitHub Repo Design Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

GitHub 仓库设计与 README 最佳实践指南 - Claude Code Skill

## 功能

这是一个 Claude Code skill，提供以下指导：

- 仓库文件结构设计
- README.md 编写最佳实践
- 开源项目必备文件配置
- Issue/PR 模板设计
- GitHub Actions CI/CD 配置
- 分支保护规则设置
- 发布管理最佳实践
- GitHub Profile README 设计
- 安全最佳实践
- Monorepo 结构设计

## 架构

本 skill 采用**分包分级架构**，将内容组织为 15 个独立模块：

```
github-repo-design/
├── SKILL.md                    # 主入口，概述和索引
├── README.md                   # 仓库说明
├── LICENSE                     # 许可证
└── modules/                    # 模块目录
    ├── 01-structure/           # 仓库结构
    ├── 02-readme/              # README 设计
    │   ├── README.md           # 主指南
    │   ├── badges.md           # 徽章配置
    │   └── tools.md            # 工具推荐
    ├── 03-config/              # 配置文件
    ├── 04-templates/           # Issue/PR 模板
    ├── 05-settings/            # 仓库设置
    ├── 06-cicd/                # CI/CD
    ├── 07-profile/             # GitHub Profile
    ├── 08-security/            # 安全实践
    ├── 09-monorepo/            # Monorepo
    ├── 10-docs/                # 文档网站
    ├── 11-versioning/          # 版本管理
    ├── 12-quality/             # 代码质量
    ├── 13-community/           # 社区建设
    ├── 14-i18n/                # 国际化
    └── 15-faq/                 # 常见问题
```

## 安装

```bash
cd ~/.claude/skills
git clone https://github.com/LeoLin990405/github-repo-design-skill.git github-repo-design
```

## 使用

在 Claude Code 中，当你需要：
- 创建新的 GitHub 仓库
- 设计项目结构
- 编写 README 文件
- 配置开源项目

Claude 会自动使用此 skill 提供指导。

## 触发词

- `github repo`
- `repository design`
- `readme design`
- `仓库设计`
- `项目结构`
- `开源项目`
- `profile readme`
- `github profile`

## 模块概览

| 级别 | 模块 | 内容 |
|------|------|------|
| 基础 | 01-structure | 推荐的项目目录结构 |
| 基础 | 02-readme | README 设计、徽章、工具 |
| 基础 | 03-config | LICENSE, CONTRIBUTING, SECURITY |
| 基础 | 04-templates | Bug 报告、功能请求、PR 模板 |
| 基础 | 05-settings | Topics, 社交预览图, 分支保护 |
| 进阶 | 06-cicd | GitHub Actions 工作流 |
| 进阶 | 07-profile | GitHub Profile README |
| 进阶 | 08-security | Dependabot, CodeQL, 密钥扫描 |
| 进阶 | 09-monorepo | Monorepo 结构和工具 |
| 进阶 | 10-docs | 文档网站集成 |
| 高级 | 11-versioning | SemVer, Conventional Commits |
| 高级 | 12-quality | Linting, Pre-commit, EditorConfig |
| 高级 | 13-community | Discussions, 贡献者认可, 赞助 |
| 高级 | 14-i18n | 多语言 README, 文档国际化 |
| 高级 | 15-faq | 常见问题解答 |

## 许可证

MIT License
