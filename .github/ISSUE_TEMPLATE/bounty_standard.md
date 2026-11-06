---
name: "Bounty — Standard (Tier 1 & Tier 2)"
about: "Scoped fix for Tier 1 (500-1000 LKR) or Tier 2 (2500-4000 LKR). Strict 48-hour SLA once moved to In Progress."
title: "[Bounty] "
labels: ""
assignees: ""
---

<!--
  HOW TO USE THIS TEMPLATE
  1. Fill in EVERY section below. Incomplete tickets are not moved to In Progress.
  2. Add exactly ONE bounty label to this issue:
       Tier-1: 500-1000 LKR   or   Tier-2: 2500-4000 LKR
  3. Assign an owner, then move the card to "In Progress" on the Acenzo Bounty Board.
-->

## Symptom / Objective

<!-- What is happening right now (symptom), OR what are we trying to achieve (objective)?
     Be concrete. No solution guessing - describe the observable problem. -->

**Current behaviour:**

**Expected behaviour:**

**Where it happens** (page / API route / module / environment):


## Steps to Reproduce

1.
2.
3.

**Frequency:** <!-- Always / Intermittent / Only on X device or network -->


## Expected Outcome / Definition of Done

<!-- The ticket is only "Done" when ALL of these are true. Add/remove lines as needed. -->

- [ ] Root cause identified and fixed (not just masked/silenced).
- [ ] Behaviour matches the "Expected behaviour" described above.
- [ ] Verified locally by the assignee with evidence attached (screenshot, log, or test run).
- [ ] Pull request opened against the target branch and linked to this issue.
- [ ] PR reviewed and approved by a maintainer.
- [ ] Passes UAT / Staging verification by the reporter or maintainer.
- [ ] No regression: adjacent flows touched by the change still work.
- [ ] Rollback path is trivial (single revert of the PR).


## Evidence / References

<!-- Logs, screenshots, screen recordings, failing request + response, related issues/PRs. -->

```text
paste logs or error output here
```


## Scope Guardrails

**In scope:**

**Explicitly out of scope** (do NOT touch - becomes a new ticket):


## Bounty & SLA Terms (Tier 1 & Tier 2)

> ### Strict 48-Hour SLA
> Once this issue is moved to **In Progress**, the owner has a **strict 48-hour window** to deliver a
> reviewable pull request against the agreed Definition of Done.
>
> - **Clock starts:** the moment the card enters *In Progress* (assignment alone does not start it).
> - **Clock stops:** when a pull request is opened and linked to this issue.
> - **If blocked before 48 hours:** post a comment here with the blocker and push the work-in-progress
>   branch. The 48-hour SLA pauses and the ticket is re-triaged.
> - **If the SLA is breached with no comment and no push:** the ticket is unassigned, moved back to
>   *To-Do*, and re-listed for another contributor.
>
> **Payout:** full bounty is released only for a **merged PR that passes UAT**, not for merely opened
> PRs. LKR amounts are the ranges on the bounty label and are finalised by the maintainer at merge
> based on scope actually delivered.


## Bounty Label (maintainer sets one)

- [ ] `Tier-1: 500-1000 LKR`
- [ ] `Tier-2: 2500-4000 LKR`


## Assignee Checklist

- [ ] I have read the Definition of Done and agree to the 48-hour SLA.
- [ ] I have confirmed I can reproduce the issue / understand the objective.
- [ ] I will push my branch and open a PR rather than leaving work local.
