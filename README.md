# AI Clean

Clean up messy text copied from AI CLI tools (Claude Code, Copilot CLI, etc.).  
It removes borders, extra spaces, and broken line wraps so you can paste clean text anywhere.

Workflow: **copy → ai-clean → paste**

---

## Features

- Removes CLI borders (`│`, `|`)
- Fixes wrapped lines
- Removes extra whitespace
- Keeps code formatting
- Cleans clipboard instantly

---

## Install

### macOS
```sh
brew install Nabeel-Farooq/tap/ai-clean
One-line install (macOS / Linux)
curl -fsSL https://github.com/Nabeel-Farooq/ai_clean/releases/latest/download/ai-clean.tar.gz | sudo tar -xz -C /usr/local/bin ai-clean
Usage
ai-clean              # clean clipboard
ai-clean --dry-run    # preview output
ai-clean --stdin      # use in pipes
ai-clean --explain    # show changes
ai-clean --version
Example

Before:

│ messy cli output │
│ with borders     │

After:

messy cli output with borders
