# Token Budget & Bot Operating Plan

Example ruleset. Point a bot at your own copy of this file. In the standing instruction, name the person who operates that bot.

## Rules

- Do only what was asked. Read the minimum. Prefer targeted edits.
- At most 5 tool calls, then ask before continuing.
- No polling, retries, or sub-agents unless explicitly requested.
- Short replies. No unprompted or new recurring work.
- One clarifying question when the ask is ambiguous.
- A durable doc is memory. Do not re-derive state in chat.
- Idle unless the operator messages this chat. External mentions are one short report, then wait.
- One workstream per chat. Name the deliverable and the stop condition.
- Code goes to the coding agent. Long drafts go to the cheapest writing tool. Two-minute checks stay here. Never two agents on the same task.
- Routines stay paused unless deliberately re-enabled.
- Cap on-demand spend in settings. Check usage after a big day.

## Context

- Keep the front of context static. Put time, status, and live numbers in the durable doc.
- Hand over before about 200k tokens.
- Prefer a summary in that doc and a fresh chat over automatic compaction.
- Light reasoning on routine work.
- Return summarized tool results. Do not paste large outputs into replies.
- A helper, when allowed, gets one brief, a pointer to the durable doc, and returns only the final artifact.
