# my-pi-extensions

A docs-only index of pi extensions. `README.md` (English) and `README_zh.md` (Chinese)
carry the list; no extension source code lives here.

## Keep both READMEs in sync

Land every edit in both files in the same change: same rows, same order, same meaning in
each language.

## Adding a plugin to the README

Add one row to the `My extensions` (中文：`我的插件`) table in **both** files.

| Column | Rule |
| --- | --- |
| Extension / 插件 | Link the repo: `[name](https://github.com/Wade11s/<repo>)` |
| Status / 状态 | Emoji + development status, reusing an existing pair: 🚀 Actively improving / 持续优化 · 🚧 In development / 开发中 · 🔧 Maintained / 维护 · ⚠️ Deprecated / 已弃用 |
| Category / 分类 | The plugin's capability domain, narrow enough to separate it from the other rows (e.g. `Model provider`, `X search`). Reuse an existing term when it fits. |
| What it does / 能力 | One sentence naming the user-visible capability, not the commands, tools, or files behind it |

Order rows by status — 🚀, 🚧, 🔧, ⚠️ — keeping the current relative order within a status.
Done when both tables carry the row at the same position and all four cells match the rules.

## Commit messages

Conventional Commits, imperative subject:

    <type>(<scope>): <subject>

- `type`: `feat`, `fix`, `docs`, `refactor`, `chore`.
- `scope`: optional; the file or area touched, e.g. `readme`, `agents`.
- `subject`: lowercase, no trailing period, ≤ 72 characters.
- Body: optional `-` bullet list, one per change.
