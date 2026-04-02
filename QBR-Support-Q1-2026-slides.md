# Support QBR — Jan to Mar 2026

---
---

## Slide 1: Quarter at a glance

**199 tickets resolved** this quarter | 55 still open/pending

| | Q4 2025 | Q1 2026 |
|---|---|---|
| Tickets resolved | 254 | 199 |
| Overall SLA compliance | 78.3% | **85.9%** |
| Resolved within 1 day | 30.7% | **32.2%** |
| Urgent ticket avg resolution | 3.9 days | **1.5 days** |
| Open/pending at quarter end | 11 | 55 |

### SLA compliance by priority

| Priority | Tickets | Resolution SLA | First Response SLA | Avg Resolution |
|---|---|---|---|---|
| **Urgent** | 46 | 52.2% | 60.9% | **1.5 days** |
| **High** | 125 | **96.8%** | 50.4% | 12.7 days |
| **Medium** | 22 | **90.9%** | 72.7% | 26.6 days |
| **Low** | 6 | **100%** | 83.3% | 6.6 days |

**Reading this:** High/Medium/Low tickets have strong resolution SLA (91-100%). Urgent tickets resolve the fastest (1.5 days avg) but only 52% meet SLA — because the SLA window for Urgent is tighter. First response is weakest for High priority (50.4%) — these are the bulk of tickets (125) and many don't get a first response on time.

Monthly: Jan 54 | Feb 52 | Mar 93

30 of the 199 were older backlog tickets from previous quarters — the team actively cleared pending debt.

---
---

## Slide 2: What went well

### SLA compliance improved across the board

| Metric | Q4 | Q1 | Improvement |
|---|---|---|---|
| Resolution SLA | 78.3% | 85.9% | +7.6pp |
| Urgent resolution | 3.9 days | 1.5 days | 62% faster |
| Resolution violations | 20.8% | 14.1% | -6.7pp |
| First response violations | 54% | 42.7% | -11.3pp |

### Why things improved

- **AI usage increased** — team used AI tools and the Avni skill folder to draft responses, summarize ticket history, and resolve faster
- **Ticket complexity was lower this quarter** — fewer deep technical issues compared to Q4
- **Goonj tickets dropped 53%** (34 to 16) — one of the highest volume orgs stabilized
- **More team capacity** — additional team members contributing to resolutions

### Backlog cleared

The team didn't just handle incoming tickets — they went back and resolved **30 older tickets** from previous quarters that were sitting open. This is proactive cleanup.

---
---

## Slide 3: What didn't go well

### 1. The "unassign and pick up" experiment didn't work

We tried a process where tickets were unassigned and people would pick them up. In practice, **people hesitated to pick up tickets where conversations had already happened**. The originally assigned person ended up taking it back anyway. Net result: delays, no real distribution improvement.

### 2. Too many RCA misses

Root cause analysis was missed on several tickets — likely because new team members joined and weren't yet trained on the RCA tagging process.

### 3. Still dependent on product team

**23 product interventions + 19 product bugs = 42 tickets (21%)** that the support team couldn't resolve alone. This dependency adds wait time and back-and-forth.

### 4. Launchpad NGO consulting ate bandwidth

Newly onboarded Launchpad clients (Purna Clinic, Gubbachi) needed hand-holding beyond standard support. This consulting work competed with ticket resolution time.

### 5. Purna Clinic's small-ticket pattern

Purna Clinic raised **12 tickets** — mostly small implementation changes (7 tagged). Avg resolution: **14.6 working days** (slow because each was small but numerous). Normally we charge if a request crosses 2 hours, but since each ticket is small individually, we don't. This needs a billing/process review.

### 6. Field visit catchup lag

When team members return from field visits, they play catchup with accumulated tickets — causing spikes in response delay.

---
---

## Slide 4: Where the effort went

### 66% of tickets were preventable

| Category | Tickets | % | How to prevent |
|---|---|---|---|
| Implementation changes | 62 | 31% | Self-serve admin tools |
| User knowledge gaps | 37 | 19% | FAQs, training, docs |
| No-op / Zombie | 24 | 12% | Better intake triage |
| Can be product feature | 9 | 5% | Product investment |
| **Total preventable** | **132** | **66%** | |

### Top 5 companies (48% of all tickets)

| Company | Tickets |
|---|---|
| APF | 31 |
| Animedh | 22 |
| Goonj | 16 |
| JSS MP Sickle Cell | 15 |
| Purna Clinic | 12 |

### Top tags

| Tag | Count |
|---|---|
| Implementation change | 62 |
| User Knowledge | 37 |
| Product intervention | 23 |
| Product bug | 19 |
| No-op | 17 |
| Implementation bug | 10 |

### The one number that matters

**62 implementation change tickets** = nearly 1 every working day. These are config changes that orgs cannot do themselves. If we build self-serve tooling for even the top 10 patterns, we free up ~30% of support capacity.

---
---

## Slide 5: Goals for next 3 months (Apr–Jun 2026)

### 5 commitments

| # | Goal | How | Target |
|---|---|---|---|
| 1 | **Finalize support SOP** | Document the end-to-end ticket lifecycle, assignment rules, escalation paths, RCA process | April |
| 2 | **Add FAQs for new NGOs** | Cover top 20 user knowledge gaps + common implementation changes as self-serve articles | 20+ articles by June |
| 3 | **Reduce open/pending backlog** | Clear the 55 open tickets. Weekly backlog review every Monday. | <15 open at quarter end |
| 4 | **Close long-due tickets** | Identify tickets open >30 days, contact requester, close if no response in 7 days | Process live by April |
| 5 | **Auto-answer common questions** | Set up FAQ-based auto-responses for User Knowledge and Implementation Change tags via Freshdesk | Deflect 30+ tickets |

### What we'll stop doing

- The "unassign and pick up" experiment — going back to clear ownership from day one
- Treating all tickets as equal priority — triage urgency properly at intake

### What we'll continue

- AI-assisted support workflows
- Clearing backlog alongside current tickets
- Tagging every ticket by root cause

### What we need from other teams

| From | What | Why |
|---|---|---|
| Product | Act on 23 intervention requests + 19 bugs | 42 tickets (21%) blocked on product |
| Product | Build self-serve for top impl changes | 62 tickets/quarter = highest volume |
| Implementation | Onboarding playbook for new orgs | Purna Clinic + Gubbachi needed heavy hand-holding |
| Leadership | Decide on Purna Clinic billing model | Small-ticket pattern isn't sustainable without charging |

---

*Data: Freshdesk API + CSV export (199 resolved tickets, Jan–Mar 2026)*
