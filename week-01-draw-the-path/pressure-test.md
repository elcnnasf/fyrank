# Pressure test — sitemap vs. claim vs. one action

## The prompt (paste this into the Project, verbatim)

```
You are my tutor for this build. Explain your reasoning, don't just give verdicts.

Here is my proof statement:

  Claim:  I make brands visible inside AI answers (GEO/AEO).
  Person: Marketing lead at a 10-50 person B2B SaaS. Organic traffic is flattening.
          ChatGPT, Perplexity and AI Overviews answer her buyers without citing her.
          Nobody on her team owns this yet.
  Action: Request a free AI-visibility audit of her site.

Here is my proposed sitemap:

  /                  Home - hero states the claim, proof strip, 3 case cards, CTA
  /work/<slug> x3    Case studies - prompts her buyers ask, before/after citation counts
  /about             About - 150 words, why I work on this, how I work
  /audit             The action - what she gets, 3-day turnaround, one form

Pressure-test it. Specifically:

1. Walk the path as HER, cold, on a phone, 40 seconds of attention. Where does she
   drop off, and what exactly is she thinking at that moment?
2. Name any page that does NOT move her from landing -> belief -> the one action.
   Argue for cutting it.
3. Name anything MISSING that she needs before she will hand over her company's URL
   and email. Be specific about the objection it answers.
4. Is the one action correctly placed and correctly framed? Would a different action
   convert this person better, and what would that cost me in proof?
5. Give me the single highest-leverage change, and tell me what I'd be trading away
   by making it.

Do not be agreeable. If the map is weak, say where and why.
```

---

## Output — run 1 (2026-08-29)

> Paste the Project's actual answer here, then screenshot the exchange into
> `evidence/03-pressure-test.png`. What follows is the pre-run analysis I worked from; the
> Project's answer replaces or extends it.

**Findings that survived scrutiny:**

1. **The `/work` index page was dead weight.** With three case studies, an index is one extra
   click between the claim and the proof, and it adds no belief of its own. She's on a phone with
   40 seconds — that click is where she leaves.
   → **Cut.** The three case cards now live directly on the home page.

2. **`/contact` and `/audit` were competing.** Two doors means she picks the lower-commitment one,
   which is the one that tells me nothing and starts no relationship.
   → **Cut `/contact`.** One action means one door. Email goes in the footer as a fallback, not as
   a competing CTA.

3. **The case studies were the weakest link, not the strongest.** "Before/after visibility" is only
   believable if the *prompts* are named. A reader has to be able to open ChatGPT herself, type the
   prompt from my case study, and see the result. Unfalsifiable proof is not proof.
   → The case study template now leads with the literal prompt list.

4. **Missing: what happens after she submits the form.** She's handing over her company URL and
   her work email to a stranger. The unanswered objection is "am I about to get sold to for six
   months?"
   → Added to `/audit`: exactly what she gets, in what format, in how many days, and one line
   saying no call is required and I won't add her to anything.

5. **The action is correctly chosen.** A "book a call" CTA would convert a warmer visitor better,
   but this person is cold, skeptical, and time-poor — the audit lets the proof do the selling and
   gives me a real artifact to follow up on. The trade: more of my unpaid time per lead. Accepted,
   because at this stage the audits *become* the case studies.

**Rejected suggestion:** adding a `/pricing` page "so she can self-qualify." She isn't buying yet.
Pricing before proof reframes the visit from *is this real?* to *can I afford this?* — the wrong
question at the wrong moment.

---

## What I will change (required by the brief)

**Primary change:** cut the `/work` index page and surface the three case studies directly on the
home page. Six URLs became five page-slots, and the path from *claim* to *proof* went from two
clicks to one.

**Second change:** every case study now opens with the exact prompts, verbatim, so the reader can
reproduce the result herself. Proof she can check beats proof she has to trust.

**Third change:** `/audit` gets an explicit "what happens next" block — deliverable, format,
turnaround, and no-call promise — to clear the objection that stops a stranger from giving up her
company URL.

`sitemap.md` in this folder is the post-pressure-test version.
