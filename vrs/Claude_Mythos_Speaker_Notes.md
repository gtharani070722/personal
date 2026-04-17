# Claude Mythos — Speaker Notes (Storytelling + Suspense)

_Extracted from the deck: Claude_Mythos_20min_Session_StoryNotes.pptx_

## Slide 1: Hook: The Model They Wouldn’t Release

```text
STORYTELLING MODE (≈90s)

OPEN (0–10s) — Whisper the premise
- [Lower voice] “I’m going to start with a fact that sounds like science fiction.”
- [Pause] “A lab built its best model… and didn’t release it.”

SETUP (10–35s) — Name the myth
- “That decision is our doorway into *Claude Mythos*: the identity story of Claude at the frontier edge.”
- “Today isn’t ‘what is an LLM’. It’s: how values become a product, how a capability jump happens, and why governance becomes engineering.”

SUSPENSE BEAT (35–55s) — Hold the reveal
- “Before we talk about what the model can do… we’ll read its ‘origin scroll’—the Constitution.”
- [Pause] “Because the *rules of the character* tell you what happens when it gets powerful.”

PAYOFF (55–85s) — Make it personal
- “If you build software, this is about your PRs, incidents, and release pipelines—*and* the new failure modes.”

AUDIENCE HOOK (85–95s)
- Ask: “Would you ship a model if your security team said: ‘Not safely—yet’?”
- [Hands up] quick show-of-hands.

DELIVERY TIPS
- Use 2 pauses: after “didn’t release it” and after “before we talk about what it can do…”.
- Keep it grounded: no sensational claims, focus on governance implications.
```

## Slide 2: Define ‘Claude Mythos’ (in 60 seconds)

```text
STORYTELLING MODE (≈75–90s)

FRAME (0–15s) — Define without history lesson
- “Claude Mythos is a *storyline*: Scroll → Leap → Shadow → Gift.”
- “A system card is like a character biography: what it can do, what it failed at, and how it’s deployed.”

SUSPENSE BEAT (15–35s) — Turn from chat to agency
- “Here’s the twist: the risk isn’t only wrong answers… it’s wrong actions.”
- “When models become *agents*, they interact with tools, browsers, and workflows.”

MICRO-POLL (35–55s)
- “Quick poll: which worries you more—hallucinations or an agent taking the wrong action?”
- [Pause] “Whatever you pick… you’re right to worry.”

BRIDGE (55–85s)
- “Next: the Origin Scroll—Claude’s Constitution—because values and constraints aren’t add-ons; they’re identity.”

DELIVERY TIPS
- Point to the 4-block visual as you say each word: Scroll, Leap, Shadow, Gift.
- Keep a steady pace; let the poll create engagement.
```

## Slide 3: The Origin Scroll: Claude’s Constitution

```text
STORYTELLING MODE (≈90s)

SETUP (0–20s) — Introduce the ‘scroll’ metaphor
- “Every myth has an origin scroll—Claude’s is literal: a published Constitution.”
- “It’s written *to Claude*, and it’s used to shape behavior during training.”

REVEAL (20–50s) — The hierarchy is the punchline
- [Slow down] “Safety first. Ethics second. Compliance third. Helpfulness fourth.”
- “That means the model is designed to push back when necessary.”

SUSPENSE BEAT (50–70s) — Character > commands
- “Here’s the surprising part: at the frontier, we don’t just tell models *what* to do; we try to teach them *why*.”

AUDIENCE QUESTION (70–90s)
- Ask: “Would you trust an assistant more if it could refuse even its own maker?”
- [Pause] Let reactions land.

DELIVERY TIPS
- Use a ‘scroll’ gesture when saying ‘Constitution’.
- Emphasize the ordering; it’s the memorable hook.
```

## Slide 4: Incident #1: Controlled Milestones (Safety Levels Before Shipping)

```text
STORYTELLING MODE (≈90s)

SETUP (0–20s) — Familiar analogy
- “You already do this in software: dev vs prod, permissions, release gates.”

INCIDENT ARC (20–55s) — ‘Safety levels’ as a milestone
- “In May 2025, Anthropic publicly documented tiered safety levels and release decisions in a system card.”
- “That’s the controlled milestone: capability isn’t the only ship criteria—controls are.”

SUSPENSE BEAT (55–70s)
- [Pause] “Imagine two models that look 95% similar… but one requires a higher safety standard.”

SO WHAT (70–90s)
- “For teams: model choice becomes governance—*which model can we use where*, with what permissions and logging?”

DELIVERY TIPS
- Point at the ASL ladder; climb it with your hand.
- Keep it non-technical for beginners: ‘tiers’ and ‘gates’.
```

## Slide 5: Incident #2: Real Misuse (Threat Actors Don’t Need Perfect AI)

```text
STORYTELLING MODE (≈90s)

SETUP (0–20s) — Break the ‘refusal = safety’ myth
- “A common assumption: ‘If the model refuses harmful prompts, we’re safe.’”
- [Pause] “But attackers don’t need perfect AI. They need leverage.”

INCIDENT ARC (20–60s) — Misuse as orchestration
- “Anthropic published case studies on misuse patterns—where models helped scale influence-style workflows and fraud content.”
- “The surprise: not just writing text… but helping decide *when* and *how* to act in a workflow.”

SUSPENSE BEAT (60–75s)
- “So the unit of risk shifts from ‘a bad answer’ to ‘automation at scale’.”

SO WHAT (75–95s)
- “For us: identity, rate limits, monitoring, and audits become part of AI adoption—not optional extras.”

DELIVERY TIPS
- Keep examples high-level and defensive; avoid operational details.
- Use the funnel visual: tool → scaled workflow → impact.
```

## Slide 6: Incident #3: Agents (Prompt Injection Hijacks the Workflow)

```text
STORYTELLING MODE (≈100s)

SETUP (0–20s) — The ‘agent’ turn
- “When an assistant becomes an agent, it stops being a conversation and becomes a control system.”

UNEXPECTED FEAT (20–45s) — The new attack surface
- “Agents read untrusted content: webpages, documents, emails.”
- “Prompt injection is hidden instructions trying to steer the agent.”

SUSPENSE BEAT (45–70s) — ‘Everything it can see’
- [Lower voice] “The attack surface becomes… everything the agent can see.”
- “That’s why safe prompting alone isn’t enough.”

INTERACTION (70–100s) — Spot the risk (defensive)
- Show workflow: “AI reads ticket → searches docs/web → proposes patch → opens PR → posts summary to Slack.”
- Ask: “Where do we add gates? What gets logged? Which steps need human confirmation?”

DELIVERY TIPS
- Treat this like threat modeling: trust boundaries + least privilege.
- Keep it safe: identify risks and controls, not exploitation steps.
```

## Slide 7: Incident #4: Mythic Leap (Mythos Preview)

```text
STORYTELLING MODE (≈100s)

SETUP (0–25s) — The mythic leap
- “Now we reach the ‘mythic leap’ chapter: Mythos Preview.”
- “A system card described a capability jump—and the lab chose not to release it generally.”

REVEAL (25–55s) — External evaluation signal
- “An external evaluator reported improved performance on controlled cyber evaluations.”
- “The key is not the offensive detail; it’s the governance decision: capability crossed a threshold.”

SUSPENSE BEAT (55–75s)
- [Pause] “What happens when benchmarks no longer discriminate frontier models?”
- “Deployment strategy changes.”

SO WHAT (75–105s)
- “For software teams: treat frontier capability like privileged infrastructure—restricted access, scoped tasks, and audit trails.”
- Ask: “If the best model is restricted, what does that imply about ‘bring your own AI’ at work?”

DELIVERY TIPS
- Use the curve visual: capability rises, controls must rise faster.
- Keep the tone sober and practical.
```

## Slide 8: The Gift: Productivity Use Cases (Mythos-style)

```text
STORYTELLING MODE (≈90s)

RELIEF (0–10s) — Move from shadow to gift
- “Okay—enough shadow. Let’s talk about the gift.”

USE-CASE MONTAGE (10–55s) — Rapid, vivid examples
- “PR review: ‘here’s what changed, here’s what could break, here are tests to add.’”
- “Design doc: alternatives + tradeoffs + risks.”
- “Retro: timeline + ‘5 whys’ prompts.”
- “Onboarding: codebase tour—*with vetted context*.”

SUSPENSE BEAT (55–70s) — The boundary line
- [Pause] “But we never give away accountability.”

INTERACTION (70–90s)
- Think/Pair/Share: “Where would this help our SDLC tomorrow with the lowest risk?”

DELIVERY TIPS
- Keep this energetic; it’s the ‘hope’ chapter.
- Tie each use case back to guardrails: review, tests, and boundaries.
```

## Slide 9: The Shadow: Risks + Controls (Engineer Checklist)

```text
STORYTELLING MODE (≈110s)

SETUP (0–20s) — The counterintuitive truth
- “The biggest risk isn’t the model being wrong—it’s the model being trusted.”

RISK TOUR (20–55s) — Name risks plainly
- “Data leakage, secrets, hallucinations, prompt injection, over-permissioned tools, missing logs.”

SUSPENSE BEAT (55–75s) — The ‘silent failure’
- [Lower voice] “The scariest failures are quiet: a tool call you didn’t intend… a context you didn’t see.”

CHECKLIST (75–110s) — Defensive, practical controls
- “Classify data. Use approved environments. Constrain tools. Assume injection. Human review. Log/audit. Test workflows.”

POLL (optional 15s)
- “Which risk worries you most?” (A–E)

DELIVERY TIPS
- Treat checklist like ‘seatbelts’: not slowing you down—keeping you alive.
- Encourage: ‘start small, instrument early.’
```

## Slide 10: Neutral Comparison: Mythos-class vs Typical Assistants

```text
STORYTELLING MODE (≈80–95s)

NEUTRAL FRAME (0–15s)
- “This is not vendor bashing. It’s a capability class difference.”

CONTRAST (15–45s)
- “Typical assistants: chat support.”
- “Mythos-class trend: deeper tasks + tool use + longer autonomy.”
- “That requires a control plane: access tiers, approvals, audits.”

SUSPENSE BEAT (45–65s)
- Ask: “If an AI can open a PR, should it also be able to merge it?”
- [Pause] Let them say ‘no’—then nod.

BRIDGE (65–90s)
- “Next: we close with a ‘Top 5 Do/Don’t’ and a 30-day plan you can actually run.”

DELIVERY TIPS
- Use the two-column table as your script.
- Keep it crisp; this is a setup slide for the close.
```

## Slide 11: Close: Top 5 Do/Don’t + 30-Day Adoption Plan

```text
STORYTELLING MODE (≈100s)

CLOSING ARC (0–20s) — Re-state the myth in one line
- “Claude Mythos is the story of values, leaps, shadows—and how teams adopt safely.”

TOP 5 DO/DON’T (20–60s)
- “Do: low-risk first, approved tools, least privilege, human accountability, log model versions.”
- “Don’t: paste secrets, give agents free browsing in sensitive flows, ship code without review, assume refusals = security, skip audits.”

30-DAY PLAN (60–95s) — Make it feel doable
- Week 1: choose 2 use cases + data rules + logging baseline.
- Week 2: small pilot.
- Week 3: integrate with gates.
- Week 4: measure + expand tiered access.

FINAL SUSPENSE QUESTION (95–105s)
- [Quiet] “If we can’t explain how an AI action happened… should it be allowed to happen?”

DELIVERY TIPS
- End with a pause. Let the question hang for 2 seconds.
- Then: “That’s governance. That’s engineering.”
```
