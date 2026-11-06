---
name: "Bounty — Complex (Tier 3 / Spike / Diagnostic)"
about: "Tier 3 (6000-10000 LKR), Spike (research) or Diagnostic (2500 LKR). Includes mandatory Bounty Terms and Kill/Discovery Fee rules."
title: "[Bounty] "
labels: ""
assignees: ""
---

<!--
  HOW TO USE THIS TEMPLATE
  1. Fill in EVERY section, including the mandatory Bounty Terms acknowledgement.
  2. Add exactly ONE bounty label to this issue:
       Tier-3: 6000-10000 LKR   |   Diagnostic: 2500 LKR   |   Spike: Research
  3. Assign an owner, then move the card to "In Progress" on the Acenzo Bounty Board.
  4. Tier 3 / Spike / Diagnostic work is expected to span multiple sessions. Use the
     Kill/Discovery clause instead of silently disappearing.
-->

## Symptom / Objective

<!-- What is happening right now (symptom), OR what are we trying to learn/build (objective)?
     Describe observable behaviour and business impact. Do not prescribe the solution. -->

**Current behaviour:**

**Expected behaviour:**

**Business / user impact** (who is affected, how often, how bad):

**Where it happens** (page / API route / service / repo / environment):


## Context & Constraints

<!-- Everything the owner must know up front so they do not rediscover it. -->

**Relevant code / modules / files:**

**Systems & dependencies involved** (DB, queue, storage, third-party API, infra):

**Hard constraints** (do not touch, backwards compatibility, data safety, deployment rules):

**Known prior attempts** (what was already tried and why it failed):


## Steps to Reproduce / Investigation Starting Point

1.
2.
3.

**Frequency:** <!-- Always / Intermittent / Only on X device or network / Unknown -->


## Expected Outcome / Definition of Done

<!-- The ticket is only "Done" when ALL applicable items are true. -->

- [ ] Root cause identified and documented (or, for a Spike: the research question is answered with evidence).
- [ ] Fix / implementation is applied and matches the "Expected behaviour".
- [ ] Findings written up in this issue (cause, approach, trade-offs, what was ruled out).
- [ ] Evidence attached (screenshots, logs, profiler output, reproduction script).
- [ ] Pull request opened against the target branch and linked to this issue.
- [ ] PR reviewed and approved by a maintainer.
- [ ] Passes UAT / Staging verification by the reporter or maintainer.
- [ ] No regression in adjacent flows.
- [ ] Rollback / kill-switch path documented.
- [ ] Follow-up work (if any) captured as separate linked issues.


## Evidence / References

```text
paste logs, stack traces, query plans, network traces or measurements here
```

**Linked issues / PRs / docs:**


## Scope Guardrails

**In scope:**

**Explicitly out of scope** (becomes a new ticket):


## Bounty Terms  — MANDATORY, READ BEFORE STARTING

> **By moving this ticket to In Progress, the assignee accepts these terms.**
>
> ### 1. Full Payout
> The **full bounty amount is paid only when a pull request is merged and passes UAT** (Staging
> verification by the maintainer or reporter). Opened, draft, or self-approved PRs do not qualify.
> Partial credit is not paid for partially working code that is merged behind a disabled flag unless
> the ticket explicitly allows it.
>
> ### 2. Kill / Discovery Fee — 25% to 30% of the bounty
> A **25-30% Kill/Discovery Fee** is paid **only** when **both** of these are true:
> 1. A **hard blocker** is hit that makes the objective unreachable within this ticket's scope
>    (e.g. missing credentials/access, broken upstream dependency, undocumented legacy behaviour,
>    architectural limitation, or a discovered defect outside this ticket's blast radius); **and**
> 2. The **broken / work-in-progress branch is pushed to the repository** and **documented** in this
>    issue: what was tried, what was ruled out, the exact blocker, the evidence, and the recommended
>    next step.
>
> ### 3. No Payout for Abandonment
> **No payout is made for abandoning the ticket without documentation.** Going quiet, leaving work
> only on a local machine, or closing/parking the ticket without the write-up above results in
> **zero payout**, and the ticket returns to the pool.
>
> ### 4. Clock, Handover & Escalation
> - The **48-hour response SLA** applies: while In Progress, the assignee must produce visible
>   progress (commit, PR, or issue comment) at least every 48 hours.
> - Two consecutive silent 48-hour windows = automatic unassignment with no payout.
> - Handover is allowed at any time: push your branch + comment the state and the next owner may
>   continue. Payout for a handed-over ticket is split at the maintainer's discretion based on
>   contribution.
> - Spike / Diagnostic tickets are paid on **delivery of the written discovery** (findings +
>   evidence), not on a code merge — but they still require the documented push/handover above.

**Assignee acknowledgement (required):**

- [ ] I have read and accept the Full Payout condition (merged PR + passing UAT).
- [ ] I have read and accept the Kill/Discovery Fee condition (hard blocker + pushed branch + documentation).
- [ ] I understand there is **no payout** for abandoning without documentation.


## Bounty Label (maintainer sets one)

- [ ] `Tier-3: 6000-10000 LKR`
- [ ] `Diagnostic: 2500 LKR`
- [ ] `Spike: Research`


## Diagnostic / Spike Deliverable Format

<!-- For Diagnostic and Spike tickets, the deliverable is this written block filled in. -->

**Finding / root cause:**

**Evidence:**

**Options considered + recommendation:**

**Estimated effort for the real fix:**

**Risks if we do nothing:**
