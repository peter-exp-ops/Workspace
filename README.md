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

Do **not** add `/Rules.md` to that box. If Cursor has a **second** field (e.g. “Rule file”, “Path”, “Subpath”), put **`Rules.md`** there only.

If there is only **one** URL field and no path field, import the repo, then point the rule at **`Rules.md`** in the picker if Cursor offers it; otherwise use the raw file below.

**Also valid (no `.git`):**

`https://github.com/peter-exp-ops/Workspace`

**If you still get `Not Found`:** the repo may be **private** and the import may run git without your GitHub login. Make the repo public or import via **raw URL** / paste file content instead.

**Alternative:** paste the raw file into a project rule, or copy from:

`https://raw.githubusercontent.com/peter-exp-ops/Workspace/main/Rules.md`
