# Copilot Skills

A collection of skills for GitHub Copilot. Each subdirectory is a self-contained
skill containing a `SKILL.md` file (and optional supporting `scripts/`).

## Usage

Clone this repository and copy the skills you want into your Copilot skills
directory:

```bash
git clone https://github.com/HansenQingchun/copilot-skills.git
```

Then copy an individual skill folder (for example `arxiv-search/`) into the
location your Copilot client loads skills from.

## Structure

- `<skill-name>/SKILL.md` — the skill definition.
- `<skill-name>/scripts/` — optional helper scripts used by the skill.
- `*.zip` — zipped backups of selected skills.
