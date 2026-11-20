[简体中文](README.md) | **English**

## Install with one message

Copy this message into Codex to ask it to install the English edition of reader-first-writing:

```text
Use $skill-installer to install en/reader-first-writing from the GitHub repository iceshade000/task-alignment.
```

Want all four? Copy this message:

```text
Use $skill-installer to install these four English skills from the GitHub repository iceshade000/task-alignment: en/task-alignment, en/reader-first-writing, en/paper-reading, and en/innovation-discovery. Skip any that are already installed.
```

After installation, use them in your next message. Choose either the English or Chinese edition of each skill; see the [Chinese README](README.md) for Chinese installation instructions.

## Which skill should I use?

| Skill | When to use it |
| --- | --- |
| [task-alignment](en/task-alignment/SKILL.md) | Align goals, deliverables, and execution plans when a task is complex, ambiguous, or drifting. |
| [reader-first-writing](en/reader-first-writing/SKILL.md) | Organize answers and articles around reader questions when writing is confusing, repetitive, or heavy on jargon. |
| [paper-reading](en/paper-reading/SKILL.md) | Close-read papers or compare studies, explaining the authors' arguments, methods, and experimental evidence. The English edition translates non-English passages into English when needed. |
| [innovation-discovery](en/innovation-discovery/SKILL.md) | Develop product, research, or proposal ideas from audience needs, converging on valuable outputs, core selling points, and validation. |

## Usage examples

After installation, send any of these messages to Codex with your task or materials:

```text
Use $task-alignment to help me align this project's goals, expected deliverables, and execution plan first.
```

```text
Use $reader-first-writing to revise the following text so someone who was not part of our discussion can understand it.
```

```text
Use $paper-reading to closely review this paper and explain its problem, methods, training process, and experimental evidence.
```

```text
Use $innovation-discovery with these needs and existing outputs to propose a few distinctive core selling points and ways to validate them.
```

## Update installed skills

When you want an update, send this message to Codex:

```text
Check the en directory in the GitHub repository iceshade000/task-alignment and update the skills I previously installed from it to their latest versions. Compare local differences first; preserve my custom changes and report conflicts rather than overwriting them.
```

## Update history

### 2026-11-20 · Updated reader-first-writing and innovation-discovery

- reader-first-writing: State the audience's most important benefit directly in the summary, organize supporting material around reader questions, and retain necessary conditions and evidence.
- innovation-discovery: Assess multiple output-quality dimensions, ground evaluation procedures in prior research, and refine design and validation together. Strengthened core-value expression and revision of recurring problems.

Updated both language editions.

### 2026-11-19 · Updated reader-first-writing

> Author's note: If it doesn't work on GPT6.2 Astra, switch back to GPT6. 6.2 is too stubborn—it just won't follow the skill.

- Added paragraph guidance: state the important point early, explain relationships between facts, and measure information by understanding gained.
- Preserve source arguments rather than inventing motives or causes after compression.
- Align complex material by dependencies in understanding; when one problematic sentence is identified, check and repair the same pattern throughout the authorized scope. Updated both language editions.

### 2026-11-19 · Updated innovation-discovery

- Start from domain consensus and audience needs, define valuable final outputs, then compare existing approaches and project assets to locate important gaps.
- Actively compare alternatives and converge on a few coherent capabilities and selling points, linked to concrete design, strong comparisons, and testable outcomes.
- Added audience-focused selling-point guidance and independent revision checks. Updated both editions and invocation prompts; removed the old discussion case no longer included in the source skill.

### 2026-11-18 · Updated innovation-discovery

Added domain foundations: establish goals, consensus, objects of study, relationships, and evaluation criteria before locating important gaps. Distinguish the domain task from the proposed system, avoiding premature constraints from existing assets or anticipated solutions. Updated both skill editions and invocation prompts.

### 2026-11-19 · Added innovation-discovery

Map key entities and information flows to find innovation opportunities in concrete gaps in understanding, processing, action, and feedback. Useful for finding differentiation, moving beyond similar proposals, or resolving repeated revisions without progress. Both editions include a full discussion case.

[English skill](en/innovation-discovery/SKILL.md) · [中文版 skill](zh-CN/innovation-discovery/SKILL.md)

### 2026-11-17 · Updated reader-first-writing

Require explanations of technical terms and abbreviations at first mention, including their meaning, purpose, and relevance; spelling out an abbreviation alone is insufficient. Use natural, concrete language and avoid invented terms, awkward combinations, and labels readers must guess at. Updated both language editions.

### 2026-11-15 · Updated paper-reading

- Keep excerpts and translations in source-checking notes while allowing coherent paraphrases in the final reading document; add reviewer assessments when requested.
- Explain construction, training roles, and experimental evidence in greater detail, including test data, reference answers, comparisons, scoring, and result conditions.
- Added guidance for multi-paper overviews, individual close readings, and focused comparisons, plus public-resource and delivery checks.

Updated both skill editions and invocation prompts. The English edition defaults to English and translates non-English originals into English only when needed.

### 2026-11-14 · Added paper-reading

Close-read papers through original excerpts and summaries of the authors' reasoning across five parts: task value, field status and objectives, methodological outputs, training, and experimental validation. Keep the authors' argument distinct from the reviewer's assessment.

Available in both languages: the Chinese edition includes Chinese translations; the English edition uses English and translates only non-English passages into English.

[English skill](en/paper-reading/SKILL.md) · [中文版 skill](zh-CN/paper-reading/SKILL.md)

### 2026-11-13 · Updated reader-first-writing

- Reorganize for the final audience, separate discussion history from the deliverable, and preserve the starting point and premises new readers need.
- Limit unsolicited advice. Identify opinions, inferences, and recommendations before elaborating; when removing advice, remove its substance.
- Reassess the whole structure when content is disorganized. Preserve necessary operations and dependencies when shortening, and clear outdated statements throughout after corrections.

Updated both language editions.

### 2026-11-13 · Updated reader-first-writing

- Distinguish source facts from the author's recommendations. Preserve the original conditions, scope, and strength of requirements; do not replace facts readers need with advice.
- Select information before explaining it. Remove irrelevant details instead of continually expanding the background to explain unnecessary material.
- Keep numbers, parameters, and examples relevant to the current question, with a clear subject, measurement basis, and purpose. Do not fill gaps with values from another subject.

Updated both language editions and the corresponding review checks.

### 2026-11-13 · Updated reader-first-writing

Strengthened direct expression: state the subject, scope, conditions, and actions directly; correct misunderstandings only when readers explicitly raise them, reducing defensive wording aimed at imagined misunderstandings. Updated both language editions.

### 2026-11-12 · Added reader-first-writing

Organizes writing around what readers ask and already know, reducing logical gaps, repetition, and mismatched evidence to make answers and articles easier to understand. Use it independently or alongside task-alignment.

[English skill](en/reader-first-writing/SKILL.md) · [中文版 skill](zh-CN/reader-first-writing/SKILL.md)

<details>
<summary>View the reader-first-writing English screenshot</summary>

<sub>The image below is a screenshot of the original SKILL.md.</sub>

![reader-first-writing English screenshot](reader-first-writing-en.png)

</details>

---

## task-alignment

**An all-in-one solution for GPT misunderstanding you, sounding unnatural, writing defensively, reinventing the wheel, and more.**

Other skills I found online made no difference whether GPT read them or not. But an ancient prompt for task alignment and planning from my private collection turned out to work surprisingly well. My guess is that focusing on understanding what the user is saying leaves it no context to wander off on its own. Give it a try.

<details>
<summary>View the task-alignment English screenshot</summary>

<sub>The image below is a screenshot of the original SKILL.md.</sub>

![English](en.png)

</details>
