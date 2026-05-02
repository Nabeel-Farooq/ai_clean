# AI Clean

Clean up messy text copied from AI CLI tools (like Claude Code, Copilot CLI, etc.).  
It removes borders, extra whitespace, and broken line wraps so your text is ready to paste anywhere.

**Workflow:** copy → ai-clean → paste

---

## Features

- Removes CLI borders (`│`, `|`)
- Fixes broken and wrapped lines
- Trims unnecessary whitespace
- Preserves code formatting
- Instantly cleans clipboard content

---

## Installation

### macOS (Homebrew)
```sh
brew install Nabeel-Farooq/tap/ai-clean
```

### One-line install (macOS / Linux)
```sh
curl -fsSL https://github.com/Nabeel-Farooq/ai_clean/releases/latest/download/ai-clean.tar.gz \
  | sudo tar -xz -C /usr/local/bin ai-clean
```

---

## Usage

```sh
ai-clean              # clean clipboard
ai-clean --dry-run    # preview output without modifying clipboard
ai-clean --stdin      # process piped input
ai-clean --explain    # show what changed
ai-clean --version
```

---

## Example

**Before:**
```
│ messy cli output │
│ with borders     │
```

**After:**
```
messy cli output with borders
```
