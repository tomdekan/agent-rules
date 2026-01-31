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
| `communication-style.mdc` | Direct feedback, minimal formatting, no compliments | Always |
| `decision-support.mdc` | Evaluate suggestions, propose better alternatives | Always |
| `python-style.mdc` | Type hints, f-strings, function size, import conventions | `**/*.py` |
| `tests-automatic.mdc` | Guidelines for writing automated tests | `**/test*.py` |
| `tests-manual.mdc` | When and how to run manual tests | Always |
| `llm-choice.mdc` | Prevent unintended LLM model changes | Always |
