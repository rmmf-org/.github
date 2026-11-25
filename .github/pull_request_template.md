<!-- Title: the plain-English outcome ("Charge each order only once, even if Pay is clicked repeatedly"), not a
code name. Replace every example below. The standard: https://github.com/moraph-com/mainspring/blob/main/docs/work-tracking-writing-standard.md, section 7. -->

## In plain English

The extended version for a business reader who has not seen the code or the conversation: what this is, why it was
needed, what changes for whom once it is live, what was checked, and anything the owner should know or do. Several
short paragraphs; define any technical term in brackets the first time.

## What this changes

Two to four plain sentences. What is different for a customer or staff member once this is live. If nothing visible
changes, say so and say what improves behind the scenes.

Closes #

## Why

One or two sentences summarising the problem, so the reader does not have to open the issue. Link to the issue for
the full background.

## Before and after

| | Before | After |
|---|--------|-------|
| What the customer experiences | | |
| Relevant number (speed, error rate, cost) | | |

Screenshots or a short recording for anything visible.

## How it was checked

| Check | What it shows | Result |
|-------|---------------|--------|
| [Plain description of a test, with its counts: passed, failed, skipped] | [What passing proves] | Passed / Failed / Not run |

**Not checked:** [anything that could not be tested, and why].

## Risk and how to undo it

- **Risk level:** Low / Medium / High. [One sentence of reasoning.]
- **What could go wrong:** [the realistic worst case, in business terms].
- **Who would notice, and how:** [alert, customer report, dashboard].
- **How to undo:** [steps and how long it takes]. [Say plainly if it cannot be easily undone.]

## What the reviewer should look at

Where a human's judgement is most valuable.

## What this does not do

Related things left for later, each with an issue link.

## Release notes

One sentence suitable for telling customers or staff, or "No announcement needed."

---

## Technical details

- Summary of changes by area.
- Anything needed at release time: settings, data changes, order of steps.
- Decisions made in the code that are not in the issue.

_Written by an AI agent, supervised by [person]. Say which parts, if any, a person wrote or reviewed._
