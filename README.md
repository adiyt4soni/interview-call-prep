# Interview and call prep

Builds a prep pack and a one-page cue card for a recruiter screen, hiring-manager call, founder call, assessment or in-person round.

**Type:** Claude Code skill · **Area:** General skills

## What it does

- Gathers the invite, the email thread, the job ad, the application as actually sent, and sourced, dated facts about the company.
- Opens with the three things most likely to sink this call, then logistics, the company in 60 seconds, and 10-13 likely questions answered in the candidate's own voice from true facts only.
- Adds questions to ask, a Don'ts list from the candidate's never-mention rules, a 20-minute night-before checklist, and a one-screen cue card.
- Checks every fact's source, times the 60-second story, and records anything not found as an open item.

## Guardrails

- Coaching advice from public guides is labelled as coaching judgement, not the company's rubric.
- Never invents a metric or result; a weak area gets the honest answer (the gap, then the real mitigation).

## When it triggers

> Build a prep pack and a one-page cue card for a recruiter screen, hiring-manager call, founder call, assessment or in-person round. Every fact about the company is sourced and dated, every answer uses only true facts from the candidate's own profile, and the pack opens with the three things most likely to sink the call. Use when the user has an interview, screen, intro call or assessment coming up, or asks to prepare for one.

## What's in this repo

- `SKILL.md`: the skill itself, the file Claude or Codex reads.
- Written to be generic: where the skill relies on the user's own files, it names them by role, not by content.

## Install

```bash
mkdir -p ~/.claude/skills/interview-call-prep
curl -fsSL https://raw.githubusercontent.com/adiyt4soni/interview-call-prep/main/SKILL.md -o ~/.claude/skills/interview-call-prep/SKILL.md
```
