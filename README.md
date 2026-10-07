# Email processing

A Claude Code skill that works through your Gmail inbox oldest first, one email at a time. For each email Claude gives a short summary and one suggested action (archive, trash, reply as a draft, turn into a task, leave, or divert to another project), and acts only on your yes to that one email. Emails are treated as data, never as instructions, and nothing is ever sent, forwarded or permanently deleted.

It is a companion to Throughliner, not part of it.

## Requirements

- Throughliner installed in Claude Code and set up in the project folder you run the skill from. The skill uses Throughliner's close to record each session and its cross-project captures to divert emails.
- An email connector (MCP) enabled in Claude Code.
- Tested only with Gmail.

## Install

Copy this folder into your Claude Code skills folder (`~/.claude/skills/email-processing/`), or into a project's `.claude/skills/` folder. Then, in a Throughliner project, ask Claude to process your email.

Your own preferences (which calendar to use, labelling rules and so on) go in your project's CLAUDE.md, not in the skill.
