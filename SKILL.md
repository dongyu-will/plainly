---
name: plainly
description: "Rewrite user-facing product and service copy in plain language. Use for UI labels and actions, messages and notices, help and onboarding, or concise page and product descriptions. Preserve meaning and behavior, compare original and revised copy, and clarify ambiguous functionality."
---

# Plainly

Help people understand at a glance what something is, what it does, and what to do next. Combine product judgment with concrete, concise, restrained writing.

Use this skill for admin tools, websites, apps, notifications, help, service descriptions, and short customer messages. Apply the rules relevant to the request. Longer editorial work, brand strategy, and visual redesign need their own scope.

## Establish meaning before rewriting

1. **Find the source and scope.** Read the supplied copy, page, or files the user has authorized you to inspect. Use existing context to identify the audience, location, and task. Ask only for missing information that changes the writing. If a rewrite has no accessible source, request the original copy or a readable location. For new copy, draft from the facts provided.
2. **Understand each item.** Identify its object, action, result, and relevant permissions, conditions, or consequences. Know what happens after a button is selected and what a status actually means. Use the real workflow or the user's explanation; a label alone does not establish behavior.
3. **Clarify ambiguity.** Ask specific questions before finalizing uncertain functionality, facts, or consequences: “Does Submit save a draft or send it for approval?” Bundle the most consequential 1–3 questions and continue with clear items. Keep uncertain items unchanged and mark them “Needs clarification” until answered. Choose ordinary wording and tone yourself.
4. **Cover the requested scope.** If the user asks for all copy, make a source inventory. Account for every item with a revision, a reason to retain it, or a clarification question. Evaluate identical strings separately when their contexts differ. For large inventories, work in batches and state which sources are covered.

For statuses, destructive actions, onboarding, notices, customer messages, help, or product descriptions, read the relevant section of [Scenarios and examples](references/scenes.md).

## Make the copy easy to understand

Use these principles as decision tools:

- **Don't Make Me Think:** Use familiar words, make actions and results predictable, and put the key meaning first. Remove wording that makes readers stop and interpret.
- **The Non-Designer's Design Book:** Contrast distinguishes different purposes; repetition makes shared terms consistent; alignment makes peer labels parallel; proximity keeps related information together. For copy, distinguish names, explanations, actions, and feedback, then present related items together.
- **Restrained product writing:** Describe concrete uses and supported benefits. Remove empty claims, exaggeration, and unnecessary decoration. Borrow the clarity and economy associated with Apple copy while writing naturally for the product.

Preserve these distinctions:

- Prefer everyday words. Remove “system,” “center,” or “management” only when they add no useful meaning. Keep necessary domain, legal, brand, and familiar product terms; explain them when needed.
- Navigation names say what people can find; buttons say what they do; statuses say what is happening. Distinct meanings need distinct wording.
- Use consistent names for the same objects and actions. Unify terms only when they mean the same thing. Respect clear established product terminology.
- Preserve amounts, dates, eligibility, fees, permissions, scope, statuses, promises, and recoverability. Ask about missing facts instead of inventing capabilities, offers, outcomes, or performance claims.
- Error messages state the known problem and an available next step. If the cause or outcome is unknown, say so. An unconfirmed payment or submission must not be presented as a failure that should be repeated.
- Keep functionality unchanged. “Disable” is not “Delete”; “Sign out” is not “Close account”; “Request a refund” is not “Refund complete.”
- Keep navigation destinations, order, and grouping unchanged in a copy-only task. Describe structural or workflow suggestions separately if they are needed.

## Match language and length to context

Write in the user's requested language. Otherwise, retain the product's existing language and locale. English skill instructions do not imply English output. For multilingual source files, preserve each locale unless translation is requested.

These are defaults, not universal limits:

| Context | Default target |
| --- | --- |
| Chinese navigation, feature, and field names | 2–4 characters with a clear meaning |
| Chinese buttons and action links | Prefer 2–4 characters; use more when an action or object requires it |
| Chinese one-line feature descriptions and field hints | At most 20 characters |
| English navigation, fields, and actions | Usually 1–3 familiar words; retain necessary qualifiers |
| Page, notice, and onboarding headings | One clear point in a short, natural phrase |
| Errors, empty states, and confirmations | Usually 1–2 short sentences containing the information needed to understand and act |
| Notice bodies and product descriptions | Lead with the result or use, then add essential conditions or next steps |
| Help and customer replies | Organize around the task; one action per step, enough detail to complete it |

Explicit user limits take precedence. If a hard limit conflicts with an essential distinction, condition, or consequence, explain the specific conflict and ask before finalizing that item. With no hard limit, allow necessary detail and briefly note a meaningful exception. Apply language-appropriate brevity rather than transferring Chinese character limits to other languages.

For a Chinese hard limit, count visible characters, including punctuation, digits, and letters; exclude spaces and line breaks unless the platform specifies otherwise. Never meet a limit by dropping essential facts.

## Deliver and check

Default to an **Original → Revised** comparison table. Localize the headings, notes, and questions to the requested output language:

| Location/context | Original | Revised |
| --- | --- | --- |

Preserve originals verbatim; never invent source text. For new copy, label the original column “— (new).” Put a name and its description on separate rows for easy review. Follow a user-specified format; a few items may use direct “Original → Revised” lines.

Add clarification questions, important retention reasons, or a small terminology list only when useful. For unresolved items, write “Needs clarification” in the revised column rather than a guessed replacement.

Before delivery, verify:

- Every source item has an outcome; unread pages and files are not counted as complete.
- Revisions match the real behavior and facts. Adjacent features remain distinguishable, and actions have predictable results.
- Object, action, and status terms are consistent. Variables, placeholders, links, numbers, and conditions are intact.
- Length requirements are met without losing essential consequences.
- Questions are specific enough to determine the wording; confirmed items are ready to use.

A rewrite request normally produces copy in the reply. When the user asks to apply it to a project, update the relevant displayed text and matching accessible names or hints. Preserve code identifiers, routes, APIs, analytics events, interpolation variables, and business logic. Report any issue that needs a layout or behavior change separately.
