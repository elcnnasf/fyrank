# FL-01 — Toolkit setup (things only I can do)

These four steps need a human at a keyboard with my own credentials. Each one ends with a file
dropped into `evidence/`.

## 1. Accounts
| Account | URL | Evidence file |
|---|---|---|
| Claude | https://claude.ai | `evidence/01-claude-account.png` |
| ChatGPT | https://chatgpt.com | `evidence/02-chatgpt-account.png` |
| Anthropic Academy | https://anthropic.skilljar.com | `evidence/03-academy-account.png` |

Sign up with `elcan.atashoff@gmail.com` for all three so the grader can see one identity across the
screenshots. Make sure the account email is visible in each shot.

## 2. Academy enrolment
1. Go to Anthropic Academy → **AI Fluency: Framework & Foundations** (free, certificate track).
2. Click **Enroll**.
3. Complete **Module 1** end to end — don't skip the knowledge check.
4. Screenshot the course page showing the progress bar with Module 1 marked complete →
   `evidence/04-academy-module-1-complete.png`.

## 3. Claude Project
1. claude.ai → left sidebar → **Projects** → **Create project**.
2. Name it `Flyrank-ai — Founder Desk`.
3. Open **Set project instructions** (or "Custom instructions") and paste the full contents of
   [`claude-project-instructions.md`](claude-project-instructions.md).
4. Optional but useful: drop the Flyrank-ai one-pager and this audit into the Project knowledge base.
5. Screenshot the Project **with the instructions text visible** →
   `evidence/05-claude-project.png`. A screenshot of an empty Project won't pass — the instructions
   have to be readable in the image.

## 4. Baselines to measure against
Before FL-02 starts, record the current manual numbers so the success definitions in `audit.md §3`
have something to beat:

| Target task | Baseline to record | Current estimate |
|---|---|---|
| SEO/GEO article draft | minutes from outline → publishable draft | ~2 h |
| Debug a failed crawl run | minutes from error → applied fix | ~45 min |
| Weekly metrics report | minutes of hands-on assembly | ~40 min |

Log real timings for one week in `FL-01-workflow-audit/baselines.csv` rather than trusting these
estimates.
