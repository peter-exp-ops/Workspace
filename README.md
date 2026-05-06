# Workspace

Shared **Rules.mdc** (Cursor project rule format: YAML frontmatter + markdown) for AI assistants and collaborators across projects.

## Cursor: import these rules (GitHub)

Cursor runs **`git clone <url>`** on what you type. The URL must be the **git remote for the whole repository only** — no file name, no `/blob/`, no path after the repo name.

| Wrong (will fail) | Right |
|-------------------|--------|
| `https://github.com/peter-exp-ops/Workspace/blob/main/Rules.mdc` | `https://github.com/peter-exp-ops/Workspace.git` |
| `https://github.com/peter-exp-ops/Workspace/Rules.mdc` | `https://github.com/peter-exp-ops/Workspace.git` |

**Copy-paste for “Repository URL” (or equivalent):**

```text
https://github.com/peter-exp-ops/Workspace.git
```

Do **not** append `/Rules.mdc` to the repository URL.

The importable rule file is **`Rules.mdc`** at the **repository root**. If Cursor’s importer only looks under **`.cursor/rules/`**, copy **`Rules.mdc`** there in your project, or paste the raw file into a project rule.

**Also valid (no `.git`):**

`https://github.com/peter-exp-ops/Workspace`

**If you still get `Not Found`:** the repo may be **private** and the import may run git without your GitHub login. Make the repo public or paste the raw file instead.

**Raw file (copy / manual rule):**

`https://raw.githubusercontent.com/peter-exp-ops/Workspace/main/Rules.mdc`
