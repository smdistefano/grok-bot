# grok-bot

Practical notes on running Grok Bot efficiently.

## Token Efficiency Reference

See **[Grok Bot Token Efficiency: Lessons from a 182M Token Day](grok-bot-token-efficiency-one-pager.md)** for a one-pager covering:

- Real usage numbers from October 18, 2026
- How tokens actually get spent (context tax, fan-out, loops, etc.)
- Standing operating rules
- Grok-specific efficiency tips (caching, long-context threshold, reasoning, handovers)

The chart image (`oct-18-token-usage.png`) should be placed in the repo root so the Markdown renders it.
