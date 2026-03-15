# 🔺 Prism Thinking Refinery

**An adaptive cognitive training skill for OpenClaw.**

Most people think in one or two default modes. Prism breaks that pattern — it maps your unique thinking profile across multiple cognitive dimensions, then pushes you to grow where you're weakest.

## How It Works

Every user gets a **Thinking Radar** — a spider-web profile of cognitive dimensions like first-principles reasoning, inverse thinking, systems thinking, and more. The radar isn't a static score; it evolves with every interaction, adjusting ±0.1 to ±0.5 based on how you actually think, not how you think you think.

```
🔺 Thinking Radar

first_principles    ████████░░  7.2
inverse_thinking    ████░░░░░░  4.1
stakeholder_lens    ██████░░░░  6.0
systems_thinking    █████░░░░░  5.3
game_theory         ███░░░░░░░  3.4
historical_analogy  ████░░░░░░  4.0
second_order_effects █████░░░░░  5.1
cross_domain        ██████░░░░  6.2
```

## Five Modes

| Mode | What It Does |
|------|-------------|
| 🔺 **Prism Analysis** | Analyze any topic through 3–5 thinking frameworks, biased toward your weak spots |
| 🥊 **Thought Sparring** | Challenge your ideas with genuine adversarial pressure — not polite devil's advocacy |
| 📚 **Curated Feed** | Cross-domain reading recommendations tailored to your growth areas |
| 📓 **Decision Journal** | Record predictions, review them monthly, calibrate your judgment over time |
| ✍️ **Clarity Writing** | Turn fuzzy ideas into sharp arguments through guided refinement |

## Adaptive by Design

The skill adjusts its approach based on your dimension scores:

- **Low (1–3):** Guides you step by step with examples
- **Mid (4–6):** Gives you the framework, lets you try, then fills gaps
- **High (7–9):** Challenges your assumptions directly
- **Mastery (10):** Asks you to teach — because teaching is the final test

You can also add **custom dimensions** (ethical reasoning, aesthetic judgment, etc.) anytime. The system treats them identically.

## Setup

1. Install the skill in your OpenClaw workspace (`skills/prism-thinking-refinery/`)
2. On first use, the agent runs a **calibration session** — 3 scenario-based questions to map your starting profile
3. Set your digest preferences (daily/weekly push of curated content)
4. Start thinking differently

## Privacy

Your personal data (`data/` — radar scores, journal entries, predictions) is `.gitignore`d by default. The skill framework is shareable; your thinking profile stays yours.

## Requirements

- [OpenClaw](https://github.com/openclaw/openclaw)
- Any supported LLM (works best with models that support extended reasoning)

## License

MIT
