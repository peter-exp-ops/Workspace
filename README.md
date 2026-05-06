# Workspace

Shared **Rules.md** for AI assistants and collaborators across projects.

## Cursor: import these rules (GitHub)

Cursor runs **`git clone <url>`** on what you type. The URL must be the **git remote for the whole repository only** — no file name, no `/blob/`, no path after the repo name.

| Wrong (will fail) | Right |
|-------------------|--------|
| `https://github.com/peter-exp-ops/Workspace/blob/main/Rules.md` | `https://github.com/peter-exp-ops/Workspace.git` |
| `https://github.com/peter-exp-ops/Workspace/Rules.md` | `https://github.com/peter-exp-ops/Workspace.git` |

**Copy-paste for “Repository URL” (or equivalent):**

```text
https://github.com/peter-exp-ops/Workspace.git
```

Do **not** add `/Rules.md` (or any path) to the repository URL.

**Importable Cursor rules** live under **`.cursor/rules/*.mdc`** (YAML frontmatter + markdown). This repo includes **`.cursor/rules/workspace-standards.mdc`**. Root **`Rules.md`** is the same content for humans, GitHub browsing, and raw copy-paste — Cursor’s GitHub rule import does **not** use `Rules.md` by itself.

**Also valid (no `.git`):**

`https://github.com/peter-exp-ops/Workspace`

**If you still get `Not Found`:** the repo may be **private** and the import may run git without your GitHub login. Make the repo public or import via **raw URL** / paste file content instead.

**Alternative:** paste into a project rule, or copy from:

- `https://raw.githubusercontent.com/peter-exp-ops/Workspace/main/Rules.md`
- `https://raw.githubusercontent.com/peter-exp-ops/Workspace/main/.cursor/rules/workspace-standards.mdc`
