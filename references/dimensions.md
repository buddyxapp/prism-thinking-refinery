# Cognitive Dimensions

Definitions, examples, and growth resources for each dimension in the Thinking Radar.

## Built-in Dimensions

### First Principles (first_principles)

**Definition:** Decompose a problem to its fundamental truths, stripping away assumptions and conventions. Rebuild reasoning from the ground up.

**In practice:**
- "What do we actually know vs assume here?"
- "If we started from scratch with no existing solution, what would we build?"
- Elon Musk on battery costs: instead of accepting market price, decompose to raw material costs

**Weak signals (score 1–3):** Accepts conventional wisdom easily, frames problems by analogy to existing solutions rather than root causes.

**Strong signals (score 7+):** Quickly identifies which "facts" are actually assumptions, rebuilds arguments from base truths, comfortable saying "everyone does it this way, but why?"

**Resources:** Aristotle's *Posterior Analytics*, Musk's first-principles interviews, Shane Parrish (Farnam Street) mental models series

---

### Inverse Thinking (inverse_thinking)

**Definition:** Instead of asking "how do I succeed?", ask "how would I guarantee failure?" Invert the problem to reveal hidden risks, blind spots, and overlooked factors.

**In practice:**
- "What would make this project definitely fail?"
- "If I wanted to destroy this company's culture, what would I do?"
- Charlie Munger: "Tell me where I'm going to die, and I'll never go there"

**Weak signals (score 1–3):** Only thinks forward/positively about plans, surprised by failure modes, doesn't naturally stress-test ideas.

**Strong signals (score 7+):** Habitually inverts questions, identifies failure modes before they happen, uses pre-mortem thinking naturally.

**Resources:** Charlie Munger's *Poor Charlie's Almanack*, Gary Klein's pre-mortem technique, Nassim Taleb on via negativa

---

### Stakeholder Lens (stakeholder_lens)

**Definition:** Examine a situation from the perspectives of all affected parties — not just the decision-maker. Each stakeholder has different incentives, constraints, information, and emotional stakes.

**In practice:**
- "How does the customer see this? The employee? The regulator? The competitor?"
- "Whose interests are we accidentally ignoring?"
- Amazon's empty chair representing the customer in every meeting

**Weak signals (score 1–3):** Analyzes from own/single perspective, surprised when others react differently, misreads organizational dynamics.

**Strong signals (score 7+):** Naturally maps stakeholder incentives, predicts reactions accurately, designs for multiple audiences simultaneously.

**Resources:** Roger Fisher's *Getting to Yes*, stakeholder mapping frameworks, Robert Cialdini on influence and perspective

---

### Systems Thinking (systems_thinking)

**Definition:** See the whole system — feedback loops, delays, non-linear effects, emergent behavior. Understand that components interact in ways that individual analysis misses.

**In practice:**
- "What feedback loops exist here?"
- "If we fix this part, what breaks somewhere else?"
- Why adding highway lanes increases traffic (induced demand)

**Weak signals (score 1–3):** Treats problems as isolated, fixes symptoms not causes, surprised by unintended consequences.

**Strong signals (score 7+):** Identifies reinforcing/balancing loops, anticipates emergent effects, thinks in terms of system archetypes (tragedy of the commons, fixes that fail).

**Resources:** Donella Meadows' *Thinking in Systems*, Peter Senge's *The Fifth Discipline*, system dynamics modeling

---

### Game Theory (game_theory)

**Definition:** Analyze strategic interactions where outcomes depend on the choices of multiple agents. Consider incentives, Nash equilibria, prisoner's dilemmas, credible commitments, and signaling.

**In practice:**
- "If I do X, how will they respond, and then what?"
- "Is this a zero-sum or positive-sum situation?"
- Price wars: why competitors sometimes cooperate without communicating

**Weak signals (score 1–3):** Doesn't consider others' strategic responses, treats competitors as static, misses signaling dynamics.

**Strong signals (score 7+):** Maps strategic interactions naturally, identifies equilibria, designs mechanisms that align incentives.

**Resources:** Avinash Dixit's *Thinking Strategically*, Robert Axelrod's *The Evolution of Cooperation*, Ben Thompson (Stratechery) on platform strategy

---

### Historical Analogy (historical_analogy)

**Definition:** Draw parallels between current situations and historical precedents. Use pattern recognition across time to inform judgment — while knowing when analogies break down.

**In practice:**
- "When has something like this happened before, and what happened next?"
- "This feels like the railroad bubble of the 1840s — massive overinvestment in infrastructure that eventually becomes essential"
- Understanding AI hype through the lens of previous technology waves

**Weak signals (score 1–3):** Treats every situation as unprecedented, doesn't draw on historical patterns, falls for "this time is different."

**Strong signals (score 7+):** Rich mental library of historical patterns, knows when analogies apply and when they break, uses history to stress-test predictions.

**Resources:** *Lessons of History* by Will & Ariel Durant, Carlota Perez's *Technological Revolutions and Financial Capital*, Ray Dalio's *Principles for Dealing with the Changing World Order*

---

### Second-Order Effects (second_order_effects)

**Definition:** Think beyond the immediate consequence to what happens next, and then what happens after that. Most people stop at first-order; the best thinkers go 2–3 levels deep.

**In practice:**
- "OK, so that happens. Then what?"
- "What are the consequences of the consequences?"
- Rent control → fewer new apartments → housing shortage worsens → the people it was meant to help are hurt most

**Weak signals (score 1–3):** Stops at first-order effects, surprised by downstream consequences, plans without considering chain reactions.

**Strong signals (score 7+):** Naturally traces causal chains 2–3 steps, identifies where second-order effects reverse first-order intentions, factors this into planning.

**Resources:** Howard Marks' *The Most Important Thing* (Chapter on second-level thinking), Frédéric Bastiat's "That Which Is Seen and That Which Is Not Seen"

---

### Cross-Domain Connection (cross_domain)

**Definition:** Transfer insights, patterns, and mental models from one field to another. Innovation often happens at the intersection of disciplines.

**In practice:**
- "This biological immune system pattern looks exactly like how cybersecurity should work"
- "What can restaurant logistics teach us about cloud computing?"
- Steve Jobs connecting calligraphy to typography in the Mac

**Weak signals (score 1–3):** Stays within domain expertise, doesn't see structural similarities across fields, reads narrowly.

**Strong signals (score 7+):** Reads widely, spots structural isomorphisms, creates novel solutions by importing ideas from distant fields.

**Resources:** David Epstein's *Range*, Frans Johansson's *The Medici Effect*, Steven Johnson's *Where Good Ideas Come From*

---

## Adding Custom Dimensions

Users may add any dimension. To define a new dimension, provide:

1. **Key** (snake_case, e.g. `ethical_reasoning`)
2. **Definition** — what it means
3. **Weak/strong signals** — how to assess it
4. **Resources** — optional, for self-study

Custom dimensions are stored in `profile.json` under `customDimensions` and treated identically
to built-in dimensions in all five modes.
