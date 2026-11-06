# Rouben Malian Memorial Foundation — organization profile and GitHub defaults

Organization profile for the Rouben Malian Memorial Foundation, with the default issue forms and pull request template for every rmmf-org repository.

> Part of the Rouben Malian Memorial Foundation portfolio · Project board: [Rouben Malian Memorial Foundation · Foundation Website](https://github.com/orgs/rmmf-org/projects/1) · Initiative: [rmmf-org/roubenmalianmemorial-org#148](https://github.com/rmmf-org/roubenmalianmemorial-org/issues/148)

## Overview

The special `.github` repository of the [rmmf-org](https://github.com/rmmf-org) organization. GitHub reads it in two ways:

- `profile/README.md` is shown on the organization's page at https://github.com/rmmf-org. Edit it to change that page.
- Files under `.github/` are the **defaults** for every repository in the organization that has no files of its own: issue forms and the pull request template.

It is for anyone maintaining the Foundation's GitHub organization. The Foundation's website is [www.roubenmalianmemorial.org](https://www.roubenmalianmemorial.org).

## Features

- Organization profile: the Foundation's mission, flagship initiatives, how the work fits together, and contact addresses.
- Default issue forms (Bug, Feature, Task, Epic, Initiative); each form sets the matching organization issue type (Initiative > Epic > Feature / Task / Bug).
- Issue chooser links (`config.yml`) to the website and the contact page, which is also where security issues should be reported privately rather than in a public issue.
- Default pull request template: summary, linked issue (`Closes #`), type of change, screenshots, test plan and a checklist (project board, tests, docs, no secrets, accessibility).

## Tech stack

Markdown and GitHub issue-form YAML only. No code, build or runtime.

## Repository structure

```
profile/README.md                   the organization profile shown on github.com/rmmf-org
.github/ISSUE_TEMPLATE/bug.yml      Bug form (type Bug)
.github/ISSUE_TEMPLATE/feature.yml  Feature form (type Feature)
.github/ISSUE_TEMPLATE/task.yml     Task form (type Task)
.github/ISSUE_TEMPLATE/epic.yml     Epic form (type Epic)
.github/ISSUE_TEMPLATE/initiative.yml  Initiative form (type Initiative)
.github/ISSUE_TEMPLATE/config.yml   blank issues allowed; contact links
.github/pull_request_template.md    default pull request template
SECURITY.md                         organization security policy (the default for every repository)
README.md                           this file
```

## Getting started

Prerequisites: write access to `rmmf-org/.github` and the GitHub CLI (`gh`) or a browser.

```sh
gh repo clone rmmf-org/.github
cd .github
# edit profile/README.md or a file under .github/, then open a pull request
```

There is nothing to install, build or test. Preview Markdown in a pull request; to try an issue form, open "New issue" in any rmmf-org repository that has no forms of its own after the change is merged. No environment variables or secrets.

## Deployment

Changes take effect as soon as they reach the default branch `main`: the profile on https://github.com/rmmf-org updates immediately, and the default forms and template apply to every repository without its own. This repository must stay **public** for GitHub to show the profile README. A repository with its own `.github/ISSUE_TEMPLATE/` (for example `roubenmalianmemorial-org`, once its forms land) uses those instead of these defaults.

## Project management

Organization-wide work is tracked on the [Rouben Malian Memorial Foundation · Foundation Website](https://github.com/orgs/rmmf-org/projects/1) project.

- **Hierarchy:** Initiative ([rmmf-org/roubenmalianmemorial-org#148](https://github.com/rmmf-org/roubenmalianmemorial-org/issues/148)) > Epic (repository and documentation work sits under [Reliability, security and developer experience](https://github.com/rmmf-org/roubenmalianmemorial-org/issues/149)) > Feature / Task / Bug, using organization issue types and sub-issues.
- **Issue forms:** the Bug, Feature, Task, Epic and Initiative forms in this repository.
- **Labels:** `documentation`, `security`, `area:profile`, `area:templates`, plus the estate set (`blocked`, `needs-triage`, `help wanted`, …).
- **Board fields:** Status (Backlog → Ready → In progress → In review → Done), Priority (P0–P3), Size (XS–XL), Iteration (two weeks), Start/Target date, Platform, Area.
- **Pull requests** say `Closes #n` (or `Closes rmmf-org/<repo>#n` across repos) so the issue closes on merge.

## Related repositories

- [rmmf-org/roubenmalianmemorial-org](https://github.com/rmmf-org/roubenmalianmemorial-org) — the Foundation's website (www and volunteer.roubenmalianmemorial.org) on Cloudflare Workers.
- [rmmf-org/roubenmalianmemorial-apex-redirect](https://github.com/rmmf-org/roubenmalianmemorial-apex-redirect) — Worker that redirects the bare roubenmalianmemorial.org domain to www.

## Security

Please do not report a vulnerability in a public issue. Use the [contact page](https://www.roubenmalianmemorial.org/contact) or email **support@roubenmalianmemorial.org**. The organization security policy, which applies to every repository here, is [SECURITY.md](SECURITY.md): supported versions, how to report, the 5-business-day response target and safe harbor.

## License / ownership

Proprietary — © Rouben Malian Memorial Foundation Inc. All rights reserved.
