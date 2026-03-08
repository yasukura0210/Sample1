# Copilot Instructions for Sample1

## Repository Overview

This is a minimal sample/demonstration repository owned by **yasukura0210**. It currently contains a single Markdown file (`test1.md`) with a Mermaid flowchart diagram written in Japanese.

### Current Repository Contents

| File | Description |
|------|-------------|
| `test1.md` | A Mermaid `flowchart TD` diagram illustrating a basic process flow in Japanese |

### Diagram in `test1.md`

The flowchart represents:
- **開始** (Start) → **入力を受け取る** (Receive Input) → **処理を実行** (Execute Process) → **結果を表示** (Display Results) → **終了** (End)

---

## Key Facts for a Coding Agent

### Language & Framework
- No programming language or framework has been established yet.
- There is no source code, no `package.json`, no `Makefile`, no `requirements.txt`, or any other dependency/build manifest.

### Build, Test & Lint
- **No build system exists.** Do not attempt to run `npm run build`, `make`, `gradle`, or similar commands — they will fail.
- **No test framework exists.** Do not attempt to run `npm test`, `pytest`, `go test`, or similar — they will fail.
- **No linter configuration exists.** Do not attempt to run `eslint`, `flake8`, `golint`, or similar — they will fail.
- When adding new code to this repository, establish the appropriate toolchain (e.g., `npm init`, `pip install`, etc.) **before** writing application code.

### Errors & Workarounds Encountered
- No CI/CD pipelines (`.github/workflows/`) exist, so there are no automated checks to pass.
- The repository was initialized with only two commits. The git history is shallow (cloned with `--depth`). If full history is needed, run `git fetch --unshallow` first.

---

## How to Work Efficiently

1. **Understand the goal first.** This is a blank-slate sample project. Ask for or look for clarification on what language, framework, or application type is desired before adding files.

2. **Use scaffolding tools.** When the language/framework is known, use the standard project initialization tools:
   - JavaScript/TypeScript: `npm init` or `npx create-react-app`, `npx create-next-app`, etc.
   - Python: Create `requirements.txt` or `pyproject.toml` and a virtual environment.
   - Go: `go mod init`.
   - Java: Use Maven archetype or Gradle init.

3. **Add a `.gitignore` early.** Before committing generated code, create an appropriate `.gitignore` for the chosen language/framework to avoid committing build artifacts or dependency folders.

4. **Add a `README.md`.** The repository has no `README.md`. Creating one early helps document intent and usage.

5. **Set up CI/CD when adding code.** Add a `.github/workflows/` directory with appropriate workflow files (build, test, lint) once a technology stack is chosen.

6. **Japanese language context.** The existing content is in Japanese. If the project is intended for a Japanese audience or team, consider writing comments, variable names, and documentation accordingly unless directed otherwise.

7. **Minimal changes principle.** Make the smallest possible changes to address a requirement. Avoid refactoring or restructuring unrelated parts of the project.
