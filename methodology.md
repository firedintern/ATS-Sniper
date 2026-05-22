# CV Tailoring Methodology

The SOP. The CV Modifier project follows this every time.

---

## Core principles

1. **Fit-first, not volume.** Only apply when you're 70-80%+ on must-haves. The methodology surfaces real fit; it doesn't manufacture it.
2. **Translate, don't invent.** Past work expressed in the JD's language is fair game. Skills you haven't actually used aren't — even if you "could refresh" them.
3. **Defendable in 30 seconds.** Every line in a tailored CV must survive a "tell me more about this" follow-up in an interview.
4. **Clearer, not louder.** One sharp bullet beats three vague ones.

---

## The translation–invention line

This is the most important rule and the easiest to fudge. Drawing it cleanly:

**Translation (legitimate)**
You built a service in C# in 2022 that used SOAP messaging. The JD asks for WCF. WCF is one of the C# SOAP frameworks. If you actually used WCF (or its direct equivalent on the same project) and can demo the code in an interview → include it, even if "WCF" isn't the word you'd reach for first.

**Invention (not legitimate)**
You read about WCF but never shipped with it. The JD lists it as mandatory. You add it to your CV as "recently used." If asked to demo, you'd stall. **This is the line. Don't cross it.**

The test:
> If the interviewer pulled up the project today and asked you to walk through the code, could you?

If yes → translate freely.
If no → leave it out and either flag the gap honestly in the cover letter ("closest experience is X, comfortable picking up") or skip the application.

---

## JD intake (every application starts here)

Spend ~3 minutes on this before drafting anything. Output as a structured block.

1. **Title & seniority** — what's the actual scope? Engineer vs. Senior vs. Lead. Check responsibilities, not just title.
2. **Top 5 responsibilities** in JD order, verbatim if useful.
3. **Top 5 must-have skills** — things that appear >1x or are listed as required.
4. **Nice-to-haves** — things mentioned once, often in "bonus" sections.
5. **Primary intent** — pick one from the classifier below.
6. **Disqualifiers** — anything hard-required that you don't have. Flag immediately.

---

## JD intent classifier

Every JD has a primary thing the team is hiring against. Identify it so bullets prioritize the right wins.

| Intent | Signals in JD | Prioritize bullets about |
|--------|---------------|--------------------------|
| **Throughput / latency** | "scale," "performance," "high-volume," "p95," "low latency" | p95/throughput wins, capacity gains, query optimization |
| **Reliability / compliance** | "uptime," "SRE," "incident," "audit," "regulated," "MiCA," "AML" | MTTR, SLOs, incident leadership, audit trails, compliance work |
| **Cost / efficiency** | "cost," "optimize," "right-size," "FinOps" | % cost down, CPU/memory reductions, right-sizing |
| **Stakeholder / product** | "cross-functional," "stakeholder," "roadmap," "PM-adjacent" | workshops, cross-team coordination, measurable business impact |
| **GTM / growth** | "go-to-market," "adoption," "user growth," "partnerships," "launch" | user growth %, partnership wins, launches shipped, content reach |
| **Builder / shipping speed** | "ship fast," "0-to-1," "scrappy," "MVP," "founder mentality" | projects launched, time-to-ship, solo or small-team builds |
| **BD / sales** | "pipeline," "deals closed," "ARR," "quota," "enterprise" | deal sizes, pipeline value, named accounts, conversion rates |

A JD can have a secondary intent. Primary gets ~70% of the emphasis, secondary ~30%.

---

## ATS mechanics (the firewall)

ATS systems parse your CV into structured fields (name, dates, employers, skills). They fail in predictable ways. Survive by avoiding these.

**Formatting failures**
- ❌ Multi-column layouts → parsers read columns out of order
- ❌ Tables for content → most ATS read tables as scrambled raw text
- ❌ Headers/footers containing substantive info → often skipped entirely
- ❌ Text inside images, icons, or graphics → invisible to parsers
- ❌ Unusual section titles ("What I've Achieved," "My Story") → use the standard names: Summary, Experience, Skills, Education, Projects
- ❌ Fancy fonts, bright colors → may pass parsing but lower the human-reviewer score
- ❌ Inconsistent date formats → "Spring 2022" vs "Mar 2022" can break date parsing

**Content failures**
- ❌ Skills mentioned only in narrative paragraphs and not in a Skills section → parser misses them
- ❌ Missing keyword match for must-haves → low fit score regardless of actual fit
- ❌ Acronyms only (or expansions only) when both are common → use both at least once, e.g. "Go-to-Market (GTM)"

**Major ATS platforms and quirks**
- **Workday** — aggressive parser, dislikes graphics, prefers strict chronological order
- **Greenhouse** — kinder parser, but human-driven scorecards dominate the decision
- **Lever** — similar to Greenhouse
- **Ashby** — newer, generally well-behaved with most clean formats
- **Taleo** — older, still common at large enterprises, brittle — use the most boring formatting possible
- **iCIMS** — common at large enterprises, prefers minimal formatting

**Default-safe formatting**
- One column, left-aligned
- Standard sans-serif font (Inter, Calibri, Arial)
- Plain bullets (•) not custom characters
- Dates in "Mon YYYY – Mon YYYY" format
- No graphics, no photos, no icons (even Unicode icons)
- Save as `.docx` for submission; keep a `.pdf` for direct sending

---

## Tailoring procedure (~10 minutes per JD)

The original doc had both "1 minute" and "10-12 minutes" — the real number is ~10 once you're practiced. If you're rushing 1-minute passes, you're skipping the defendability check, and that's where misses happen.

1. **JD intake** (~3 min) — see template above
2. **Map must-haves to master_cv.md** (~2 min) — for each must-have, note which master bullets are the strongest evidence
3. **Draft three core sections** (~4 min) — Summary, Skills, Experience, in that order, following section rules below
4. **Self-audit** (~1 min) — run the checklist

If a JD is unusually complex (e.g., a senior role with very specific domain stack), allow up to 15 min and don't compromise the audit.

---

## Section rules

### Summary (3-5 lines)

Formula: **Title/scope + 3-4 JD verbs/skills echoed naturally + one proof metric + target domain fit.**

Do:
- → Lead with the targeted role title, not a generic descriptor
- → Mirror 3-4 of the JD's verbs naturally in normal sentences
- → Include exactly one proof line (the strongest defendable metric)

Don't:
- → No generic adjectives ("hard-working," "passionate")
- → No tool/skill list — save that for Skills
- → No "passionate about" anything

### Skills (grouped, ranked, ATS-friendly)

Structure as three groups:

1. **Core** — the JD must-haves you have, in roughly the order they appear in the JD
2. **Supporting** — relevant tools you use that aren't must-haves but reinforce fit
3. **Familiar** — only include if the JD specifically names them; otherwise omit

Annotate with proficiency (`Expert` / `Proficient` / `Familiar`) only when it adds clarity. Don't annotate every item.

Rule: if it's not in the JD or you can't defend it live, cut it or move it to Familiar. Don't list outdated tools (FoxPro, Delphi, etc.) — they don't add value and can signal "out of date" to reviewers.

### Experience (proof, not tasks)

One-bullet formula: **Verb | Scope | Tech/How | Outcome**

> Verb (action) + what you built/improved + how (tools/scale) + measurable outcome (%, time, cost, reliability)

3-6 bullets per role for the most relevant 2-3 roles. Older or less relevant roles collapse to 1-2 bullets. Roles older than ~10 years can be omitted or shown as a single line.

**Before/after examples**

Before: "Worked on APIs for the ordering system"
After: "Built order API for 300+ stores on .NET 8 + Postgres, cutting p95 from 420ms to 240ms (-43%) and raising uptime to 99.95%."

Before: "Responsible for Kafka consumers"
After: "Designed Kafka consumers with exactly-once semantics; reduced duplicate events by 99.7% and cut reprocess time from hours to <10 min."

Before: "Helped migrate to Azure"
After: "Led lift-and-shift to Azure AKS with blue-green deploys, trimming infra spend 22% and enabling daily releases (from weekly)."

### Projects (optional, lane-dependent)

Include when applying to builder-PM or technical roles. List 3-5 projects max, each one line: name + one-sentence what + stack + outcome/scope.

### Education

Bottom of CV. Single line per degree. No GPA unless asked or recent grad.

---

## Self-audit checklist

Before sending, every tailored CV passes these checks:

- [ ] Every must-have from the JD has at least one matching bullet (or is explicitly flagged as a gap)
- [ ] No claim or skill not present in `master_cv.md`
- [ ] No item from `master_cv.md` § Anti-claims
- [ ] Every bullet has a quantifier OR is flagged as `[needs metric]`
- [ ] No generic adjectives ("hard-working," "results-driven," "passionate")
- [ ] No keyword wall — Skills section reads as grouped, not dumped
- [ ] Section titles are standard (Summary, Experience, Skills, Education, Projects)
- [ ] One column, no content tables, no graphics
- [ ] Dates in consistent format (Mon YYYY – Mon YYYY)
- [ ] One page (or two if seniority justifies)
- [ ] Defendability: every bullet survives "tell me more about this"

---

## Metric gap flag

If a tailored bullet has no quantifier, the methodology marks it inline as `[needs metric]`. Two outcomes:

1. **Dig up the number** — check old reviews, project docs, ask former colleagues. Add to `master_cv.md` § Metrics inventory once confirmed.
2. **Downgrade the bullet** — if no number exists, rephrase to focus on what was built and how, without false precision.

Don't ship a CV with un-resolved `[needs metric]` markers. Either fill them or rewrite.

---

## After the application

Log the application in `outcome_tracker.md`. After 20-30 entries, patterns become visible — which variants convert, which JD types respond, which bullets are doing the work. This is the only way to know if the methodology is actually working or just feels good.

---

## Closing principle

Be clearer, not louder. Fit-first, honest tailoring beats volume every time. None of this guarantees a shortcut — what it does is raise the odds that a qualified human gets seen by a human.
