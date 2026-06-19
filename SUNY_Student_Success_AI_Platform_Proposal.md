# Google Cloud AI Platform for SUNY Student Success
## Expanding from Research Computing to ASAP|ACE: A Strategic Proposal

---

## Executive Summary

SUNY's AI Platform has already proven transformational for research — 230+ researchers across 9 campuses, 15 GCP services in production, Gemini Enterprise deployed system-wide, and 10-15x workload speedups. The opportunity now is to apply the same proven cloud foundation to SUNY's highest-priority institutional challenge: **student retention and completion at scale**.

Governor Hochul's ASAP|ACE program is expanding from 4,270 students (Fall 2024) to 10,000 at 44 campuses by Fall 2026, backed by $20M in annual state funding. This program, modeled on the most rigorously evaluated community college intervention in U.S. history, is producing early results — 17 percentage-point retention gains at SUNY. But ASAP|ACE's current analytics infrastructure is fragmented, campus-by-campus, and largely vendor-dependent. There is no unified "Student 360" view across the 64-campus system.

**Google Cloud can close this gap** by extending the existing SUNY AI Platform into a Student Success data and AI layer — delivering a unified student view, predictive analytics, and generative AI-powered advising tools that amplify what ASAP|ACE's comprehensive support model already does well. This isn't about prediction for prediction's sake (which research shows doesn't work alone) — it's about connecting the right intervention to the right student at the right time, across the entire SUNY system.

---

## Part 1: The ASAP|ACE Program — What It Is and Why It Matters

### The CUNY Origin Story

ASAP (Accelerated Study in Associate Programs) launched at CUNY in 2007 as a comprehensive support model for community college students. Its results are extraordinary and rigorously validated:

| Metric | SUNY CC Average | National CC Average | ASAP (MDRC RCT) |
|--------|----------------|--------------------|--------------------|
| **3-Year Graduation Rate** | **~26%** | **~34%** | **40.1%** |
| **Gap to Close** | 8 pp below national | Baseline | **+6 pp above national** |
| **Source** | IPEDS / Center for an Urban Future | National Student Clearinghouse (2020 cohort) | MDRC randomized controlled trial |

**SUNY community colleges graduate students at 8 percentage points below the national average.** ASAP doesn't just close that gap — it surpasses it, achieving 40.1% three-year graduation rates vs. 21.8% for matched control group students (+18.3 pp effect). This is **the largest graduation rate effect of any community college intervention evaluated across 30+ RCTs** — the gold standard in education research.

CUNY has served over 120,000 students across 18 cohorts, and the model has been replicated at 60+ institutions in nine states.

> **Sources:** MDRC, "Evaluating the Academic and Economic Effects of CUNY's ASAP"; CUNY ASAP Fast Facts (Nov 2025); National Student Clearinghouse Research Center, Completing College (2024); Center for an Urban Future, "Struggling to the Finish Line" (2017)

### What ASAP Actually Provides

ASAP is not a single intervention — it's a **bundled, comprehensive support model** lasting up to three years:

- **Tuition waivers** covering gaps after financial aid
- **Textbook vouchers** eliminating a major cost barrier
- **Monthly financial incentives** (MetroCards, stipends)
- **Intensive advising** with low advisor-to-student ratios
- **Enhanced tutoring** and supplemental instruction
- **Career counseling** and workforce development
- **Full-time enrollment requirement** maintaining momentum

The annual incremental cost per student is modest relative to the return: ASAP's comprehensive support model consistently delivers the highest graduation rate gains of any evaluated community college intervention.

> **Source:** MDRC core components documentation

### ACE: The Four-Year Extension

ACE (Accelerated Completion and Engagement) extends the model to bachelor's degree students, adapting the intensive advising and financial support structures to four-year campuses. Together, ASAP|ACE represents SUNY's comprehensive approach to student success across associate and baccalaureate programs.

### SUNY's ASAP|ACE: Scaling Fast, Results Emerging

Governor Hochul announced the expansion, with total state investment now at **$20M annually**:

| Timeline | Students | Campuses | Funding |
|----------|----------|----------|---------|
| Fall 2024 | 4,270 | 25 | — |
| Fall 2025 | 7,050 | 34 | — |
| Fall 2026 (target) | 10,000 | 44 | **$20M annually (FY26-27 State Budget)** |

**Early SUNY results** (preliminary, quasi-experimental):
- **17 pp** first-to-second-term retention increase
- **15 pp** one-year retention increase
- **20%** higher credit completion rate (ASAP students: 73% vs. 61% non-ASAP)
- **9%** higher credit completion rate (ACE students: 89% vs. 82% non-ACE)
- **80% vs. 72%** spring-to-fall persistence (ASAP vs. non-ASAP)
- At Westchester Community College, MDRC's RCT found **11.8 pp** degree completion increase (35.5% vs. 23.7%)

By Fall 2025, SUNY achieved its enrollment target with a **500+ student waitlist** — demand is outstripping capacity.

### How SUNY Compares to National ASAP Implementations

SUNY's results are strong — but trail the most mature implementations. This is the gap Google Cloud can help close:

| Implementation Site | ASAP Grad Rate | Control Rate | Effect | Study Type |
|---------------------|---------------|-------------|--------|------------|
| **CUNY ASAP (original)** | **40.1%** | 21.8% | **+18.3 pp** | MDRC RCT |
| **Ohio (3 colleges)** | **35%** | 19% | **+16 pp** | MDRC RCT |
| **SUNY Westchester CC** | **35.5%** | 23.7% | **+11.8 pp** | MDRC RCT |
| **SUNY system-wide** | *Too early* | — | **17 pp retention** | Quasi-experimental |

CUNY's 18.3 pp effect and Ohio's 16 pp effect were achieved with years of data infrastructure maturation. SUNY's Westchester RCT (+11.8 pp) was conducted during COVID-19, making it impressive in context — but the implementation gap is real. **The difference between an 11.8 pp and an 18.3 pp graduation effect across 10,000 students is approximately 650 additional graduates per year.**

Google Cloud's Student 360 AI Platform directly addresses the factors that separate mature implementations from emerging ones: unified cross-campus data, predictive intervention targeting, and advisor capacity scaling — the exact infrastructure advantages that CUNY and Ohio built over years, delivered to SUNY in months.

> **Sources:** Governor Hochul press release (June 3, 2025); SUNY press releases (October 2025, June 2026); MDRC, "CUNY ASAP Doubles Graduation Rates in New York City and Ohio"; MDRC, Westchester CC Viking ROADS evaluation

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

| Dimension | Typical Vendor Approach | Google Cloud Approach |
|-----------|------------------------|----------------------|
| **Core product** | Prediction dashboard as the product | Prediction powering ASAP\|ACE's proven interventions |
| **Procurement model** | Campus-by-campus SaaS licenses | System-wide platform across 64 campuses — one contract, one investment |
| **Framing** | Enrollment revenue optimization | Student outcomes and equity |
| **Model transparency** | Proprietary black-box algorithms | Explainable AI with Vertex AI and BigQuery ML |
| **Data ownership** | Data accessible only through vendor UI; export limited | SUNY owns all data, models, and dashboards in BigQuery |
| **Scaling** | Per-seat or per-campus pricing grows linearly | Infrastructure scales elastically — marginal cost per campus decreases |
| **Customization** | Configurable within vendor parameters | Fully customizable models, dashboards, and workflows built on open APIs |
| **Integration** | Pre-built connectors to common SIS; limited beyond that | Open data lakehouse ingests any source — SIS, LMS, financial aid, custom |
| **Lock-in risk** | Multi-year contracts; migration is costly | Standards-based tools (SQL, Python, REST); portable by design |

### Architecture: The Student 360 Data Platform

Building on the existing SUNY AI Platform foundation (GCP org, IAM, networking already in place from Phase 1), the Student Success layer would integrate:

```
                    SUNY Student 360 AI Platform
    ┌─────────────────────────────────────────────────────┐
    │                                                     │
    │  ┌────────────────────────────────────────────────┐  │
    │  │         Gemini Enterprise — AI Layer            │  │
    │  │  ┌─────────────┐ ┌──────────┐ ┌─────────────┐ │  │
    │  │  │ AI Advising │ │  Early   │ │  Student    │ │  │
    │  │  │  Copilot    │ │  Alert   │ │  Chatbot    │ │  │
    │  │  │ (for staff) │ │  Triage  │ │ (self-serve)│ │  │
    │  │  └─────────────┘ └──────────┘ └─────────────┘ │  │
    │  └────────────────────┬───────────────────────────┘  │
    │                       │                             │
    │  ┌────────────────────┴───────────────────────────┐  │
    │  │    Looker Dashboards & Operational Reporting     │  │
    │  │  (Campus leaders, advisors, system admin)        │  │
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
    │  │        BigQuery — Unified Data Lakehouse       │  │
    │  │     (Student 360 View across 64 campuses)      │  │
    │  └────────────────────┬───────────────────────────┘  │
    │                       │                             │
    │  ┌──────────┐  ┌──────────┐  ┌──────────────────┐  │
    │  │   SIS    │  │   LMS    │  │  Financial Aid   │  │
    │  │(Banner/  │  │(Canvas/  │  │   (FAFSA data,   │  │
    │  │ Ellucian)│  │Brightsp.)│  │    scholarships)  │  │
    │  └──────────┘  └──────────┘  └──────────────────┘  │
    │                                                     │
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

**Key differentiator:** Augments advisors rather than replacing them — aligned with ASAP's relationship-centered model. Built on SUNY's secure Gemini Enterprise instance already deployed in Phase 1.

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

**Solution:** Automated eligibility matching against program criteria using BigQuery, with the SUNY AI Portal (already built in Phase 1) extended to include:
- Self-service ASAP|ACE eligibility checking
- Automated document collection and verification
- Waitlist management with priority scoring based on need indicators
- Onboarding workflow automation via integration with TeamDynamix (already operational)

**Measurable target:** Reduce onboarding processing time by 70%, matching the Portal's proven impact on research environment provisioning.

---

## Part 4: Why Google Cloud — The Competitive Advantage

### 1. We're Already Here — And Already Delivering Results

The existing SUNY AI Platform is already operational — infrastructure, governance, and trust are in place. The Student Success platform builds on:
- **Existing GCP organization** with IAM, networking, and security controls
- **Existing Gemini Enterprise** deployment (secure, compliant instance)
- **Existing GrantAI** with PURE API integration and Grants.gov matching
- **Existing AI Portal** with automated provisioning and TeamDynamix integration
- **Existing relationships** with 9 campuses and 230+ active researchers

No competitor can match this installed base.

#### Phase 1 Research Impact — By the Numbers

| Metric | Result |
|--------|--------|
| Experiment time reduction | **70%** vs. sequential local execution |
| Training throughput speedup | **3.5x** for complex 3D models (cycles reduced to 4 days) |
| Training loss reduction | **95.4%** on large-scale 32B parameter models |
| AI workload acceleration | **10-15x** speedups across research teams |
| Training cycle compression | **20 days → 2-3 days** for model training |
| Model scale unlocked | **7B parameter** models — impossible on local campus HPC |

#### Researcher Testimonials

> *"Without the SUNY AI Platform, this research could not have proceeded… The platform provided our first cost-effective access to the computational resources required for intensive model fine-tuning experiments."*

> *"Without the platform, we would have had to manage separate API accounts and billing across multiple cloud providers, which would have fragmented our experimental pipeline and made fair comparisons far more difficult."*

#### Tangible Academic Outcomes

- **Tier-1 publications:** Research supported by the platform has been published at **AAAI** and **NeurIPS** — the top venues in artificial intelligence
- **Grant competitiveness:** Platform directly strengthened proposals to **NSF**, **NIH**, and the **Spencer Foundation**
- **Named researchers driving impact:** Lei Ying, Dimitris Samaras, Carl Lipo, Shiqi Zhang, Toni May, Ziyang Lu

This is not a pilot or a proof-of-concept. This is a production platform with measurable research outcomes that no competitor can replicate.

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

### ROI Projections — Anchored to the 40% Graduation Rate Target

The ASAP model has demonstrated a path to **40% three-year graduation rates** — nearly double the national community college average. The Student 360 AI Platform accelerates SUNY's trajectory toward this target by making interventions smarter and more precisely timed.

#### The ASAP ROI — Independently Verified

An independent benefit-cost analysis by Columbia University's Teachers College found that **ASAP returns $3.50 to taxpayers for every $1 invested** and **$12.20 to students for every $1 they invest**:

| ROI Metric | Value | Source |
|------------|-------|--------|
| **Taxpayer return** | **$3.50 per $1 invested** | Levin & García (2013), CBCSE, Columbia |
| **Student return** | **$12.20 per $1 invested** | Levin & García (2013) |
| **Cost per graduate** | **$6,500 lower** than non-ASAP (despite higher upfront cost) | Levin & García (2013) |
| **Net benefit per 1,000 students** | **$46.5 million** vs. comparison group | Levin & García (2013) |
| **Graduation rate effect** | 24.1% → 54.9% (studied cohort) | Levin & García (2013) |

> **Full citation:** Levin, H.M. & García, E. (2013). *Benefit-Cost Analysis of Accelerated Study in Associate Programs (ASAP) of the City University of New York (CUNY).* Center for Benefit-Cost Studies of Education (CBCSE), Teachers College, Columbia University. [PDF](https://www.cuny.edu/wp-content/uploads/sites/4/page-assets/home-preview/asap/evaluation/Levin_ASAP_Benefit_Cost_Report_FINAL_05222013.pdf) | Published as journal article: Levin & García (2017), *The Journal of Higher Education*.

#### Platform ROI for SUNY

**Per-student return when retained:**
- **$7,000-$12,000** in annual tuition and fees (community college)
- **$10,000-$15,000** in state funding per FTE

**Conservative scenario:** If the platform enables a **2% improvement** in retention across 10,000 ASAP|ACE students (200 additional retained students):
- **Direct tuition recovery:** $1.4M-$2.4M annually
- **State funding retention:** $2.0M-$3.0M annually
- **Combined annual recovery:** $3.4M-$5.4M

**Scaling scenario:** As the platform drives graduation rates toward the 40% ASAP benchmark across the broader SUNY community college population (~90,000 students), each percentage point gained represents **~900 additional completions** and proportional funding recovery.

### 8-Week No-Cost Prototype

To demonstrate value before any long-term commitment, Google Cloud is offering an **8-week no-cost prototype** engagement:

- **Scope:** Student 360 data integration at 2-3 pilot campuses
- **Deliverables:** Initial retention risk model, advisor-facing dashboard MVP, and Gemini-powered student summary prototype
- **Data:** SIS and LMS feeds connected to BigQuery; first predictive scores generated
- **Outcome:** Tangible proof of concept that SUNY leadership can evaluate before any investment decision

This prototype is designed as a leave-behind — a working system SUNY can assess in real advising workflows, not a slide deck.

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
- KR1: Deliver Looker dashboards to campus leaders at all 44 ASAP|ACE campuses
- KR2: Reduce state reporting preparation time from weeks to hours
- KR3: Publish first cross-campus ASAP|ACE effectiveness analysis using unified data

---

## Part 6: The Narrative for Leadership

### For the Governor's Chief of Staff

> "SUNY's AI Platform has already demonstrated what's possible for research — 10-15x speedups, tier-1 publications, Gemini Enterprise adopted system-wide. Now we're extending that same proven foundation to SUNY's #1 strategic priority: student success.
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

### Phase 2A: Foundation (Months 1-4)
- Data architecture design for Student 360 lakehouse
- SIS/LMS/Financial Aid data integration at 3-5 pilot campuses
- BigQuery data models for student risk scoring
- Governance framework for student data (FERPA compliance)

### Phase 2B: Intelligence Layer (Months 4-8)
- Vertex AI retention risk models trained on SUNY historical data
- Early alert triage system with advisor-facing dashboards
- Gemini advising copilot pilot with 20 ASAP|ACE advisors
- Looker dashboards for campus leaders

### Phase 2C: Scale (Months 8-12)
- Expand to all 44 ASAP|ACE campuses
- Student-facing self-service features (chatbot, eligibility checker)
- GrantAI extension for student success research funding
- Cross-campus benchmarking and system-level reporting

### Phase 2D: Optimize (Months 12-18)
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

9. **Levin & García — Benefit-Cost Analysis of ASAP** (2013, Columbia University / CBCSE) — $3.50 taxpayer ROI per $1 invested; $46.5M net benefit per 1,000 students
   - https://www.cuny.edu/wp-content/uploads/sites/4/page-assets/home-preview/asap/evaluation/Levin_ASAP_Benefit_Cost_Report_FINAL_05222013.pdf
   - Journal article: Levin & García (2017), *The Journal of Higher Education*

10. **National Student Clearinghouse Research Center** — National community college completion rates (~34% three-year for 2020 cohort)
   - https://nscresearchcenter.org/completing-college/

11. **Center for an Urban Future** — "Struggling to the Finish Line: Community College Completion in New York State" (2017) — SUNY CC average ~26%
   - https://nycfuture.org/research/community-college-completion-in-new-york

---

*Prepared for: Camille Joseph Varlack, SUNY | Google Cloud Account Team*
*Date: June 2026*
