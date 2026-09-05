# personal-knowledge-base

一个把上传材料整理成个人 Markdown/Obsidian 知识库的通用 Codex Skill。

## 功能

- 接收 PDF、Word、图片、网页链接和粘贴文本
- 创建来源卡、主题页、索引、截止日期看板和待确认事项
- 保留原始材料，并为事实标记 `EXTRACTED`、`INFERRED` 或 `UNVERIFIED`
- 处理重复材料、版本更新、冲突和过期信息
- 不局限于学校场景，可用于学习、科研、求职、项目和生活管理

## 使用

将本目录作为 Skill 安装到 Codex 的 skills 目录，然后上传材料并提出类似请求：

> 用 personal-knowledge-base 整理这些材料，录入我的知识库。

Skill 会优先搜索已有知识库，更新相关页面，并报告新建内容、来源和待核实信息。

## 目录

```text
SKILL.md                    # 核心工作流
agents/openai.yaml          # Codex 界面元数据
references/                 # 证据、摄取和库结构规范
```

## 范围与隐私

本仓库只发布通用 Skill，不包含任何个人知识库材料。使用时请把私人原始文件保存在自己的本地 vault 中。

## 版本

当前版本：`1.0.0`

---

# personal-knowledge-base (English)

A general-purpose Codex Skill for turning uploaded materials into a personal Markdown/Obsidian knowledge base.

## Features

- Accepts PDFs, Word files, images, web links, and pasted text
- Creates source cards, topic notes, indexes, deadline boards, and review lists
- Preserves originals and labels claims as `EXTRACTED`, `INFERRED`, or `UNVERIFIED`
- Handles duplicates, revisions, conflicts, and stale information
- Works for study, research, job search, projects, and personal planning—not only university content

## Usage

Install this directory as a Skill in Codex's skills directory, then upload materials with a request such as:

> Use personal-knowledge-base to organize these materials into my knowledge base.

The Skill searches the existing vault first, updates related pages, and reports new pages, sources, and unresolved items.

## Scope and privacy

This repository contains only the generic Skill. It does not contain anyone's private knowledge-base materials. Keep private originals in your own local vault.

## Version

Current version: `1.0.0`
