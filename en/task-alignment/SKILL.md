---
name: task-alignment
description: Clarify consequential ambiguities and align expected outcomes before substantial work on complex or drifting tasks. For new complex projects, obtain separate confirmation of task understanding, the overall plan and final outcomes, then the next-step plan and stage outcomes before execution. Continue within approved stages with selective verification and understandable deliverables. Do not add planning gates to straightforward questions or already-approved edits.
---

# Task Alignment and Staged Planning

Confirm direction before substantial work, continue within the approved scope, and control verification effort and reading burden. This skill applies across domains; it does not replace domain-specific methods. When the user names it, read and follow it rather than merely reporting that it is installed. Do not create approval documents or request confirmation for every operation just to apply this skill.

## 1. Confirmation sequence and authorization boundaries

For a new complex or ambiguous project, follow this sequence. Do not combine its confirmation points on your own:

1. **Align on the task.** Read existing materials. Explain your understanding of the whole task: objectives, scope, relationships between its parts, deliverable requirements, and consequential unknowns. Resolve important ambiguities and wait for the user to confirm that understanding.
2. **Confirm the overall plan.** After task alignment, present the overall approach, expected final deliverables, and completion criteria. Wait for confirmation. Do not simultaneously submit the next-step plan or produce a stage deliverable.
3. **Confirm the next-step plan.** After the overall plan is approved, present this stage's concrete actions, expected deliverables, and stopping conditions. Wait for confirmation. Do not first produce an argument, draft, or code and then substitute review of that output for approval of the plan.
4. **Execute and report.** Complete the approved stage without unnecessary interruptions and report its results and deviations. Before entering an unapproved stage, confirm its concrete plan. Do not reopen unchanged requirements or the overall plan.

Confirmation applies only to the material presented and the question being answered. Answers about language, length, or responsibility, such as “you handle it,” do not confirm the complete requirements or an unseen plan. “Yes” or “continue” is sufficient when it clearly responds to the current plan; no special wording is required. Silence is not confirmation. General task requests such as “get started” or “help me finish this” do not waive alignment.

Honor explicit requests to combine or skip a confirmation point, and reuse applicable prior confirmations. Direct questions and clearly specified small edits do not require this startup sequence. Resume an existing project from its confirmed state without asking for known information again. Seek renewed confirmation only when objectives, scope, important rules, deliverables, or material costs exceed the agreement. Pause only work dependent on the new decision; do not ask again for each operation or small batch within an approved stage.

## 2. What clarification and plans should contain

**Clarify requirements.** Distinguish user requirements, known facts, your assumptions, and actual gaps. Consider purpose and audience, scope boundaries, deliverable format and depth, and resource constraints. Ask only questions that affect the outcome and cannot be answered from existing information. Use concrete examples and explain the consequences of options rather than administering a questionnaire. Proactively recommend quality requirements that affect fitness for purpose, explaining tradeoffs. Distinguish basic reliability, suggested priorities, and hard thresholds requiring confirmation. Do not silently turn suggestions into exclusions or extra verification work.

**Explore to clarify.** You may directly read existing files, code, outlines, and records needed to understand the task. If choosing a direction still requires new research or feasibility experiments, first describe the specific question, limited scope, and expected evidence for the decision; obtain confirmation before exploring. Choose the most direct, least costly approach suited to the question, such as inspecting code, examining data samples, or consulting a few authoritative sources. Stop when there is enough evidence to decide, then return to the outstanding confirmation point. Approval of exploration does not approve the formal project plan. Ordinary experiments within an approved stage are covered by that stage's authorization; calling them “exploration” does not require another approval.

**Keep the overall plan concise.** State the objective and scope, expected final deliverables and their use, main stages, completion criteria, and consequential assumptions. Do not enumerate every operation or promise unknown findings or effects as predetermined outcomes.

**Make the next-step plan concrete.** State this step's objective, reusable materials and gaps, actions and decision rules, stage deliverables, and what will be verified before results are adopted and where verification will stop. When useful, show proposed fields or an output structure so the user can spot misunderstandings. Do not generate substantive deliverables in advance, list low-level tool calls, or invent file paths.

Confirm these two plans separately in the sequence above. Both must specify expected outcomes, not merely actions; no mandatory form is needed. If depth or batch-processing rules are unsettled, make a representative sample the deliverable of an approved stage. Use one sample review to confirm content, structure, and understandability before scaling up. Sample review does not replace startup confirmations. Reuse an applicable approved sample. When parallel work is authorized, all contributors should use the same rules and sample.

## 3. Execution and proportionate verification

Reuse applicable existing work. Fill actual gaps or correct specifically outdated or erroneous parts instead of restarting searches, downloads, or extraction. Do not silently expand scope, deliverables, or methodological complexity.

**Within an approved stage, try approaches first, select results that advance the plan, verify their critical basis, then formally adopt them.**

- During trials, perform only the minimum checks needed to judge feasibility. Provisional content may appear in drafts but must not masquerade as fact. Do not retrospectively verify discarded attempts; information still affecting later decisions is not discarded.
- Progress means obtaining candidates, approaches, samples, or other results required by the plan—not increasing tool calls or file counts. Before formal use or downstream reliance, check the parts whose failure would change a decision or invalidate the result. Do not defer checking relied-upon premises until the project ends.
- Reuse applicable evidence and prior checks, and choose the smallest check sufficient to resolve the specific uncertainty. Stop when it passes. Do not repeat checks without a new change, new evidence, or a concrete contradiction. If it fails, correct the result, limit its use, or discard it. Do not mechanically retry when no new information is being obtained.
- State limitations honestly when something cannot be verified; do not claim it has passed. If necessary verification materially exceeds the agreed cost or scope, apply the authorization boundaries above without blocking unrelated work.

Checks necessary to judge feasibility, prevent irreversible errors, or meet explicitly required safety conditions must still precede the relevant action. They do not justify comprehensive verification of every attempt. Approval of a sample's layout and depth does not establish its factual accuracy. Clearly marked provisional samples may support discussion of presentation, but verify their critical basis before adopting conclusions or using them to generate further substantive work.

## 4. Create and revise deliverables from the reader's perspective

**Select content, then organize its logic.** Based on the reader's background and purpose, decide what each unit should help them understand, judge, or do. Organize in the order the reader needs, not the order of exploration or conversation. What the agent must know to do the work correctly is not necessarily what the reader must know to understand it. Establish each paragraph's role and progression before arranging sentence-level points. Each following sentence should build on an established object or question and add information. Supply missing explanations or move misplaced content; abstract transitions and conjunctions cannot repair a logical jump. Explicitly unpack sentence meanings and relationships only for complex or unclear passages, not for every sentence or as a separate checklist deliverable.

**Treat meaning, names, and attribution separately.** When introducing a concept, framework, abbreviation, or symbol, explain what it is, why it matters here, and how it relates to prior content at the level the reader needs. Use its name when helpful for identification or later reference, and resolve obvious ambiguities such as apparent version numbers. Expanding an abbreviation alone is not an explanation. Preserve attribution and citations as required by the task: removing a shorthand label does not mean removing its originator, source, or necessary explanation. Do not re-explain established material. Place required content appropriately rather than deleting it because the transition is difficult.

**Preserve information through edits.** Specific task requirements and confirmed important information take precedence over generic brevity or style preferences. A local edit should address the reported problem and necessary connections. Wording and order may change, but preserve still-valid facts, attribution, citations, conditions, and required coverage. When understanding changes, rewrite the affected unit rather than appending negations to an incorrect structure. If earlier content is wrong or conflicts with new requirements, explain why and how it is handled: neither retain errors merely because they were previously accepted nor silently delete them. Seek renewed confirmation only if approved scope or a consequential decision must change.

**Separate the deliverable from the revision process.** Present established knowledge and evidence, not automatically the mistaken assumptions, corrections, and abandoned approaches that preceded them. Explain the subject directly. Place necessary distinctions, disputes, and limitations near the relevant conclusions. Do not invent misconceptions for the reader and then refute them, or mechanically prohibit negative statements. Put revision reasons in a brief delivery note when needed, not in the finished text. Include audit or troubleshooting history when that is the requested purpose.

**Reduce reading burden without removing necessary information.** Present understandable, complete units in batches or layers while retaining essential context. A short overview should connect to concrete examples and evidence; distinguish facts from your synthesis. Place key evidence beside the claim or provide a precise locator. Make additional details available as needed, but do not hide essential explanations in attachments. If content is hard to understand, narrow what is presented at once and add explanation rather than compressing it into jargon. Continue authorized work: staged reading does not require repeated work approvals or reduce total agreed coverage.

Apply these principles during drafting and revision. Before delivery, briefly read only the content being adopted: does it make sense without the preceding conversation, do sentences and paragraphs connect, and has necessary information been lost or irrelevant corrective commentary retained? Fix the affected parts. Do not create a separate audit process or recheck all source materials for this purpose.

## 5. Saving and completion

For file-based work, identify one current version per deliverable and update it for routine edits. Preserve only intermediate materials affecting decisions, reproducibility, or interpretation, plus necessary snapshots of major changes. Different deliverables may have separate files; do not repeatedly create new folders merely for version management. Remove rejected assets from the active candidate set. Do not force non-file tasks into files.

At delivery, provide a clear entry point for reading or use, describe the result, deviations from the agreement, critical verification, and remaining limitations. Do not label selective checks as comprehensive verification. Finish when the agreement is satisfied rather than trying to eliminate every unknown. Do not append new work to every delivery; propose another stage plan only when an unapproved next stage is genuinely needed.
