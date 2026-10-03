# OpenDL — the 14 Grand Challenges, as open protocols

Automating the experimental loop is necessary but not sufficient. For most of the
National Academy of Engineering's [14 Grand Challenges](https://www.nae.edu/20782/grand-challenges-project),
the rate limiter is not propose → run → examine. It is the institutional path
around the experiment: the permit, the review, the license, the award negotiation.

Fusion does not wait on confinement runs. It waits on NEPA review under 10 CFR
Part 1021 and a radioactive materials license under 10 CFR Part 30. Solar does not
wait on cell efficiency. It waits on PURPA Qualifying Facility self-certification
(FERC Form 556) and CAISO Scheduling Coordinator onboarding. Those are serial,
human, and re-derived from scratch by every team that attempts them.

**The bet:** codify each challenge's real statutory path as a runnable protocol —
typed steps, named roles, verification gates — so an automated loop has something
to execute against instead of a wiki page.

**Why open:** a protocol nobody can read or fork is just another closed loop. If a
handful of people automate their loop privately, the world gets faster experiments
at one company; the parts that actually take years stay tribal knowledge.

## The 14

| # | Challenge | Processes | Board |
|---|---|---|---|
| 1 | [Make Solar Energy Economical](challenges/solar.md) | 14 | [#194](https://github.com/orgs/HardisonCo/projects/194) |
| 2 | [Provide Energy from Fusion](challenges/fusion.md) | 13 | [#206](https://github.com/orgs/HardisonCo/projects/206) |
| 3 | [Develop Carbon Sequestration Methods](challenges/carbon.md) | 13 | [#196](https://github.com/orgs/HardisonCo/projects/196) |
| 4 | [Manage the Nitrogen Cycle](challenges/nitrogen.md) | 14 | [#197](https://github.com/orgs/HardisonCo/projects/197) |
| 5 | [Provide Access to Clean Water](challenges/water.md) | 14 | [#195](https://github.com/orgs/HardisonCo/projects/195) |
| 6 | [Restore and Improve Urban Infrastructure](challenges/urban.md) | 14 | [#193](https://github.com/orgs/HardisonCo/projects/193) |
| 7 | [Advance Health Informatics](challenges/healthinfo.md) | 12 | [#203](https://github.com/orgs/HardisonCo/projects/203) |
| 8 | [Engineer Better Medicines](challenges/medicines.md) | 14 | [#200](https://github.com/orgs/HardisonCo/projects/200) |
| 9 | [Reverse Engineer the Brain](challenges/brain.md) | 14 | [#205](https://github.com/orgs/HardisonCo/projects/205) |
| 10 | [Prevent Nuclear Terror](challenges/nuclear.md) | 13 | [#204](https://github.com/orgs/HardisonCo/projects/204) |
| 11 | [Secure Cyberspace](challenges/cyber.md) | 14 | [#201](https://github.com/orgs/HardisonCo/projects/201) |
| 12 | [Enhance Virtual Reality](challenges/vr.md) | 13 | [#202](https://github.com/orgs/HardisonCo/projects/202) |
| 13 | [Advance Personalized Learning](challenges/learning.md) | 13 | [#199](https://github.com/orgs/HardisonCo/projects/199) |
| 14 | [Engineer the Tools of Scientific Discovery](challenges/discovery.md) | 14 | [#198](https://github.com/orgs/HardisonCo/projects/198) |

189 processes across the 14.

## Status — read this before citing anything here

Every page in `challenges/` is a **specification with an authored protocol pack**, not
a shipped system. The processes are real and sourced from statute and agency practice.
As of 2026-09-23 all 189 have an authored, source-cited protocol pack (intent + deal
template + reviewed step typings) in
[CI-API `Modules/Codify/Database/Seeders/bundles/opendl-<label>/`](https://github.com/HardisonCo/CI-API/tree/main/Modules/Codify/Database/Seeders/bundles)
— each re-derived from primary sources (eCFR, statute, the agency's own forms and
pages) and adversarially verified against them. Each challenge page links every
process to its slug, its codify-launch EPIC and its pack. Program generation on the
`<label>.openyc.org` tenants is the operator's lane and is not yet done. Nothing here
claims a solved challenge.

Runtime and surfaces: https://opendl.ai
