# FL-01 — Workflow Audit
**Name:** Elcan Atashoff · **Date:** 2026-08-28 · **Context:** Solo founder, Flyrank-ai
**Week shape:** product build (code), content/SEO, research & reporting. AI already used daily for drafting and coding, but unsystematically.

Classification key (Mollick, *On-boarding your AI Intern*):
**JM** = Just me · **DR** = Delegate to AI, I review · **CO** = Collaborate with AI · **FA** = Fully automate

---

## 1. Task audit

| # | Recurring task | Freq | Class | One-line rationale |
|---|---|---|---|---|
| 1 | Build core Flyrank-ai features (crawler, scoring pipeline) | Daily | CO | I hold the architecture and edge cases; AI writes faster than I do inside a design I've already fixed. |
| 2 | Debug production errors / failed crawl runs | 3–4×/wk | CO | AI reads stack traces and proposes hypotheses fast, but only I know which subsystem is load-bearing. |
| 3 | Review my own diffs before merge | Daily | DR | A second reader catches the dumb stuff; I still make the merge call because I own the blast radius. |
| 4 | Schema migrations, types, API boilerplate | 2×/wk | DR | Mechanical, well-specified, easy to verify — review is cheaper than writing it. |
| 5 | Write unit / integration tests for new endpoints | 2×/wk | DR | Tests are pattern work from a spec I supply; I review that they actually assert the failure mode. |
| 6 | Decide the roadmap — what to build next, what to kill | Weekly | **JM** | This is judgment under my own risk and runway; AI has no stake and no access to the gut signal from user calls. |
| 7 | Pricing & positioning decisions | Monthly | **JM** | Depends on conviction about who I'm building for; an averaged answer here is actively harmful. |
| 8 | Draft SEO/GEO blog articles for Flyrank-ai | 2×/wk | DR | High-volume drafting from my outline and angle; I edit for voice and verify every claim. |
| 9 | Keyword + AI-answer (GEO) research for target queries | Weekly | CO | AI expands and clusters the query space; I pick which clusters we can actually win. |
| 10 | Competitor teardown / feature gap analysis | Bi-weekly | CO | AI structures the comparison, I supply the "so what" — it can't tell which gap is a moat. |
| 11 | Weekly metrics report (signups, activation, MRR, crawl volume) | Weekly | FA | Deterministic pull from fixed sources into a fixed template; no judgment in the assembly step. |
| 12 | Landing page copy variants for A/B tests | Bi-weekly | CO | Volume of variants is AI's strength, taste in which two to actually ship is mine. |
| 13 | Answer user support / onboarding emails | Daily | DR | Most are repeat questions with known answers; I read every reply before it goes out because it's my name on it. |
| 14 | Voice memo / call notes → structured task list | 3×/wk | FA | Pure transcription and formatting, zero downside if the wording is imperfect. |
| 15 | Read GEO/LLM-retrieval papers and decide what applies to Flyrank | Weekly | **JM** | Summaries would let me skip the part where understanding actually forms; the point is my model of the field, not the notes. |

**Distribution:** JM 3 · DR 5 · CO 5 · FA 2

---

## 2. What the audit surfaced

- **The "collaborate" band is where my week actually lives** (5 tasks, all daily-ish). That's also where I currently get the least structure — I chat ad hoc instead of setting up the task.
- **Two tasks are quietly mis-classified today:** I hand-assemble the weekly metrics report (FA work I'm doing manually) and I sometimes let AI reason about roadmap (JM work I'm outsourcing). Both are corrected above.
- **My "just me" tasks share a trait:** the value is in *me having done it*, not in the artifact. Roadmap conviction, pricing nerve, and field understanding don't transfer through a summary.

---

## 3. Three target tasks for FL-02 → FL-04

One from each band that FL-02–04 escalate through: delegation → collaboration → automation.

### Target 1 — Draft an SEO/GEO article from my outline (`DR`, → FL-02 delegation)
**Done well means:**
- Full draft (1,200–1,500 words) from a 5-bullet outline in **≤ 15 min** wall clock, vs. ~2 h by hand.
- **≤ 30% of sentences need my edit** on the first pass (I count edited vs. total sentences).
- **Zero unverified factual claims** survive: every stat/citation either has a source I checked or is cut.
- Reads in my voice: no em-dash-per-paragraph, no "in today's fast-paced world", no listicle padding.

### Target 2 — Debug a failed crawl / production error (`CO`, → FL-03 collaboration)
**Done well means:**
- From error to a **ranked list of 3 candidate root causes with a distinguishing test for each**, in ≤ 10 min.
- The true cause is in the top 3 **at least 7 of 10 times** (I log this).
- I can state *why* the fix works before applying it — no cargo-culted patch.
- Mean time to resolution drops from my current ~45 min baseline to **≤ 20 min**.

### Target 3 — Weekly metrics report (`FA`, → FL-04 automation)
**Done well means:**
- Runs **unattended every Monday 08:00**, output in my inbox before I open the laptop.
- Numbers match a manual spot-check **exactly**, 3 weeks running, before I stop checking.
- Flags any metric moving **>20% week-over-week** with the number, not a narrative.
- My hands-on time goes from **~40 min/week → under 5 min** (read + react only).

---

## 4. Evidence checklist

| Item | Status |
|---|---|
| Claude account (claude.ai) | ☐ |
| ChatGPT account | ☐ |
| Anthropic Academy account | ☐ |
| Enrolled: *AI Fluency: Framework & Foundations* | ☐ |
| Module 1 complete | ☐ |
| Claude Project created + custom instructions | ☐ |
| Screenshot of configured Project | ☐ |
