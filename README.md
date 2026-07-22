# Steward
External Working Memory for Humans
> Steward is a work in progress, and how you begin using Steward is up to you. You don't have to go from zero to 100 on day one. You can adopt a few ideas, make change as you go, and change Steward for your own needs.

You aren't forgetting things, you are losing continuity.

Steward is a neurodiverse-friendly second brain to help with executive function, and is geared towards preserving context, commitments, and continuity across interruptions. It combines a daily note template with AI. (Use the AI of your choice)

It helps answer the question:
1. What am I working on?
2. What did I promise?
3. What interrupted me?
4. What will I forget tomorrow?

Without AI, Steward is simply a better daily note template that helps you recover from interruptions and keep track of what you've promised, what's blocking you, and what currently has your attention.

With AI, it becomes an executive function assistant that reads those notes for you and proactively surfaces forgotten commitments, lost context, recurring themes, and useful reminders through briefings and notifications.

Importantly, it isn't making decisions for you or managing your projects. It's taking care of the things that are expensive from an executive function perspective.

## Getting Started
To get started, use the [daily-note-template.md](https://github.com/acodega/steward/blob/main/daily-note-template.md) in your app of choice. If your app supports Markdown, you can drop the file into your template folder. ([Obsidian.md](https://obsidian.md/) is recommended)

Second, with the AI of your choice, start each day with a daily briefing prompt. It's better if your AI can automatically read your daily notes folder, for example by using Cursor, but for the first week you can simply paste your notes and then the prompt below:

```
You are my executive function assistant.

Review this week's/yesterday's daily note[s] and provide my Morning Briefing:

1. Forgotten commitments.
2. Things I should prioritize today.
3. Information I am likely to have lost context on.
4. Items I am waiting on.
5. Anything that appears repeatedly important.

Keep the response concise.
```
## Using The Daily Note
*Each day:*
Create or open the daily note.
Update Current Context when work changes.
Record commitments when they are made.
Record blockers in Waiting On.
Record context that Future Me is likely to lose.
Use Scratch Pad when information does not fit elsewhere.

*At the end of the day:*
Ensure Commitments is current.
Ensure Waiting On is current.
Add any remaining Future Me notes.

The Morning Briefing is responsible for reviewing the previous day's information. The daily note is responsible for capturing changes in context throughout the day.

## A Sample Daily Note (fictional, of course)
```
2026-07-01-Wednesday

Current Context
- Working on MDM migration.
- Debugging enrollment profile issues.
- Reviewing CIS recommendations.

Commitments
- Review Bob's PR before Friday.
- Complete documentation before Monday.
- Send migration proposal next week.

Waiting On
- Waiting for networking to verify firewall rules.
- Waiting for Steve's feedback on project outline.
- Waiting for change plan approval.

Future Me
- The enrollment issue only occurs after device assignment.
- Check the profile payloads first.
- Conference CFP closes August 5th.

Scratch Pad
- Conference sticker concept.
- Golf thought.
- Potential automation idea.
```

---
## Steward, current features

### v0.1

```text
Steward
├── Daily Notes
└── Morning Briefing
```

## Future plans
### v0.5

```text
Steward
├── Daily Notes
├── Morning Briefing
├── Slack Notifications
├── Context Preservation
└── Waiting On Tracking
```

### v1.0

```text
Steward
├── Daily Notes
├── Morning Briefing
├── Evening Briefing
├── Semantic Recall
├── Cursor Context Injection
├── Slack Integration
├── Jira Awareness
└── Commitment Tracking
```
