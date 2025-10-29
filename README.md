# Claude Code Configuration

A comprehensive configuration for Claude Code that defines coding standards, autonomy rules, and behavior patterns for software engineering tasks.

## What is this?

This repository contains a curated `CLAUDE.md` configuration file that can be placed in your `~/.claude/` directory to customize Claude Code's behavior across all your projects.

## Installation

```bash
# Copy main.md to your Claude configuration directory
cp CLAUDE.md ~/.claude/CLAUDE.md
```

## Key Features

- **Discussion-First Mode**: Defaults to brainstorming and exploration rather than immediate implementation
- **Autonomy Framework**: Clear rules for when Claude should act independently vs. ask for permission
- **Code Quality Standards**: Language-agnostic best practices for clean, maintainable code
- **Security Baseline**: Non-negotiable security requirements
- **Git Workflow**: Conventional commit format and branch naming conventions
- **Anti-Deletion Policy**: Prevents premature code deletion during debugging

## Configuration Highlights

- Senior engineer communication style (direct, no hedging)
- Explicit action verbs required for code execution
- Comprehensive testing requirements (80% coverage minimum)
- Architecture pattern preferences (composition over inheritance, etc.)
- Language-specific conventions for Python, JavaScript/TypeScript

## Usage

Once installed, Claude Code will automatically use these guidelines for all interactions. The configuration emphasizes:

1. Discussion and exploration by default
2. Code execution only when explicitly requested with action verbs
3. High code quality standards with comprehensive testing
4. Security-first approach to all implementations

## License

MIT
