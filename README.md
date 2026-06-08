# Reading List Research Skill

Use official academic reading lists to evaluate whether a university program, major, studio, or course actually fits a student's interests.

This skill turns public course reading lists, module bibliographies, syllabi, and library resource lists into a practical program-fit report. It is especially useful when comparing master's programs, undergraduate majors, design studios, education programs, interdisciplinary tracks, or any field where the real curriculum is better revealed by what students are asked to read than by social media opinions.

## When to Use

- Compare several universities or programs before applying.
- Validate whether a specific program matches your interests.
- Find official reading lists from systems like Talis Aspire, Leganto, Library Reading Lists, or university module pages.
- Build a starter reading plan before committing to a school or direction.
- Identify overlapping books, papers, authors, and themes across top programs.

## What It Produces

- A short fit verdict.
- A source-backed evidence map.
- Strong fit and mismatch signals.
- A prioritized starter reading list.
- Follow-up checks for missing or uncertain evidence.

## Install

```bash
python3 /Users/susicorp/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo YOUR_GITHUB_USERNAME/reading-list-research-skill \
  --path . \
  --name reading-list-research
```

Replace `YOUR_GITHUB_USERNAME` with your GitHub username after publishing the repository.

## Example Prompt

```text
Use $reading-list-research to compare Goldsmiths MA Design, UAL MA Interaction Design, and RCA Design Products through their official course reading lists. I care most about critical design, STS, and speculative design.
```

## Files

- `SKILL.md`: The skill instructions Codex reads when the skill triggers.
- `agents/openai.yaml`: Codex App display metadata.
