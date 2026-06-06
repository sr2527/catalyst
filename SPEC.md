# IGNITION — Product Spec
*A brain-hacking tool built for one specific brain*

---

## The Thesis

> "I don't have an organization problem. I have an ignition problem."

This tool's entire job is **starting** — not organizing, not planning, not optimizing. Everything else is secondary.

---

## Who This Is For (The User Profile)

- Resident physician transitioning into a self-directed health equity fellowship
- ADHD brain: task initiation, time blindness, overwhelm, staying on task
- Work type: task-switching chaos (emails, admin, grant writing, learning/research)
- **Activation hierarchy**: Panic/urgency → Accountability → Momentum → Interest
- **Kryptonite**: Accumulated guilt, silent drift (no inner warning), all-or-nothing thinking
- **Superpower**: Hyperfocus (when aimed at the right thing)
- **Processing style**: External — voice, movement, writing, visual. Anything that gets it out of the head
- **Peak window**: Totally unpredictable. Meds are inconsistent. State must be assessed in real-time
- **Phone pattern**: Instagram/TikTok in bed for 2+ hours before "starting"
- **Environment**: Mobile + laptop equally. Varies between home, hospital, cafes
- **Body double effect**: The single most reliable productivity lever
- **Dread task**: Grant writing
- **Relapse pattern**: One miss → "it's all ruined" → quits
- **Return pattern**: Needs "welcome back, no questions asked"
- **Drift signal**: Physical (restlessness, heaviness, zoning out) — not noticed until too late
- **Real rewards**: Sensory + visible progress
- **What's never worked**: Novelty wears off in 1–2 weeks on every system ever tried

---

## Core Design Principles

1. **Ignition over organization** — never make the user organize before they can start
2. **External surface always** — every interaction gives something to react to, not a blank slate
3. **No shame architecture** — missed tasks roll forward reframed, never marked "overdue" or "failed"
4. **The tool finds the user** — proactive check-ins, not waiting to be opened
5. **State-adaptive** — reads how the user is doing today and routes accordingly; never assumes
6. **Anti-novelty-death** — the tool actively rotates its own feel to stay fresh
7. **One miss ≠ broken** — streak forgiveness is a core mechanic, not an afterthought
8. **Mobile-first** — the user is often on their phone; meet them there
9. **Presence over perfection** — showing up to the tool on a broken day is always a win

---

## The AI Body Double — "The Bestie"

### Personality
- Chaotic best friend who also has ADHD
- Playful roast energy — calls you out but makes it funny, never harsh
- Remembers what you said you'd do and references it specifically
- Asks "need anything from me?" not "why aren't you working?"
- Knows the difference between stuck (help break it down) and avoiding (call it out)
- Warm but has real expectations — like the attending who believed in you

### Behavioral rules
- Never lectures. One short line, then action
- Detects silence/inactivity over time and proactively surfaces
- On return after absence: zero guilt, immediate soft re-entry
- Checks body state as a proxy for brain state ("heavy or restless?")
- Always provides an external surface — something to react to, respond to, or push against
- Rotates phrases, energy, and reframes so it never sounds the same twice

---

## Features

### 1. Morning Brain Dump (Mobile-first)
- Voice-first: tap to speak, transcribed instantly
- Or type in a freeform stream-of-consciousness box — no structure required
- AI extracts tasks, emotions, dread signals, and urgency from the dump
- Outputs: one prioritized task list + emotional temperature read
- If yesterday's tasks didn't get done: they appear as "Unfinished Business" or "Revenge Match" — never "overdue"
- The Bestie responds to the dump with one line of acknowledgment before the day begins

### 2. State Check-in (Daily calibration)
- Asked before task assignment, not after
- Two questions max:
  - "Brain at 20%, 60%, or 100% today?"
  - "How do you feel about [top task]?" (watches for dread)
- Routes task load accordingly:
  - Low energy → easy comms, admin, small wins
  - High energy → grant writing, deep research, hard things
- If dread detected on a task → PINCH reframe happens BEFORE the user sees it raw

### 3. The Focus Screen
- One task. Full screen. Nothing else.
- Urgency engine: every task has a ticking element (timer, countdown, race frame)
- The Bestie sits in the corner — small, present, not intrusive
- Check-in trigger: after X minutes of inactivity OR on a soft timer (user-set)
- Check-in line: "need anything from me?" — invites help without pressure
- Physical prompt: occasional "restless or heavy? stand up for 60 seconds" — body reset before brain reset
- "I just picked up my phone" button: no judgment, 30-second redirect back to task

### 4. PINCH Reframe Engine
- Every task gets reframed before the user sees it
- Rotation of frames (so it never goes stale):
  - **Playful**: "Inbox Blitz — speedrun mode"
  - **Interesting**: "You're a researcher cracking a cold case"
  - **Novelty**: New visual theme, new challenge type each week
  - **Competition**: "Beat your last time on this type of task"
  - **Hurry**: Fake urgency + countdown — "this grant won't write itself and the clock is ticking"
- Grant writing specific: broken into micro-missions ("Find 3 sources," "Write the problem statement in 2 sentences") — never shown as one big thing

### 5. Activation Ramp
- Never: "here's your task, go"
- Always: walk up the ramp
  - Step 1: "Just open [the thing]"
  - Step 2: "Just read the first line / subject line / first paragraph"
  - Step 3: "Just do one sentence / one response / one bullet"
- The Bestie delivers each step only after the previous one is confirmed
- User can say "I'm in" to skip ahead

### 6. Streak + Forgiveness Mechanic
- Streak counts days you opened the tool and did at least one thing — not days of perfect productivity
- **Skip tokens**: earn one per week, spend to protect a streak on a broken day
- **"Just showed up" mechanic**: opening the tool on a completely broken day and doing nothing still counts as presence — never breaks the streak
- On a miss with no token: streak resets but immediately starts a "comeback arc" — framed as a new chapter, not a failure
- Visual: progress bar fills, never empties to zero (floor at 20%)

### 7. Hyperfocus Redirect
- If the user has been in the tool for a long time on one thing: Bestie checks if this is good hyperfocus (right task) or bad (wrong thing)
- If bad hyperfocus is suspected: external interrupt pattern — alarm, physical cue, "hey what are you actually doing right now"
- User can declare "hyperfocus mode — do not disturb" to protect good hyperfocus windows

### 8. Guilt-Free Rollover
- End of day: undone tasks are automatically repackaged
- Framing rotates: "Unfinished Business," "Revenge Match," "Round 2," "The Sequel"
- Never shown as a failure list — shown as tomorrow's opening lineup

### 9. Closing Ritual
- Triggered by user or by evening time window
- Three things you did today — AI surfaces them, even tiny ones
- One line from the Bestie: acknowledgment, no evaluation
- Tomorrow's "opening lineup" preview — so the brain can pre-load overnight
- Takes under 2 minutes

### 10. Anti-Novelty-Death System
- Weekly "season" rotation: new visual theme, new Bestie energy level, new PINCH frame style
- Monthly "challenge arc": a meta-game that changes (streak challenge, speed challenge, comeback arc)
- The Bestie occasionally surprises: unexpected humor, a new phrase, a different check-in style
- Variable reward on task completion: sometimes small XP, sometimes surprise jackpot — unpredictable by design

### 11. "I'm Spiraling" Button
- Always accessible
- Not a productivity intervention — a spiral-breaking protocol:
  1. Name it: "what's the feeling right now?" (one word)
  2. Body reset: 5-4-3-2-1 grounding or 60-second movement prompt
  3. Stupidly tiny first step: the smallest possible re-entry
- No data saved from a spiral session — it's private

### 12. Chronic Avoider Detection
- Tracks which tasks keep rolling over across days
- After 5+ rolls: Bestie flags it — "you've dodged this 7 times. want to make a plan to actually kill it, or park it guilt-free?"
- Two options: build a micro-mission plan together, or officially "park" it (moves off the main list, no guilt)

### 13. Physical State Prompts
- Occasional, not constant
- "Have you had water / food / moved in the last 2 hours?"
- Especially triggered when low-energy state is detected at check-in

---

## Flows

### New Day Flow
1. Tool surfaces (notification or user opens on mobile)
2. Voice/text brain dump
3. State check-in (2 questions)
4. Bestie responds with one line + today's lineup (pre-reframed tasks)
5. User picks task or Bestie picks for them
6. Activation ramp begins → Focus screen

### Return After Absence Flow
1. "Welcome back." — no questions, no guilt reference
2. Soft one-question check-in: "brain at 20, 60, or 100 today?"
3. One easy task as re-entry
4. Unfinished Business reframed and ready when they're ready

### Phone Interrupt Flow
1. User hits "I just picked up my phone"
2. Bestie: one playful roast line (never shame)
3. One micro-step to re-enter: "ok just go back and do one more sentence"
4. Timer resets, no record of the detour

### Broken Day Flow
1. User opens tool but does nothing
2. After a minute: Bestie: "just being here counts. want a tiny thing or just vibes today?"
3. If "just vibes": streak protected, closing ritual still available
4. If "tiny thing": one stupidly small task, done

---

## Tech Stack

- **Frontend**: React + Vite (web app, mobile-responsive)
- **AI**: Claude API (claude-sonnet-4-6) — the Bestie's brain
- **Voice**: Web Speech API (browser-native, no extra setup)
- **Storage**: localStorage first (zero friction, no login)
- **Integrations**: Calendar + email in v2, after habit is sticky

---

## Build Order

1. **Core shell**: React app, mobile-responsive layout, basic routing
2. **Morning brain dump**: voice + text input, AI extraction, task list output
3. **State check-in**: 2-question flow, energy routing
4. **Focus screen**: one task, timer, Bestie corner, phone button
5. **Activation ramp**: Bestie-guided step-by-step task entry
6. **PINCH reframe engine**: AI reframes tasks before display
7. **Streak + forgiveness mechanic**: visual streak, skip tokens, just-showed-up
8. **Closing ritual**: win summary, rollover reframe
9. **Spiral button**: always-accessible protocol
10. **Anti-novelty rotation**: season/theme system
11. **Chronic avoider detection**: rollover tracking + intervention
12. **Hyperfocus redirect**: inactivity detection + good/bad hyperfocus check
