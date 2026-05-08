# permis-course-marketplace

Marketplace for the **Permis Côtier de Plaisance** AI tutor plugin.

## Installing in Cowork

```bash
# 1. Add this marketplace (one-time)
/plugin marketplace add WilliamMasquelier/permis-course-marketplace

# 2. Install the plugin
/plugin install permis-course

# 3. Install Python dependencies
cd ~/.claude/plugins/cache/permis-course
uv sync
```

After install, the following skills are available in every Cowork session:

| Command | What it does |
|---------|-------------|
| `/permis-tutor` | Start a Socratic teaching session — reviews due flashcards, shows the lesson inline, teaches in French |
| `/permis-scenario` | Branching coastal navigation scenario with COLREGs debrief |
| `/permis-exam` | Full 40-question mock exam (pass threshold: 35/40) |
| `/permis-render` | Re-render lesson HTML and run visual QA |
| `/permis-setup` | Verify all prerequisites |
| `/permis-author` | Teacher/author mode — edit lessons and wiki content |

## Updating

```bash
/plugin update permis-course
```

## Prerequisites

- Claude Code / Cowork v2.1.49+
- Python 3.13+ with [uv](https://docs.astral.sh/uv/)

## Source

Plugin source: [WilliamMasquelier/permis-course](https://github.com/WilliamMasquelier/permis-course)
