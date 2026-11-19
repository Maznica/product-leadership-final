# Outcome Roadmap & Trade-off Memo: Fable Growth

> Module 2 · Turn Your Strategy into an Outcome Roadmap

## 1. Trade-off memo

> **Rock 1:** Fix the notification system (wrong times, timezone bug) (supports KR2): Reminders arrive at the user’s chosen ritual time instead of 3 a.m. Users past day 90 complete more weekly sessions and turn notifications off less.
>
> **Rock 2:** Add a daily streak feature to drive habit formation (supports KR2): It turns “3+ sessions a week” into a goal users can see and keep. That gives them a reason to open Fable when nothing is wrong, and missing a week isn’t punished.
>
> **Rock 3:** Build a content library: guided meditations, articles, audio (supports KR1): at day 60, each user gets a Steady Plan filled with content matched to their needs and history: the formats, lengths and times that helped them, with enough variety that the plan doesn't get stale. A plan that keeps fitting the user is one they are still practicing with 4 weeks later (KR1), and that keeps their weekly routine going past day 90 (KR2). Because it builds on personal history, it also strengthens the advantage competitors can't copy, which supports premium renewal (revenue check).
>
> **Hard no 1:** Launch a premium tier with therapist-matching: it breaks the non-clinical constraint, costs about 15 person-months and moves none of the KRs
>
> **Hard no 2:** Redesign the onboarding flow based on 40% drop-off data: churn happens at days 90–120, not in week one, and the redesign would take design time all three rocks need. Only a one-question tag for cohort analysis stays.
>
> **Hard no 3:** Build a web version (frequently requested in reviews): popular in reviews, but the ritual happens on a phone. A second platform costs about 12 person-months and would take engineers off the rocks.

## 2. Outcome roadmap

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| **Now (0 to 3 mo)** | **(KR2)** We bet fixing reminder timing so reminders arrive at each user's chosen ritual moment will raise weekly routine completion and cut notification opt-outs for users past day 60; **(KR2)** we bet a daily streak feature will turn feeling better into a visible daily habit, and so a routine of 3+ sessions a week, for stress graduates past day 60*; **(KR1)** we bet a content library of guided meditations, articles and audio, offered at a day-60 graduation moment, will keep day-60 users practicing with their Steady Plan for 4+ weeks** | Squad "Check-in & Return"; Growth team + squad "Graduate & Plan" (design); Steady Studio (content + clinical) + squad "Graduate & Plan" (matching) | ≥95% of reminders arrive in the user's chosen window, more sessions start from a reminder, opt-outs flat or down; rising share of users past day 60 with an active streak and 3+ sessions a week, wellbeing score holds; plan with library content beats a generic plan by ≥20% in week-4 routine completion (E2), share still practicing at 4 weeks moving toward 20% |
| **Next (3 to 6 mo)** | AI daily check-ins built from each user's history, within clinically approved prompt templates (KR3): *comes after Now because the prompts need tagged content to point to and approved templates*; existing crisis flow reused as a one-tap return path (KR3): *comes after the check-ins, which show when strain returns, and after a clinical review*; faster load on the ritual and sleep path (KR2): *comes after Now shows how much friction the 4.2s load causes once reminders work*; Steady buddy, practice-only social (KR2): *only if the fake-door test (E4) run in Now gets ≥10% clicks*; Steady inside premium, a renewal offer for graduates (revenue check): *only after E1 proves graduates take up the plan, so there's no paywall at the graduation moment* | Squad "Check-in & Return" + clinical advisor + counsel; Squad "Check-in & Return" + clinical advisor; Squad "Graduate & Plan"; Growth team; Product Leader + Growth | 30-day return rate of lapsing users up with opt-outs up by ≤2 points (E3); share of returning users who come back through the return path; routine completion up on the ritual path; ≥10% of users who see the buddy offer send an invite, ritual completion higher with a buddy; premium renewal past day 90 moving from ~40% toward 50% |
| **Later (6 to 12 mo)** | *Bets, not commitments:* ML personalization of plans and check-ins (only if E2 shows a personal plan clearly wins); deeper non-clinical skills programs; Steady circles (live practice groups); interface-only localization for existing Spanish- and Portuguese-speaking users (only if they are ≥5% of active users); "Fable for Teams", the strategic option if E1 fails; evidence that Steady users stay well longer, as a proof point competitors can't claim | Squad "Graduate & Plan" + data contractor; Steady Studio; Growth team; Squad "Graduate & Plan"; Product Leader + business development; Clinical advisor + data | Day-120 retention of the stress cohort rising from ~20% toward 30% (KR3) and day-180 retention trending up; North Star (KR2) moving from ~10% toward 20% |
 
**Comments:**
- \* **Daily streak:** forgiving by design. A missed day doesn't wipe out progress and there's no guilt messaging, so it builds habit without encouraging compulsive use. Success is still measured against KR2's 3+ sessions a week.
- \*\* **Content library:** we don't mean more of the same content. We mean variety and personalization: formats, lengths and times of day matched to each user's needs and history, so the Steady Plan keeps fitting the user and doesn't get stale.
