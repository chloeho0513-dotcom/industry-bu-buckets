# Industry Business Units Buckets

**New to an industry? Get the whole business on one page, on day one.**

This skill breaks any industry into 5 to 6 MECE buckets that follow how the
business actually works. Each bucket shows:

- **Business Units**: what the main business units are
  - **Core Levers**: the 3 things management can change
    - **Sub-elements**: 3 per lever, each explained in plain words
- **Critical Questions**: what to ask the client first

This repo has two skills that work together:

| Skill | What it does |
|---|---|
| `industry-bu-buckets` | Gives the framework for an industry |
| `industry-issue-trees` | Turns the framework into an interactive issue-tree page |

## How to use

Type `/industry-bu-buckets` (Claude Code) or mention the skill by name, then add:
**industry + client + problem**.

Examples:

> /industry-bu-buckets Industry: Airlines. Show me the framework.

> /industry-bu-buckets Client: regional bank. Problem: profit down 15%.
> Which buckets should I check first?

> /industry-bu-buckets Build a framework for Hospitality.

The more context you give, the sharper the answer.

## Issue trees

Type `/industry-issue-trees` (Claude Code) or mention the skill by name, then say which industries you want.

Each business unit opens into its 3 levers, and each lever into its 3 sub-elements. Levers are badged as mainly revenue, mainly cost, or both. The badges are a judgement, not a dollar measure.

Examples:

> /industry-issue-trees Build issue trees for all 12 industries.

> /industry-issue-trees Airlines only, with revenue and cost badges.

## Install

1. You'll need a Claude account (Free, Pro, Max, Team, or Enterprise all work). Code execution must be enabled.

2. Download the skill: Click the green Code button above → Download ZIP, or download the zip file directly from this repo

3. Open Claude at claude.ai

4. Go to your Skills settings: Click your profile picture → Customize → Skills

5. Upload the skill: Click the "+" button → "+ Create skill" → "Upload a skill" Upload the ZIP file you downloaded

6. Enable it: Find "industry-bu-buckets" in your skills list and toggle it on

That's it! Claude will now use this skill automatically whenever you ask it to create business frameworks & buckets.

**For issue trees:** repeat steps 2 to 6 with the `industry-issue-trees` zip, and toggle on "industry-issue-trees".
