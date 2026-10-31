# Product Strategy One-Pager & OKRs: Fable

> Module 1 · Write a Strategy That Can Survive a Test, ★ Deliverable 1
>
> Your one spine: the **Playing to Win** cascade, one deliberate **hard no**, and an **OKR cascade** that flows directly from it.
> Draft the cascade + hard no in Sprint 1, then add the OKRs in Sprint 2. The goal: specific enough that a skeptical board member couldn't poke a hole in it.

## 0. Chosen scenario

**Path:** Fable Growth (B2C · retention + engagement)

I picked Fable Growth because my pod owns post-acute retention, the open question this strategy answers is whether users stay after their acute need is resolved, and that is the problem I work on.

## 1. Playing to Win cascade

| Question | Your choice |
|---|---|
| **Winning aspiration** | Fable exists to help people understand what keeps them well, build confidence in their ability to navigate life's challenges, and provide trusted support whenever they need it. Winning means our users feel stronger, more self-aware, and more capable of living their lives, whether they use Fable every day, once a month, or only when it matters most. |
| **Where to play** | Fable will focus on digitally comfortable adults in its established markets who have emerged from an acute period of anxiety or stress and want to protect their progress. Through a privacy-first mobile experience, Fable will help them capture what works, maintain a personal wellness baseline, navigate meaningful stressors, and return quickly to trusted support when circumstances change. |
| **How to win** | Fable will win by becoming the most trusted source of personal wellness knowledge in a user's life. Through years of accumulated understanding, Fable will help people recognize meaningful changes, remember what has worked before, and take action before challenges become crises. Competitors can replicate features, content, and AI experiences, but they cannot easily replicate a trusted longitudinal relationship built around a user's unique path to well-being. |
| **Capabilities required** | Fable will build world-class capabilities in personal wellness intelligence, trusted AI guidance, behavioral science, privacy, and outcomes measurement. It will partner for clinical services and broader support ecosystems, and buy commodity technology infrastructure. By owning the capabilities that deepen understanding and trust while leveraging partners for complementary services, Fable can become the most trusted system for helping people maintain well-being throughout life's changes. |
| **Management systems** | Fable will manage the business through outcomes, trust, and resilience rather than engagement alone. The company will measure success by whether people become more capable, self-aware, and prepared to navigate future challenges. Through recurring reviews of customer outcomes, trust indicators, and strategic alignment, Fable will ensure that every quarter reinforces its mission of helping people stay well, not simply spend more time in the app. |

## 2. Your one hard no

> **Hard no:** Fable will not optimize for engagement, even when doing so would accelerate growth, because engagement mechanics (streaks, pressure loops, session-frequency targets) create dependence on the app, and this strategy only works if users become more resilient and more trusting, including when they open Fable less.

## 3. OKR cascade

> **Objective:** Enable users to sustain well-being after the acute phase by helping them build confidence, self-awareness, and resilience without increasing dependence on Fable.
>
> - **KR1:** Increase the percentage of post-acute users who agree with the statement "I know what to do when I start feeling overwhelmed again" from 42% to 65%. (Interim checkpoint: 52% by June 30, 2027.)
> - **KR2:** Increase the percentage of users who take a proactive action after identifying an early warning sign of declining well-being from 25% to 50%. (Interim checkpoint: 35% by June 30, 2027.)
> - **KR3:** Increase successful re-engagement of post-acute users, users who return to Fable for support during a later stressful period, from 30% to 55%. (Interim checkpoint: at least 35% by September 30, 2027.)
>
> **Strategic learning objective (added in the pressure test, §4):** Increase the percentage of recovering users who opt into an ongoing resilience experience from 0% to 40%, to validate whether recovering users want a continuing relationship with Fable at all.

## 4. AI pressure-test notes

| Prompt question | What the AI surfaced | Change or defend? |
|---|---|---|
| Biggest assumption that could be wrong | That users who feel better still want an ongoing relationship with a mental wellness product. If recovery makes Fable irrelevant to them, there is no post-acute market to retain. | **Change.** My original framing assumed the ongoing relationship. The strategy now treats it as the thing to validate: we believe users need support transitioning from recovery to resilience, and the strategy is to validate and serve that need, which is why the opt-in learning objective (0% to 40%) was added to §3. |
| The board question I can't yet answer | Whether memory-based personalization feels helpful or like surveillance at scale. The whole model runs on trusted wellness memory, and I can't yet prove how users will read it outside early testing. | **Defend, with a guardrail.** We proceed because trust is measured, not assumed: if personalization-related complaints or check-in opt-outs exceed 2% of recipients in any month, the AI prompts pause immediately pending review. A trust breach invalidates the premise regardless of the KRs. |
| KRs that are outputs in disguise | KR3 as first drafted, "recovering users who opt into an ongoing resilience experience, 0% to 40%", measures uptake of a feature we ship, not an outcome for the user. | **Change.** KR3 is rewritten as successful re-engagement of post-acute users, from 30% to 55%, matching the roadmap and the business case. The opt-in measure moved to a strategic learning objective, where it belongs. |
| The "no" I should reconsider | The daily streak feature. It is low effort, a proven retention mechanism, and would create more occasions to deliver support, the case made for it in our show-and-swap review. | **Defend.** Streaks optimize for app usage and habit formation, not resilience; they are engagement mechanics, which the hard no and the charter's out-of-scope list explicitly exclude. More sessions is the metric this strategy refuses to chase, and a streak that punishes a missed day works against users exactly when they are struggling. |
| Strategy or wish list? Why? | Whether the KR targets (42% to 65%, 25% to 50%) are just a list of goals with no mechanism behind them. | **Defend, it is a strategy.** It names a bet (users act proactively when guidance is grounded in their personal history), a mechanism (history → confidence → proactive action → re-engagement → LTV), the alternatives considered and rejected (more acquisition spend pours users into the same leaky bucket at a $54 CAC; human coaching personalizes but cannot scale), and an out-of-scope list that is as much the strategy as the bet itself. |

## 5. Self-diagnostic (6 questions)

- [x] **Clear**: a new PM could read it and know exactly what we will and won't do
- [x] **Names the real challenge**: the diagnosis is specific enough to be uncomfortable
- [x] **Makes a hard bet**: it says no to something valuable
- [x] **Cascadable**: teams can translate it into their own OKRs
- [x] **Coherent**: every choice reinforces the others
- [x] **Committed**: resources are actually moving toward it

## Link to full artifact

Full deliverable set in this repo: [Outcome Roadmap & Trade-off Memo](../02-roadmap/outcome-roadmap.md) · [Team Charter](../03-team-charter/team-charter.md) · [Financial Model](../04-financial-model/financial-model.md)
