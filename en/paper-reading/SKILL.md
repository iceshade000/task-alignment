---
name: paper-reading
description: Conduct close readings, literature reviews, and focused comparisons of research papers. Faithfully preserve the authors' arguments and understandable experimental evidence across five parts covering task value, field status and objectives, methodological outputs, training or construction, and evaluation. Use for understanding papers, preparing reading materials, or writing student review instructions, not merely finding paper lists or producing one-sentence summaries.
---

# Close Reading and Research Review

Help readers who have not read the original understand why the authors study the problem, what they actually do, and how they validate the results. Apply across research fields, following the user's requested scope and existing organizational structure.

## Sources and presentation

- Prioritize the original paper and supplementary material relevant to the current question. Record pages, sections, figures, tables, and versions. Record publication date, journal or conference, author affiliations, and study type separately; distinguish preprints from formal publications.
- Keep original excerpts, corresponding translations where needed, and relationships within the authors' argument in the source-checking notes. The final reading document may use coherent, faithful paraphrases with key short quotations and precise references; do not require a repeated three-part template in every section. Follow the user's format when parallel originals and translations are requested. Respect quotation limits. Write in English by default: translate non-English passages into English when needed, and do not duplicate English originals as translations unless another language is requested.
- When only an abstract or part of the paper is available, describe only what was actually read. Record important gaps as unknown rather than supplying details from general knowledge. Attaching the full text does not mean its entirety has been checked.
- By default, present source facts, the authors' claims, and their reasoning. Add the reviewer's judgments separately when the user requests relevance analysis, recommendations, or evidence assessment. Do not insert implications for our work, relationships between papers, or research-topic suggestions into factual accounts of individual papers.
- Condense in units of the minimum complete explanation, preserving the subject, action, necessary conditions, examples, and results. Do not compress an argument into inputs and outputs, keywords, or abstract labels. For example, explain which model is held constant, what is removed, and which results are compared in an ablation using the same base model.
- State actual methods and scope directly, avoiding irrelevant defensive qualifications such as “not” or “cannot be equated with.” Explain genuine limitations affecting understanding or conclusions where they matter.
- In English materials, explain unfamiliar diseases, methods, metrics, and abbreviations in English at first mention. For dataset and task names, also explain what the data contain and what is predicted or judged; do not infer the task from its name alone. Retain proper names without established English translations and explain their meaning. Supply necessary explanations on separate pages or in independently readable tables, without repeating them in every sentence.

## Five-part structure

### 1. Task definition and value to the field

Follow the original in explaining the practical need in the field and why the authors consider it worth studying. Preserve facts and examples supporting that rationale, then introduce the paper's task, inputs and outputs, and scope of applicability.

“Provide images and labels, obtain a model” explains only an interface; it cannot replace the authors' argument about clinical needs and difficulties in choosing methods. Do not invent significance for the paper from general domain knowledge.

### 2. State of the field, challenges, and research objectives

Connect the authors' reasoning: what prior work has achieved → what specific difficulties remain → why existing approaches struggle with them → what change this paper seeks to bring about. Connect to Part 1 without repeating background.

Distinguish the authors' objectives from experimentally demonstrated results; do not present intended improvements as already achieved.

### 3. Methods, implementation approach, and outputs

Explain what each component does, why the components connect as they do, and how the final outputs are produced. Use necessary examples from the paper to explain concepts and operations rather than substituting architecture names for method descriptions.

Distinguish outputs such as models, tools, workflows, and databases. Explain their actual inputs, operations, and outputs separately; do not force an input-output interface onto results without one. Make existing tools, newly proposed mechanisms, and actually executed components distinguishable.

### 4. Training data and training or construction process

Help readers understand how the methods in Part 3 were obtained:

- Data sources, scale, and construction; who generates questions, demonstrations, and reference answers, and how these are screened or checked.
- Which model is trained, which generates training material, and which components are operational tools or scoring models; avoid calling them all simply “the model.”
- Each stage's training objective, feedback or loss, key settings needed for understanding, and connections between stages.

When no training is involved, describe the actual construction process, such as tool integration, rule organization, or external memory updates. Record key details missing from the paper rather than filling them in by speculation.

### 5. Experimental evaluation and validation of objectives

Organize experiments around what the authors seek to demonstrate. For each major experiment, help readers understand:

1. **What is evaluated and the unit of evaluation:** Patient predictions, task completion, generated reports, tool calls, or the evaluator itself; whether the unit is a patient, question, task category, run, or human rating.
2. **Where data and references come from:** Test-set construction, splits, and filtering; the sources of reference labels, correct answers, human annotations, or scoring rules. Explain the respective roles of data used for training, search, selection, and final testing.
3. **What is compared:** The actual baseline procedures, shared conditions, and factors that change. Separate whole-system comparisons from mechanism comparisons using the same base model; distinguish results cited from other papers from reruns under the same conditions.
4. **How outcomes are judged and scored:** Success and failure criteria, plain-English meanings of metrics, numerators and denominators or scoring procedures, evaluators, and aggregation. Explain formula variables and the question each formula answers. Describe how abstentions, execution failures, invalid submissions, filtering, and repeated runs are handled when they affect the statistics.
5. **Actual results:** Values and their conditions, with necessary uncertainty or significance information. Explain how the authors use them to address the objectives; do not combine numbers from different experiments into a single comparison.

Choose relevant information according to the experiment; do not fabricate content for inapplicable fields. “77% success” or “improved F1” alone is insufficient. For example, in milestone-based experiments, explain separately how the fraction completed within a task and the rate of fully successful tasks are calculated. Distinguish an automated evaluator's agreement with humans from the research system's own success rate.

Do not infer unreported scoring rules and present them as established facts. If reconstructing proportions from table counts, state the basis and any discrepancies. For perspective or review articles, explain that their evidence comes from cited studies rather than inventing an independent benchmark for the article.

When the user only wants to understand a paper, fully present the authors' validation approach. Assess whether experiments sufficiently support conclusions separately only when evidence critique, proposal recommendations, or similar analysis is requested, distinguishing source claims from your own judgments.

## Organizing multiple papers

Choose structures separately for the overview, individual close readings, and cross-paper comparisons; do not automatically reuse one ordering for all three.

- **Overview:** Summarize publication information, study type, task, and contributions claimed in the abstract. Follow the user's requirements on relevance grouping and analysis of potential uses.
- **Individual close readings:** Preserve the full argument across the five parts. Use the agreed order; chronological order often helps explain development over time.
- **Cross-paper comparisons:** Extract material around the selected focus areas, using appropriate comparison dimensions for each. A task table may compare background, difficulties, and objectives; an evaluation table may compare data, references, scoring, controls, and results. Do not repeat each paper's complete story in every row or compress away the premises needed for understanding. Follow the agreed grouping and order, including only material relevant to the focus area.

Comparisons and close readings share a factual basis but should not be mechanically copied. Provide suitable access to originals or close readings when full details are needed, with navigation following the user's requirements.

## Public resources and scope

Briefly check whether code is actually public and what has been released. Distinguish code, data, weights, tool configurations, and evaluation procedures as applicable. Record accessible entry points and the time of checking; distinguish author promises, materials actually found, and reproduction results.

Keep the five parts as the main structure rather than automatically expanding into licenses, budgets, deployment, or complete experimental plans. When the user requests only review instructions, provide guidance without conducting the literature review for them; when discussing one part, focus on it.

## Before delivery

Check from the perspective of someone who has not read the paper:

- Can they explain why the authors raised the problem and how existing difficulties connect to the objectives? Have labels replaced the argument?
- Can they understand the key methods, training material, and how outputs are produced? Are terms and task names given concrete meaning?
- Can they explain how a major experimental score is obtained, where reference answers come from, and what is compared? Do numbers have units, denominators, and conditions?
- Are faithful paraphrases, original author claims, and reviewer judgments distinct? Is there unnecessary advice about uses or defensive wording?
- Does each comparison retain only its relevant focus while preserving necessary context?
- After edits, are the source document, overview or comparison, and final presentation updated consistently? Do original links, tables, and page navigation work?

When a premise needed for understanding is missing, add concrete information rather than substituting more words or sections for repairing the logic.
