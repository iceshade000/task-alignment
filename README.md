# Task Alignment

**GPT听不懂人话，防御性写作，不说人话，一站式解决方案。**

A Codex skill for aligning on complex tasks, following through on approved work, and writing for the reader.

[中文](#中文说明) · [English](#english) · [MIT License](LICENSE)

## 中文说明

### 为什么做这个 skill

网上找的其他skill给GPT看了和没看一样，不过我发现珍藏的上古版本提示词意外的好用，大家可以试试。

`task-alignment` 是一套可复用的协作指令，重点约束三件事：

| 你遇到的问题 | 规则要求 Codex 怎么做 |
| --- | --- |
| 还没理解需求就开工，越做越偏 | 先读材料、确认需求，再分别确认整体计划和下一步计划 |
| 不断确认、反复检查，却迟迟没有成果 | 在已批准阶段内持续执行，只核验会影响采用结果的关键依据 |
| 句子生硬、逻辑跳跃，修改时丢信息 | 按读者需要组织内容，补足解释，保留仍然成立的重要信息 |

### 适合什么时候用

适合目标需要澄清、交付分多个阶段，或要反复修改的任务，例如资料整理、报告写作、项目规划和软件开发。明确的小修改与直接问答不需要套用完整确认流程。

**使用成本：**复杂新任务默认先确认需求，再分别确认整体计划和本阶段计划，因此开头会多几轮交流。进入已批准阶段后，应持续推进。你也可以明确要求合并或跳过某一确认点。

### 安装：选一个语言版本

- [中文版规则](zh-CN/task-alignment/SKILL.md)
- [English instructions](en/task-alignment/SKILL.md)

两版名称都叫 `task-alignment`，选择一版即可。每版包含 `SKILL.md` 和 `agents/openai.yaml`。

1. 在本仓库页面点击 **Code → Download ZIP**，解压文件。
2. 中文版取 `zh-CN/task-alignment` 文件夹；英文版取 `en/task-alignment` 文件夹。
3. 将选中的整个 `task-alignment` 文件夹复制到个人 skills 目录。目录不存在时先创建：
   - Windows：`%USERPROFILE%\.agents\skills\`（可粘贴到文件资源管理器地址栏）。
   - macOS / Linux：`~/.agents/skills/`。
4. 在 Codex 中打开新对话并调用；如果没有识别到，重启 Codex 后再试。

安装后的结构应为：

```text
.agents/skills/task-alignment/
├── SKILL.md
└── agents/
    └── openai.yaml
```

复制的是内层 `task-alignment` 文件夹，不是整个仓库。如果你已有同名 skill，包括曾安装在 `.codex/skills/` 下的版本，请先检查、备份并确定保留哪一版，避免重复安装或覆盖自己的修改。

安装目录与调用方式参考 [OpenAI 官方 skills 文档](https://learn.chatgpt.com/docs/build-skills)。本说明面向支持本地 skills 的 Codex 环境。

### 开始使用

在 Codex 对话中明确调用，并补充你的任务与材料位置：

```text
请使用 $task-alignment 帮我完成这件事：
[描述你要做的事]
现有材料在：[路径或说明]
先阅读材料并确认你对需求的理解。
```

例如（调用示例，不是效果实测记录）：

```text
请使用 $task-alignment，帮我把现有研究笔记整理成一篇给非专业读者看的介绍。
笔记在当前项目的 notes 文件夹里。
先了解材料、目标读者和我想交付的内容，再和我确认需求。
```

复杂新任务中，预期顺序是：**需求理解 → 整体计划与最终成果 → 本阶段计划与阶段成果 → 执行和交付**，前三步分别确认。你可以观察它是否真正读过材料、是否保留了重要要求、进入执行后是否持续推进，而不只看它有没有复述规则。

### 当前状态与反馈

这是经过实际使用反馈迭代的初期版本。中文版已有试用反馈；英文版是对应翻译，尚未单独实测。效果会受模型、任务和上下文影响，指令不能保证每次都被遵循，也不能保证事实准确或专业内容完整。它是协作流程辅助，不替代专业判断。

欢迎在本仓库的 Issues 中分享使用反馈：任务类型、使用的版本与模型、你期待的行为、实际发生的情况，以及去除私人信息的简短例子。尤其欢迎英文版的使用反馈。

### 许可证

[MIT License](LICENSE) · Copyright (c) 2026 iceshade000

## English

### Why this skill exists

Other skills I found online made no difference whether GPT read them or not. But an old prompt I had saved turned out to work surprisingly well. Give it a try.

`task-alignment` provides reusable collaboration instructions in three areas:

| Problem | Intended behavior |
| --- | --- |
| Work starts before requirements are understood | Read existing material, align on requirements, then separately confirm the overall and next-step plans |
| Repeated approvals and checks delay useful work | Continue within the approved stage and verify the critical basis of results selected for use |
| Writing is hard to follow or revisions lose information | Organize for the reader, explain missing connections, and preserve still-valid requirements and facts |

### When to use it

Use it for ambiguous, staged, or revision-heavy tasks such as research synthesis, reports, project planning, and software development. Direct questions and clearly specified small edits do not need the full startup sequence.

**Tradeoff:** A new complex task normally begins with three separate confirmations: requirements, the overall plan, and the current stage plan. This adds conversation upfront. Execution should then continue within the approved stage. You can explicitly request that a confirmation point be combined or skipped.

### Install one language edition

Choose [English](en/task-alignment/SKILL.md) or [Chinese](zh-CN/task-alignment/SKILL.md). Both use the name `task-alignment`; install only one.

1. On this repository page, select **Code → Download ZIP** and extract it.
2. Select the inner `task-alignment` folder from `en/` or `zh-CN/`.
3. Copy that entire folder into your personal skills directory, creating the directory if needed:
   - Windows: `%USERPROFILE%\.agents\skills\` (paste into File Explorer).
   - macOS / Linux: `~/.agents/skills/`.
4. Start a new Codex chat and invoke the skill. Restart Codex if it is not detected.

The resulting files should be `~/.agents/skills/task-alignment/SKILL.md` and `~/.agents/skills/task-alignment/agents/openai.yaml`. Do not copy the whole repository as the skill folder.

If a skill with the same name already exists, including an earlier installation under `.codex/skills/`, review and back it up before choosing which edition to keep. Avoid duplicate installations or overwriting your changes.

See the [official OpenAI skills documentation](https://learn.chatgpt.com/docs/build-skills) for local discovery and invocation. These instructions target Codex environments with local skill support.

### Use it

Explicitly invoke the skill and provide your task and materials:

```text
Use $task-alignment to help me with this task:
[Describe your task.]
Existing materials: [path or description].
Read the materials first and confirm your understanding of my requirements.
```

Example prompt, not a measured outcome:

```text
Use $task-alignment to turn my research notes into an introduction for non-specialist readers.
The notes are in the notes folder of this project.
First understand the material, intended audience, and deliverable, then align with me on the requirements.
```

For a new complex task, expect: **requirements → overall plan and final outcomes → stage plan and stage outcomes → execution and delivery**, with separate confirmations for the first three steps. Look for actual reading of the materials, preservation of requirements, and continued execution after approval, rather than a recital of the rules.

### Status and feedback

This is an early version refined through use and feedback. The Chinese edition has received trial feedback; the English edition is a translation and has not been independently field-tested. Results vary by model, task, and context. Instructions do not guarantee consistent compliance, factual accuracy, or complete domain coverage. This workflow aid does not replace domain expertise.

Share feedback through this repository's Issues: task type, skill edition and model, expected behavior, actual behavior, and a short example with private information removed. Feedback on the English edition is especially welcome.

### License

[MIT License](LICENSE) · Copyright (c) 2026 iceshade000

