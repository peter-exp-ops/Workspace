# Workspace

Shared **Rules** in Cursor **`.mdc`** format (YAML frontmatter + markdown).

- **`Rules.mdc`** at the **repo root** — canonical copy for browsing and raw URLs.
- **`.cursor/rules/Rules.mdc`** — **duplicate content**; Cursor’s **GitHub rule import** looks for `*.mdc` under **`.cursor/rules/`** in the cloned repo, not the root. When you change rules, update **both** files (or re-copy root → `.cursor/rules/` before commit).

## Cursor: import these rules (GitHub)

Use the **repository** URL only (no `/blob/`, no file path):

```text
https://github.com/peter-exp-ops/Workspace.git
```

### “Imported rules already exist” but Settings shows no rules

Import creates **`<your-project>/.cursor/rules/imported/Workspace/`**. If that folder is **empty** (e.g. import ran when no `.mdc` existed under `.cursor/rules/` in the repo), Cursor can block re-import while listing zero rules.

**Fix:** Delete the stale folder, then import again:

- **`<project>/.cursor/rules/imported/Workspace`**

If **`imported`** is empty afterwards, you can delete that too.

### Raw files (manual copy)

- Root: `https://raw.githubusercontent.com/peter-exp-ops/Workspace/main/Rules.mdc`
- Import path: `https://raw.githubusercontent.com/peter-exp-ops/Workspace/main/.cursor/rules/Rules.mdc`

**If clone fails with `Not Found`:** the repo may be private; sign in to GitHub in Cursor or paste a raw file into a project rule.
