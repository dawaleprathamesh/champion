# Graphify Setup Guide

## Prerequisites
- Python 3.10+
- pip
- AI Assistants:
  - Claude
  - Cursor
  - Codex
  - Gemini CLI
  - GitHub Copilot CLI
  - VS Code Copilot Chat

## Installation Commands
Run the following commands to install Graphify:
```bash
pip install graphifyy
graphify install
```

## Platform-Specific Install Commands
- **Claude Code**: `graphify claude install`
- **Cursor**: `graphify cursor install`
- **Codex**: `graphify codex install`
- **Gemini CLI**: `graphify gemini install`
- **GitHub Copilot CLI**: `graphify copilot install`
- **VS Code Copilot Chat**: `graphify vscode install`

## How to Run on Codebase
To run Graphify on your codebase, use:
```bash
/graphify .
$graphify . # for Codex
```

## Expected Output Tree
```
.
├── graphify.yml
├── README.md
├── docs
│   └── graphify.md
└── your_code_files
```

## Recommended Always-Available Install Commands
```bash
graphify claude install
graphify cursor install
graphify codex install
graphify gemini install
graphify copilot install
graphify vscode install
```

## .graphifyignore Example
```
# Ignore Python compiled files
__pycache__/
*.pyc

# Ignore Jupyter notebooks
*.ipynb
```

## Query Examples
- To analyze the code: `graphify analyze .`
- To run tests: `graphify test .`

## Copy-Paste Agent Prompt Template
```
# Prompt:
Please analyze the codebase at GRAPHIFY_OUT_PATH according to the specifications.
```

## Rules
1. Ensure you have the necessary permissions to modify the codebase.
2. Follow any specific guidelines provided by the project maintainers.
3. Use the prompt template as a base and modify as needed before executing it.
