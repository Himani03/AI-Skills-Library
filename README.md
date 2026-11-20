# Job Search Skills

Two custom Claude skills I use during my job search: one for tailoring resumes, one for cold outreach.

## What's inside

**resume-tailor**
Tailors my resume to a job description as a one-page ATS-friendly .docx. It gives me an honest fit rating before touching anything, makes small targeted edits instead of rebuilding, swaps in my best-matching real projects, and never adds a claim I can't back up.

**cold-outreach**
Researches the company first, then writes cold emails, LinkedIn notes and DMs, recruiter replies, and follow-ups. Each message gets two personalized sentences on why I'm interested, a real proof point from my work, and one small ask. It's written in a casual, natural voice and can save drafts to Gmail, but it never sends on its own.

## Structure

```
job-search-skills/
  README.md
  resume-tailor/
    SKILL.md
  cold-outreach/
    SKILL.md
```

Each skill is a folder with a single `SKILL.md`: a short YAML header (name and description) followed by the instructions.

## Using them

- **Claude Code:** copy the skill folders into `~/.claude/skills/` (or a project's `.claude/skills/`).
- **Claude app:** zip a skill folder and upload it as a custom skill in Claude's settings.

## Making them your own

These are written around my background and voice, so swap in your own before using them:

- In `resume-tailor/SKILL.md`: the name, contact email, links, and the formatting rules (font, margins, divider color).
- In `cold-outreach/SKILL.md`: the voice rules, banned phrases, and length targets.
- In both: any wording that says "Himani" or "her".
