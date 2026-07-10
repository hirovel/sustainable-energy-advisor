# Sustainable Energy Advisor

> Understand your energy pattern, then find one next step worth testing.

[![License: MIT](https://img.shields.io/badge/License-MIT-2f855a.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Standard-Agent%20Skills-2563eb.svg)](https://agentskills.io)
[![Hosts](https://img.shields.io/badge/Claude%20Code%20%7C%20Codex%20%7C%20Copilot-475569.svg)](#quick-start)

[中文](README.md) · [Quick start](#quick-start) · [Example](#example) · [Scope](#scope)

---

Sustainable Energy Advisor is an Agent Skill for everyday work and study. It helps users understand the energy patterns behind fatigue, low focus, AI-tool anxiety, low motivation, and broken routines, then narrows the next step to one experiment that is easy to start and useful to observe.

It does not respond to “I feel tired” with an immediate list of sleep, exercise, diet, and meditation tips. When context is missing, it asks the few questions that would actually change the advice. When enough is known, it explains why the pattern may be happening and chooses one direction worth testing first.

## What it helps with

- **Locate the problem.** Distinguish physical capacity, emotional drain, fragmented attention, and loss of direction instead of reducing everything to discipline.
- **Understand the reason behind the advice.** Explain the mechanism relevant to the user's situation before discussing action.
- **Begin with one small experiment.** Test one clearly scoped direction with observable feedback instead of redesigning an entire life at once.
- **Adapt to feedback.** Reinforce what works; when something fails, review friction and the original hypothesis instead of repeating the same advice.
- **Build a phased plan when needed.** Turn long-term rhythm recovery into a reviewable path rather than a rigid schedule.

## Use it when

- “I have plenty of time but cannot get into study mode.”
- “I rested for two days and still cannot start. I cannot tell whether I am tired or avoiding the task.”
- “I crash in the afternoon but can focus at night.”
- “AI makes me faster, but I keep comparing tools and worrying about falling behind.”
- “I want to rebuild my study and exercise rhythm over a week or a month.”
- “The previous suggestion did not work. I want to understand what got in the way.”

Describe the situation naturally. You do not need to understand an energy model or complete an intake form first.

## Quick start

Install the complete repository directory so the references used by `SKILL.md` remain available.

### Claude Code

```bash
git clone https://github.com/hirovel/sustainable-energy-advisor.git \
  ~/.claude/skills/sustainable-energy-advisor
```

### Codex / GitHub Copilot CLI

```bash
mkdir -p ~/.agents/skills
git clone https://github.com/hirovel/sustainable-energy-advisor.git \
  ~/.agents/skills/sustainable-energy-advisor
```

Restart the session if the host does not discover the skill immediately. Host locations and invocation behavior may change; refer to the official documentation: [Claude Code](https://docs.anthropic.com/en/docs/claude-code/skills) · [Codex](https://developers.openai.com/codex/skills) · [GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-skills)

## Example

### User

> AI makes me faster at coding, but I feel more anxious every day. I keep refreshing models and tools because I am afraid of falling behind. I still have four hours of work today, but my mind is scattered.

### Assistant (excerpt)

> You have noticed a specific tension: AI has made coding faster, while “is there a better model or tool?” has become an always-open doorway that keeps pulling attention away from the current task. Across the four energy dimensions, the clearest signals are emotional and cognitive; there is not enough physical information to make a claim about sleep or baseline capacity.
>
> *The more tools you have, the more attention needs a boundary. The value of staying current ultimately has to return to the work in front of you.*
>
> For the next hour, write one clear delivery outcome and continue with the model and tools already open. When the urge to refresh or compare appears, add it to a “check later” list and return to the code. At the end, notice how far the outcome moved and whether your mind can return to the same problem more easily than before.

The example demonstrates reasoning order and response depth, not wording that the skill reuses as a template.

## What makes the method different

### Conversation before framework

The skill considers physical, emotional, cognitive, and purpose energy internally, but it does not turn every response into a four-part report. It surfaces only what helps the user now.

### Recovery is not the only answer

Continuous demand without recovery can deplete capacity, while prolonged underuse without appropriate challenge can make starting harder. The skill tries to distinguish recovery, re-engagement, and loss of direction.

### Test one primary direction at a time

An experiment may last 24–48 hours, three days, or seven days. Duration follows the available evidence and expected friction rather than a universal seven-day template.

### Feedback matters more than obeying a plan

An action is useful not only when it becomes a habit, but also when it produces information. The next step changes in response to the friction the user actually encounters.

## Scope

Designed for non-clinical work and study fatigue, low focus, AI-tool anxiety, recovery gaps, motivation, and everyday rhythm problems.

It is not for medical diagnosis, therapy, crisis support, severe or persistent sleep and mental-health symptoms, or generic calendar and task management. When signals fall outside its scope, it stops energy guidance and directs the user toward appropriate support.

To review the skill's implementation, see [`SKILL.md`](SKILL.md), the [methodology contract](references/methodology-contract.md), and [safety boundaries](references/safety-boundaries.md).

## Sources and originality

The project is informed by general ideas from energy management, performance psychology, behavior design, recovery-aware work, and sustainable knowledge work. All workflows, templates, and examples are original expressions; they do not reproduce or replace source materials.

See [`NOTICE.md`](NOTICE.md) and [further reading](references/further-reading.md).

## License

[MIT](LICENSE) © [hirovel](https://github.com/hirovel)
