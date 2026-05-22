# Outcome Tracker

Log every application. After 20-30 entries, patterns become visible — which variants convert, which JD types respond, which bullets are doing the work. Without this, the methodology is unfalsifiable.

---

## Application log

| Date | Company | Role | Lane | JD intent | Variant | Match score | Cover letter? | Outcome | Notes |
|------|---------|------|------|-----------|---------|-------------|---------------|---------|-------|
|      |         |      |      |           |         |             |               |         |       |

---

## Outcome values

- `no response` — default after 3 weeks of silence
- `auto-reject` — within 48h, ATS or recruiter screen
- `screen scheduled` — recruiter call booked
- `interview` — past recruiter screen, into hiring manager / panel
- `offer`
- `withdrawn` — you pulled out

---

## Variant naming convention

Format: `jd-{lane}-{intent}-{date}.md`

Examples:
- `jd-bd-gtm-2026-05-21.md` — BD lane, GTM intent, applied 21 May 2026
- `jd-builder-shipping-2026-05-23.md` — Builder-PM lane, shipping-speed intent

This way each tailored CV is traceable to its outcome.

---

## Patterns to track

After ~20 applications, write up observations here.

### Lane performance
- Lane A (BD/Strategy): [response rate, interview rate, offer rate]
- Lane B (Builder-PM): [response rate, interview rate, offer rate]
- Lane C (founder-adjacent): [response rate, interview rate, offer rate]

### Intent performance
Which JD intents respond best to your background? (e.g., GTM intent might convert better than reliability intent if you're emphasizing Pyme/Sunrise.)

### Bullet effectiveness
Which `master_cv.md` bullets show up in CVs that got interviews vs. those that didn't? Bullets that consistently appear in winning variants are worth investing in (better metrics, sharper phrasing).

### Time-to-response by company size
- Startup (<50): typical days
- Scale-up (50-500): typical days
- Enterprise (500+): typical days

### Rejection patterns
When rejected with feedback, log the stated reason. Look for repeats — they signal real gaps in the master file or positioning.

---

## When the methodology isn't working

If after 20+ honest applications the response rate is <10%, something is off. Diagnose in this order:

1. **Lane misfit** — are you applying to roles where you're below the 70-80% must-have bar?
2. **JD intent missed** — are you reading the JDs correctly? Re-run a few through the classifier with fresh eyes.
3. **Master file thin** — are the metrics in `master_cv.md` strong enough? Are the [TODO] markers blocking you?
4. **Format/ATS issues** — run one variant through Jobscan or Resume Worded to check ATS parsing.
5. **Outbound channels** — is the bottleneck the CV, or the application channels themselves? (Direct outreach often outperforms job-board applications regardless of CV quality.)

---

## Quick log template

When in a hurry, just paste this and fill in:

```
- date:
- company:
- role:
- lane: A / B / C
- jd_intent:
- variant_file:
- match_score:
- cover_letter: y/n
- outcome: [pending]
- notes:
```
