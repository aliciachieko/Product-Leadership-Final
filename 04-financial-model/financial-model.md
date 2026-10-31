# Financial Model: Fable, Rock #2: Personalize Support Using Wellness Memory

> Module 5 · Master Product Financials & Strategic Bets, ★ Deliverable 5
>
> The business case for funding your bet, and the explicit kill criteria that would tell you to stop.

**Strategic bet:** We bet users will take proactive steps to manage stress when guidance is grounded in their personal history rather than generic wellness advice.

**Key initiative:** Add AI-generated check-in prompts personalized to user history.

**Connects to:** KR1 and KR2 (and supports KR3)

- KR1: Increase confidence in managing future stress from 42% to 65%.
- KR2: Increase proactive action after identifying early warning signs from 25% to 50%.
- KR3 (supported): Increase successful re-engagement of post-acute users from 30% to 55%.

## 1. Business case

*Why this initiative is worth funding over the alternatives. Include the key unit economics assumptions, CAC, LTV, payback period, where relevant.*

| Assumption | Value | Source / rationale |
|---|---|---|
| CAC | $54 | Blended paid + organic acquisition cost per user, in line with consumer wellness benchmarks. This bet does not change CAC, it raises the value of each user already acquired. |
| LTV | $118 today, $171 with this bet (+45%) | Modeled at a $15/month subscription. The lift comes from re-engagement rising from 30% to 55% and longer post-acute engagement; every retained post-acute user is revenue we already paid to acquire. |
| Payback period | ~5 months (CAC); ~2 quarters (this investment) | CAC payback at current contribution margin. The initiative's build cost is recovered from incremental retained revenue within about two quarters of launch. |
| Investment required | $210K | One quarter for the pod (PM3, 2 engineers, 1 designer, loaded) plus AI inference (~$0.90 per active user/month at expected check-in volume) and evaluation tooling. |
| Expected return | ~$690K incremental annual revenue at steady state | ~52,000 users/year complete an acute episode; a 25-point re-engagement lift = ~13,000 additional retained users × $53 LTV lift. ≈3.3× first-year return on the build investment. |

**The case in one paragraph:** Fable's differentiator is trusted wellness memory and personalized guidance, generic wellness advice is what every competitor gives away free, and it is why post-acute users drift away once their acute need resolves. The alternatives for this pod don't fix that leak: more acquisition spend pours new users into the same leaky post-acute bucket at $54 a head, and human coaching delivers the personalization but cannot scale to the full post-acute population. This bet monetizes the asset only Fable has, the user's own history, raising LTV roughly 45% with no change to CAC, paying back within about two quarters, and moving KR1 and KR2 directly. If the personalization effect isn't real, the kill criteria below stop the spend within two quarters.

## 2. Kill criteria

*The specific signals that would tell you this bet is no longer worth pursuing. Be explicit about the metric, the threshold, and the timeline.*

*(Assumes launch at the start of Q1 2027; shift the dates with the launch.)*

> If KR1 (confidence in managing future stress) does not reach 52% by June 30, 2027, two full quarters post-launch, against a 42% baseline and 65% target, we will stop personalization development and revert to the standard check-in cadence.

> If KR2 (proactive action after identifying early warning signs) does not reach 35% by June 30, 2027, against a 25% baseline and 50% target, we will kill AI-generated prompts and redirect the pod to Rock #1 (re-engagement timing).

> If KR3 (successful re-engagement of post-acute users) does not improve by at least 5 points (30% to 35%) by September 30, 2027, we will stop funding this rock and reallocate the pod to the next strategic bet.

> Guardrail: if personalization-related complaints or check-in opt-outs exceed 2% of recipients in any month, we will pause AI-generated prompts immediately pending review, this bet is built on trusted wellness memory, and a trust breach invalidates the premise regardless of the KRs.

## Link to full artifact

*[link to this deliverable in your repo]*
