# Built-in features for quality-loop-os

Purpose: software QA testing

1. **organize work and records** — run quality-loop-os-workspace. It creates ~/Documents/quality-loop-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run quality-loop-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/quality-loop-os-session-plans/.
3. **check records and task readiness** — run quality-loop-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/quality-loop-os-workspace features/quality-loop-os-plan features/quality-loop-os-check "$HOME/.local/bin/"
