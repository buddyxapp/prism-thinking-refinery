# Framework Library

Detailed thinking frameworks tagged by the cognitive dimension they primarily exercise.
Frameworks may exercise multiple dimensions; the primary tag indicates the strongest connection.

## Table of Contents

1. [First Principles Thinking](#first-principles-thinking)
2. [Inversion / Pre-Mortem](#inversion--pre-mortem)
3. [Stakeholder Mapping](#stakeholder-mapping)
4. [Causal Loop Diagrams](#causal-loop-diagrams)
5. [Game Trees & Payoff Matrices](#game-trees--payoff-matrices)
6. [Historical Pattern Matching](#historical-pattern-matching)
7. [Second-Order Consequence Chains](#second-order-consequence-chains)
8. [Cross-Domain Transfer](#cross-domain-transfer)
9. [OODA Loop](#ooda-loop)
10. [Cynefin Framework](#cynefin-framework)
11. [Wardley Mapping](#wardley-mapping)
12. [Red Team / Blue Team](#red-team--blue-team)
13. [Opportunity Cost Analysis](#opportunity-cost-analysis)
14. [Regret Minimization](#regret-minimization)

---

## First Principles Thinking
**Primary dimension:** first_principles
**Also exercises:** systems_thinking

Break any problem down to its irreducible components:

1. **Identify assumptions** — List everything you "know" about the problem
2. **Challenge each** — Is this a fact or a convention? Can it be different?
3. **Reconstruct** — From the remaining truths, build up a new solution

**Example application:**
> "Cloud computing is expensive." → What are the actual costs? Compute, storage, network, people.
> Which of these can be reduced by 10x? Where is the real cost driver vs perceived cost?

**When to use:** When stuck in "that's how it's always done" thinking, or when optimizing an existing approach yields diminishing returns.

---

## Inversion / Pre-Mortem
**Primary dimension:** inverse_thinking
**Also exercises:** stakeholder_lens

Instead of planning for success, plan for failure:

1. **Assume failure** — "It's one year from now and this project has failed spectacularly"
2. **Write the post-mortem** — What went wrong? List every cause
3. **Work backwards** — Which of these causes can you prevent right now?

**Example application:**
> Launching a new product → Pre-mortem: "Users didn't understand the value prop, onboarding was too complex, we ran out of budget in month 4, key engineer quit."
> Now: address each risk before launch.

**When to use:** Before major decisions, project kickoffs, or whenever optimism is running high and nobody is asking "what could go wrong?"

---

## Stakeholder Mapping
**Primary dimension:** stakeholder_lens
**Also exercises:** game_theory

Map all affected parties and their positions:

1. **List stakeholders** — Anyone affected by or who can influence the outcome
2. **For each:** What do they want? What do they fear? What power do they have?
3. **Map relationships** — Who influences whom? Where are alliances and conflicts?
4. **Identify the overlooked** — Who isn't at the table but should be?

**When to use:** Any decision affecting multiple parties, organizational changes, negotiations, product launches.

---

## Causal Loop Diagrams
**Primary dimension:** systems_thinking
**Also exercises:** second_order_effects

Visualize how variables in a system influence each other:

1. **Identify key variables** in the system
2. **Draw arrows** showing influence (A → B means A affects B)
3. **Label polarity** — same direction (+) or opposite direction (−)
4. **Find loops** — Reinforcing (R) loops amplify; Balancing (B) loops stabilize
5. **Find delays** — Where do effects take time to materialize?

**Example:** Employee burnout → Lower quality → More rework → More hours → More burnout (R loop)

**When to use:** Complex organizational or market dynamics, policy analysis, anywhere "it's complicated."

---

## Game Trees & Payoff Matrices
**Primary dimension:** game_theory
**Also exercises:** inverse_thinking, stakeholder_lens

Map strategic interactions formally:

1. **Identify players** and their available moves
2. **Trace sequences** — If I do X, they do Y, then I do Z
3. **Estimate payoffs** for each outcome
4. **Find equilibria** — Where does rational behavior converge?
5. **Look for dominant strategies, credible threats, commitment devices**

**When to use:** Competitive strategy, negotiations, any multi-party decision where outcomes depend on others' choices.

---

## Historical Pattern Matching
**Primary dimension:** historical_analogy
**Also exercises:** second_order_effects

Find precedents and extract lessons:

1. **Identify the structural pattern** — Not surface similarity, but structural
2. **Find 2–3 historical parallels**
3. **Compare trajectories** — What happened then? What was similar/different?
4. **Stress-test the analogy** — Where does it break down?
5. **Extract actionable insight** — What does history suggest about timing, risks, opportunities?

**Caution:** History rhymes but doesn't repeat. Always identify where the analogy fails.

**When to use:** Market shifts, technology transitions, organizational transformations, geopolitical analysis.

---

## Second-Order Consequence Chains
**Primary dimension:** second_order_effects
**Also exercises:** systems_thinking

Trace the ripple effects of any action:

1. **First order** — What is the immediate, obvious consequence?
2. **Second order** — What does that consequence cause?
3. **Third order** — And then?
4. **Who is affected at each level?** (overlay with stakeholder_lens)
5. **Where do effects reverse?** (often second-order effects oppose first-order intentions)

**Template:**
```
Action → [1st order] → [2nd order] → [3rd order]
         Who gains?    Who loses?     What breaks?
```

**When to use:** Policy decisions, incentive design, any action where "sounds good in theory" might not survive reality.

---

## Cross-Domain Transfer
**Primary dimension:** cross_domain
**Also exercises:** first_principles

Import solutions from unrelated fields:

1. **Abstract the problem** — Strip away domain-specific details to reveal the structural challenge
2. **Search for structural analogues** — What other field solves a similar structural problem?
3. **Import and adapt** — Translate the solution back into your domain
4. **Test the fit** — Where does the borrowed solution work? Where does it need modification?

**Example:** Netflix's recommendation engine → Apply collaborative filtering to match sales reps with leads (similar behavioral patterns predict fit).

**When to use:** When domain-native solutions feel exhausted, or when you want to innovate rather than optimize.

---

## OODA Loop
**Primary dimensions:** systems_thinking, inverse_thinking

John Boyd's decision cycle for dynamic environments:

1. **Observe** — Gather raw information from the environment
2. **Orient** — Analyze and synthesize (this is where mental models, cultural heritage, and previous experience apply)
3. **Decide** — Select a course of action
4. **Act** — Execute, then loop back to Observe

**Key insight:** Speed through the loop matters. Whoever cycles faster gains initiative. But Orient is the critical phase — a faster loop with bad orientation just makes you wrong faster.

**When to use:** Fast-changing competitive situations, crisis response, iterative strategy.

---

## Cynefin Framework
**Primary dimensions:** systems_thinking, first_principles

Dave Snowden's sense-making framework for categorizing problems:

| Domain | Characteristic | Approach |
|--------|---------------|----------|
| **Clear** | Cause-effect obvious | Sense → Categorize → Respond (best practice) |
| **Complicated** | Cause-effect discoverable | Sense → Analyze → Respond (good practice, experts) |
| **Complex** | Cause-effect only in retrospect | Probe → Sense → Respond (emergent practice) |
| **Chaotic** | No cause-effect | Act → Sense → Respond (novel practice) |

**Key insight:** The biggest mistake is treating complex problems as complicated (hiring consultants to "solve" culture) or complicated problems as complex (experimenting when an expert could just tell you).

**When to use:** Before choosing an approach — first determine what kind of problem you're facing.

---

## Wardley Mapping
**Primary dimensions:** systems_thinking, game_theory

Simon Wardley's technique for strategic positioning:

1. **Map the value chain** — From user need to components
2. **Position by evolution** — Genesis → Custom → Product → Commodity (x-axis)
3. **Identify movement** — Everything evolves left to right over time
4. **Find strategic plays** — Where to invest, outsource, or disrupt

**When to use:** Technology strategy, build-vs-buy decisions, competitive positioning, understanding market evolution.

---

## Red Team / Blue Team
**Primary dimensions:** inverse_thinking, game_theory

Structured adversarial thinking:

1. **Blue Team** presents the plan/strategy
2. **Red Team** actively tries to defeat it — find vulnerabilities, exploit weaknesses
3. **Debrief** — What did Red Team find? How does Blue Team adapt?

**Key insight:** The red team must genuinely try to win, not just play devil's advocate politely. The value comes from real adversarial pressure.

**When to use:** Security reviews, strategy validation, before major launches or announcements.

---

## Opportunity Cost Analysis
**Primary dimensions:** first_principles, second_order_effects

Every choice has a cost — what you give up:

1. **Identify the choice and its alternatives**
2. **For each alternative:** What value would it create?
3. **The opportunity cost = the value of the best forgone alternative**
4. **Include non-obvious costs:** time, attention, optionality, relationships

**Key insight:** Busy people under-count the cost of their time and attention. "I'll just do both" is often a lie.

**When to use:** Resource allocation, prioritization, any "should I do X?" decision.

---

## Regret Minimization
**Primary dimensions:** inverse_thinking, second_order_effects

Jeff Bezos's framework for irreversible decisions:

1. **Project yourself to age 80**
2. **Look back at this decision**
3. **Which choice minimizes regret?**
4. **Distinguish reversible vs irreversible decisions** — Use this framework mainly for irreversible ones

**When to use:** Career moves, major life decisions, one-way door decisions. Not for daily operational choices.
