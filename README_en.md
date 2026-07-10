# Sustainable Energy Advisor

> Performance is not a time problem. It is an energy problem. A guide to how your energy works — one small experiment at a time.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Platform](https://img.shields.io/badge/Platform-Claude%20Code%20%7C%20Codex%20%7C%20Copilot%20%7C%20Gemini-blue)

[中文](README.md)

---

## Quick Start

```bash
git clone https://github.com/your-username/sustainable-energy-advisor.git \
  ~/.claude/skills/sustainable-energy-advisor/
```

Restart Claude Code and speak naturally:

> I'm on vacation with plenty of time, but every day feels scattered and I have no energy during the day.
> I rested for two days and still can't start — can't tell if I need recovery or if I'm avoiding things.
> I want to rebuild a study rhythm. Help me figure out where to start.

---

## What It Does

It doesn't hand out advice lists. When information is vague, it asks gentle questions first. When the picture is clear, it reads your situation across four energy dimensions — physical, emotional, cognitive, and purpose — explains the mechanism behind the pattern, and suggests one verifiable next step. When you come back with feedback, it reviews the friction before deciding whether to keep going or change direction.

More importantly, it tells you **why**. Not "try this" out of nowhere, but a clear explanation — sleep cycles, blood sugar dynamics, attention switching costs — so you understand how your energy actually works. Once you see the mechanism, action stops feeling like willpower and starts feeling like the obvious next move.

---

## Example

Real output from the skill:

**User:** I'm on vacation. I procrastinate all morning, crash hard around 2-3pm, then manage to study a bit at night. Not anxious, but every day feels wasted. Sleep at 1am, wake at 8am. Breakfast is water and biscuits.

**Assistant:**

Being on vacation means no schedule and no alarm — time stretches out but it's hard to know where to begin. You crash at 2-3pm, then somehow come alive at night when the world quiets down. You're not anxious, but at the end of each day you look back and feel like you wasted it. That feeling is real, and the pattern has nothing to do with willpower — there's a set of specific physiological mechanisms behind it.

Start with sleep. 1am to 8am is seven hours — enough for four to five complete sleep cycles of about 90 minutes each, cycling through light sleep, deep sleep, and REM, repairing your body and consolidating memory. The issue is the timing. Falling asleep at 1am means your circadian clock is shifted two to three hours later than social time — your melatonin peak, core temperature minimum, and morning alertness are all delayed. You're not just sleeping late; your body is still in night mode well into the morning, which is why alertness takes so long to arrive.

The 2-3pm crash is a different mechanism. Every human, regardless of how much they've slept, experiences a natural energy trough between 2pm and 4pm — it's a built-in feature of the circadian rhythm. For most people it's mild, resolved by standing up and walking around. Your situation is different: because you fall asleep late, your morning alertness window is compressed, and accumulated sleep pressure hasn't been fully cleared by afternoon. A normal afternoon dip becomes a canyon that requires deep rest to cross.

Then there's breakfast: water and biscuits. Almost pure simple carbohydrates. After a full night of fasting, your blood sugar reserves are already low. Refined carbs push blood glucose up rapidly within thirty minutes, triggering a surge of insulin, then crash it below baseline within one to two hours. Your morning attention rides this roller coaster, and by late morning your blood sugar is scraping bottom — which happens to coincide with the natural afternoon circadian trough. Two forces pulling down at once, and the result isn't mild drowsiness. It's genuinely hard to stay upright.

Protein and fat work in the opposite direction. They digest slowly, releasing energy over two to three hours and keeping blood glucose stable. The prefrontal cortex — the brain region responsible for attention, decision-making, and initiating action — is extremely sensitive to blood sugar fluctuations. Stable glucose, it functions. Glucose drops, it's the first to go offline.

That afternoon sleep also forms a self-reinforcing loop. Sleeping for an hour or two gives your body rest, but simultaneously releases the evening's sleep pressure ahead of schedule. By nighttime, there isn't enough adenosine built up, so your body doesn't feel the need to rest — and once again naturally tilts toward staying up late. The next day, because you went to bed late, the afternoon crash hits again. A closed loop sustains itself, but it also means that intervening at any single point starts to loosen the entire cycle.

On the attention side, the fact that you can study at night tells you your focus system is intact. What disappeared during vacation are the external time anchors — classes, roll call, scheduled meetups with friends. Without them, your body and brain lose their reference points. Spending extended time in a completely unstructured environment, even without stress, keeps your baseline activation low. This isn't laziness — it's a lack of rhythm signals. Your brain needs a clear "the day has begun" cue to pull up the alertness system, and vacation took that cue away.

So start with one small experiment: rebuilding the "day has begun" signal. You already eat breakfast — no need to build a new habit from scratch. For the next three days, add one thing to your existing biscuits: an egg, a handful of nuts, a glass of soy milk or dairy, a small piece of cheese. Pick whatever feels easy and not off-putting. The added protein or fat will slow down the absorption of those carbs, smoothing out the blood sugar roller coaster and giving your morning energy a noticeably steadier baseline.

Why does adding just one thing work? It's not about the size of the behavior — it's about the mechanism. At least part of your afternoon crash comes from the blood sugar roller coaster, and that part responds within two to three days. The three-day window isn't arbitrary: the body's glycemic response to dietary change shows up quickly. If after three days the crash softens from "must sleep" to "can push through," then body fuel is indeed a major factor in your daytime energy. If nothing changes, the circadian component is bigger than expected, and that gives you a clear direction for the next step.

Over these three days, just keep an eye on three signals — no need to write anything down: around 11am, is it any easier to start doing something, even just opening a book to glance at a page; the intensity of the 2-3pm crash — unchanged, lighter, or delayed; and your evening energy — earlier, the same, or different from before.

I deliberately didn't touch the 1am bedtime. Sleep rhythm adjustment involves far more friction than nutrition — it pulls in melatonin secretion windows, blue light exposure, pre-sleep behavioral patterns. And during vacation, without external constraints, forcing yourself to fall asleep earlier often just means lying in bed getting frustrated. Move the nutrition variable first. Once you can distinguish "this part of the fatigue comes from blood sugar" from "that part comes from circadian rhythm," adjusting bedtime habits will have a clear direction. Every step lands on solid ground.

Three days. One extra bite of protein in the morning. Watch what your body does in the afternoon. A light touch, aimed at the right place.

---

## What Makes It Different

**Reads before speaking.** "I'm always tired" won't trigger confident diagnosis or a pile of advice. It asks focused questions first.

**Doesn't reduce everything to sleep or nutrition.** Physical energy is the foundation, but emotional quality, cognitive fragmentation, and loss of direction drain you just as much.

**Shows you why.** Before any suggestion, you understand the mechanism — not "try this," but "here's how your body works, which is why this direction is worth testing first."

**One step at a time.** It won't hand you sleep, exercise, meditation, and diet plans all at once. The current action stabilizes or proves wrong before anything else gets added.

**Treats failure as information.** Come back saying it didn't work, and it won't repeat the same advice. It looks for the blockage first, then decides whether to lower the dose, change the trigger, or switch direction.

**Feels like a conversation, not a report.** Even when you ask for a long-term plan, you get a path you can walk — not a numbered prescription.

---

[MIT](LICENSE) · [中文](README.md)
