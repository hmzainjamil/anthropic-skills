# anthropic-skills

> **Anthropic official skills — curated Claude Code skill collection from Anthropic**

![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat)
![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-FF6B35?style=flat)
![Stars](https://img.shields.io/github/stars/hmzainjamil/anthropic-skills?style=flat)
![Last Commit](https://img.shields.io/github/last-commit/hmzainjamil/anthropic-skills?style=flat)

---

## CONCEPTS

| Concept | Description |
|---|---|
| **Official Skills** | Vetted by Anthropic team for quality |
| **Core Skills** | Caveman, compress, summarize, context management |
| **Agency Skills** | Video agency, outreach, client ops |
| **Media Skills** | fal.ai image/video generation |
| **Dev Skills** | Code review, security, architecture |
| **Auto-Activate** | Intent-based keyword activation |
| **Index** | Searchable skill manifest (index.json) |
| **Updates** | Regular additions as Claude evolves |

---

## 🔥 Hot Commands

```bash
# Activate skill
claude --skill anthropic-skills 'your task'

# Quick workflow
claude 'anthropic automation task'

# Get capabilities
claude 'what can anthropic-skills do?'
```

## ■ tip
> Mention **anthropic** or **skills** in your prompt to auto-activate this skill.

---

## ☠️ STARTUPS / BUSINESSES

- **Agencies**: automate anthropic workflows for clients at scale
- **Founders**: ship skills features 10x faster
- **Freelancers**: deliver official work with AI precision

---

## Features

- Anthropic automation
- Skills automation
- Official automation
- Claude automation
- Code automation
- Curated automation

---

## Installation

```bash
git clone https://github.com/hmzainjamil/anthropic-skills.git
cd anthropic-skills
```

---

## Usage

```bash
# Activate skill in Claude Code
claude --skill anthropic-skills "your task here"

# Quick workflow
claude "anthropic automation task"

# Get help
claude "what can anthropic-skills do?"
```

---

## Configuration

| Variable | Description | Default |
|---|---|---|
| `API_KEY` | Primary API key | Required |
| `MODEL` | AI model to use | claude-3-5-sonnet |
| `DEBUG` | Enable verbose debug | false |
| `MAX_TOKENS` | Max token budget | 8192 |
| `TIMEOUT` | Request timeout (sec) | 30 |
| `LOG_LEVEL` | Logging verbosity | info |

---

## Architecture

```
anthropic-skills/
├── README.md           # Documentation
├── SKILL.md            # Claude Code skill definition
├── scripts/            # Automation scripts
├── templates/          # Output templates
├── examples/           # Usage examples
└── docs/               # Extended documentation
```

---

## Examples

### Basic

```bash
# Simple task
claude --skill anthropic-skills "anthropic task"

# Verbose
claude --skill anthropic-skills --verbose "detailed skills task"
```

### Advanced Pipeline

```bash
# Chain skills
claude --skill anthropic-skills "step 1" | claude --skill summarize

# Batch run
for item in $(cat list.txt); do
  claude --skill anthropic-skills "process $item"
done
```

---

## Troubleshooting

| Issue | Cause | Fix |
|---|---|---|
| Auth fails | Invalid API key | Re-export key in shell profile |
| Timeout | Network or large payload | Increase TIMEOUT value |
| Empty output | Prompt too vague | Add more context |
| Rate limit | Too many requests | Add delay between calls |
| Model error | Unsupported version | Update MODEL variable |
| Import error | Missing dependency | Run pip install -r requirements.txt |

---

## Comparison

| Feature | This Skill | Alt A | Alt B |
|---|---|---|---|
| Claude Code native | ✅ | ❌ | ✅ |
| Auto-activation | ✅ | ✅ | ❌ |
| Free to use | ✅ | ❌ | ✅ |
| Production ready | ✅ | ✅ | ❌ |
| Active maintenance | ✅ | ❌ | ❌ |

---

## Changelog

| Version | Changes |
|---|---|
| v2.0 | Claude 4 support, auto-activation |
| v1.5 | Added keyword triggers |
| v1.0 | Initial release |

---

## Contributing

1. Fork → feature branch → commit → PR
2. Follow conventional commits: `feat:`, `fix:`, `docs:`
3. Add tests for new features

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/anthropic-skills&type=Date)](https://star-history.com/#hmzainjamil/anthropic-skills&Date)

---

## 📜 License

MIT — free to use, modify, distribute.

---

Made with ❤️ by [@hmzainjamil](https://github.com/hmzainjamil)
