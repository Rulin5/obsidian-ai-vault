# Agent Instructions

This folder is an Obsidian vault template used as an AI-assisted personal knowledge base and project review system.

## Boundaries

- Treat this vault as the working directory.
- Do not read, edit, or create files outside this vault unless the user explicitly provides a path and asks for it.
- Preserve user-written notes unless the user asks for rewriting or restructuring.

## Vault Structure

- `个人项目系统/`: personal project management and review system.
- `prompts/`: reusable prompts.
- `docs/`: usage documentation.

## Project Management System

When the user uses any of these commands, first read `个人项目系统/00-控制中心/AI总规则.md` and `个人项目系统/00-控制中心/当前状态.md`:

- `执行月度规划`
- `执行项目拆解：项目名称`
- `执行本周计划`
- `执行今日复盘`
- `执行本周复盘`
- `执行想法整理`
- `执行反思分类`

Generate a preview before modifying files. Only write after the user sends `确认写入`.

For `执行反思分类`, preserve the original reflection, split it into atomic reflections, classify it into system categories, write executable items only to `个人项目系统/05-想法收集箱/待规划任务.md`, and never insert them directly into monthly, weekly, or daily plans.

## Style

- Use concise Chinese by default.
- Keep one note focused on one topic.
- Prefer headings, short paragraphs, and tables.
