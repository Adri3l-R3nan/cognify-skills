# Cognify Agent Skills

![Agent Skills](https://img.shields.io/badge/Agent_Skills-FF6B35?style=for-the-badge)
![Claude](https://img.shields.io/badge/Claude-D4A574?style=for-the-badge&logo=anthropic&logoColor=white)
![Cognify](https://img.shields.io/badge/Cognify-5856D6?style=for-the-badge)
![License](https://img.shields.io/badge/License-grey?style=for-the-badge)
![Apache 2.0](https://img.shields.io/badge/Apache_2.0-lightgrey?style=for-the-badge)

19 business operations skills for AI agents. Built to the [Agent Skills open standard](https://agentskills.io).

## Skills

### Strategy & Analysis
| Skill | What It Does |
|-------|-------------|
| **[cognify-workflow-analysis](.github/skills/cognify-workflow-analysis/)** | Analyzes business workflows, scores pain points, matches automation patterns, calculates ROI with payback period |
| **[business-roi-analyzer](.github/skills/business-roi-analyzer/)** | ROI, NPV, IRR, and payback analysis for any business investment with scenario modeling |
| **[competitive-intelligence](.github/skills/competitive-intelligence/)** | Competitive analysis with positioning matrices, feature comparison, SWOT, and battle cards |
| **[strategic-planning-facilitator](.github/skills/strategic-planning-facilitator/)** | Facilitates strategic planning sessions — SWOT, OKRs, initiative prioritization, and execution roadmaps |
| **[operations-audit](.github/skills/operations-audit/)** | Comprehensive SMB operations audit across 8 functional areas with scoring and 90-day action roadmap |

### Sales & Revenue
| Skill | What It Does |
|-------|-------------|
| **[client-discovery-interview](.github/skills/client-discovery-interview/)** | Structured discovery interviews — problem identification, stakeholder mapping, qualification scoring |
| **[sales-pipeline-analyzer](.github/skills/sales-pipeline-analyzer/)** | Pipeline health diagnostics, conversion rate analysis, bottleneck scoring, and revenue forecasting |
| **[abm-campaign-builder](.github/skills/abm-campaign-builder/)** | Account-Based Marketing campaigns — ICP definition, buying committee mapping, outreach sequences |
| **[seo-strategy-analyzer](.github/skills/seo-strategy-analyzer/)** | SEO audit, keyword research, content gap analysis, and prioritized action plan with traffic projections |

### Finance & Risk
| Skill | What It Does |
|-------|-------------|
| **[budget-planning-assistant](.github/skills/budget-planning-assistant/)** | Annual and project budget planning with variance analysis, scenario modeling, and approval workflows |
| **[vendor-evaluation-scorecard](.github/skills/vendor-evaluation-scorecard/)** | Weighted vendor comparison — scoring matrix, TCO analysis, risk assessment, and decision documentation |
| **[risk-assessment-matrix](.github/skills/risk-assessment-matrix/)** | Enterprise risk identification, scoring, heat mapping, and mitigation planning |

### People & HR
| Skill | What It Does |
|-------|-------------|
| **[hiring-decision-analyzer](.github/skills/hiring-decision-analyzer/)** | Hire vs. contract vs. automate analysis — total cost of employment, decision matrix, break-even |
| **[employee-onboarding-designer](.github/skills/employee-onboarding-designer/)** | Structured onboarding programs — 30/60/90 plans, training schedules, milestone tracking |
| **[change-management-planner](.github/skills/change-management-planner/)** | Change management planning — stakeholder analysis, communication plans, adoption tracking |

### Customer & Service
| Skill | What It Does |
|-------|-------------|
| **[customer-success-playbook](.github/skills/customer-success-playbook/)** | CS programs — health scoring, intervention playbooks, QBR frameworks, churn early warning systems |
| **[customer-feedback-analyzer](.github/skills/customer-feedback-analyzer/)** | Feedback analysis — sentiment scoring, theme extraction, prioritized improvement recommendations |

### Operations & Process
| Skill | What It Does |
|-------|-------------|
| **[process-documentation](.github/skills/process-documentation/)** | SOPs, workflow diagrams, decision trees, and runbooks — publication-ready process documentation |
| **[meeting-agenda-optimizer](.github/skills/meeting-agenda-optimizer/)** | Meeting design — structured agendas, time allocation, decision frameworks, and action item tracking |

## Quick Start

### Claude Code
```bash
# Clone and add skills directory
git clone https://github.com/Yarmoluk/cognify-skills.git
# Point Claude Code to the skills:
# Settings → Skills → Add skill path → /path/to/cognify-skills/.github/skills/
```

### Any Skills-Compatible Agent
These skills follow the [agentskills.io](https://agentskills.io) open standard and work with Claude Code, Claude.ai, VS Code, Cursor, OpenAI Codex, Gemini CLI, and 20+ other platforms.

Place the skill folders in your project's `.github/skills/` directory.

## What Makes These Different

- **Quantified outputs** — Every recommendation includes specific dollar amounts, not vague "significant savings"
- **Scoring rubrics** — Structured frameworks that produce consistent, reproducible analysis
- **Pattern-matched** — Solutions drawn from a catalog of proven automation patterns with real benchmarks
- **Industry-aware** — Construction, healthcare, legal, beauty, retail, and professional services context built in
- **ROI-first** — Payback period and annual ROI calculated for every recommendation
- **Reference data included** — Industry benchmarks, formula libraries, and framework references bundled with each skill

## Use Cases

- **Consultants**: Run structured discovery calls and produce professional deliverables
- **Agency owners**: Scope automation projects with accurate pricing and timelines
- **Founders**: Identify where AI saves the most time in your operations
- **Sales teams**: Build competitive intelligence, pipeline diagnostics, and battle cards
- **Marketers**: Plan SEO strategy and ABM campaigns with data-driven frameworks
- **Operations leaders**: Audit processes, document workflows, and plan organizational change
- **Finance teams**: Build business cases, evaluate vendors, and assess risk

## Sample Output

These skills produce structured deliverables with specific dollar amounts, not vague recommendations.

**From [cognify-workflow-analysis](examples/workflow-analysis-tusk-builders.md)** — a commercial construction company:

> **Pain Point:** PM spends 2.5 hrs/day sorting 120 emails manually
> **Pattern Match:** Email Triage & Routing → AI classifier + rules engine
> **Result:** $7,740/month net value, 369% ROI, 6-week payback

**From [competitive-intelligence](examples/competitive-intel-brief.md)** — a SaaS monitoring company:

> **Finding:** Flat-rate pricing saves customers 35-53% vs. primary competitor at 50 hosts
> **Battle Card:** "Have you calculated what your bill will be at 3x your current hosts?"
> **Action Plan:** 5 prioritized moves with owners and deadlines

Full example outputs: [examples/](examples/)

## Related

| Resource | Description |
|----------|-------------|
| [Custom Skill Developer Guide](https://yarmoluk.github.io/custom-skill-developer/) | Learn to build your own Agent Skills — 17 chapters, 55K words |
| [Skill Quality Analyzer](https://github.com/Yarmoluk/skill-quality-analyzer) | Audit Agent Skills against the agentskills.io spec |
| [agentskills.io](https://agentskills.io) | The open standard specification |
| [anthropics/skills](https://github.com/anthropics/skills) | Anthropic's official example skills |

## License

Apache 2.0
