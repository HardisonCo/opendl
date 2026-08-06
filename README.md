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

| # | Challenge | Processes mapped |
|---|---|---|
| 1 | [Make Solar Energy Economical](challenges/solar.md) | 14 |
| 2 | [Provide Energy from Fusion](challenges/fusion.md) | 13 |
| 3 | [Develop Carbon Sequestration Methods](challenges/carbon.md) | 13 |
| 4 | [Manage the Nitrogen Cycle](challenges/nitrogen.md) | 14 |
| 5 | [Provide Access to Clean Water](challenges/water.md) | 14 |
| 6 | [Restore and Improve Urban Infrastructure](challenges/urban.md) | 14 |
| 7 | [Advance Health Informatics](challenges/healthinfo.md) | 12 |
| 8 | [Engineer Better Medicines](challenges/medicines.md) | 14 |
| 9 | [Reverse Engineer the Brain](challenges/brain.md) | 14 |
| 10 | [Prevent Nuclear Terror](challenges/nuclear.md) | 13 |
| 11 | [Secure Cyberspace](challenges/cyber.md) | 14 |
| 12 | [Enhance Virtual Reality](challenges/vr.md) | 13 |
| 13 | [Advance Personalized Learning](challenges/learning.md) | 13 |
| 14 | [Engineer the Tools of Scientific Discovery](challenges/discovery.md) | 14 |

189 processes across the 14.

## Status — read this before citing anything here

Every page in `challenges/` is a **specification**, not a shipped system. The
processes are real and sourced from statute and agency practice; the protocols that
execute them are in progress. Nothing here claims a solved challenge.

Runtime and surfaces: https://opendl.ai
