# kath-a-log

Personal project management for
[Kath Sherratt](https://kathsherratt.github.io/).

A daily source of truth for setting manageable tasks, prioritising,
and evaluating work against larger objectives.
Designed for ADHD: low friction, visible progress, smallest
possible next step.

## How it works

The system uses a gardening metaphor.
Projects are **beds** that move through a lifecycle
(germinating, growing, fruiting, harvest).
Daily work is **tending**.
Objectives are grouped by **season**.

### Daily workflow (~8 minutes)

**Morning:** open `today.md`, review what carried over, set up to
5 tasks with time estimates, pick one Focus item.

**During the day:** check off tasks. Anything that comes up but
isn't for today goes in the Shed.

**End of day:** review what got done, archive `today.md` to
`log/YYYY-MM-DD.md`, reset for tomorrow.

**Weekly:** review beds, update next steps, check progress against
seasonal objectives.

### Key files

| File | What it does |
|------|-------------|
| `today.md` | Today's tasks. The one file that matters. |
| `log/` | Daily archives. The growth log. |
| `beds.md` | Active project index with lifecycles and next steps. |
| `seasons.md` | Seasonal objectives (3-5 per season). |
| `landscaping/dna.md` | Core interests, motivations, values. |
| `landscaping/seed-tray.md` | Project plans germinating before they become beds. |

### Claude integration

The repo includes a `CLAUDE.md` that sets up a gardener voice
for Claude Code sessions.
A portable `/garden` skill is also available for quick check-ins
from any repo.

## Licence

Personal use. Public for transparency.
