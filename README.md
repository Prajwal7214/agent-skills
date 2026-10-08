# Agent Skills 🚀

A comprehensive repository of curated skills for **Anthropic Claude Code** and **Google DeepMind Antigravity** (`agy`).

This repository brings together workflow methodologies, automation extensions, and agent capabilities into a single organized structure.

---

## 📂 Repository Structure

```text
agent-skills/
├── README.md
├── .gitignore
├── claude/                            # Skills for Claude Code CLI / Agent
│   ├── built-in-browser/
│   ├── canvas-design/
│   ├── chrome-browser/
│   ├── computer-use/
│   ├── content-repurposing/
│   ├── deep-research/
│   ├── docs/
│   ├── docx/
│   ├── google-workspace/
│   ├── import-memory/
│   ├── morning/
│   ├── pdf/
│   ├── pptx/
│   ├── skill-creator/
│   └── xlsx/
└── antigravity/                       # Skills for Antigravity CLI / IDE
    ├── superpowers/                   # Core software engineering workflows
    │   ├── brainstorming/
    │   ├── brand-identity/
    │   ├── dispatching-parallel-agents/
    │   ├── error-handling-patterns/
    │   ├── executing-plans/
    │   ├── finishing-a-development-branch/
    │   ├── generating-skills/
    │   ├── receiving-code-review/
    │   ├── requesting-code-review/
    │   ├── subagent-driven-development/
    │   ├── systematic-debugging/
    │   ├── test-driven-development/
    │   ├── using-git-worktrees/
    │   ├── using-superpowers/
    │   ├── verification-before-completion/
    │   ├── writing-plans/
    │   └── writing-skills/
    └── builtin/                       # Antigravity system & platform skills
        ├── agy-customizations/
        ├── antigravity_guide/
        ├── automation/
        ├── generative_ui/
        ├── migrate-workflows/
        ├── permissioned-github/
        ├── plugin/
        ├── ui-extension/
        └── ui-plugin-navigation/
```

---

## 🧠 Claude Skills Index

| Skill | Purpose |
|---|---|
| `built-in-browser` | Web automation and browsing via integrated browser engine |
| `canvas-design` | Visual canvas layout, graphics, and design creation |
| `chrome-browser` | Chrome browser automation, DOM inspection, and navigation |
| `computer-use` | Operating system interactions and GUI task automation |
| `content-repurposing` | Transforming and reformatting content across channels |
| `deep-research` | Multi-step research workflows, literature exploration, and synthesis |
| `docs` | Documentation extraction, generation, and reference lookups |
| `docx` | Microsoft Word (`.docx`) file creation, editing, and parsing |
| `google-workspace` | Integration with Google Docs, Sheets, Drive, and Workspace apps |
| `import-memory` | Context and memory restoration from previous sessions |
| `morning` | Daily morning routines, task prioritization, and briefing |
| `pdf` | PDF document analysis, extraction, and generation |
| `pptx` | PowerPoint presentation authoring and formatting |
| `skill-creator` | Interactive generator for authoring new Claude skills |
| `xlsx` | Excel workbook generation, formulas, and tabular data handling |

---

## ⚡ Antigravity Skills Index

### 1. Superpowers & Engineering Workflows (`antigravity/superpowers/`)

| Skill | Purpose |
|---|---|
| `brainstorming` | Explore user intent, requirements, and design before implementation |
| `brand-identity` | Single source of truth for design tokens, UI guidelines, and voice/tone |
| `dispatching-parallel-agents` | Parallel subagent orchestration for independent tasks |
| `error-handling-patterns` | Resilient error architectures, Result types, and graceful degradation |
| `executing-plans` | Controlled step-by-step plan execution with verification checkpoints |
| `finishing-a-development-branch` | Post-implementation git integration, cleanup, and merging |
| `generating-skills` | Scaffolds new Antigravity skills following predefined templates |
| `receiving-code-review` | Technical evaluation and rigorous handling of code review feedback |
| `requesting-code-review` | Verification and preparation of code before requesting review/merging |
| `subagent-driven-development` | Plan execution by delegating independent tasks to subagents |
| `systematic-debugging` | Root-cause analysis and hypothesis testing before proposing bug fixes |
| `test-driven-development` | Test-Driven Development (TDD) discipline and red-green-refactor loop |
| `using-git-worktrees` | Isolated workspace environments via git worktrees |
| `using-superpowers` | Master skill coordinator and invocation rules |
| `verification-before-completion` | Evidence-first verification before declaring tasks complete |
| `writing-plans` | Multi-step implementation planning documentation |
| `writing-skills` | Creating, updating, and validating skills |

### 2. Built-in Platform Skills (`antigravity/builtin/`)

| Skill | Purpose |
|---|---|
| `agy-customizations` | Reference and guide for skills, rules, plugins, hooks, and MCP servers |
| `antigravity_guide` | Quick reference, sitemap, CLI commands, and slash commands |
| `automation` | Long-running task and cron-based background workflow automation |
| `generative_ui` | Inline interactive widgets and rich visual HTML artifacts |
| `migrate-workflows` | Automated migration of legacy workflows to modern skills |
| `permissioned-github` | Permissioned GitHub access and operations |
| `plugin` | Creating and structuring Antigravity extensions and plugins |
| `ui-extension` | Antigravity IDE UI extension development |
| `ui-plugin-navigation` | Navigation, menus, and sidebars for IDE plugins |

---

## 📥 How to Use & Install

### For Claude Code
To use these skills with Claude Code, copy the desired skill folder to your personal Claude skills directory:

```bash
# Copy all Claude skills
cp -r claude/* ~/.claude/skills/

# Or copy a specific skill
cp -r claude/deep-research ~/.claude/skills/
```

### For Antigravity (`agy`)
To use these skills with Antigravity, place them in your global or workspace configuration directory:

```bash
# Global Antigravity skills
cp -r antigravity/superpowers/* ~/.gemini/config/skills/

# Built-in or custom skills
cp -r antigravity/builtin/* ~/.gemini/antigravity/builtin/skills/
```

---

## 📄 License
This collection is provided for personal and developer productivity. Refer to individual skill directories for any upstream license specifications.
