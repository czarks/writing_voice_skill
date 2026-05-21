# AGENTS.md

## Cursor Cloud specific instructions

This is a **documentation-only repository** (`khazix-skills`) containing AI Agent skill definitions following the [Agent Skills](https://agentskills.io) open standard. There is no executable code, no build system, no dependencies, and no services to run.

### Repository structure

```
README.md                                    # Repo overview (Chinese)
czar_writer_voice/
  SKILL.md                                   # Main skill definition (YAML frontmatter + Markdown)
  references/
    content_methodology.md                   # Content strategy reference
    style_examples.md                        # Writing style examples
```

### Development workflow

- The "product" is the Markdown files themselves. Editing and reviewing `.md` files is the entire development loop.
- `SKILL.md` uses YAML frontmatter (`---` delimiters) with `name` and `description` fields. Keep that frontmatter valid YAML when editing.
- No lint, test, build, or run commands exist. Validate changes by reviewing Markdown rendering and YAML frontmatter correctness.
- Skills are published via GitHub Releases as `.skill` packages. See `README.md` for installation instructions.
