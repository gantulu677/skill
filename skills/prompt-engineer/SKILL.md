---
name: prompt-engineer
description: Design, analyze, test, and refine AI prompts with explicit objectives, context, constraints, output contracts, and evaluation criteria.
---
# Prompt Engineer

## Purpose
Create prompts that communicate tasks, context, constraints, and desired outputs clearly while reducing ambiguity and unsupported assumptions.

## Triggers
Use to write, improve, debug, evaluate, standardize, or template prompts and prompt workflows.

## Principles
- Optimize for task success, not length.
- State objective and intended audience.
- Include only context that materially affects the result.
- Separate instructions, source material, constraints, and examples.
- Define output format and acceptance criteria.
- Resolve conflicting requirements explicitly.
- Prompt wording does not guarantee model capability or factual correctness.
- Separate portable prompt logic from platform-specific syntax.

## Workflow
1. Identify goal, user, downstream use, and success criteria.
2. Gather source material, relevant facts, assumptions, and missing context.
3. Define scope, exclusions, tone, length, safety, tools, and authorization constraints.
4. Structure role/context, task, inputs, process, constraints, output schema, and evaluation.
5. Ask the smallest necessary clarification or state bounded assumptions.
6. Specify output fields, ordering, format, and examples where useful.
7. Stress-test conflicts, edge cases, incomplete inputs, adversarial content, and likely misinterpretations.
8. Evaluate against observable criteria; separate objective checks from subjective preferences.
9. Remove redundancy and resolve contradictions.
10. Deliver the final prompt with concise usage notes or test cases when useful.

## Checklist
A clear primary objective; sufficient relevant context; ordered instructions; explicit constraints/exclusions; marked variables; specified output; non-conflicting examples; conditional tool use; separation of untrusted input; observable evaluation criteria; labeled platform-specific features.

## Templates
Use descriptive placeholders such as `{{subject}}` and `{{source_material}}`. State which are required, optional, or defaulted. Do not leave ambiguous placeholders unexplained.

## Safety
Do not create prompts to bypass safety controls, obtain secrets, impersonate authorization, or cause unauthorized actions. Require appropriate verification and confirmation for consequential workflows. Do not present generated content as verified fact without evidence.

## Output
Final prompt, required variables, assumptions, intended platform (if any), and evaluation checklist. Explain practical differences when multiple versions are requested.

## Completion
Objective, context, constraints, inputs, output contract, and evaluation criteria are clear, with representative edge cases considered.
