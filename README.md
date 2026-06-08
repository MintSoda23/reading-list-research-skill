# Reading List Research Skill

## 中文

用官方课程书单判断一个大学项目、专业、studio 或课程是否真的适合你。

这个 skill 会把公开的课程 reading list、module bibliography、syllabus、library resource list 转成一份可执行的「项目适配度报告」。它特别适合用来比较硕士项目、本科专业、设计 studio、教育项目、跨学科方向，或者任何一个“真实课程内容比社交媒体评价更重要”的申请场景。

### 什么时候用

- 申请前比较多所大学或多个项目。
- 判断某个具体项目是否匹配自己的兴趣。
- 查找 Talis Aspire、Leganto、Library Reading Lists、大学 module 页面等官方书单来源。
- 在确定学校或方向前，先做一份 starter reading list。
- 找出顶尖项目之间反复出现的书、论文、作者和主题。

### 它会产出什么

- 简短的适配度判断。
- 带来源链接的证据表。
- 强适配信号和不适配信号。
- 优先级排序后的 starter reading list。
- 下一步需要核查的资料。

### 安装

```bash
python3 /Users/susicorp/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo MintSoda23/reading-list-research-skill \
  --path . \
  --name reading-list-research
```

### 示例 Prompt

```text
Use $reading-list-research to compare Goldsmiths MA Design, UAL MA Interaction Design, and RCA Design Products through their official course reading lists. I care most about critical design, STS, and speculative design.
```

---

## English

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
  --repo MintSoda23/reading-list-research-skill \
  --path . \
  --name reading-list-research
```

## Example Prompt

```text
Use $reading-list-research to compare Goldsmiths MA Design, UAL MA Interaction Design, and RCA Design Products through their official course reading lists. I care most about critical design, STS, and speculative design.
```

## Files

- `SKILL.md`: The skill instructions Codex reads when the skill triggers.
- `agents/openai.yaml`: Codex App display metadata.
