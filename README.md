# Plainly

[简体中文](README.zh-CN.md)

A reusable agent skill for product and service copy people can understand at a glance.

Rewrite UI labels, buttons, forms, feedback, onboarding, notices, help, product descriptions, and short customer messages. Preserve the underlying behavior and facts, ask about ambiguous meanings, and deliver an **Original → Revised** comparison.

## What it does

- Uses everyday language and concrete actions.
- Keeps permissions, fees, conditions, statuses, and irreversible consequences accurate.
- Uses consistent names for the same concepts while keeping different actions distinct.
- Adapts length to the language and context.
- Keeps menu structure and product behavior intact during a copy-only rewrite.

| Known context | Original | Revised |
| --- | --- | --- |
| A button only saves a draft | Submit | Save draft |
| An invoice list is loaded and empty | No data | No invoices yet |
| Chinese navigation opens an invoice list | 发票管理中心 | 发票 |

## Language

The skill instructions are in English. The output follows your requested language or the product's existing language.

For Chinese short UI copy, names default to **2–4 characters** and one-line descriptions to **20 characters or fewer**. Longer messages preserve essential details. English labels usually use 1–3 familiar words. Explicit limits override these defaults; the skill asks when a hard limit would obscure meaning.

## Install in Codex

Clone this repository into your personal skills directory:

```sh
git clone https://github.com/dongyu-will/plainly.git "${CODEX_HOME:-$HOME/.codex}/skills/plainly"
```

If that directory already exists, review and update its files instead of cloning over it. Start a new chat if the newly installed skill is not listed.

This is an instruction-only skill. It requires no API keys or additional runtime packages.

## Use

```text
$plainly
Rewrite the following admin copy for first-time users.
Preserve the actual functionality and return a before/after table.
Ask about ambiguous actions before rewriting them:
[paste the copy and any relevant behavior]
```

Chinese requests work too:

```text
$plainly
重写下面的后台文案，使用日常说法，保留功能和事实。
输出“原文案 → 新文案”对照表，不确定的功能含义先问我。
[粘贴文案]
```

You can supply original strings or a page or file the agent is authorized to read. A rewrite normally returns suggestions in the conversation. Ask explicitly if you want the agent to apply them to a project.

## Files

- [SKILL.md](SKILL.md): instructions, language and length defaults, delivery checks.
- [references/scenes.md](references/scenes.md): context-specific guidance and examples.
- [agents/openai.yaml](agents/openai.yaml): Codex skill-list metadata and an invocation prompt.

## Contributing

For a wording or behavior change, include a realistic source example, its known functionality, and the expected outcome. Clarify why the existing guidance falls short. Keep shared rules in the entrypoint and scenario-specific detail in the reference.

## Inspiration and credit

Inspired by [向阳乔木 (@vista8)'s X post](https://x.com/vista8/status/2107887033947660597), published on October 8, 2026, about making AI-generated admin menus and descriptions easier to understand. This project expands the idea into a reusable skill for broader product and service contexts.

The approach also draws on the principles of *Don't Make Me Think* by Steve Krug and *The Non-Designer's Design Book* by Robin Williams, plus concise, restrained product writing.

## License

[MIT](LICENSE).
