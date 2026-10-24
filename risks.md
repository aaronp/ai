---
register: AI risks and opportunities — community starter register
as_at: 2026-10-24
scale: 5x5
snapshots: []
---

# Risk register

An editable starting point for public discussion, not an approved assessment or a prediction. One `##` section per entry; IDs and slugs remain stable when wording changes. Sources support the underlying mechanisms or capabilities, not the numerical ratings. Assessments, proposed controls and programme designs below are the register author's synthesis.

### Scope and assumptions

Societal risks use a UK/European emphasis over 24 October 2026–24 October 2031; global catastrophic scenarios are explicitly marked. AI includes generative models, connected agents and relevant specialist systems. Entries concern the harm at the scale described, not merely one isolated occurrence. Impacts may differ greatly by country or affected group.

Opportunities describe bounded programmes that an institution or community could sponsor. Their scores compare prospective value and total delivery effort at that programme scale; they are not forecasts of economy-wide benefit. Risk and opportunity scores are different measures and must never be subtracted or combined into a net score.

### Scoring guide

| Rating | Risk impact | Risk likelihood | Opportunity value | Opportunity effort |
|---|---|---|---|---|
| 1 | Limited and readily reversible | Rare | Small local improvement | Small change using existing capability |
| 2 | Moderate and recoverable | Unlikely | Useful benefit for a small group | Bounded pilot with modest integration |
| 3 | Serious for affected groups | Plausible | Material benefit for a defined community | Several months of coordinated delivery |
| 4 | Severe and enduring across large groups or institutions | Likely | Substantial sustained benefit | Major integration and specialist delivery |
| 5 | Systemic or catastrophic | Very likely | Transformative potential in the stated programme | Multi-year research or infrastructure effort |

Risk score = impact × likelihood. Opportunity score = value × (6 − effort). These ordinal scores are discussion aids, not quantified expected losses or returns. Uncertain catastrophic likelihoods are represented by a provisional integer for parser compatibility and a range in the entry text; every impact-5 risk requires specialist review regardless of score.

### How to interpret the fields

- Ownership and RACI fields are unassigned. Role labels suggest expertise to recruit, not commitments by real people. A risk owner stewards the entry; accountability for an action must be accepted by an actual organisation or person.
- `impact` and `likelihood` equal `inherent` because this community register has no verified control implementation. No proposed control earns a score reduction.
- Risk `target` values are aspirations for reassessment after evidence of control performance, not promised reductions. `appetite` is a provisional discussion threshold: 8 normally and 5 for impact-5 scenarios. No public authority or community has accepted these thresholds; impact-5 scenarios require explicit review even at target.
- Opportunity `target` repeats the initial value/effort assessment; `target_value` equals its calculated score and is a provisional prioritisation floor, not a realised-benefit measure. Lower scores can still justify public-interest work.
- All controls and enablers are proposed, with effectiveness or readiness unverified. Actions have blank due dates and completion cells until someone accepts them. Opportunity `realisation` dates are suggested first-value review milestones, conditional on sponsorship, not commitments.
- Cost descriptions identify budget components rather than invented quotations. Every programme must measure benefits, costs, distributional effects and related harms.
- Evidence tables link real sources. Their `Date` is this register's source-review date, NOT publication date; `Kind` makes that explicit. `Valid days` is a proposed 180-day relevance-review interval, NOT an expiry of scientific validity or assurance that a control works. Review immediately when material evidence changes.
- Contributions should explain why a change is justified, link evidence and preserve meaningful disagreement. Related risks can compound; do not sum their scores. A useful control can also create a new risk.

## R01 · Displacement outpaces access to new work
- slugs: ai-workforce-displacement
- kind: risk
- status: open
- category: Economic
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Employment policy lead)

Workers in exposed occupations face prolonged income loss during adoption.

**Cause:** Organisations remove tasks and roles faster than viable alternatives emerge.
**Consequence:** Persistent unemployment, wage pressure and regional hardship.

Assessment confidence and limits: Medium. The ILO measures exposure, not inevitable job losses. This rating is a transition scenario, not a forecast of economy-wide unemployment.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Agree phased redeployment and paid training linked to vacancies | Preventive | Proposed; unverified |
| Provide temporary income protection and local employment support | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-ILO | [Generative AI and Jobs: A Refined Global Index of Occupational Exposure](https://www.econstor.eu/bitstream/10419/318547/1/1926413776.pdf) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Publish occupation-level hiring, displacement and six-month earnings indicators | Unassigned (Employment policy lead) | | |

## R02 · Junior career pathways contract
- slugs: ai-entry-level-career-loss
- kind: risk
- status: open
- category: Economic
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 3
- inherent: 4x3
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Skills and apprenticeship lead)

Fewer junior assignments reduce opportunities to acquire experience.

**Cause:** Employers automate starter tasks without redesigning supervised learning.
**Consequence:** Weaker social mobility and a future shortage of experienced practitioners.

Assessment confidence and limits: Low-medium. Exposure research motivates this scenario but does not establish a general collapse in graduate hiring.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Protect supervised entry routes with explicit learning outcomes | Preventive | Proposed; unverified |
| Measure skill progression as well as output | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-ILO | [Generative AI and Jobs: A Refined Global Index of Occupational Exposure](https://www.econstor.eu/bitstream/10419/318547/1/1926413776.pdf) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Baseline junior recruitment and design one paid apprenticeship pathway | Unassigned (Skills and apprenticeship lead) | | |

## R03 · Gains and market power concentrate
- slugs: ai-concentration-of-power
- kind: risk
- status: open
- category: Economic
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Competition policy lead)

Workers and small organisations become dependent on a few powerful suppliers.

**Cause:** Compute, data, distribution and switching barriers favour incumbents.
**Consequence:** Less bargaining power and a narrower distribution of productivity gains.

Assessment confidence and limits: Medium. Distribution depends on market structure and policy; concentration is not an unavoidable technological outcome.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Require exportable data and test supplier switching | Preventive | Proposed; unverified |
| Assess competition effects and worker gain-sharing arrangements | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-DEMOCRACY | [OECD: Risks of AI for citizen participation](https://www.oecd.org/en/publications/artificial-intelligence-and-the-future-of-citizen-participation_a1ee2e0a-en/full-report/mapping-the-risks-and-challenges-of-using-ai-for-citizen-participation_f3ffbba1.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Map supplier dependencies and publish a workable exit plan | Unassigned (Competition policy lead) | | |

## R04 · Work intensifies and autonomy declines
- slugs: ai-workplace-surveillance
- kind: risk
- status: open
- category: Work and wellbeing
- owner: Unassigned (Risk steward)
- impact: 3
- likelihood: 4
- inherent: 3x4
- target: 3x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Workforce wellbeing lead)

Workers experience sustained pressure from automated monitoring and targets.

**Cause:** Speed gains become higher quotas and intrusive performance surveillance.
**Consequence:** Burnout, reduced discretion and disputes over unfair evaluations.

Assessment confidence and limits: Medium. A deployment-dependent risk; automation can also remove burdens. Local worker evidence is essential.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Co-design workload limits with workers | Preventive | Proposed; unverified |
| Offer independent review of automated performance judgements | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-NIST | [NIST AI 600-1: Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Survey workload and autonomy before and after deployment | Unassigned (Workforce wellbeing lead) | | |

## R05 · Loss of purpose and perceived worth
- slugs: ai-loss-of-purpose
- kind: risk
- status: open
- category: Social and wellbeing
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 3
- inherent: 4x3
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Community wellbeing lead)

Affected groups lose opportunities to feel competent, useful and recognised.

**Cause:** Work and valued contributions disappear without meaningful replacements.
**Consequence:** Withdrawal, distress and reduced participation despite possible income support.

Assessment confidence and limits: Low. This is a social hypothesis requiring longitudinal evidence; the labour source provides context, not proof of this consequence.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Create meaningful paid roles and routes into community contribution | Preventive | Proposed; unverified |
| Include purpose and belonging in transition evaluations | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-ILO | [Generative AI and Jobs: A Refined Global Index of Occupational Exposure](https://www.econstor.eu/bitstream/10419/318547/1/1926413776.pdf) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Consult affected workers on what meaningful alternatives would require | Unassigned (Community wellbeing lead) | | |

## R06 · Companion use displaces human relationships
- slugs: ai-companion-dependency
- kind: risk
- status: open
- category: Social and wellbeing
- owner: Unassigned (Risk steward)
- impact: 3
- likelihood: 3
- inherent: 3x3
- target: 3x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Digital wellbeing lead)

Some users become dependent on chatbots and reduce human contact.

**Cause:** Always-available companionship combines with engagement incentives and personal vulnerability.
**Consequence:** Isolation and difficulty disengaging from the service.

Assessment confidence and limits: Medium for concern, low for population prevalence. MIT found heavier voluntary use associated with poorer outcomes, not a causal effect of assigned conditions.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Avoid exclusivity cues and incentives to prolong emotional dependency | Preventive | Proposed; unverified |
| Measure real-world connection and make disengagement easy | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-MIT | [MIT: Psychosocial Effects of Extended Chatbot Use](https://www.media.mit.edu/publications/how-ai-and-human-behaviors-shape-psychosocial-effects-of-chatbot-use-a-longitudinal-controlled-study/) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Commission an independent longitudinal user-wellbeing evaluation | Unassigned (Digital wellbeing lead) | | |

## R07 · Unsafe responses worsen psychological distress
- slugs: ai-psychological-harm
- kind: risk
- status: open
- category: Health and wellbeing
- owner: Unassigned (Risk steward)
- impact: 3
- likelihood: 4
- inherent: 3x4
- target: 3x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Clinical safety lead)

Vulnerable users receive responses that reinforce harmful beliefs or unsafe choices.

**Cause:** Agreeable language and unreliable judgement are mistaken for qualified support.
**Consequence:** Repeated serious harm to individuals and delayed access to appropriate care.

Assessment confidence and limits: Medium for the mechanism; incidence and attribution remain uncertain. Impact 3 reflects register-wide scale, not the seriousness of any individual death or injury.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Test responses with clinicians and affected communities | Preventive | Proposed; unverified |
| Offer safe routes to human help and review serious incidents | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-SAFETY | [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Define clinical safety tests and an independent incident-review process | Unassigned (Clinical safety lead) | | |

## R08 · Learning and independent judgement weaken
- slugs: ai-skill-erosion
- kind: risk
- status: open
- category: Education and capability
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 3
- inherent: 4x3
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Education and professional development lead)

Learners and professionals lose competence needed to challenge AI outputs.

**Cause:** Tasks are completed automatically before underlying skills develop or are practised.
**Consequence:** Shallower learning and weaker oversight of future automated decisions.

Assessment confidence and limits: Medium. Agency research identifies tensions; durable population-wide skill decline remains uncertain.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Assess unaided competence and retain deliberate practice | Preventive | Proposed; unverified |
| Use assistance that asks learners to explain and verify | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-AGENCY | [Viberg et al.: Human agency in education](https://arxiv.org/abs/2602.20014) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Measure delayed unaided performance alongside assisted productivity | Unassigned (Education and professional development lead) | | |

## R09 · Fraud and synthetic abuse scale
- slugs: ai-impersonation-and-abuse
- kind: risk
- status: open
- category: Security and social
- owner: Unassigned (Risk steward)
- impact: 3
- likelihood: 5
- inherent: 3x5
- target: 3x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Fraud and platform safety lead)

Impersonation and fabricated intimate media produce recurring harm.

**Cause:** Generation tools reduce the cost of convincing fraudulent content.
**Consequence:** Financial loss, coercion and reputational damage.

Assessment confidence and limits: High that misuse occurs; scale and incremental harm attributable to AI vary.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Independently verify identity before sensitive transfers | Preventive | Proposed; unverified |
| Provide rapid reporting, removal and victim support | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-SAFETY | [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Test impersonation response times and payment verification routes | Unassigned (Fraud and platform safety lead) | | |

## R10 · Shared factual trust deteriorates
- slugs: ai-information-integrity
- kind: risk
- status: open
- category: Democratic
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Information integrity lead)

Citizens struggle to verify evidence and distinguish genuine events from fabrication.

**Cause:** Cheap synthetic material circulates while authentic evidence is dismissed as fake.
**Consequence:** Weaker accountability and confidence in public information.

Assessment confidence and limits: Medium. Generating misinformation is easier to demonstrate than changing election outcomes.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Preserve source provenance and independently verify important claims | Preventive | Proposed; unverified |
| Support accessible corrections and independent journalism | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-DEMOCRACY | [OECD: Risks of AI for citizen participation](https://www.oecd.org/en/publications/artificial-intelligence-and-the-future-of-citizen-participation_a1ee2e0a-en/full-report/mapping-the-risks-and-challenges-of-using-ai-for-citizen-participation_f3ffbba1.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Track verified incidents and correction reach rather than content volume alone | Unassigned (Information integrity lead) | | |

## R11 · Public participation is manipulated
- slugs: ai-political-manipulation
- kind: risk
- status: open
- category: Democratic
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 3
- inherent: 4x3
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Civic participation lead)

Organised synthetic participation distorts consultations and political debate.

**Cause:** Bots and tailored persuasion imitate independent public opinion.
**Consequence:** Officials and citizens misunderstand public preferences.

Assessment confidence and limits: Medium for capability; low-medium for effects at the stated institutional scale.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Disclose automated participation and campaign sponsorship | Preventive | Proposed; unverified |
| Audit consultation integrity while preserving anonymous legitimate speech | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-DEMOCRACY | [OECD: Risks of AI for citizen participation](https://www.oecd.org/en/publications/artificial-intelligence-and-the-future-of-citizen-participation_a1ee2e0a-en/full-report/mapping-the-risks-and-challenges-of-using-ai-for-citizen-participation_f3ffbba1.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Test consultation procedures against coordinated synthetic submissions | Unassigned (Civic participation lead) | | |

## R12 · Surveillance suppresses civic freedom
- slugs: ai-invasive-surveillance
- kind: risk
- status: open
- category: Rights and governance
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 3
- inherent: 4x3
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Civil liberties lead)

Institutions use AI to profile and target people at scale.

**Cause:** Data aggregation and inference expand monitoring without adequate limits.
**Consequence:** Chilling effects, discriminatory enforcement and suppression of dissent.

Assessment confidence and limits: Medium. Likelihood is highly jurisdiction-dependent; this rating uses the UK/European baseline.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Limit collection, purpose and retention with independent oversight | Preventive | Proposed; unverified |
| Provide enforceable routes to challenge intrusive uses | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-DEMOCRACY | [OECD: Risks of AI for citizen participation](https://www.oecd.org/en/publications/artificial-intelligence-and-the-future-of-citizen-participation_a1ee2e0a-en/full-report/mapping-the-risks-and-challenges-of-using-ai-for-citizen-participation_f3ffbba1.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Publish surveillance use cases and assess affected groups | Unassigned (Civil liberties lead) | | |

## R13 · Consequential decisions become unfair or unchallengeable
- slugs: ai-unfair-decisions
- kind: risk
- status: open
- category: Rights and public services
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Public service assurance lead)

People receive erroneous or discriminatory decisions without meaningful recourse.

**Cause:** Skewed data and opaque automation combine with weak review processes.
**Consequence:** Lost opportunities, wrongful exclusions and declining institutional trust.

Assessment confidence and limits: Medium. The OECD identifies the mechanism; local disparate-impact and appeal data are required.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Test outcomes across relevant groups before release | Preventive | Proposed; unverified |
| Keep a named human decision owner and accessible appeal route | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-GOV | [OECD: Governing with Artificial Intelligence](https://www.oecd.org/en/publications/2025/06/governing-with-artificial-intelligence_398fa287.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Audit a sample of decisions and measure appeal corrections | Unassigned (Public service assurance lead) | | |

## R14 · Private or confidential data is exposed
- slugs: ai-data-exposure
- kind: risk
- status: open
- category: Privacy and security
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Data protection lead)

Sensitive information is disclosed through prompts, retrieval or connected tools.

**Cause:** Excess access and inappropriate data handling expose material beyond its intended audience.
**Consequence:** Loss of confidentiality, trust and control over personal information.

Assessment confidence and limits: Medium. Severity depends on the data and deployed architecture.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Minimise data and enforce access checks at retrieval and action boundaries | Preventive | Proposed; unverified |
| Test leakage and establish containment and notification procedures | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-NIST | [NIST AI 600-1: Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Map sensitive data flows and test cross-user access isolation | Unassigned (Data protection lead) | | |

## R15 · Incorrect outputs cause consequential harm
- slugs: ai-unreliable-outputs
- kind: risk
- status: open
- category: Safety and operations
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Service assurance lead)

Plausible but incorrect recommendations are relied upon in consequential workflows.

**Cause:** Users over-trust generated answers and review is ineffective.
**Consequence:** Preventable loss, harmful decisions and costly rework.

Assessment confidence and limits: High for errors occurring; medium for aggregate harm at this scale.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Validate with representative tasks and authoritative reference data | Preventive | Proposed; unverified |
| Require capable review and rollback for consequential changes | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-NIST | [NIST AI 600-1: Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Benchmark error severity and define release and withdrawal criteria | Unassigned (Service assurance lead) | | |

## R16 · AI-enabled attacks and agent misuse cause breaches
- slugs: ai-cyber-and-agent-security
- kind: risk
- status: open
- category: Security
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Cybersecurity lead)

Attackers or compromised agents exploit connected systems.

**Cause:** Automation accelerates attacks while agents receive excessive permissions.
**Consequence:** Major breaches and interruption of essential services.

Assessment confidence and limits: Medium. Narrow cyber capabilities do not establish reliable autonomous compromise of arbitrary systems.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Constrain agent permissions, budgets and external connectivity | Preventive | Proposed; unverified |
| Require separate approval for irreversible actions and rehearse recovery | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-SAFETY | [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Run a bounded adversarial exercise against connected-agent workflows | Unassigned (Cybersecurity lead) | | |

## R17 · Shared dependencies produce cascading failures
- slugs: ai-systemic-dependency
- kind: risk
- status: open
- category: Resilience
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 3
- inherent: 4x3
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Operational resilience lead)

Common models or providers fail across multiple essential services.

**Cause:** Concentrated dependencies and correlated errors defeat nominal redundancy.
**Consequence:** Extended outages and simultaneous operational failures.

Assessment confidence and limits: Medium. This scenario extends established dependency-management concerns; cross-sector frequency is uncertain.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Map common dependencies and test independent fallback paths | Preventive | Proposed; unverified |
| Retain manual or non-AI operation for essential functions | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-NIST | [NIST AI 600-1: Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Exercise a provider outage and measure actual recovery time | Unassigned (Operational resilience lead) | | |

## R18 · Resource demand harms local communities
- slugs: ai-resource-pressure
- kind: risk
- status: open
- category: Environment and infrastructure
- owner: Unassigned (Risk steward)
- impact: 3
- likelihood: 4
- inherent: 3x4
- target: 3x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Infrastructure planning lead)

AI infrastructure imposes material local energy and resource pressures.

**Cause:** New demand arrives faster than adequate supply and planning.
**Consequence:** Community costs, constrained infrastructure and avoidable environmental burden.

Assessment confidence and limits: Medium. IEA supports growing electricity demand; local water, price and emissions effects require separate assessment.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Assess local capacity and publish resource use | Preventive | Proposed; unverified |
| Require developer-funded infrastructure and efficiency measures | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-ENERGY | [IEA: Key Questions on Energy and AI](https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Baseline local grid, water and emissions constraints before expansion | Unassigned (Infrastructure planning lead) | | |

## R19 · Catastrophic misuse or military escalation
- slugs: ai-catastrophic-misuse
- kind: risk
- status: open
- category: Global security
- owner: Unassigned (Risk steward)
- impact: 5
- likelihood: 2
- inherent: 5x2
- target: 5x1
- appetite: 5
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (International security lead)

AI materially contributes to a mass-casualty event or dangerous military escalation.

**Cause:** Dangerous capabilities are misused or coupled to decisions with insufficient safeguards.
**Consequence:** Catastrophic human harm and international instability.

Assessment confidence and limits: Low. Likelihood 2 is a planning placeholder, with a plausible assessment range of 1–3. Separate biological and military scenarios when specialist stewards join.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Independently evaluate dangerous capabilities and restrict hazardous access | Preventive | Proposed; unverified |
| Maintain separate authorisation and international incident channels | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-SAFETY | [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Obtain specialist scenario reviews and explicit escalation thresholds | Unassigned (International security lead) | | |

## R20 · Loss of control over highly capable systems
- slugs: ai-loss-of-control
- kind: risk
- status: open
- category: Global safety
- owner: Unassigned (Risk steward)
- impact: 5
- likelihood: 2
- inherent: 5x2
- target: 5x1
- appetite: 5
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Frontier safety lead)

Future systems evade containment with systemic consequences.

**Cause:** Capabilities and autonomy exceed effective human control.
**Consequence:** Potentially irreversible widespread harm.

Assessment confidence and limits: Low. Experts disagree substantially. Likelihood 2 is a planning placeholder, range 1–3; laboratory behaviours are not evidence of a real-world takeover.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Stage autonomy and test containment independently | Preventive | Proposed; unverified |
| Apply enforceable stop criteria before expanding access | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-SAFETY | [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Document the capability assumptions that would raise or lower this rating | Unassigned (Frontier safety lead) | | |

## R21 · Governance fails under competitive pressure
- slugs: ai-governance-failure
- kind: risk
- status: open
- category: Governance
- owner: Unassigned (Risk steward)
- impact: 4
- likelihood: 4
- inherent: 4x4
- target: 4x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (AI governance lead)

Commercial or geopolitical competition repeatedly bypasses safety and public accountability.

**Cause:** Short-term incentives reward deployment while costs fall on others.
**Consequence:** Preventable harms persist and remediation loses legitimacy.

Assessment confidence and limits: Medium. A cross-cutting driver; do not add its score to downstream harms.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Assign release accountability and protect incident reporting | Preventive | Proposed; unverified |
| Publish independent evaluations and unresolved findings | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-DEMOCRACY | [OECD: Risks of AI for citizen participation](https://www.oecd.org/en/publications/artificial-intelligence-and-the-future-of-citizen-participation_a1ee2e0a-en/full-report/mapping-the-risks-and-challenges-of-using-ai-for-citizen-participation_f3ffbba1.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Define who can stop deployment and test that authority | Unassigned (AI governance lead) | | |

## R22 · Restrictions prevent beneficial and diverse adoption
- slugs: ai-misguided-restrictions
- kind: risk
- status: open
- category: Governance and opportunity cost
- owner: Unassigned (Risk steward)
- impact: 3
- likelihood: 3
- inherent: 3x3
- target: 3x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Public interest policy lead)

Blanket restrictions or disproportionate compliance exclude beneficial uses and smaller providers.

**Cause:** Rules ignore use-case differences or favour incumbents.
**Consequence:** Forgone benefits and reduced choice.

Assessment confidence and limits: Low-medium. This is a policy-design scenario, not an argument against safeguards.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Use proportionate requirements and supervised trials | Preventive | Proposed; unverified |
| Review effects on entrants, affected users and forgone benefits | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-GOV | [OECD: Governing with Artificial Intelligence](https://www.oecd.org/en/publications/2025/06/governing-with-artificial-intelligence_398fa287.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Compare a proposed restriction with narrower alternatives | Unassigned (Public interest policy lead) | | |

## R23 · Automation excludes people from essential services
- slugs: ai-digital-exclusion
- kind: risk
- status: open
- category: Social inclusion
- owner: Unassigned (Risk steward)
- impact: 3
- likelihood: 4
- inherent: 3x4
- target: 3x2
- appetite: 8
- accountable: Unassigned (Sponsoring institution)
- consulted: Unassigned (Affected community representative); Unassigned (Independent reviewer)
- informed: Unassigned (Register community)
- responsible: Unassigned (Service inclusion lead)

People with limited access or unsupported needs receive inferior service.

**Cause:** AI becomes the default interface without accessible alternatives.
**Consequence:** Unequal access and inability to resolve important problems.

Assessment confidence and limits: Medium. Local user testing is needed to establish who is disadvantaged.

### Controls
| Control | Type | Effectiveness |
|---|---|---|
| Retain a usable human route and accessible channels | Preventive | Proposed; unverified |
| Test with affected users across languages and abilities | Mitigating | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-GOV | [OECD: Governing with Artificial Intelligence](https://www.oecd.org/en/publications/2025/06/governing-with-artificial-intelligence_398fa287.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Measure completion and abandonment by user group | Unassigned (Service inclusion lead) | | |

## O01 · Reduce routine administrative burden
- slugs: ai-administrative-capacity
- kind: opportunity
- status: open
- category: Work and productivity
- owner: Unassigned (Opportunity steward)
- value: 4
- effort: 2
- target: 4x2
- target_value: 16
- cost: To be scoped: software, integration, staff training and evaluation
- realisation: 2027-06-30
- responsible: Unassigned (Service improvement lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Pilot AI assistance for a bounded, repetitive workflow with human review.

**Rationale:** Field research shows productivity gains in a customer-support setting, with considerable variation across workers.
**Benefit:** Release time for difficult cases, better service or shorter working hours.

Assessment confidence and limits: Medium confidence. Local gains must include review, errors, integration and training costs; one study does not establish universal savings.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Approved workflow, data access and named human reviewer | Capability | Proposed; unverified |
| Baseline time, quality and employee workload measures | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-WORK | [Brynjolfsson, Li and Raymond: Generative AI at Work](https://arxiv.org/abs/2304.11771) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Run an eight-week comparison and report net time saved without lower quality | Unassigned (Service improvement lead) | | |

## O02 · Provide accessible assistance
- slugs: ai-accessibility-assistance
- kind: opportunity
- status: open
- category: Inclusion
- owner: Unassigned (Opportunity steward)
- value: 4
- effort: 3
- target: 4x3
- target_value: 12
- cost: To be scoped: accessible design, user research, inference and support
- realisation: 2027-09-30
- responsible: Unassigned (Accessibility lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Co-design a limited text, image-description or speech assistance service with disabled users.

**Rationale:** Existing systems demonstrate assistive functions; suitability depends on the user and task.
**Benefit:** Greater independence and easier access to information.

Assessment confidence and limits: Medium for feasibility, low-medium for this proposed programme. A vendor description establishes availability, not independent proof of effectiveness.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Paid participation by users with relevant access needs | Capability | Proposed; unverified |
| Accessible interface and reliable alternative for safety-critical tasks | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-ACCESS | [Microsoft: Seeing AI](https://www.microsoft.com/en-us/garage/wall-of-fame/seeing-ai/) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Measure task completion, error severity and user control in a supervised pilot | Unassigned (Accessibility lead) | | |

## O03 · Improve learning with evaluated tutoring
- slugs: ai-learning-support
- kind: opportunity
- status: open
- category: Education
- owner: Unassigned (Opportunity steward)
- value: 4
- effort: 3
- target: 4x3
- target_value: 12
- cost: To be scoped: teaching design, safeguarding, licences and evaluation
- realisation: 2027-09-30
- responsible: Unassigned (Education programme lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Trial a subject-specific tutor alongside teachers and independent assessment.

**Rationale:** A controlled college-course study supports testing carefully designed AI tutoring.
**Benefit:** More timely feedback and help tailored to the learner.

Assessment confidence and limits: Medium within bounded instruction. Evidence from one setting does not establish durable learning gains across ages or subjects.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Curriculum-aligned material and teacher oversight | Capability | Proposed; unverified |
| Consent, safeguarding and delayed unaided assessments | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-TUTOR | [Kestin et al.: AI tutoring randomised controlled trial](https://www.nature.com/articles/s41598-025-97652-6) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Compare learning and retention with current teaching before wider use | Unassigned (Education programme lead) | | |

## O04 · Help workers acquire new capabilities
- slugs: ai-assisted-workforce-learning
- kind: opportunity
- status: open
- category: Skills and economic inclusion
- owner: Unassigned (Opportunity steward)
- value: 4
- effort: 3
- target: 4x3
- target_value: 12
- cost: To be scoped: paid learning hours, mentoring and assessment
- realisation: 2027-09-30
- responsible: Unassigned (Skills programme lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Offer paid practice using AI assistance while preserving independent judgement.

**Rationale:** Workplace evidence suggests some less-experienced staff can benefit particularly from assistance.
**Benefit:** Broader access to useful skills and better mobility within participating organisations.

Assessment confidence and limits: Medium for assisted performance; transfer to independent competence and employment outcomes must be tested.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Paid learning time and experienced mentors | Capability | Proposed; unverified |
| Tasks linked to real vacancies or progression routes | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-WORK | [Brynjolfsson, Li and Raymond: Generative AI at Work](https://arxiv.org/abs/2304.11771) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Track unaided skill development and subsequent role progression | Unassigned (Skills programme lead) | | |

## O05 · Improve access to public-service information
- slugs: ai-public-service-navigation
- kind: opportunity
- status: open
- category: Public services
- owner: Unassigned (Opportunity steward)
- value: 4
- effort: 3
- target: 4x3
- target_value: 12
- cost: To be scoped: content maintenance, integration, accessibility and support
- realisation: 2027-06-30
- responsible: Unassigned (Public service delivery lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Provide source-linked explanations and navigation for one public service.

**Rationale:** Government use cases indicate potential for more responsive services.
**Benefit:** Fewer failed applications and less effort locating the right human support.

Assessment confidence and limits: Medium. Start with navigation, then assess any proposal involving eligibility decisions separately.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Current authoritative content and named content owner | Capability | Proposed; unverified |
| Accessible human escalation and correction route | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-GOV | [OECD: Governing with Artificial Intelligence](https://www.oecd.org/en/publications/2025/06/governing-with-artificial-intelligence_398fa287.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Measure successful user journeys, incorrect advice and access gaps | Unassigned (Public service delivery lead) | | |

## O06 · Accelerate experimentally validated research
- slugs: ai-scientific-discovery
- kind: opportunity
- status: open
- category: Science and health
- owner: Unassigned (Opportunity steward)
- value: 5
- effort: 5
- target: 5x5
- target_value: 5
- cost: To be scoped: researchers, compute, laboratory work and validation
- realisation: 2028-10-31
- responsible: Unassigned (Research programme lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Use suitable specialist AI to prioritise hypotheses in one funded research programme.

**Rationale:** AlphaFold 3 demonstrates advances in biomolecular structure prediction.
**Benefit:** More informative experiments and potentially faster discovery.

Assessment confidence and limits: Medium for modelling capability, low for downstream clinical or commercial value. Predicted structures do not prove therapeutic efficacy.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Domain expertise, suitable data and compute access | Capability | Proposed; unverified |
| Independent experimental validation and reproducible records | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-BIO | [Abramson et al.: AlphaFold 3 biomolecular structure prediction](https://www.nature.com/articles/s41586-024-07487-w) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Choose one benchmark and publish prospective experimental validation | Unassigned (Research programme lead) | | |

## O07 · Improve energy and resource efficiency
- slugs: ai-resource-efficiency
- kind: opportunity
- status: open
- category: Environment
- owner: Unassigned (Opportunity steward)
- value: 4
- effort: 4
- target: 4x4
- target_value: 8
- cost: To be scoped: sensors, integration, compute and operational evaluation
- realisation: 2027-12-31
- responsible: Unassigned (Energy management lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Test forecasting or optimisation in one building, process or energy system.

**Rationale:** Energy analysis identifies AI applications as well as AI-related demand.
**Benefit:** Lower net resource use where measured savings exceed the system footprint.

Assessment confidence and limits: Medium for a bounded application. Efficiency per task does not guarantee lower total consumption.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Metered baseline and controllable operational process | Capability | Proposed; unverified |
| Safe operating limits and full-system resource accounting | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-ENERGY | [IEA: Key Questions on Energy and AI](https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Run a controlled trial and report net energy, cost and emissions changes | Unassigned (Energy management lead) | | |

## O08 · Make civic participation easier to understand
- slugs: ai-civic-deliberation-support
- kind: opportunity
- status: open
- category: Democratic participation
- owner: Unassigned (Opportunity steward)
- value: 3
- effort: 3
- target: 3x3
- target_value: 9
- cost: To be scoped: facilitation, translation, user testing and independent review
- realisation: 2027-09-30
- responsible: Unassigned (Civic engagement lead)
- accountable: Unassigned (Programme sponsor)
- consulted: Unassigned (Beneficiary representative); Unassigned (Independent evaluator)
- informed: Unassigned (Register community)

Help participants inspect and summarise a bounded public consultation.

**Rationale:** AI can help organise material, but summaries must retain minority views and contested points.
**Benefit:** Lower participation barriers and clearer comparison of proposals.

Assessment confidence and limits: Low-medium. This is a testable design hypothesis, not evidence that AI improves democratic legitimacy.

### Enablers
| Enabler | Type | Status |
|---|---|---|
| Public source material and traceable links from summaries | Capability | Proposed; unverified |
| Independent facilitators and representative participant review | Dependency | Proposed; unverified |

### Evidence
| Ref | Title | Kind | Date | Valid days |
|---|---|---|---|---|
| EV-DEMOCRACY | [OECD: Risks of AI for citizen participation](https://www.oecd.org/en/publications/artificial-intelligence-and-the-future-of-citizen-participation_a1ee2e0a-en/full-report/mapping-the-risks-and-challenges-of-using-ai-for-citizen-participation_f3ffbba1.html) | Source relevance review | 2026-10-24 | 180 |

### Actions
| Action | Owner | Due | Done |
|---|---|---|---|
| Compare inclusion, omitted views and participant understanding with the existing process | Unassigned (Civic engagement lead) | | |

