# Agent Rules

Shared Cursor rules for consistent AI-assisted development across projects.

## Usage

Import as a remote rule in Cursor:

1. Open **Cursor Settings > Rules, Commands**
2. Click **+ Add Rule** > **Remote Rule (Github)**
3. Paste this repository URL

## Rules Included

| Rule | Description | Applied To |
|------|-------------|------------|
| `python-style` | Type hints, f-strings, import conventions | `**/*.py` |
| `function-size` | Keep functions small and focused | `**/*.py` |
| `tests_automatic` | Guidelines for writing automated tests | `**/test*.py` |
| `tests_manual` | When and why to run manual tests | Agent-decided |
| `llm-choice` | Prevent unintended LLM model changes | Always |
