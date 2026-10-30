# Life Decision Guide

**72 criteria for mapping the social relationships you are locked into, and pricing the cost of leaving each one.**

> This is an English summary. The full text — 50,000 Chinese characters, 72 criteria with their failure conditions — is in Chinese, in [`references/01-律目全谱.md`](references/01-律目全谱.md). The point of this page is to let you decide whether it is worth having someone translate it for you.

---

## The case it starts from

A man has spent eight years at one company. The pay has barely moved, his manager is difficult, and he is not leaving. Ask him why, and he says: *"I'm used to it."*

"I'm used to it" is not a reason. It is an unfinished account.

What actually holds him is seven invisible lines: the mortgage, continuity of social insurance, his child's school district, his spouse's job, his parents' illnesses, his industry contacts, and the identity of *being a senior employee here*. **Pull any one, and the other six come loose at the same time.**

The method does one thing: **list those lines, count them, and price what it costs to pull each one out.**

---

## Three steps

**1. List the interfaces**
What he was born into (birthplace, household registration, class origin, gender role, mother tongue, the local industry) and what he opted into (profession, marriage, platform accounts, loans, social insurance). Which are breaking, which are forming.

> The discipline: write down *what he is attached to*, never *whether he should be*. Turning a moral question into a structural one is the whole point of this step.

**2. Locate the mother-port**
The one relationship that dominates the production or distribution of core resources.

- **Production type**, marked by *possession*: kinship → ownership of persons → land → capital
- **Distribution type**, marked by *the checkpoint*: trade routes and tariffs / traffic entry points and quotas / platform revenue-share rules / establishment and rank allocation

Three tests, all required: does it decide *who gets access and whose value is recognized*? Remove it — do the derived relations re-aim? Is it merely an intermediate link, or does it set the direction and speed of flow?

**3. Price the insertion and removal**

> Attachment strength = number of interfaces × exit cost per interface × joint-liability between interfaces

Four costs per interface: **identity binding / sunk cost / survival dependence / internalized belief**.
Three questions to finish the account: *how deep does that money go* (survival / development / consumption — never mixed) · *if I pull A, does B fail too* · *how many alternative paths exist outside this door*.

**One line: freedom is not a mindset. It is a function of insertion-and-removal cost.**

---

## The three questions behind it

> **Who controls your life? Whose consumable are you? How do you break out?**

Each has a decomposable answer:

- **Who controls your life** — not "some person", but whichever relationship holds the mother-port. Miss it, and you will keep blaming the boss, the industry, or fate.
- **Whose consumable are you** — follow the three costs (access, maintenance, removal) and see whose ledger they settle on. **Those who hold rights without liability are rentiers; those who hold liability without rights are consumables.**
- **How do you break out** — price the exit before discussing whether to leave. **Most "breakouts" that were never priced are just a change of venue for being a consumable.**

---

## 30-second self-test

Two out of three, and this is worth your time. None, and close the tab.

| Have you seen this? | If yes, it means |
|---|---|
| Someone capable and not badly off, who simply will not move | The account is unfinished, not the person lazy |
| An organization that changed its rules three times and its people twice, still stuck on the same problem | Everything changed was a derived relation; the mother-port was never touched |
| A system that collapsed overnight instead of eroding | Joint liability failing all at once |

---

## What it is not

| Not | Why |
|---|---|
| A universal explanatory frame | Use it to explain everything and it becomes a new fetishism. **Criteria may be added; the root may not be dropped.** |
| A moral judgment | It explains *why*, not *whether it is good*. |
| A course of action | It locates the constraint, not the choice. The latter needs values. |
| An academic work | No literature review, no school positioning — only criteria and their failure conditions. |

---

## Install

**Claude Code / Codex** — drop the directory into your skills folder:

```
your-project/.claude/skills/life-decision-guide/
├── SKILL.md
└── references/
```

**WorkBuddy** — user-level for all projects, or project-level for one:

```
~/.workbuddy/skills/life-decision-guide/
<project>/.workbuddy/skills/life-decision-guide/
```

The directory name must match the `name` field in `SKILL.md` (`life-decision-guide`). The `name` field accepts lowercase letters, digits and hyphens only.

---

## What's in the repository

| File | What it is |
|---|---|
| `SKILL.md` | Skill entry point: three steps, retrieval protocol, output format |
| `references/01-律目全谱.md` | The 72 criteria, 50,000 characters, each with its failure condition |
| `references/02-操作判据.md` | Three questions / five questions / six common misreadings — a one-page version |
| `references/00-索引.md` | Lookup table by problem |
| `金句_72条.md` | All 72 compressed to one line each |
| `examples/` | Five worked-through cases (2 for analyzing others, 3 for yourself) |
| `FAQ.md` | Twelve common objections, answered |

---

## License

**CC BY-NC-ND 4.0** — attribution, non-commercial, no derivatives.

Why no derivatives: every criterion carries a failure condition. Allow rewriting and you will get versions with the boundary clipped off and only the conclusion kept — and those sentences turn into geographic determinism, blood determinism, or fatalism. That is not this framework. It is the opposite of it.

**Author**: 一坡 (Yipo) · **Version**: v1.1.2 · **Repository**: [Gitee](https://gitee.com/leonma19940126/life-decision-guide)
