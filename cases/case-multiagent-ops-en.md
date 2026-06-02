# Case: Building a Multi-Agent Operations Team

> Automating the operations of an online business as a "team" of six role-specialized AI agents.

## The challenge

In small or solo-run businesses, work like strategy, content planning, audience growth,
and product design all pile onto one person, and day-to-day operations fall behind.
The business isn't big enough to justify hiring — but left unattended, it stalls.
The goal was to fill exactly that gap.

## What I built

I split the work into six roles, each defined as a specialized AI agent (a virtual team member).

| Role | Area of responsibility |
|------|------------------------|
| Manager | Overall coordination, progress checks, the owner's point of contact |
| SEO lead | Title and search-traffic optimization |
| Content planner | Planning and scriptwriting |
| Community lead | Empathetic copy and communication design |
| Product designer | Product and funnel (customer journey) design |
| Marketing strategist | Strategy across acquisition channels |

Each agent has its own **persona definition file** — tone, decision criteria, and priorities are
all characterized. The owner simply talks to the "Manager," and the relevant specialists' expertise
is drawn in as needed.

## Key design points

- **Unattended morning runs**: scheduled execution starts the whole team at a fixed time each morning, generating that day's report.
- **Evidence-based completion**: a task isn't "done" just because instructions were written. Completion requires *visible evidence the owner can see* — a report produced, records updated, and so on. This prevents automation from silently stalling while appearing to have run.
- **Direct via conversation**: just message the Manager, and the loop of status check → report → next instructions keeps turning.

## Results

- A system where operational proposals come in daily without the owner lifting a finger.
- Because output is split by specialist role, "what to do next" is clear every morning.
- Reproduces the feeling of "running with a team" — without hiring anyone.

## Tech used

Claude Code / multi-agent collaboration / role-based persona definitions / scheduled execution / Markdown-based instructions and evidence tracking
