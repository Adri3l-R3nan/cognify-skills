# Workflow Analysis: Tusk Builders

**Client:** Tusk Builders (commercial construction, 45 employees)
**Prepared:** February 2026
**Skill used:** cognify-workflow-analysis

---

## Executive Summary

Tusk Builders loses an estimated **$9,360/month** to manual email triage, disconnected project communication, and redundant status reporting. A three-phase automation program costing $1,620/month in tooling would recover **$7,740/month in net value** — a **369% ROI** with a **6-week payback period**.

---

## Current State Assessment

### Pain Points Identified

| Pain Point | Frequency (1-5) | Impact (1-5) | Solvability (1-5) | Priority Score |
|------------|:---:|:---:|:---:|:---:|
| Email overload — PM spends 2.5 hrs/day sorting project emails | 5 | 4 | 5 | 100 |
| Status reporting — 3 people compile the same weekly report manually | 4 | 3 | 5 | 60 |
| Bid follow-up — estimates sent but no systematic follow-up | 3 | 5 | 4 | 60 |
| Change order tracking — verbal approvals, no paper trail | 4 | 4 | 3 | 48 |
| Subcontractor scheduling — phone/text coordination, frequent conflicts | 4 | 3 | 3 | 36 |

### Workflow Mapping

**Email triage workflow (current):**
```
Inbox (avg 120 emails/day)
  → PM manually reads each email
  → Forwards to relevant project folder or person
  → Flags urgent items
  → Responds to RFIs inline
  → Time: 2.5 hours/day × $65/hr loaded = $812/week
```

**Weekly status reporting (current):**
```
Monday: PM pulls data from 3 systems (Procore, QuickBooks, shared drive)
Tuesday: Office manager compiles subcontractor updates via phone
Wednesday: Owner reviews, edits, sends to clients
  → 3 people × 3 hours each × $55 avg loaded rate = $495/week
```

---

## Value Hypothesis

### Automation Pattern Match

| Pain Point | Pattern | Tool Category | Confidence |
|------------|---------|---------------|:---:|
| Email overload | Email Triage & Routing | AI email classifier + rules engine | High |
| Status reporting | Reporting Automation | Dashboard + scheduled PDF export | High |
| Bid follow-up | Lead Qualification & Nurture | CRM sequence automation | Medium |

### Financial Projection

**Monthly savings breakdown:**

| Automation | Hours Saved/Month | Loaded Rate | Monthly Value |
|------------|:-:|:-:|:-:|
| Email triage AI | 42 hrs | $65/hr | $2,730 |
| Automated status reports | 36 hrs | $55/hr | $1,980 |
| Bid follow-up sequences | — | — | $4,650 (est. 1 additional win/quarter at $13,950 margin) |
| **Total monthly value** | | | **$9,360** |

**Monthly cost:**

| Tool | Monthly Cost |
|------|:-:|
| Email AI classifier (custom GPT + Zapier) | $120 |
| Dashboard platform (Databox or similar) | $200 |
| CRM automation (HubSpot Starter) | $300 |
| Implementation amortized (12 months) | $1,000 |
| **Total monthly cost** | **$1,620** |

---

## Future State Design

### Email triage (automated):
```
Inbox (120 emails/day)
  → AI classifier categorizes by project, urgency, type (RFI/submittal/schedule/billing)
  → Auto-routes to project channel in Slack or Teams
  → Flags RFIs with >48hr response deadline
  → PM reviews pre-sorted queue: 25 minutes/day (down from 2.5 hours)
```

### Status reporting (automated):
```
Friday 4pm: Dashboard auto-pulls from Procore + QuickBooks
  → Generates PDF report per active project
  → Emails to client contacts on distribution list
  → Owner reviews exceptions only
  → Time: 20 minutes/week total (down from 9 person-hours)
```

### Bid follow-up (automated):
```
Estimate sent → CRM logs event
  → Day 3: Automated check-in email
  → Day 7: PM gets task to call
  → Day 14: Second follow-up with case study
  → Day 21: Final touch — "still interested?" with easy reply options
  → No lead falls through the cracks
```

---

## Implementation Timeline

| Phase | Scope | Duration | Investment |
|-------|-------|:--------:|:----------:|
| **Phase 1** | Email triage automation | Weeks 1-3 | $4,500 |
| **Phase 2** | Reporting dashboard | Weeks 4-6 | $3,500 |
| **Phase 3** | CRM bid follow-up sequences | Weeks 7-10 | $4,000 |
| **Total** | | **10 weeks** | **$12,000** |

---

## Success Metrics

| Metric | Current | Target (90 days) | Measurement |
|--------|:-------:|:-----------------:|-------------|
| PM email time per day | 2.5 hrs | 0.4 hrs | Time tracking |
| Weekly report prep time | 9 person-hrs | 0.3 person-hrs | Time tracking |
| Bid follow-up rate | ~40% | 100% | CRM tracking |
| Estimates converted to contracts | 18% | 23% | QuickBooks |
| Monthly operational savings | $0 | $7,740 net | Finance review |

---

## ROI Summary

| Metric | Value |
|--------|:-----:|
| Monthly gross benefit | $9,360 |
| Monthly tooling cost | $620 |
| Monthly implementation (amortized 12mo) | $1,000 |
| **Monthly net value** | **$7,740** |
| **Annual net value** | **$92,880** |
| **Simple ROI** | **369%** |
| **Payback period** | **6 weeks** |
