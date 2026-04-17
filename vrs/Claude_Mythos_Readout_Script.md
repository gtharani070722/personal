# Claude Mythos — Read‑Out Speaker Script (with Vocal Cues)

> **How to use:** Read the lines exactly as written. Treat bracketed items like stage directions: **[Pause]**, **[Lower voice]**, **[Point to slide]**, etc.

---

## Slide 1 — Hook: *The Model They Wouldn’t Release*

```text
[Walk to center. Lower voice.]
I’m going to start with a fact that sounds like science fiction. [Pause]
A lab built its best model… and then chose not to release it publicly. [Pause]

Now—hold that thought. Because that one decision is our doorway into today’s theme: “Claude Mythos.”
This is not a generic “what is an LLM” session. [Beat]
This is a story about identity at the frontier edge—how values become part of a model’s character, how capability can jump suddenly, and why governance becomes an engineering problem.

[Point to the Scroll → Leap → Shadow → Gift icons.]
We’ll move through four chapters: the Origin Scroll, the Mythic Leap, the Shadow, and the Gift.

And here’s the promise: by the end, you’ll have two moments where you go, “Wait—AI can do that?” [Pause]
And you’ll also see exactly why governance matters for software teams—not as bureaucracy, but as a safety rail that lets us move faster.

[Look around the room.]
Quick show of hands: would you ship a model if your security team said, “Not safely—yet”? [Pause; invite 2–3 reactions.]
Good. That tension is the heart of the myth.
```

---

## Slide 2 — Define “Claude Mythos” (in 60 seconds)

```text
[Normal voice, confident pace.]
Let’s define “Claude Mythos” in one minute, without a history lesson.

Claude Mythos is a storyline: Scroll… Leap… Shadow… Gift. [Point to each word as you say it.]
The “scroll” is values and constraints—the identity.
The “leap” is when capabilities jump faster than you expect.
The “shadow” is real-world consequences: misuse and new failure modes.
And the “gift” is what software teams gain: speed, clarity, leverage.

Here’s the twist—this is where it stops being “chatbot stuff.” [Pause]
The risk isn’t only wrong answers… it’s wrong actions.
Because modern models are trending toward acting inside workflows—tools, browsers, code review, and agent-like behavior.

[Step closer; slightly lower voice.]
So, quick poll: what scares you more?
A hallucination—an answer that’s wrong…
or an agent taking the wrong action? [Pause; count hands.]

Whatever you chose… you’re right to worry. [Beat]
Because the Mythos isn’t just intelligence—it’s power applied through systems.

Next, we go to the Origin Scroll: Claude’s Constitution.
Because before you trust a powerful assistant, you want to know the values it was trained to follow.
```

---

## Slide 3 — The Origin Scroll: *Claude’s Constitution*

```text
[Slow down. Use a “scroll” gesture with your hands.]
Every myth has an origin scroll. Claude’s is literal: a published “Constitution.”

And here’s what makes it unusual: it’s written as if it’s addressed to Claude—like a character guide. [Pause]
It’s meant to shape behavior, not just describe policy.

Now listen to the hierarchy—this is the punchline. [Beat]
Safety first. Ethics second. Compliance third. Helpfulness fourth. [Pause after each.]

[Look up, let it land.]
That means the model is designed to push back.
It’s not “always obey the user.”
It’s “be helpful, but never at the cost of safety and ethics.”

And here’s the deeper point: at the frontier, we don’t just tell models what to do.
We try to teach them why.
Because if a model is going to face novel situations, rules alone won’t cover everything. [Pause]
It needs principles.

[Ask directly.]
Would you trust an assistant more if it could refuse even its own maker? [Pause; invite a couple reactions.]

Good—because whether we love that idea or not, it shows how identity is built into the product.
And that sets up the next part of the story: the incidents—when principles meet reality.
```

---

## Slide 4 — Incident #1: Controlled Milestones (Safety Levels Before Shipping)

```text
[Brisker pace; anchor to engineering intuition.]
This incident will feel familiar to engineers.

You already do this in software:
dev versus prod,
feature flags,
permissions,
release gates. [Nod.]

In May 2025, Anthropic publicly documented a version of that idea for models—tiered safety levels and release decisions.
The key surprise isn’t the label.
The surprise is that a major lab is openly saying: capability alone isn’t the ship criteria—controls are.

[Point to the ASL ladder and “climb” it with your hand.]
Imagine two models that look 95% similar in output… [Pause]
…but one requires a higher safety standard because the risk profile is different. [Beat]

So what does that imply for us?
It means model selection isn’t just “which is smarter.”
It’s “which is appropriate for this workflow, with these permissions, under this logging.”

In other words: “Which model can we use where?” becomes a governance question.
And now we’re ready for the next incident—where the story leaves the lab and hits the real world.
```

---

## Slide 5 — Incident #2: Real Misuse (Threat Actors Don’t Need Perfect AI)

```text
[Lower voice; serious tone.]
Here’s a myth we need to break:
“If the model refuses harmful prompts, we’re safe.” [Pause]
But attackers don’t need perfect AI.
They need leverage.

Anthropic published case studies describing misuse patterns—things like fraud content, credential-focused abuse patterns, and influence-style automation.

And here’s the surprise: it isn’t only about generating text.
It’s about orchestrating workflows:
deciding when to act,
how to sequence actions,
how to scale. [Pause]

That shifts the unit of risk.
It’s no longer “one bad answer.”
It’s “automation at scale.”

[Point to the funnel visual.]
Tool → scaled workflow → impact.

So what does that mean for software teams?
It means identity controls matter.
Rate limits matter.
Monitoring matters.
Audit trails matter. [Beat]
Not because we’re paranoid—because automation multiplies outcomes.

And this leads directly to the next incident:
when models act inside tools and browsers, the attack surface becomes something you don’t expect.
```

---

## Slide 6 — Incident #3: Agents (Prompt Injection Hijacks the Workflow)

```text
[Shift to “threat modeling” tone. Slightly slower.]
When an assistant becomes an agent, it stops being a conversation…
and becomes a control system.

Agents read untrusted content:
webpages,
documents,
emails,
tool outputs.

Now here’s the unsettling part. [Lower voice]
Prompt injection is hidden instructions embedded inside that content—trying to steer the agent.

And the surprise is simple but huge:
the attack surface becomes… everything the agent can see. [Pause]

That’s why safe prompting alone isn’t enough.
This is architecture:
trust boundaries,
isolation,
least privilege,
and human confirmation for meaningful actions.

[Run the exercise.]
Let’s do a quick “spot the risk” drill.
Workflow: AI reads a ticket… searches docs and the web… proposes a patch… opens a PR… and posts a summary to Slack. [Pause]

Where do we add gates?
What gets logged?
Which steps require human confirmation? [Pause; take 2–3 answers.]

Perfect. You just did agent threat modeling.
Now we’re ready for the mythic leap—when capability rises fast enough that release strategy changes.
```

---

## Slide 7 — Incident #4: Mythic Leap (Mythos Preview)

```text
[Build suspense. Slow down. Let the room lean in.]
Now we reach the mythic leap chapter: Mythos Preview.

A system card described a striking capability jump… and the lab chose not to release it generally. [Pause]
Instead, access was restricted and framed around defensive use.

An external evaluator reported improved performance on controlled cyber evaluations.
And I want to be very clear: we’re not here for offensive details. [Firm tone]
We’re here for the governance signal.

Because when capability crosses a threshold…
deployment strategy changes. [Pause]

Here’s the question that should make every engineer sit up:
What happens when benchmarks stop discriminating frontier models? [Beat]
You can’t “test your way” into safety with yesterday’s yardsticks.

So what do we do as software teams?
We treat frontier capability like privileged infrastructure:
restricted access,
scoped tasks,
audited use,
clear boundaries. [Pause]

And now the uncomfortable question:
If the best model is restricted, what does that imply about “bring your own AI” at work? [Pause]
Exactly. Governance becomes non-negotiable.

Okay—now let’s talk about the gift.
```

---

## Slide 8 — The Gift: Productivity Use Cases (Mythos‑style)

```text
[Energy lift. Smile. Faster pace.]
Alright—enough shadow. Let’s talk about the gift.

Imagine a teammate with infinite patience and perfect memory of the context you provide.
Not a replacement—an accelerator.

PR review: “Here’s what changed, here’s what could break, here are tests to add.”
Refactoring: “Here’s a safe sequence of steps and a migration checklist.”
Design docs: “Here are options, tradeoffs, risks, and open questions.”
Incident retros: “Here’s the timeline; here are ‘5 whys’; here are action items.”
Testing: boundary cases, regression plans, safe fuzz ideas.
Onboarding: a “codebase tour”—with vetted context, not secrets.
Runbooks: turn tribal knowledge into structured, reviewable steps.

[Pause; lower voice.]
But we never give away accountability. [Beat]
AI suggests. Humans decide.

[Think/Pair/Share.]
Take 60 seconds: where would this help our SDLC tomorrow with the lowest risk?
Turn to someone next to you—pick one use case. [Pause; let them talk.]

Great. Now we balance the gift with the shadow: risks and controls—engineer practical.
```

---

## Slide 9 — The Shadow: Risks + Controls (Engineer Checklist)

```text
[Serious tone; crisp.]
Here’s the counterintuitive truth:
the biggest risk isn’t the model being wrong…
it’s the model being trusted. [Pause]

Let’s name the risks plainly:
data leakage,
secret exposure,
hallucinations,
prompt injection,
over-permissioned tools,
and weak logging and audit. [Beat]

And the scariest failures are quiet. [Lower voice]
A tool call you didn’t intend.
A context you didn’t notice.
A “helpful” action that bypassed your expectations.

So we respond like engineers: with controls.

[Checklist cadence—like a runbook.]
Classify data first.
Use approved environments.
Constrain tools—read-only by default.
Assume injection will happen.
Require human review for meaningful actions.
Log prompts, tool calls, approvals, and model versions.
Test workflows like you test software. [Pause]

Quick poll: which risk worries you most?
A data leakage, B prompt injection, C hallucinations, D tool permissions, or E audit gaps? [Pause]

Perfect—because now we can govern based on where our workflow is most sensitive.
Next, we do a neutral comparison: what changes when assistants become agentic.
```

---

## Slide 10 — Neutral Comparison: Mythos‑class vs Typical Assistants

```text
[Neutral tone; no vendor bashing.]
This is not vendor bashing.
It’s a capability class difference.

Typical assistants live mostly in chat: they suggest, summarize, explain.
Mythos-class assistants trend toward deeper tasks and tool use—more persistence, more autonomy.

And that means you need a control plane:
who can use what,
with which permissions,
under what monitoring,
with what approvals and audits. [Beat]

Here’s the litmus test question:
If an AI can open a PR… should it also be able to merge it? [Pause]
Most people say “no.” And that “no” is exactly what least privilege sounds like.

So the lesson is simple:
as assistants become agents, governance starts to look like software access control.

Now let’s close with something you can actually run: Top 5 Do/Don’t and a 30-day plan.
```

---

## Slide 11 — Close: Top 5 Do/Don’t + 30‑Day Adoption Plan

```text
[Confident, practical. Slightly slower for clarity.]
Let’s close the myth in one line:
Claude Mythos is the story of values, leaps, shadows—and how teams adopt safely.

Top 5 DO:
start with low-risk, high-value tasks,
use approved tools and accounts,
apply least privilege,
keep humans accountable,
and log model versions and actions.

Top 5 DON’T:
don’t paste secrets or customer data,
don’t give agents free browsing in sensitive workflows,
don’t ship AI-generated code without review and tests,
don’t assume refusals equal security,
and don’t skip audit trails.

Now the 30-day plan—this should feel doable.

Week 1: choose two use cases, set data rules, define logging.
Week 2: pilot with a small group.
Week 3: integrate into the SDLC with gates—PR review, design docs, retro summaries.
Week 4: measure outcomes and risks, then expand with tiered access.

[Final suspense. Lower voice. Slow.]
And the question I want you to leave with is this: [Pause]
If we can’t explain how an AI action happened… should it be allowed to happen? [Pause 2 seconds]

That’s governance.
And in 2026, governance is engineering.
```
