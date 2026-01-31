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
| `communication-style` | Direct feedback, minimal formatting, no compliments | Always |
| `decision-support` | Evaluate suggestions, propose better alternatives | Always |
| `python-style` | Type hints, f-strings, function size, import conventions | `**/*.py` |
| `tests_automatic` | Guidelines for writing automated tests | `**/test*.py` |
| `tests_manual` | When and why to run manual tests | Always |
| `llm-choice` | Prevent unintended LLM model changes | Always |
