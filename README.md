# ⚡ Superpowers Skills

A collection of 14 AI agent skills for **Antigravity** that supercharge your development workflow — from brainstorming and planning to code review and debugging.

## 🚀 Installation

Run this single command from the **root of any project** to install all skills:

```bash
curl -sSL https://raw.githubusercontent.com/Drscq/superpowers-skills/main/install_superpowers.sh | bash
```

This will create a `.agents/skills/` directory (if it doesn't exist) and install all 14 superpowers skills into it.

## 📦 Included Skills

| Category | Skill | Description |
|---|---|---|
| **Brainstorming & Planning** | `superpowers-brainstorming` | Explores user intent, requirements and design before implementation |
| | `superpowers-writing-plans` | Creates multi-step implementation plans from specs or requirements |
| | `superpowers-executing-plans` | Executes written implementation plans with review checkpoints |
| **Development & Debugging** | `superpowers-subagent-driven-development` | Executes implementation plans with independent sub-tasks |
| | `superpowers-test-driven-development` | Implements features using TDD — write tests before code |
| | `superpowers-systematic-debugging` | Structured debugging for bugs, test failures, or unexpected behavior |
| **Code Review & Quality** | `superpowers-requesting-code-review` | Verifies work meets requirements before merging |
| | `superpowers-receiving-code-review` | Processes code review feedback with technical rigor |
| | `superpowers-verification-before-completion` | Runs verification commands before claiming work is done |
| **Environment & Git** | `superpowers-using-git-worktrees` | Creates isolated git worktrees for feature work |
| | `superpowers-finishing-a-development-branch` | Guides completion of development work (merge, PR, or cleanup) |
| **Meta-Skills** | `superpowers-using-superpowers` | Establishes how to find and use skills |
| | `superpowers-writing-skills` | Creates and verifies new skills |
| | `superpowers-dispatching-parallel-agents` | Dispatches independent tasks to parallel agents |

## 📝 Requirements

- `git` must be installed
- `bash` shell
