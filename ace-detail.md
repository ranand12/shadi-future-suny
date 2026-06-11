# Google Cloud AI Platform for SUNY Student Success
## Expanding from Research Computing to ASAP|ACE: A Strategic Proposal

---

## Executive Summary

SUNY's AI Platform has already proven transformational for research — 230+ researchers, 15 GCP services, $2.84M in cloud consumption, and 10-15x workload speedups. The opportunity now is to apply the same proven cloud foundation to SUNY's highest-priority institutional challenge: **student retention and completion at scale**.

Governor Hochul's ASAP|ACE program is expanding from 4,270 students (Fall 2024) to 10,000 by Fall 2026, backed by $12M in state funding. This program, modeled on the most rigorously evaluated community college intervention in U.S. history, is producing early results — 17 percentage-point retention gains at SUNY. But ASAP|ACE's current analytics infrastructure is fragmented, campus-by-campus, and largely vendor-dependent. There is no unified "Student 360" view across the 64-campus system.

**Google Cloud can close this gap** by extending the existing SUNY AI Platform into a Student Success data and AI layer — delivering a unified student view, predictive analytics, and generative AI-powered advising tools that amplify what ASAP|ACE's comprehensive support model already does well. This isn't about prediction for prediction's sake (which research shows doesn't work alone) — it's about connecting the right intervention to the right student at the right time, across the entire SUNY system.

---

## Part 1: The ASAP|ACE Program — What It Is and Why It Matters

### The CUNY Origin Story

ASAP (Accelerated Study in Associate Programs) launched at CUNY in 2007 as a comprehensive support model for community college students. Its results are extraordinary and rigorously validated:

| Metric | ASAP Students | Comparison Group | Effect |
|--------|--------------|-----------------|--------|
| Three-year graduation rate (MDRC RCT) | 40.1% | 21.8% | **+18.3 pp** |
| Historical three-year graduation rate | 53% | 25% | **+28 pp** |
| Ohio replication (8-year follow-up) | 46% | 31% | **+15 pp** |
| Annual earnings gain (Ohio, 8 years) | — | — | **+$3,337** |

MDRC's randomized controlled trial found this to be **the largest graduation rate effect of any community college intervention evaluated across 30+ RCTs** — the gold standard in education research. CUNY has served over 120,000 students across 18 cohorts, and the model has been replicated at 60+ institutions in nine states.

> **Source:** MDRC, "Evaluating the Academic and Economic Effects of CUNY's Accelerated Study in Associate Programs"; CUNY ASAP Fast Facts (Nov 2025)

### What ASAP Actually Provides

ASAP is not a single intervention — it's a **bundled, comprehensive support model** lasting up to three years:

- **Tuition waivers** covering gaps after financial aid
- **Textbook vouchers** eliminating a major cost barrier
- **Monthly financial incentives** (MetroCards, stipends)
- **Intensive advising** with low advisor-to-student ratios
- **Enhanced tutoring** and supplemental instruction
- **Career counseling** and workforce development
- **Full-time enrollment requirement** maintaining momentum

The annual incremental cost: **$3,440 per student**. Columbia University's cost-benefit analysis shows **$3.50 return per $1 invested**, with net social benefits of nearly $43,000 per participant ($125,000+ including intergenerational effects).

> **Source:** MDRC core components documentation; Columbia Center on Poverty and Social Policy (Dec 2024)

### ACE: The Four-Year Extension

ACE (Accelerated Completion and Engagement) extends the model to bachelor's degree students, adapting the intensive advising and financial support structures to four-year campuses. Together, ASAP|ACE represents SUNY's comprehensive approach to student success across associate and baccalaureate programs.

### SUNY's ASAP|ACE: Scaling Fast, Results Emerging

Governor Hochul announced the expansion on June 3, 2025:

| Timeline | Students | Campuses | Funding |
|----------|----------|----------|---------|
| Fall 2024 | 4,270 | 25 | — |
| Fall 2025 | 7,050 | 34 | — |
| Fall 2026 (target) | 10,000 | — | **$12M (FY26 State Budget)** |

**Early SUNY results** (preliminary, quasi-experimental):
- **17 pp** first-to-second-term retention increase
- **15 pp** one-year retention increase
- **20%** higher credit completion rate (ASAP students vs. matched comparisons)
- **9%** higher credit completion rate (ACE students vs. matched comparisons)
- At Westchester Community College, MDRC's RCT found **11.8 pp** degree completion increase (35.5% vs. 23.7%)

By Fall 2025, SUNY achieved its enrollment target with a **500+ student waitlist** — demand is outstripping capacity.

> **Source:** Governor Hochul press release (June 3, 2025); SUNY press releases (October 2025)

---

## Part 2: The Problem — Fragmented Data, Overwhelmed Advisors

### The Retention Crisis in Numbers

SUNY community colleges face systemic challenges. SUNY Broome is illustrative:

- **25% headcount decline** (2016-2022)
- **47.9%** fall-to-fall retention rate
- **~25.7%** two-year graduation rate (IPEDS standard)
- **250 students per advisor** (national median: 296)
- **45%** of students have at least one D, F, or Withdrawal on record

> **Source:** Civitas Learning case study; IPEDS data; NACADA national benchmarks

### The Analytics Gap

The current landscape is fragmented:

- **Campus-by-campus procurement**: Individual institutions like SUNY Broome have adopted vendor platforms (Civitas Learning), but there is no system-wide analytics infrastructure
- **No unified Student 360 view**: Student data lives in silos — SIS, LMS (Brightspace/Canvas), financial aid, advising notes, library systems, dining/housing — with no integrated data layer across the 64-campus system
- **Vendor lock-in risks**: Existing vendors like EAB Navigate and Civitas frame student success primarily as institutional revenue optimization, not student-centered outcomes

### Why Prediction Alone Fails

This is critical context for the proposal: **a large-scale DOE-funded RCT of proactive advising based on predictive analytics at 11 universities found no statistically significant improvements** except at Georgia State University. The exception? Georgia State had pre-existing data infrastructure and deep institutional commitment to intervention.

The research is clear: **prediction without effective intervention infrastructure doesn't move the needle**. ASAP|ACE already has the intervention infrastructure — the comprehensive supports, the intensive advising, the financial incentives. What it lacks is the data and AI layer to target those interventions precisely and at scale.

This is exactly the gap Google Cloud can fill.

> **Source:** MAAPS Evaluation (Ithaka S+R); "Selling Student Success" (Annenberg Institute EdWorkingPaper, December 2025)

### The Equity Imperative

Current vendor models raise equity concerns. A FOIA analysis of EAB Navigate revealed that predictive models often include age, gender, race, veteran status, and first-generation status as predictors — creating bias risks. Google Cloud's approach can be designed from the ground up with fairness constraints, explainability, and bias monitoring built into the pipeline.

> **Source:** Annenberg Institute working paper; The Markup (2021) FOIA investigation

---

## Part 3: The Google Cloud Solution — Student 360 AI Platform

### Strategic Positioning: Build on What Works

Google Cloud isn't entering as another predictive analytics vendor. The positioning is fundamentally different:

| Vendor Approach | Google Cloud Approach |
|----------------|----------------------|
| Prediction as the product | Prediction powering ASAP|ACE's proven interventions |
| Campus-by-campus SaaS | System-wide data platform across 64 campuses |
| Revenue/ROI framing | Student outcomes and equity framing |
| Black-box models | Explainable AI with Vertex AI and BigQuery ML |
| Siloed vendor data | Open, interoperable data lakehouse |

### Architecture: The Student 360 Data Platform

Building on the existing SUNY AI Platform foundation (GCP org, IAM, networking already in place from Phase 2), the Student Success layer would integrate:

```
                    SUNY Student 360 AI Platform
    ┌─────────────────────────────────────────────────────┐
    │                                                     │
    │  ┌──────────┐  ┌──────────┐  ┌──────────────────┐  │
    │  │   SIS    │  │   LMS    │  │  Financial Aid   │  │
    │  │(Banner/  │  │(Canvas/  │  │   (FAFSA data,   │  │
    │  │ Ellucian)│  │Brightsp.)│  │    scholarships)  │  │
    │  └────┬─────┘  └────┬─────┘  └───────┬──────────┘  │
    │       │              │                │             │
    │  ┌────┴──────────────┴────────────────┴──────────┐  │
    │  │        BigQuery — Unified Data Lakehouse       │  │
    │  │     (Student 360 View across 64 campuses)      │  │
    │  └────────────────────┬───────────────────────────┘  │
    │                       │                             │
    │  ┌────────────────────┴───────────────────────────┐  │
    │  │            Vertex AI / BigQuery ML              │  │
    │  │  ┌─────────────┐ ┌──────────┐ ┌─────────────┐ │  │
    │  │  │ Retention   │ │ Credit   │ │ Financial   │ │  │
    │  │  │ Risk Model  │ │ Momentum │ │ Distress    │ │  │
    │  │  │             │ │ Tracker  │ │ Predictor   │ │  │
    │  │  └─────────────┘ └──────────┘ └─────────────┘ │  │
    │  └────────────────────┬───────────────────────────┘  │
    │                       │                             │
    │  ┌────────────────────┴───────────────────────────┐  │
    │  │         Gemini-Powered Applications             │  │
    │  │  ┌─────────────┐ ┌──────────┐ ┌─────────────┐ │  │
    │  │  │ AI Advising │ │  Early   │ │  Student    │ │  │
    │  │  │  Copilot    │ │  Alert   │ │  Chatbot    │ │  │
    │  │  │ (for staff) │ │  Triage  │ │ (self-serve)│ │  │
    │  │  └─────────────┘ └──────────┘ └─────────────┘ │  │
    │  └────────────────────────────────────────────────┘  │
    │                       │                             │
    │  ┌────────────────────┴───────────────────────────┐  │
    │  │    Looker Dashboards & Operational Reporting     │  │
    │  │  (Campus leaders, advisors, system admin)        │  │
    │  └─────────────────────────────────────────────────┘  │
    └─────────────────────────────────────────────────────┘
```

### Core Use Cases

#### Use Case 1: Predictive Retention & Early Alert Triage

**Problem:** Advisors managing 250+ students cannot identify who needs intervention and when. Current early alert systems are reactive (triggered by faculty referrals or grade thresholds) rather than proactive.

**Solution:** BigQuery ML models that combine:
- LMS engagement signals (login frequency, assignment submission patterns, discussion participation)
- Academic momentum (credit accumulation rate, DFW patterns, course-level difficulty)
- Financial indicators (aid disbursement gaps, payment plan status, emergency fund requests)
- Behavioral signals (advising no-shows, registration timing, course drop patterns)

**Output:** Daily risk scores surfaced in an advisor-facing dashboard, with Gemini-generated intervention recommendations tailored to each student's specific risk profile.

**Key differentiator:** Models trained on SUNY's own student data across campuses, not generic vendor models. Explainable AI ensures advisors understand *why* a student is flagged, not just that they are.

**Measurable target:** Reduce advisor triage time by 50%, enabling proactive outreach to at-risk students within 48 hours of risk signal detection.

#### Use Case 2: AI Advising Copilot for ASAP|ACE Staff

**Problem:** ASAP|ACE's intensive advising model is its greatest strength but also its scaling bottleneck. As the program grows from 4,270 to 10,000 students, advisor capacity becomes the constraint.

**Solution:** A Gemini-powered advising copilot that:
- **Pre-briefs advisors** before meetings with a student summary: risk factors, academic progress, financial aid status, prior advising notes, and suggested discussion topics
- **Drafts personalized outreach** messages for advisors to review and send to at-risk students
- **Automates documentation** by generating advising session notes from structured inputs
- **Surfaces degree pathway options** based on completed coursework, remaining requirements, and course availability

**Key differentiator:** Augments advisors rather than replacing them — aligned with ASAP's relationship-centered model. Built on SUNY's secure Gemini Enterprise instance already deployed in Phase 2.

**Measurable target:** Enable each advisor to maintain quality interactions while increasing caseload capacity by 30%, directly supporting the 10,000-student scaling goal.

#### Use Case 3: Student 360-Degree View Dashboard

**Problem:** Student data is siloed across SIS, LMS, financial aid, advising systems, and campus-specific tools. No one — advisor, department chair, or SUNY System Administration — has a complete picture of a student's trajectory.

**Solution:** A BigQuery-powered unified data lakehouse that integrates data from all 64 campuses into a single, governed data layer, surfaced through Looker dashboards with role-based views:

- **Advisor view:** Individual student profiles with risk scores, academic progress, financial status, and interaction history
- **Campus leader view:** Cohort-level retention funnels, DFW rates by course, intervention effectiveness metrics
- **System admin view:** Cross-campus comparisons, ASAP|ACE program performance, state reporting metrics

**Key differentiator:** Built on the same BigQuery infrastructure already proven in the SUNY AI Platform for research — not a new vendor relationship, but an extension of an existing platform investment.

**Measurable target:** Reduce time-to-insight for program effectiveness reporting from weeks to hours; enable real-time cross-campus benchmarking.

#### Use Case 4: GrantAI for Student Success Research Funding

**Problem:** SUNY faculty researching student success interventions face the same grant-finding challenges as STEM researchers.

**Solution:** Extend the existing GrantAI platform (already integrating PURE API and Grants.gov) to surface student success research funding opportunities from:
- NSF (education research programs)
- DOE Institute of Education Sciences
- Spencer Foundation
- Gates Foundation
- Lumina Foundation
- Arnold Ventures (the original ASAP|ACE funder)

**Key differentiator:** Already built and operational — this is a configuration extension, not a new build.

#### Use Case 5: Automated ASAP|ACE Eligibility & Onboarding

**Problem:** With a 500+ student waitlist, the ASAP|ACE program needs to efficiently identify eligible students and onboard them — currently a manual, spreadsheet-driven process at many campuses.

**Solution:** Automated eligibility matching against program criteria using BigQuery, with the SUNY AI Portal (already built in Phase 2) extended to include:
- Self-service ASAP|ACE eligibility checking
- Automated document collection and verification
- Waitlist management with priority scoring based on need indicators
- Onboarding workflow automation via integration with TeamDynamix (already operational)

**Measurable target:** Reduce onboarding processing time by 70%, matching the Portal's proven impact on research environment provisioning.

---

## Part 4: Why Google Cloud — The Competitive Advantage

### 1. We're Already Here

The existing SUNY AI Platform represents a $2.84M, 26-week investment in GCP infrastructure, governance, and trust. The Student Success platform builds on:
- **Existing GCP organization** with IAM, networking, and security controls
- **Existing Gemini Enterprise** deployment (secure, compliant instance)
- **Existing GrantAI** with PURE API integration
- **Existing AI Portal** with automated provisioning and TeamDynamix integration
- **Existing relationships** with 9 campuses and 230+ users

No competitor can match this installed base.

### 2. Intervention-First, Not Prediction-First

The research is unambiguous: prediction alone doesn't improve student outcomes. ASAP|ACE already has the intervention infrastructure. Google Cloud's role is to make those interventions **smarter, faster, and more precisely targeted** — not to sell a prediction dashboard.

This framing directly addresses the critique of existing vendors and positions Google Cloud as aligned with what the evidence says actually works.

### 3. System-Wide Scale vs. Campus-by-Campus SaaS

Existing vendors (EAB, Civitas, Starfish) sell campus-by-campus SaaS licenses. Google Cloud offers a **system-wide data platform** that enables:
- Cross-campus benchmarking and learning
- System-level reporting for state accountability
- Economies of scale across 64 campuses
- Unified governance and data standards

This directly supports the "economies of scale" narrative from the plan.md discussion.

### 4. Equity by Design

Unlike vendor models that have been shown to use race, gender, and age as predictors (raising bias concerns), Google Cloud's platform can be built with:
- **Vertex AI Fairness** tools for bias detection and mitigation
- **Explainable AI** so advisors understand model reasoning
- **Fairness constraints** built into model training
- **Audit trails** for compliance and accountability

### 5. Open, Not Locked In

BigQuery, Vertex AI, and Looker are open, standards-based tools. SUNY owns its data, its models, and its dashboards. This contrasts sharply with vendor platforms where the model is proprietary and the data is accessible only through vendor interfaces.

---

## Part 5: ROI Framework and OKRs

### Cost-Benefit Model

| Investment Area | Estimated Annual Cost | Expected Impact |
|----------------|----------------------|-----------------|
| BigQuery data platform (64 campuses) | $200K-400K | Unified Student 360 view |
| Vertex AI model development & training | $150K-250K | Predictive risk models |
| Gemini Enterprise (advising copilot) | $100K-200K | Advisor capacity expansion |
| Looker dashboards & reporting | $75K-150K | Real-time operational intelligence |
| Professional services (integration) | $300K-500K | SIS/LMS/FA data integration |
| **Total Year 1** | **$825K-$1.5M** | |

### ROI Calculation

Each retained student represents approximately:
- **$7,000-$12,000** in annual tuition and fees (community college)
- **$10,000-$15,000** in state funding per FTE
- **$43,000** in net social benefits per ASAP participant (Columbia estimate)

**Conservative scenario:** If the platform enables a **2% improvement** in retention across the 10,000 ASAP|ACE students (200 additional retained students):
- **Direct tuition recovery:** $1.4M-$2.4M annually
- **State funding retention:** $2.0M-$3.0M annually
- **Social benefits:** $8.6M (lifetime, per Columbia methodology)

**Platform cost payback: Under 1 year.**

### Proposed OKRs

**Objective 1: Accelerate ASAP|ACE Program Scaling**
- KR1: Deploy Student 360 data platform integrating SIS, LMS, and financial aid data at 10 pilot campuses by Q2 2027
- KR2: Reduce ASAP|ACE onboarding processing time by 70% through AI Portal automation
- KR3: Achieve 500+ student waitlist clearance through automated eligibility matching

**Objective 2: Improve Retention Through Predictive Intervention**
- KR1: Deliver daily risk scores for 100% of ASAP|ACE students by Q3 2027
- KR2: Reduce advisor triage time by 50%, enabling proactive outreach within 48 hours
- KR3: Achieve 2+ percentage point retention improvement in pilot cohort vs. matched comparison

**Objective 3: Scale Advisor Capacity with AI**
- KR1: Deploy Gemini-powered advising copilot to 100 ASAP|ACE advisors by Q4 2027
- KR2: Increase effective advisor caseload capacity by 30% while maintaining satisfaction scores
- KR3: Generate 10,000+ personalized student outreach drafts per semester

**Objective 4: Enable System-Wide Data-Driven Decision Making**
- KR1: Deliver Looker dashboards to campus leaders at all 34 ASAP|ACE campuses
- KR2: Reduce state reporting preparation time from weeks to hours
- KR3: Publish first cross-campus ASAP|ACE effectiveness analysis using unified data

---

## Part 6: The Narrative for Leadership

### For the Governor's Chief of Staff

> "SUNY's AI Platform has already demonstrated what's possible for research — 10-15x speedups, tier-1 publications, and $2.84M in cloud adoption. Now we're extending that same proven foundation to SUNY's #1 strategic priority: student success.
>
> Governor Hochul's ASAP|ACE program is producing results — 17-point retention gains, 500+ student waitlists. But scaling from 4,270 to 10,000 students requires a data infrastructure that doesn't exist today. Google Cloud will build the Student 360 AI Platform that connects every data point about every ASAP|ACE student — academic progress, financial status, advising history — into a single view, powered by the same AI that's already transforming SUNY research.
>
> The research is clear: the programs that move the needle combine comprehensive supports with smart data. ASAP|ACE has the supports. Google Cloud delivers the intelligence layer."

### For SUNY System Administration

> "This isn't another vendor platform. This is an extension of the AI infrastructure SUNY already owns and operates. The same BigQuery, Vertex AI, and Gemini tools that 230 researchers use today will power a system-wide Student 360 view across 64 campuses — with SUNY's data, SUNY's models, and SUNY's governance. No black boxes. No vendor lock-in. No campus-by-campus procurement. One platform, one investment, system-wide impact."

### For Camille Joseph Varlack

> "The art of the possible: imagine an ASAP|ACE advisor opening their dashboard Monday morning and seeing — before any student walks in — which students missed class last week, which ones haven't logged into the LMS, which ones have a financial aid gap, and a Gemini-drafted outreach message ready to send. That's the Student 360 platform. It turns ASAP|ACE's proven model from reactive to predictive, and from 4,270 students to 10,000 without proportionally scaling headcount."

---

## Part 7: Implementation Roadmap

### Phase 3A: Foundation (Months 1-4)
- Data architecture design for Student 360 lakehouse
- SIS/LMS/Financial Aid data integration at 3-5 pilot campuses
- BigQuery data models for student risk scoring
- Governance framework for student data (FERPA compliance)

### Phase 3B: Intelligence Layer (Months 4-8)
- Vertex AI retention risk models trained on SUNY historical data
- Early alert triage system with advisor-facing dashboards
- Gemini advising copilot pilot with 20 ASAP|ACE advisors
- Looker dashboards for campus leaders

### Phase 3C: Scale (Months 8-12)
- Expand to all 34 ASAP|ACE campuses
- Student-facing self-service features (chatbot, eligibility checker)
- GrantAI extension for student success research funding
- Cross-campus benchmarking and system-level reporting

### Phase 3D: Optimize (Months 12-18)
- Model refinement based on outcome data
- Fairness audits and bias monitoring
- Integration with state reporting requirements
- M&O transition and long-term sustainability planning

---

## Appendix: Key Research Sources

1. **MDRC** — "Evaluating the Academic and Economic Effects of CUNY's ASAP" — Gold-standard RCT showing 18pp graduation effect
   - https://www.mdrc.org/work/projects/evaluating-academic-and-economic-effects-cunys-accelerated-study-associate-programs

2. **SUNY ASAP|ACE Official** — Program details and early outcomes
   - https://www.suny.edu/asap-ace/

3. **Governor Hochul Press Release** (June 3, 2025) — Expansion announcement, $12M funding, early results
   - https://www.governor.ny.gov/news/governor-hochul-announces-expansion-nation-leading-retention-and-completion-program-help-more

4. **CUNY ASAP Fast Facts** (Nov 2025) — 120,000 students served, cost-benefit data
   - https://www.cuny.edu/wp-content/uploads/sites/4/media-assets/CUNY-ASAP-and-ACE-Fast-Facts_Nov25.pdf

5. **"Selling Student Success"** (Annenberg Institute, Dec 2025) — Critical analysis of vendor analytics market
   - https://edworkingpapers.com/sites/default/files/ai25-1349.pdf

6. **Civitas Learning / SUNY Broome** — Case study on analytics adoption
   - https://www.civitaslearning.com/customer-success-stories/suny-broome-data-informed-approach-to-retention-decline/

7. **Google Cloud Higher Education** — Student success solution area
   - https://cloud.google.com/edu/higher-education

8. **Google Cloud Student Success Services Launch** (Sept 2020)
   - https://cloud.google.com/blog/topics/education/introducing-student-success-services-from-google-cloud

9. **Columbia Center on Poverty and Social Policy** (Dec 2024) — $43K net social benefits per ASAP participant

---

*Prepared for: Camille Joseph Varlack, SUNY | Google Cloud Account Team*
*Date: June 2026*
