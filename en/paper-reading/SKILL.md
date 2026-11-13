---
name: paper-reading
description: Conduct close readings of research papers, prepare literature review reports, or write student review instructions using original excerpts, English translations where needed, and summaries of the original argument. Preserve the authors' reasoning across five areas covering task value, field status and objectives, methodological outputs, training, and experimental validation. Use for in-depth research reviews, not merely finding paper lists or producing one-sentence summaries.
---

# Close Reading and Research Review

Help readers understand how the authors frame a problem, establish its value, design a method, and validate their objectives, providing a basis for later reproduction and research. These are general review requirements, not limited to medicine, multimodal research, or any particular field.

## Presentation approach

When reviewing a specific paper, present each part in this order:

1. **Original excerpts:** Select passages directly relevant to the part, retaining necessary context, key qualifications, and the authors' order of argument.
2. **English translation, when needed:** For non-English passages, provide a faithful English translation preserving the subject, scope, conditions, and degree of certainty. For passages already in English, retain the original without duplicating it as a translation. Use English for the review unless the user requests another language.
3. **Logic of the original argument:** Summarize how the authors move from premises to judgments or conclusions, showing the relationships between their claims.

A summary of the argument cannot replace the excerpts or any necessary translation, and must not mix the reviewer's speculation into the authors' reasoning. When assessing whether the evidence is sufficient, identify your own judgment separately. Use original figures, tables, equations, and examples when helpful.

Prioritize the full paper and relevant supplementary material. If only an abstract or partial material is available, identify which parts cannot yet be reconstructed rather than filling gaps with general knowledge. Respect the quotation limits applicable to the source. When restricted, retain permitted short excerpts and any necessary translations, and clearly distinguish paraphrases of the remaining material.

If the user only requests review instructions, provide guidance for the five parts below and the shared presentation approach; do not perform the students' review for them. If the user discusses only one part, focus on that part and retain the agreed requirements.

## Five parts of the review

### 1. Task definition and value to the field

Show how the authors define the task and introduce its value to the field. Through original excerpts, translations where needed, and a summary of the argument, trace how they introduce the problem, explain its importance, and formulate the task definition.

Preserve the authors' own task formulation and rationale for its value. Do not replace their argument with a predetermined framework or a single summary sentence.

### 2. State of the field, challenges, and research objectives

First show how the authors describe the state of the field, then explain what change this paper seeks to bring about. Trace what prior work has achieved, what problems remain, what the paper aims to solve, and how solving them would change the field.

This part presents the authors' intended objectives; Part 5 assesses how far the experiments demonstrate their achievement.

### 3. Approach, methods, and concrete outputs

Show the approach and methods used to pursue the objectives in Part 2, how their components work together, and what concrete outputs the work provides.

For each output, explain what it is and its inputs and outputs, connecting the method's design to the research objectives. Use original method diagrams, equations, or examples when needed. Explain inputs and outputs according to the actual nature of the result; do not invent such interfaces for results that do not have them.

### 4. Training data and training process

Describe the training datasets, including their sources, sizes, and construction, along with the training methods, loss functions, and key training settings at each stage.

Trace the full process from data preparation to completed training so readers understand how the outputs in Part 3 were obtained. Explicitly list key details the paper leaves unclear rather than supplying them yourself.

If the paper involves no training, state this and describe how its outputs were constructed according to the paper; do not invent a training stage.

### 5. Experimental evaluation and validation of objectives

Describe the evaluation datasets, metrics, comparison baselines, and results. Use the original figures, tables, and analysis to trace how the authors argue that the objectives in Part 2 have been achieved and why the methods in Part 3 are effective.

After presenting the authors' argument, assess whether the experiments sufficiently support these conclusions. Distinguish what the authors claim to have demonstrated from what the experiments actually support, identifying which objectives and design choices have supporting evidence and which still lack validation.

## Open-source checks and scope control

Briefly check whether code has actually been released and whether data and models are accessible. Record resources useful for later reproduction. Distinguish promised releases, published materials, and successfully executed implementations; finding a repository does not constitute reproduction.

Keep the five parts above as the main structure rather than expanding into a lengthy audit checklist. Unless requested, do not add separate sections on licenses, compute budgets, or deployment plans, or preselect students' research topics or complete experimental plans.

Before delivery, check that excerpts and any translations correspond and that the argument is faithfully represented; that Part 2 establishes the state of the field before introducing objectives; that Parts 3 and 4 explain the outputs and how they were obtained; and that Part 5 returns to the objectives and methods when assessing evidence.
