# LinkedIn Referral Outreach Skill

An open AGENT SKILL, created by **Katlego Mokwena** ([@black-abys](https://github.com/black-abys)). It helps an AI agent find LinkedIn jobs that fit your CV and get you referrals through personal, human-approved outreach to people who work at those companies.

## Why referrals
Referrals reach interview far more often than cold applications:
**3 in 100 applying alone vs 40 in 100 with a referral** (Ashby hiring data, 2021-2024).

## What it does
1. Reads your CV and works out your target roles, skills, school, and city.
2. Finds about 12 LinkedIn jobs that fit you.
3. Finds people at each company: current employees, same school, 2nd-degree connections, ideally on the relevant team.
4. Drafts short, genuine connection notes (under 300 characters) based on what you really share and their real recent posts.
5. Follows up with a thank-you, then once there's rapport asks for a referral, with your CV attached.

## Safety built in
- **10 outreach messages a day, max.** Mass messaging gets LinkedIn accounts restricted.
- **You approve every message** (Approve/Skip), after seeing the recipient's name, headline, and the exact text. Nothing is sent on its own.
- Read the names! Don't accidentally message your partner's parent.
- Never makes anything up, never messages anyone twice, and respects LinkedIn's ToS.

## Install
Copy the `linkedin-referral-outreach` folder (the folder that holds `SKILL.md`) into your agent's skills directory, for example:
- Claude Code: `~/.claude/skills/linkedin-referral-outreach/`
- Cursor: `~/.cursor/skills/linkedin-referral-outreach/` (or `.cursor/skills/` in a project)

```bash
git clone https://github.com/black-abys/linkedin-referral-outreach-skill
mkdir -p ~/.claude/skills/linkedin-referral-outreach
cp linkedin-referral-outreach-skill/SKILL.md ~/.claude/skills/linkedin-referral-outreach/
```

## Usage
> Read my CV. Find frontend jobs that fit. Find people who work there and say hi.

> 10 a day. Ask me before you send.

Don't: *"Message EVERYONE."* The skill will say no.

## License
MIT © 2026 Katlego Mokwena
