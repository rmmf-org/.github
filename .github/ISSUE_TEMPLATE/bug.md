---
name: Bug
about: Something is broken. Say what people experience, how many, since when, and whether money or data was lost.
title: ""
type: Bug
---

<!-- Title: the symptom in plain words ("Customers are charged twice when…"), under about 80 characters. Do not
report a security weakness here: use the repository's private vulnerability reporting. Never paste passwords, keys,
tokens or anyone's personal details. The standard: https://github.com/moraph-com/mainspring/blob/main/docs/work-tracking-writing-standard.md, sections 4.2 and 4.5. -->

## Status at a glance

| | |
|---|---|
| **Last updated** | YYYY-MM-DD |
| **What is happening now** | One sentence. |
| **Next step** | One sentence, with who does it and by when. |
| **Waiting on a person?** | No / Yes: who, for what, by when |
| **Outlook** | One sentence: will it be fixed on time, and why or why not. |

Status, priority, estimate and dates are in the project fields in the sidebar.

## Summary

Two to four sentences. What is broken and what will be different once it is fixed. No technical terms.

## What people experience

- **What happens:** what a customer or staff member sees or suffers, in their words.
- **How many are affected:** a number and a time frame ("23 customers in the last 30 days"), or "we do not know yet,
  and this is how we will find out".
- **Since when:** the date it started, or the first report.
- **Workaround today:** what people can do meanwhile, or "none".
- **Money or data lost:** yes or no, and how much.

## Why this matters

- **What it costs today:** money, time, risk, complaints. Use numbers and a time frame.
- **What happens if we do nothing:** the consequence, and how soon.
- **Why now:** what made this a priority.

## What "done" looks like

- [ ] The problem no longer happens, written as something a non-engineer could check.
- [ ] An automatic check fails if it is ever reintroduced.
- [ ] How we will confirm it after release (what we measure, for how long).

## What is included and what is not

**Included:** the specific things this issue will do.
**Not included:** related things a reader might assume are covered (refunds, a redesign), and where they are tracked.

## Approach

Three to six sentences in plain English: the cause, the fix, and why this fix. Use a decision table if options were
weighed.

## Plan

- [ ] Reproduce the problem and confirm the cause
- [ ] Count who is affected
- [ ] Fix it
- [ ] Release and confirm

## Priority and effort: the reasoning

- **Why this priority:** impact and urgency, in one or two sentences.
- **How the effort estimate was reached:** what the work consists of and what it was compared with.
- **Range:** best case, most likely, worst case, and what would cause the worst case.
- **Human time needed:** who must spend time on this, and roughly how many hours.
- **Baseline:** the estimate and target date when the work was agreed, with the date. Never edited.

## Risks and unknowns

| Risk or unknown | How likely | What it would cost | What we are doing about it |
|-----------------|-----------|--------------------|----------------------------|
| | | | |

## Who needs to be involved

- **Decision needed from:** name, the decision, the deadline.
- **Should be kept informed:** names or teams.

## Related work

- Related: #n (one line on how)

---

## Technical details

For engineers. A non-technical reader can stop above this line.

- How to reproduce: numbered steps, expected result, actual result.
- Where in the system: files, services, tables.
- Evidence: error messages and log excerpts (collapsed, with secrets and personal data removed).
