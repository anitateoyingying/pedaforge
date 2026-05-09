# PedaForge: AI-Powered Pedagogical Development Platform

A sandbox project transforming early childhood education class and curriculum management through AI-driven lesson planning, digital portfolios, digital coaching and data-informed pedagogical leadership.

---

## Table of Contents

- [The Problem](#the-problem)
- [Project Overview](#project-overview)
- [Features](#features)
  - [Profile-Driven Smart Lesson Planner](#1-profile-driven-smart-lesson-planner)
  - [Authentic Portfolio and Dynamic Profiling Engine](#2-authentic-portfolio-and-dynamic-profiling-engine)
  - [QTT-Aligned AI Coaching Agent](#3-qtt-aligned-ai-coaching-agent)
  - [Director's Leadership Dashboard](#4-directors-leadership-dashboard)
- [Architecture](#architecture)
  - [System Overview](#system-overview)
  - [AI Pipeline](#ai-pipeline)
  - [Tech Stack](#tech-stack)
- [Data Privacy and PDPA Compliance](#data-privacy-and-pdpa-compliance)
- [Academic and Empirical Validation](#academic-and-empirical-validation)
- [Success Metrics](#success-metrics)
- [Implementation Timeline](#implementation-timeline)
- [Budget](#budget)
- [Team](#team)
- [Framework Alignment](#framework-alignment)
- [Prototype and Demo](#prototype-and-demo)
- [Sustainability and Commercialisation](#sustainability-and-commercialisation)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
---

## The Problem

Singapore's early childhood education (ECE) workforce faces a documentation crisis that directly undermines the quality of teaching and learning. Despite national investments in curriculum frameworks and professional standards, educators spend a disproportionate share of their working hours on administrative tasks instead of meaningful interactions with children.

### The Evidence

The **OECD TALIS Starting Strong 2024** report identifies emotional exhaustion from administrative burden as a leading contributor to workforce attrition in early childhood settings. The report underscores that documentation workload is not merely an inconvenience; it is a systemic barrier to quality pedagogy.

The scale of the problem in Singapore's ECE sector:

| Challenge | Impact |
|-----------|--------|
| **Documentation overload** | Educators spend an average of **8 hours per week** on lesson plans, observations, portfolios, checklists, and developmental reports |
| **Reduced child interaction** | **35% less time** spent on individualised interactions due to manual documentation demands |
| **Subjective appraisals** | Annual performance reviews rely on infrequent observations and are often misaligned with Skills Framework for ECCE (SFw) competencies |
| **Limited visibility** | Centre directors lack real-time insight into pedagogical quality across classrooms |
| **Homogeneous planning** | Cognitive overload forces educators into one-size-fits-all lesson planning, undermining differentiated instruction |
| **Professional isolation** | Educators receive coaching only during scheduled observations, missing daily growth opportunities |

### The Consequence

When educators are overwhelmed by paperwork, children receive less responsive caregiving, fewer scaffolded learning experiences, and weaker attachment relationships. The documentation crisis is, at its core, a **child outcomes crisis**.

PedaForge addresses this by reallocating educator hours from administrative burden back to high-quality, responsive interactions, the foundation of effective early childhood pedagogy.

---

## Project Overview

PedaForge is a **12-month innovation project** proposed for the ECDA Early Childhood Innovation Sandbox. The platform integrates four interconnected modules that collectively reduce documentation burden, improve pedagogical quality, and equip centre leaders with actionable data. Aligned with the refreshed Early Childhood Industry Digital Plan (IDP 2.0) announced at the Committee of Supply in March 2026, PedaForge demonstrates how responsible AI adoption can drive sector-wide transformation.

The project targets deployment across 2-3 pilot preschool centres in Singapore, with the goal of demonstrating measurable improvements in educator efficiency, teaching quality (as measured by QTT domains), and child developmental outcomes.

**Core thesis:** AI should not replace educators. It should eliminate the administrative friction that prevents educators from doing what they do best: teaching, nurturing, and building relationships with children.

---

## Features

### 1. Profile-Driven Smart Lesson Planner

The lesson planner moves beyond generic activity templates by generating differentiated lesson plans informed by actual classroom profiles. Every plan is tailored to the specific children in a given cohort.

**Capabilities:**

- **Differentiated scaffolding generation.** AI analyses classroom profiles, including learning needs, developmental stages, learning styles, language abilities, and special considerations, to produce activities with built-in accommodations for diverse learners.
- **Curriculum framework mapping.** Every generated activity maps to specific learning outcomes in the Early Years Development Framework (EYDF) and Nurturing Early Learners (NEL) framework, ensuring alignment with national standards.
- **Automated spaced retrieval scheduling.** Based on Roediger and Karpicke's (2006) research on active retrieval practice, the planner schedules "Rehearse and Retrieve" sessions that revisit key concepts at optimal intervals to strengthen long-term retention.
- **Theme-based activity generation.** Educators provide a theme (e.g., "community helpers," "water cycle"), and the AI generates a full week of activities with profile-specific variations, extension tasks, and simplification options.
- **Assessment indicator auto-generation.** For each activity, the planner produces observable indicators that educators can use to assess learning, reducing the time spent creating assessment rubrics from scratch.
- **Cross-domain integration.** Activities are designed to span multiple EYDF domains (aesthetics, discovery, language, motor, numeracy, social-emotional), promoting holistic development.

**How it works:**

1. Educator selects a cohort and theme.
2. The system retrieves the living profiles of all children in that cohort.
3. Claude AI generates a differentiated weekly plan with scaffolding tiers.
4. The educator reviews, adjusts, and confirms the plan.
5. Assessment indicators are auto-populated for portfolio integration.

---

### 2. Authentic Portfolio and Dynamic Profiling Engine

The portfolio module replaces static, paper-based documentation with a continuous, AI-assisted digital record of each child's developmental journey.

**Capabilities:**

- **Multi-modal daily capture.** Educators log observations, upload work samples, record anecdotal notes, and attach photos or videos directly within the platform. Each entry is timestamped and tagged to the relevant child, activity, and learning domain.
- **AI-drafted developmental narratives.** After capturing raw observations, the AI drafts narrative summaries tagged to specific EYDF and NEL learning outcomes. Educators review and approve before narratives are finalised; the AI assists, never replaces, professional judgment.
- **Living Profile engine.** Each child has a continuously updated developmental profile that synthesises observations, assessment results, and portfolio entries into a holistic view. The Living Profile tracks progression across all EYDF domains over time.
- **Bidirectional feedback loop.** Portfolio insights flow back into the lesson planner. If the Living Profile indicates a child is progressing rapidly in numeracy but needs support in language, the planner adjusts future activities accordingly.
- **Term summary report generation.** At the end of each term, the system synthesises assessment checklists, observation records, and portfolio entries into a comprehensive summary report suitable for parent conferences and regulatory submissions.
- **Parent engagement module.** AI-generated home activity suggestions based on current classroom themes and each child's developmental focus areas. Parents receive actionable, specific recommendations, not generic advice.

---

### 3. QTT-Aligned AI Coaching Agent

This is the signature feature of PedaForge. The coaching agent provides on-demand, AI-powered professional development aligned to ECDA's Quality Teaching Tool (QTT) framework. It is designed to challenge, not merely validate, educator thinking.

The coaching engine draws on adversarial coaching research and anti-sycophancy principles. It provides honest, specific, constructive feedback, avoiding the reflexive validation that undermines genuine growth.

#### Four Coaching Modes

| Mode | Framework | Intensity | Best For |
|------|-----------|-----------|----------|
| **Reflective Practice** | Gibbs' Reflective Cycle (1988) | Supportive | Daily teaching reflection and sense-making |
| **QTT Deep Dive** | ECDA Quality Teaching Tool | Focused | Targeted improvement on specific QTT rubric domains |
| **Socratic Inquiry** | Six Socratic question types | Challenging | Surfacing hidden assumptions and pedagogical blind spots |
| **Scenario Analysis** | Gary Klein Pre-Mortem technique | Rigorous | Stress-testing lesson plans and identifying failure modes |

#### Reflective Practice Mode

Guides educators through a structured reflection using Gibbs' six-stage cycle: Description, Feelings, Evaluation, Analysis, Conclusion, and Action Plan. The coach asks probing questions at each stage and resists premature closure. It ensures the educator moves beyond surface-level description into genuine analytical reflection.

#### QTT Deep Dive Mode

Maps coaching conversations directly to QTT domains and rubric descriptors. The coach identifies which QTT domains are relevant to the educator's scenario, references specific rubric language, and guides the educator toward concrete, actionable improvements. Every coaching response is tagged with the relevant QTT domain.

#### Socratic Inquiry Mode

Deploys six types of Socratic questions: clarification, probing assumptions, probing reasons and evidence, exploring viewpoints, probing implications, and questioning the question itself. This mode is designed to surface implicit beliefs about children, learning, and pedagogy that the educator may not have examined.

#### Scenario Analysis Mode

Uses Gary Klein's Pre-Mortem technique: "Imagine this lesson has failed completely. What went wrong?" The coach systematically walks the educator through potential failure points, forcing rigorous examination of assumptions, logistics, differentiation gaps, and contingency planning.

#### Coaching Engine Design Principles

- **Anti-sycophancy directives.** The system prompt explicitly instructs the AI to avoid reflexive validation. Praise must be specific and earned. The coach disagrees constructively when it identifies pedagogical gaps.
- **Safety guardrails.** Automated de-escalation when distress signals are detected. Ethical concerns are flagged and routed to human supervisors. The system never provides clinical or diagnostic assessments.
- **QTT domain tagging.** Every coaching response includes metadata indicating which QTT domains are addressed, enabling aggregation and reporting at the centre level.
- **Session persistence.** Coaching conversations are saved and analysed over time to generate insights about an educator's growth trajectory, recurring themes, and areas of strength.
- **"Speak to a Real Coach" pathway.** At any point, the educator can request referral to a human mentor or supervisor. The system is designed to augment, not replace, human coaching relationships.
- **Composable system prompts.** The coaching engine assembles prompts from modular components: base instructions + coaching technique + anti-sycophancy layer + safety guardrails + QTT context. This architecture enables rapid iteration and quality control.

---

### 4. Director's Leadership Dashboard

The dashboard gives centre directors and pedagogical leaders a real-time, data-informed view of teaching quality across their centre. It transforms coaching from a reactive, observation-dependent activity into a proactive, continuous process.

**Capabilities:**

- **Centre-wide QTT domain averages.** Aggregated coaching data and assessment results visualised by QTT domain, showing centre-level strengths and areas for focused improvement.
- **Individual educator profiles.** Each educator's coaching engagement, QTT domain scores, and professional growth trajectory displayed in a private, confidential dashboard view.
- **PLC topic recommendations.** The system analyses centre-wide patterns to suggest Professional Learning Community (PLC) discussion topics that address the most common pedagogical challenges.
- **SFw-mapped professional development.** Gap analysis comparing each educator's demonstrated competencies against the Skills Framework for ECCE (SFw), with targeted recommendations for WSQ courses and professional development activities.
- **Learning Needs Analysis (LNA) automation.** Generates centre-level and individual LNA reports based on coaching data, QTT assessments, and SFw alignment, reducing the administrative burden of annual professional development planning.
- **WSQ course recommendations.** Based on QTT gap analysis, the system recommends specific Workforce Skills Qualifications (WSQ) courses from approved training providers.
- **Bi-annual IDP generation.** Drafts Individual Development Plans (IDPs) for each educator, pre-populated with evidence from coaching sessions, QTT assessments, and SFw mapping. Directors review and finalise collaboratively with each educator.

---

## Architecture

### System Overview

```
+------------------------------------------------------------------+
|                    PedaForge Web Application                      |
|  Lesson Planner | Portfolio | AI Coach | Director Dashboard       |
+-------------------------------+----------------------------------+
                                | REST API + SSE Streaming
                                v
+------------------------------------------------------------------+
|                       FastAPI Backend                              |
|  +---------------+  +----------------+  +----------------------+  |
|  |   API Layer   |  |  AI Services   |  |    Data Layer         |  |
|  |               |  |                |  |                      |  |
|  |  Lesson API   |  |  Claude AI     |  |    PostgreSQL         |  |
|  |  Portfolio     |  |  Coaching      |  |    (Children, Plans, |  |
|  |  Coach API    |  |  Engine        |  |     Portfolios,      |  |
|  |  Dashboard    |  |  QTT Mapper    |  |     Observations,    |  |
|  |  Auth         |  |  SFw Aligner   |  |     Coach Sessions)  |  |
|  +---------------+  +----------------+  +----------------------+  |
|                                                                    |
|  PDPA Compliant | Role-Based Access | Audit Logging               |
+------------------------------------------------------------------+
```

The architecture follows a standard three-tier pattern with clear separation between the presentation layer (React/Next.js), the API and AI service layer (FastAPI), and the data persistence layer (PostgreSQL).

**Key architectural decisions:**

- **Server-Sent Events (SSE)** for streaming AI responses. Coaching conversations and lesson plan generation stream tokens in real time, providing a responsive user experience without WebSocket complexity.
- **Composable prompt architecture** for the coaching engine. System prompts are assembled from modular components, enabling independent iteration on coaching techniques, safety guardrails, and QTT alignment without full prompt rewrites.
- **FAISS vector index** for semantic search across child observations and portfolio entries, enabling the Living Profile engine to surface relevant developmental history during lesson planning.
- **Role-based access control (RBAC)** enforced at the API layer. Educators see only their assigned cohorts. Directors see aggregated and anonymised views unless individually authorised.

### AI Pipeline

The AI pipeline processes input through five stages:

```
1. Input Capture         Observations, work samples, lesson plans,
                         coaching transcripts
                                |
                                v
2. Parsing & Structuring  Text extraction, metadata tagging,
                         EYDF/NEL domain classification
                                |
                                v
3. Embedding             sentence-transformers (all-MiniLM-L6-v2)
                         generates dense vector representations
                                |
                                v
4. Semantic Indexing     FAISS vector index enables fast similarity
                         search across all child documentation
                                |
                                v
5. AI Generation         Claude AI performs:
                          - Theme-based lesson plan generation
                          - Developmental narrative drafting
                          - Coaching conversation management
                          - QTT and SFw alignment mapping
                          - Term summary synthesis
```

**Retrieval-Augmented Generation (RAG):** When generating lesson plans or coaching responses, the system retrieves relevant context from the FAISS index (previous observations, portfolio entries, and coaching history) and includes it in the prompt to Claude. This ensures AI outputs are grounded in each child's actual developmental journey, not generic templates.

### Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Frontend | React / Next.js, TypeScript, TailwindCSS, Chart.js | Responsive SPA with server-side rendering for initial load performance |
| Backend | Python 3.11+, FastAPI, Uvicorn | Async API server with SSE streaming support |
| AI / LLM | Claude Haiku 4.5 via Azure AI Foundry (Anthropic SDK) | Cost-efficient lesson generation, coaching, narrative drafting, alignment mapping |
| Embeddings | sentence-transformers (all-MiniLM-L6-v2) | Dense vector representations for semantic search |
| Vector Search | FAISS | Fast approximate nearest neighbour search over child documentation |
| Database | PostgreSQL | Relational storage for children, plans, portfolios, observations, coaching sessions |
| Authentication | JWT (bcrypt, HS256), role-based access control | Secure educator and director authentication |
| Hosting | Azure App Service (Singapore region), Azure Files, Key Vault | Cloud infrastructure with Singapore data residency |
| Compliance | PDPA, zero public AI training, SG data residency | Regulatory alignment for child data protection |

---

## Data Privacy and PDPA Compliance

PedaForge handles sensitive data about young children. Data privacy is not a feature. It is a foundational requirement that informs every architectural and operational decision.

### Compliance Framework

| Principle | Implementation |
|-----------|---------------|
| **Zero Public AI Training** | All AI processing occurs within Azure AI Foundry's closed tenant environment. No child data is used to train public models. No data leaves the organisation's Azure tenant. |
| **Singapore Data Residency** | All data, at rest and in transit, remains within Singapore-based Azure data centres. No cross-border data transfer. |
| **Role-Based Access Control** | Every user has a unique login. Educators access only their assigned cohorts. Directors access aggregated views with explicit authorisation for individual educator data. |
| **Encryption at Rest** | AES-256 encryption for all stored data, including database records, uploaded files, and coaching transcripts. |
| **Encryption in Transit** | TLS 1.2+ for all API communication. No unencrypted data transmission. |
| **Child Data Anonymisation** | Any data processed outside the primary database (e.g., embedding generation) is anonymised. Child identifiers are replaced with opaque tokens. |
| **Parental Consent Management** | Built-in consent management module. Parents provide explicit consent for AI-assisted documentation. Consent can be withdrawn at any time, triggering data removal workflows. |
| **Audit Logging** | All data access events are logged with timestamps, user identity, and action type. Audit logs are immutable and retained for the duration required by PDPA. |

### Data Classification

| Data Type | Classification | Access Level |
|-----------|---------------|-------------|
| Child observations and portfolios | Confidential | Assigned educators, authorised directors |
| Coaching session transcripts | Private | Individual educator, authorised directors |
| QTT assessment scores | Internal | Educator (own), directors (aggregated + individual with authorisation) |
| Centre-level analytics | Internal | Directors, pedagogical leaders |
| System configuration | Restricted | Technical administrators only |

---

## Academic and Empirical Validation

PedaForge is grounded in established educational research and evidence-based pedagogical frameworks. The platform does not invent new pedagogy; it operationalises proven approaches through technology.

### Research Foundations

| Source | Year | Application in PedaForge |
|--------|------|-------------------------|
| **OECD TALIS Starting Strong Report** | 2024 | Quantifies the documentation burden and its impact on workforce quality. Validates the core problem PedaForge addresses. |
| **Bowlby, J., Attachment Theory** | 1969 | Underpins the Key Person approach embedded in the Living Profile. Each child's portfolio maintains continuity of the educator-child relationship. |
| **Vygotsky, L., Zone of Proximal Development** | 1978 | The differentiated scaffolding in the lesson planner is designed to target each child's ZPD, providing appropriately challenging activities. |
| **Roediger, H. & Karpicke, J., Active Retrieval Practice** | 2006 | The "Rehearse and Retrieve" scheduling algorithm implements spaced retrieval practice, shown to improve long-term retention by 30-50%. |
| **Gibbs, G., Reflective Cycle** | 1988 | Structures the Reflective Practice coaching mode, guiding educators through six stages of reflective analysis. |
| **Klein, G., Pre-Mortem Technique** | 2007 | Structures the Scenario Analysis coaching mode, enabling educators to stress-test lesson plans before delivery. |
| **ECDA Quality Teaching Tool (QTT)** | Current | The primary rubric framework for coaching alignment. All coaching responses are mapped to QTT domains. |
| **Skills Framework for ECCE (SFw)** | Current | Professional development mapping. The dashboard aligns educator competencies to SFw tracks and recommends WSQ courses. |
| **Early Years Development Framework (EYDF)** | Current | National curriculum framework. All lesson plans and portfolio entries map to EYDF learning domains. |
| **Nurturing Early Learners (NEL)** | Current | Complementary curriculum framework. Activity generation ensures coverage across NEL learning areas. |

### Anti-Sycophancy Research

The coaching engine design draws on emerging research into AI sycophancy, the tendency of language models to provide agreeable but unhelpful responses. PedaForge addresses this through:

- Explicit anti-sycophancy directives in system prompts
- Structured coaching frameworks that require constructive challenge
- Earned praise protocols (praise must reference specific, observable evidence)
- Mode-specific intensity calibration (from supportive to rigorous)

---

## Success Metrics

PedaForge defines six primary KPIs, each with a specific target, measurement method, and evaluation timeline.

| Metric | Baseline | Target | Measurement Method | Timing |
|--------|----------|--------|-------------------|--------|
| Documentation time per educator | 8 hrs/week | 3 hrs/week (60% reduction) | Pre/post time-tracking surveys, system usage logs | Months 6-9 |
| Differentiated lesson plans | Manual, often generic | 100% of plans address 2+ learner profiles | Automated analysis of generated plans | Continuous |
| IDP accuracy rating | Subjective annual review | 85% educator agreement with AI-generated IDP | Post-assessment surveys and educator interviews | Month 12 |
| Coaching engagement | Ad hoc, observation-dependent | 2+ sessions per educator per week | System usage analytics | Months 6-9 |
| QTT score improvement | Pre-pilot baseline assessment | +0.5 points average across QTT domains | Pre/post QTT assessment by trained assessors | Months 6, 12 |
| Educator retention intent | Industry benchmark | 90% of pilot participants would continue using the platform | End-of-pilot survey | Month 12 |

### Secondary Metrics

- Parent engagement rate with AI-generated home activity suggestions
- Portfolio completeness (observations per child per week)
- Director dashboard login frequency and feature utilisation
- PLC discussion quality (educator-reported)
- Time from observation to portfolio entry (latency reduction)

---

## Implementation Timeline

### Phase 1: Development and AI Foundation (Months 1-3)

- Azure cloud infrastructure setup (App Service, PostgreSQL, Key Vault, AI Foundry)
- Build four core modules: Smart Lesson Planner, Portfolio and Profiling, AI Coaching Agent, Director's Dashboard
- AI prompt engineering and QTT/SFw alignment
- PDPA compliance framework and role-based access control

### Phase 2: Pilot Deployment and Onboarding (Months 4-5)

- Onboard 2-3 pilot centres
- Educator workshops and digital literacy training
- Baseline metrics establishment
- Security audit and penetration testing

### Phase 3: Active Classroom Usage and Iteration (Months 6-9)

- Live platform usage across pilot centres
- SFw-aligned Individual Development Plans (IDPs)
- Weekly AI coaching sessions
- Iterative feedback and continuous improvement
- AI model refinement based on real-world data

### Phase 4: Impact Assessment and Scaling (Months 10-12)

- End-of-pilot QTT assessment
- Quantitative time-saved metrics vs baseline
- Educator satisfaction surveys
- Comprehensive impact report
- ECDA presentation and scaling proposal
- Preparation for national rollout across Busy Bees centres

---

## Budget

### Cost Breakdown

| Category | Component | Cost (SGD) |
|----------|-----------|-----------|
| **Development and Infrastructure** | Full-stack and AI development (contract, 16 days) | $8,000 |
| | Azure App Service + PostgreSQL (12 months @ $150/month) | $1,800 |
| | AI API, Claude Haiku 4.5 via Azure AI Foundry (12 months @ $85/month) | $1,020 |
| | **Subtotal** | **$10,820** |
| **Security and Compliance** | PDPA compliance review | $2,000 |
| | Security assessment | $1,200 |
| | **Subtotal** | **$3,200** |
| **Change Management** | Pedagogical consultant (QTT/SFw validation, 4 days) | $2,400 |
| | Educator onboarding workshops and materials | $2,000 |
| | **Subtotal** | **$4,400** |
| **Evaluation and Reporting** | Impact assessment, reporting, and scale planning | $2,600 |
| | **Subtotal** | **$2,600** |

| | |
|---|---|
| **Total Project Budget** | **SGD $21,000** |

### Budget Notes

- All costs are in Singapore Dollars (SGD).
- Cloud infrastructure costs assume Azure App Service B1 tier with PostgreSQL Flexible Server, scaled for 2-3 pilot centres over 12 months.
- AI API costs use Claude Haiku 4.5 via Azure AI Foundry, the most cost-efficient model in the Claude family, estimated at approximately 500 coaching sessions, 200 lesson plans, and 1,000 portfolio narratives per month across all pilot centres.
- The budget is structured to align with Early Childhood Innovation Sandbox disbursement milestones.
- Azure AI Foundry provides a managed, secure gateway to Claude models with enterprise-grade SLA, Singapore data residency, and zero public model training guarantees.

---

## Team

| Role | FTE | Responsibilities |
|------|-----|-----------------|
| **Project Lead** | 0.3 | Overall timeline and budget management. Stakeholder communication with ECDA, pilot centres, and institutional partners. Risk management. Leads evaluation and impact reporting. |
| **Technical Lead** | 1.0 | Full-stack development (FastAPI, React/Next.js). AI integration via Azure AI Foundry and prompt engineering. System architecture, database design, security, and deployment on Azure. |
| **Pedagogical Specialist** | 0.2 | EYDF, NEL, QTT, and SFw domain expertise. Validation of AI-generated content against curriculum standards. Coaching mode design. Educator training facilitation. |

### Advisory

The project team will engage advisory input from:

- ECDA-appointed pedagogical advisors for QTT alignment validation
- PDPA compliance consultants for data privacy assurance
- Preschool operators and centre directors for practical feasibility review

---

## Framework Alignment

PedaForge is designed to align with and operationalise multiple national frameworks governing early childhood education in Singapore.

### ECDA Industry Digital Plan (IDP 2.0)

PedaForge directly addresses the Early Childhood Innovation Sandbox objectives under IDP 2.0 by demonstrating how AI can reduce administrative burden, improve pedagogical quality, and enhance professional development in ECE settings. The project serves as a proof-of-concept for responsible AI adoption in the sector.

### Early Years Development Framework (EYDF)

All lesson plans, portfolio entries, and assessment indicators map to EYDF learning domains: Aesthetics and Creative Expression, Discovery of the World, Language and Literacy, Motor Skills Development, Numeracy, and Social and Emotional Development. The differentiation engine ensures activities address multiple domains simultaneously.

### Nurturing Early Learners (NEL)

NEL learning areas are integrated into the lesson planner's activity generation. The system ensures comprehensive coverage across NEL domains throughout weekly and termly planning cycles.

### ECDA Quality Teaching Tool (QTT)

The QTT is the primary rubric framework for the coaching agent. All four coaching modes reference QTT domains and rubric descriptors. The director dashboard aggregates QTT-tagged coaching data to provide centre-level quality insights.

### Skills Framework for ECCE (SFw)

The dashboard maps educator competencies demonstrated through coaching sessions and QTT assessments to SFw competency tracks. This enables data-driven professional development planning, WSQ course recommendations, and IDP generation.

### Singapore Skills Framework

PedaForge connects individual educator development to broader national skills development objectives, ensuring that professional growth within the platform contributes to recognised national qualifications and career progression pathways.

---

## Prototype and Demo

A static prototype is available demonstrating the UI/UX vision for each core module. The prototype is hosted on GitHub Pages and showcases the intended user experience, interaction patterns, and information architecture.

### Demo Pages

| Page | Description |
|------|-------------|
| `index.html` | Landing page with project overview, feature highlights, and navigation to all modules |
| `planner.html` | Smart Lesson Planner interface with cohort selection, theme input, and differentiated plan display |
| `portfolio.html` | Portfolio and Living Profile view with observation capture, narrative display, and developmental timeline |
| `coach.html` | AI Coaching Agent with mode selection, real-time conversation interface, and QTT domain tagging |
| `dashboard.html` | Director's Leadership Dashboard with QTT visualisations, educator profiles, and PLC recommendations |

### Important Note

The prototype is a static HTML/CSS/JS demonstration. It simulates AI responses and data interactions to illustrate the intended user experience. The production platform will implement these interfaces with full backend integration, real-time AI processing, and live data persistence.

---

## Sustainability and Commercialisation

PedaForge is designed for sustainability beyond the 12-month innovation sandbox period.

### Post-Pilot Commercialisation Pathway

1. **SaaS subscription model.** Monthly or annual subscription pricing for preschool operators, tiered by centre size and number of educators. Pricing designed to be accessible for both large chains and independent operators.

2. **Preschool Management System (PMS) integration.** API-based integration with existing PMS platforms used by Singapore's preschool sector, enabling PedaForge to complement rather than replace current systems.

3. **ECDA pre-approved solution.** Application for inclusion as an ECDA pre-approved solution under the Early Childhood Development Grant (ECDG), enabling operators to offset adoption costs through existing government funding mechanisms.

4. **ASEAN market expansion.** The platform architecture supports localisation for other ASEAN markets with similar ECE quality frameworks. Initial expansion targets include Malaysia, Thailand, and the Philippines, where workforce quality and documentation challenges mirror Singapore's experience.

### Long-Term Vision

- Longitudinal child development analytics spanning multiple years
- Cross-centre benchmarking for operators managing multiple sites
- Integration with national child development databases (subject to regulatory approval)
- Research partnerships with NIE and SEED Institute for continuous validation

---

## Getting Started

### Prerequisites

- Python 3.11 or higher
- Node.js 18 or higher
- PostgreSQL 15 or higher
- Azure account with AI Foundry access (for Claude API)

### Local Development Setup

```bash
# Clone the repository
git clone https://github.com/your-org/pedaforge.git
cd pedaforge

# Backend setup
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Configure environment variables
cp .env.example .env
# Edit .env with your database credentials and API keys

# Database setup
alembic upgrade head

# Start the backend server
uvicorn app.main:app --reload --port 8000

# Frontend setup (in a separate terminal)
cd frontend
npm install
npm run dev
```

### Environment Variables

| Variable | Description |
|----------|------------|
| `DATABASE_URL` | PostgreSQL connection string |
| `AZURE_AI_ENDPOINT` | Azure AI Foundry endpoint URL |
| `AZURE_AI_API_KEY` | Azure AI Foundry API key |
| `JWT_SECRET_KEY` | Secret key for JWT token signing |
| `CORS_ORIGINS` | Allowed CORS origins (comma-separated) |

### Running Tests

```bash
# Backend tests
pytest --cov=app --cov-report=html

# Frontend tests
cd frontend
npm test -- --coverage
```

---

## Contributing

Contributions are welcome during and after the pilot phase.

### How to Contribute

1. **Fork** the repository.
2. **Create a feature branch** from `main`:
   ```bash
   git checkout -b feat/your-feature-name
   ```
3. **Write tests first** following TDD methodology. Ensure 80% or higher coverage for new code.
4. **Implement** the feature or fix.
5. **Run the full test suite** and verify all tests pass.
6. **Commit** with a descriptive message following conventional commits format:
   ```
   feat: add spaced retrieval scheduling to lesson planner
   ```
7. **Open a pull request** with a clear description of the change, its motivation, and testing approach.

### Code Standards

- Python: Follow PEP 8. Use type hints. Format with `black` and lint with `ruff`.
- TypeScript: Follow the project ESLint configuration. Use strict TypeScript.
- All code must pass CI checks before merge.
- No hardcoded secrets, API keys, or credentials in source code.

### Reporting Issues

Open an issue on GitHub with:
- A clear description of the problem or suggestion
- Steps to reproduce (for bugs)
- Expected and actual behaviour
- Screenshots or logs if applicable

---

Copyright (c) 2026 Anita Teo. All rights reserved.
