# EnerGNN Governance

This document defines the project governance for EnerGNN — the community roles, how decisions are made, and how the project operates day to day. EnerGNN is a project hosted by the **LF Energy Foundation**.

This document complements, and does not duplicate, the project's **Technical Charter**, which is the binding legal document. In case of conflict, the Technical Charter takes precedence.

- Technical Charter: [`CHARTER.pdf`](./CHARTER.pdf)

---

## 1. Roles

### Contributor
Anyone who submits a contribution to the project (code, documentation, issues, reviews, or otherwise). No approval is required to become a Contributor.

### Committer / Maintainer
A Contributor who has made multiple substantive contributions and has been granted write/merge access to one or more EnerGNN repositories.

- Current committers are listed in [`COMMITTERS.csv`](./COMMITTERS.csv).
- **Promotion process**: a Contributor is nominated (by themselves or by an existing committer) 
  via a pull request adding their name to `COMMITTERS.csv`. 
  The PR requires approval from the majority of the union of committers and TSC members (if equality, the TSC chair decides) before the TSC chair merges 
  it and grants repository access.
- **Removal**: a committer who has been inactive for 12 months may be moved to
  an emeritus list by the TSC. Removal for cause requires a TSC vote (see §3).

### TSC (Technical Steering Committee) member
The TSC is the project's leadership body, as defined in the Technical Charter. It is responsible for:
- Setting the overall technical direction and roadmap of the project.
- Ensuring the project community has the resources and infrastructure needed to succeed.
- Resolving disputes within the project community.
- Reporting project updates to the LF Energy TAC.
- Reviewing and merging significant changes, and participating in feature discussions.

Current TSC members are listed in [README.md](../profile/README.md).

- **Composition**: primarily committers, but may also include key stakeholders and dedicated users, per the do-acracy principle — TSC seats go to those actively contributing time, code, or expertise on a regular basis.
- **Adding a member**: nomination by an existing TSC member, approved by TSC vote (majority, and the TSC chair decides in case of equality).
- **Annual audit**: the TSC reviews its own membership at least once a year and removes members who are no longer active, per the process above.

### TSC Chairperson
The TSC Chairperson is the project's figurehead. Responsibilities:
- Leading TSC meetings and setting the agenda in consultation with other TSC members.
- Acting as the project's public spokesperson (events, articles, blog posts, PR/AR).
- Representing the project to the LF Energy TAC and other projects/entities.

- **Selection**: Selected by the TSC members at the first TSC meeting of the year.
- Current chair: Balthazar Donon.

---

## 2. Decision-making & voting

- The project operates primarily by **consensus**. Most decisions (code review, roadmap prioritization, day-to-day process changes) are made through discussion in issues, pull requests, or TSC meetings without a formal vote.
- A formal **TSC vote** is used when consensus cannot be reached, or for decisions explicitly requiring one under the Technical Charter (e.g. charter amendments, adding/removing committers or TSC members, changes to this governance document).
- **Quorum**: all TSC members.
- **Vote**: one vote per voting TSC member, simple majority of those present, provided quorum is met, and the chair decides in case of equality.
- Votes may be conducted live during a TSC meeting or electronically (e.g. via a PR/issue with explicit +1/-1/abstain from each voting member), with the result recorded in the meeting notes either way.

---

## 3. Meetings

- The TSC meets on the first Wednesday of each month at 10am CET.
- Meetings are open to any attendee and published on the [LFX calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings).
- Meeting notes are taken and posted publicly for every TSC meeting — see [`tsc/meeting-notes/`](./meeting-notes/). Note-taking duty rotates across TSC members.
- Joining instructions: [LFX calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings).

---

## 4. Releases

- For the core package EnerGNN, one release per quarter.

---

## 5. Communication channels

- Mailing lists: `energnn-discussion@lists.lfenergy.org`, `energnn-tsc@lists.lfenergy.org`
- Slack: `#energnn` on the [LF Energy Slack](https://slack.lfenergy.org/)
- Wiki: https://lf-energy.atlassian.net/wiki/spaces/EnerGNN/overview

Maintainers are expected to keep the roadmap and release cadence public, and to be responsive to community issues and questions on these channels.

---

## 6. Code of Conduct

All participants are expected to comply with the project's [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## 7. Amendments

This document may be amended by TSC vote, following the process in §2.

*Last updated: 02.07.2026 — approved at TSC meeting #1 + marginal amendments.*
